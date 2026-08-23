# KRUTIK CYBER EXPERT — Video Vault (GitHub Pages)

Bilkul PDF/Photo wali site jaisa hi tarika — phone se, bina computer ke.

---

## ⚠️ Zaroori limits (pehle padho)

- GitHub par **ek file max 100MB** ki ho sakti hai — usse bada upload hoga hi nahi
- **50MB se upar** GitHub warning dega (kaam to karega, par slow ho sakta hai)
- Isliye videos ko chhota/compressed rakho — ho sake to **20-30MB se kam**, 1-2 minute ki clips
- Lambi/HD video daalni ho to usko phone me hi kisi video-compress app se chhota kar lena pehle

---

## Step 1 — Naya repository banao
1. https://github.com par **+** → **New repository**
2. Naam: `krutik-cyber-expert-videos` (ya jo chaho)
3. **Public** select karo → **Create repository**

## Step 2 — Files upload karo
1. **Add file → Upload files** se `index.html` aur `videos.json` daalo → Commit
2. `videos` folder banane ke liye: **Add file → Create new file** → naam type karo `videos/.gitkeep` → Commit
3. `videos` folder me jaake **Add file → Upload files** se apni video (.mp4) daalo → Commit
   (Upload me thoda time lag sakta hai, video size ke hisaab se)

## Step 3 — GitHub Pages ON karo
1. **Settings → Pages**
2. Branch: **main**, folder **/ (root)** → **Save**
3. 1-2 min baad link milega: `https://<username>.github.io/krutik-cyber-expert-videos/`

---

## Nayi video add kaise karein

1. `videos` folder me video upload karo (naam simple rakho, jaise `video1.mp4` — bina space/special characters, format **.mp4** hi rakhna best hai — sabse zyada compatible)
2. `videos.json` file khol kar pencil (✏️) icon dabao
3. Naya entry jodo:

```json
[
  {
    "title": "Video Title",
    "description": "Short description (optional)",
    "category": "General",
    "filename": "video1.mp4",
    "uploadDate": "2026-08-13"
  }
]
```

4. **Commit changes** dabao

`filename` bilkul wahi naam hona chahiye jo video ka hai — nahi to video load nahi hogi.

**Agar video kisi doosre repo me hai:** `filename` ki jagah uska poora **raw URL** bhi daal sakte ho:
```json
"filename": "https://raw.githubusercontent.com/username/repo/main/videos/video1.mp4"
```

## Video hatana ho to
1. `videos.json` se entry delete karo → Commit
2. `videos` folder se file delete karo (teen-dot menu → Delete file)

---

**Features is site me:**
- Video grid, search, category filter
- Video pe tap karke poora dekh sakte ho (lightbox, play/pause controls)
- Direct download button
- Red/black "warning" style 3D animated background (network + matrix rain)

---

## ⚠️ Content policy (zaroori)

- Sirf **apni khud ki** ya **rights-cleared** videos upload karo
- **Kisi bhi real insaan ko naam lekar accuse/target/defame** karne wala content strictly mana hai — chahe testing ke liye ho ya real, dono cases me
- Copyright wali (movies, songs, kisi aur ka content) videos mat daalo
- In rules ka ullanghan karne wale content ke liye future help nahi milegi
