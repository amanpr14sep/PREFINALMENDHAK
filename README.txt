PALAK BIRTHDAY SITE
===================
Kholne ke liye: index.html ko browser mein double-click karo.

Baad mein kya badalna ho to index.html ke andar "EDIT HERE" wale block mein sab hai:
- Photos ke numbers (assets/photos/p01.jpg ... p20.jpg)
- Shelf ke books ka text (BOOKS)
- Diary ki lines (DIARY)
- Polaroid / makeup / booth mein kaun si photo (POLAROIDS, MAKEUP, BOOTH)
- Videos: VIDEOS = ["assets/videos/v01.mp4"] likho aur file assets/videos/ mein rakho
- "Ek yaad" frame ki photos: index.html mein US_PHOTOS list (hum-dono.jpg, us-02.jpg ... us-06.jpg). Naam ya photo badalni ho to wahin.
- Us frame ki date: US_DATE (jaise "14 Feb 2025").
- Closing note ka text: index.html mein "closing-note" dhundo
- Chehra crop sahi na ho to FOCUS mein us photo ka [x%, y%] badlo

Link ke liye: poore folder ko Netlify Drop (app.netlify.com/drop) par drag-drop kar do.

AWAAZ (MUSIC) + VINYL
---------------------
- OPEN IT dabate hi celebration ki awaaz (pop, taaliyan), phir Happy Birthday ki tune (assets/audio/happy-birthday.mp3) bajti hai.
- Memory Box ke upar "Gaana lagao" vinyl hai: record pe tap = play/pause, neeche sleeves se gaana badlo.
- Naya gaana: mp3 ko assets/audio/ mein rakho aur index.html mein TRACKS list mein ek line jodo:
  { t: "Gaane ka naam", a: "Singer", f: "assets/audio/gaana-1.mp3", c: "#a53551" },
- AUTONEXT = true karoge to ek gaana khatam hote hi agla chalega.
- Neeche right ka speaker button gaana roko/chalao.

HERO (PEHLA PAGE)
-----------------
Palak ki cutout assets/cut-hero.png hai (transparent background PNG). Badalni ho to usi naam se replace karo.
Dashed pink outline assets/hero-outline.png hai (cutout ke hisaab se bani hai, naya cutout lagao to ise bhi badalna padega).

TIMER + PASSCODE
----------------
index.html ke EDIT HERE block mein OPEN_AT (kab khulegi, IST mein) aur PASSCODE hai.
Abhi: 21 Oct 2026 raat 12:00 baje khulegi. Usse pehle countdown dikhta hai; passcode daalne par pehle bhi khul jaati hai.
Note: ye phone/computer ki ghadi par chalta hai, aur ye security nahi, sirf surprise ke liye hai.
