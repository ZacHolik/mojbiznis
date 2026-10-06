# mojbiznis.online — stara stranica (37 €)

Snimka produkcijske verzije stranice kakva je bila **6. listopada 2026.**, na dan
kad je u `redesign-kon-tiki` spojen novi izgled (svijetle „bijela kava" sekcije,
brend `MojBiznis.online`, paket od 8 €).

Ovo je stranica koja je stajala na `mojbiznis.online` prije redizajna: Tailwind
CDN, Inter font, narančasti akcent, proizvod od 37 € i priča oko `kvik.online`.

## Što je unutra

| Datoteka | Što je |
|---|---|
| `index.html` | **Samostalna** kopija početne stranice |
| `izgled-desktop.png` | Snimka cijele stranice, 1440 px |
| `izgled-mobil.png` | Snimka cijele stranice, 390 px |
| `uvjeti.html`, `privatnost.html`, `hvala.html` | Podstranice, onakve kakve su bile |

## Zašto je `index.html` velik

Originalna stranica je Tailwind CSS i Inter font vukla s tuđih CDN-ova. Takva
kopija s vremenom propadne — kad se ti linkovi promijene, ostane gola hrpa
teksta. Zato je u ovoj kopiji Tailwind prekompajliran, a font ugrađen direktno u
datoteku. Otvara se dvoklikom i izgleda identično i bez interneta.

Jedino što je ostalo vanjsko je Stripe link na gumbu, što i treba ostati link.

Podstranice (`uvjeti`, `privatnost`, `hvala`) nisu zamrznute — one su kopirane
onakve kakve su bile i za ispravan prikaz im treba internet.

## Napomena

Mapa `arhiva/` je u `.vercelignore`, pa se **ne objavljuje**. Stara stranica ima
živ Stripe link i staru cijenu, pa nema potrebe da bude javno dostupna.

Izvor: grana `main`, commit `ff4823e`.
