PRINCESS KINGDOM — PWA V14

Fișiere:
- index.html — aplicația completă și cele 600 de provocări
- manifest.webmanifest — configurarea PWA
- sw.js — cache offline
- icon-192.png / icon-512.png — pictograme

Modificări V14:
1. Ajutor pentru părinți:
   - Mesajul nu mai apare peste butoanele jocului.
   - Se afișează într-o secțiune separată, sub butoanele „Ajutor pentru adult” și „Joc nou”.
   - Secțiunea împinge progresul mai jos în pagină și se închide la atingere.

2. Progres pe categorii:
   - Panou comun cu fundal crem-roz, chenar auriu și colțuri rotunjite.
   - Fiecare categorie are propriul rând încadrat și bară de progres în stilul jocului.

3. Selectarea categoriilor:
   - „Tot regatul” este selectat inițial; celelalte categorii sunt afișate în grayscale.
   - Când se selectează Desen, Mimă sau Întrebări, butonul ales rămâne colorat și conturat portocaliu; celelalte devin grayscale.
   - Selecția rămâne vizibilă și după finalizarea unei provocări.
   - La apăsarea altei categorii, jocul generează o provocare din categoria aleasă.
   - „Joc nou” resetează progresul și revine la „Tot regatul”.

4. Categoria Întrebări:
   - În provocare se afișează doar indiciul vizual (emoji-ul din banca de provocări).
   - Textul întrebării și răspunsul orientativ apar în secțiunea „Ajutor pentru adult”, pentru a fi citite de părinte.
   - În banca actuală, fiecare provocare de tip Întrebare are câmpurile emoji, task și answer; nu are un fișier imagine separat.

5. Păstrate:
   - Fundalul unic extins cu pavaj și trandafiri.
   - Butonul principal adaptiv.
   - Designul aprobat pentru butoanele „Ajutor pentru adult” și „Joc nou”.
   - 600 de provocări și salvarea progresului local.

Actualizare:
- Încarcă toate cele șase fișiere în același director pe hosting HTTPS.
- Cache Service Worker: v14-parent-help-progress.
- Pentru testare, închide complet aplicația instalată și redeschide-o după publicare.

Notă:
- Progresul se păstrează local pe dispozitiv.
- Service Worker funcționează pe HTTPS sau localhost, nu prin file:// ori content://.
