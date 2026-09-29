# Estinca · EPK

Electronic press kit (RO/EN) pentru Estinca: bio, istoric pe scenă, video live, fotografii, afișe, booking.
Site static: un singur `index.html` + folderele `img/`, `flyers/`, `video/`. Nu are nevoie de build.

## Editare linkuri și contact
În `index.html`, caută blocul `CONFIG` (secțiunea „EDITEAZĂ AICI”) și completează linkurile (Spotify, YouTube, Facebook) și datele de booking. Câmpurile goale nu apar pe pagină.

## Deploy pe Vercel
1. Urcă folderul într-un repo pe GitHub.
2. Pe vercel.com: **Add New → Project → Import** repo-ul.
3. Framework Preset: **Other**. Build command: gol. Output directory: gol (rădăcina).
4. **Deploy**. Opțional: Settings → Domains pentru un domeniu propriu.
