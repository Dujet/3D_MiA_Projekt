# Tekstualni opis projekta
Duje Huljev, 3D Modeliranje i Animacija, 2025.

Kao zadatak za samostalnu vježbu, napravljena je kratka animacija viteza.
Ostvareni elementi gradiva u radu:
1. Poligonalno modeliranje (mač)
2. Modeliranje krivuljama (križni čuvar mača)
3. Teksturiranje (mač, vitez)
4. Animacija (vitez, kamera)
5. Skeletni model lika (vitez - *Rigify*)
6. Principi dizajna (kompozicija)

Modeli preuzeti s Interneta su:
- Vitez (Mixamo - Paladin)
- Lutka za trening (Sketchfab)
- Srednjovjekovna crkva i dvorište (Sketchfab)

## Mač
Mač je modeliran tehnikama poligonalnog modeliranja te modeliranja krivuljama. Napravljena su četiri različita dijela koja su kasnije spojena u jedan objekt (sječivo, križni čuvar, drška, metalni dio na dršci).

Korištenjem tekstura preuzetih s Interneta (*Poliigon*), napravljeni su materijali za metal i dršku. Na materijal metala dodani su detalji malih ogrebotina kombinacijom tekstura pomoću *Mix Color* čvora u *Overlay* načinu rada (specifično za *roughness* i *normal* komponentu teksture).

## Vitez i animacija
Preuzeti model viteza je došao s skeletnim modelom, no on nije bio idealan za animaciju, pa sam dodao svoj skeletni model pomoću *Rigify* add-ona, što je omogućilo lakšu animaciju. Sama animacija trčanja ručno je animirana uz pomoć raznih referentnih materijala. Zbog nedostatka vremena za rafiniranje same animacije, neki njeni dijelovi se doimaju neprirodno jer pojedinačne poze i njihovi prijelazi nisu dobro vremenski raspoređeni te animacije "pati" od prekomjernog *splineanja*.

Radi postizanja prividne "ozbiljnosti" scene, kamera je animirana na specifičan način radi ostvarenja kontrasta između prvotne ozbiljnosti scene i humorističnog završetka. 

## Scena
Scena je vrlo jednostavna: sastoji se od modela crkve i njenog dvorišta, viteza, mača i lutke. Pozadina, a tako i svjetlost, ostvarena je pomoću preuzetog HDRI materijala.
