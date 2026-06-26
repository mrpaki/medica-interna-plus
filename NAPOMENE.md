# Predlog 2 — Napomene za klijenta

## Placeholder podaci koje klijent treba da potvrdi ili zameni

### Tim lekara
- **Potvrđen lekar:** Mr. sci. med. dr Milan Mijailović (osnivač, specijalista interne medicine)
- **Placeholder:** Dva dodatna lekara prikazana su sa `[Ime i prezime lekara]` i `[Specijalnost]`
  → Klijent treba da dostavi: puna imena, titule, specijalnosti i opciono kratke biografije
- **Fotografije tima:** Tim sekcija koristi placeholder ikonicu umesto stvarne fotografije
  → Zameniti sa profesionalnom fotografijom tima (preporučene dimenzije: 800×600px, format .webp ili .jpg)

### Testimonijali
- Sva tri testimonijala su izmišljeni (M. J., A. P., S. M.) sa generičkim tekstovima
  → Klijent treba da dostavi stvarne recenzije pacijenata (ime može biti inicijalizovano radi privatnosti)
  → Alternativno: koristiti Google recenzije (copy/paste teksta uz dozvolu pacijenta)

### Fotografije i vizuali
- **Hero sekcija:** Trenutno prikazuje gradijentnu pozadinu bez fotografije
  → Preporučiti profesionalnu fotografiju ordinacije ili medicinskog okruženja
  → Opciono: kratki video (10–20 sek, bez zvuka, loop) za video hero pozadinu
- **Category cards:** Koriste ikonice umesto fotografija
  → Opciono zameniti sa foto slikama ordinacije/opreme

### Radno vreme
- Prikazano: Pon–Pet 08–20h, Sub 09–14h, Ned zatvoreno
  → Potvrda od klijenta potrebna (sajt navodi 08–20 bez podele po suboti)

### Linkovi na podstranice
- Svi dropdown linkovi i CTA linkovi vode na `#` (ankere na istoj stranici)
  → Zameniti stvarnim URL-ovima kada stranice budu gotove

### Društvene mreže
- Facebook, Instagram, LinkedIn linkovi su `#` placeholderi
  → Klijent treba da dostavi stvarne profile

### Cenovnik
- Cene su tačne (preuzete sa medicainternaplus.rs/cenovnik/)
- Prikazana je selekcija od ~16 usluga — kompletna lista ima 80+ stavki
  → Opcija: dodati link na PDF cenovnik ili posebnu stranicu

### SEO podaci
- OG image (og:image) nije postavljena — klijent treba da dostavi header fotografiju (1200×630px)
- Twitter handle `@Medica_Interna` — proveriti da li profil postoji

---

## Tehnička napomena
Fajl je single-file HTML (bez eksternih CSS/JS fajlova sem Google Fonts i Tabler Icons CDN-a).
Za produkciju preporučiti: kompresiju slika, hosting fontova lokalno, i HTTPS sertifikat.
