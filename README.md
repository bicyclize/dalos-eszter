# Dalos Eszter — mediáció · coaching · konzultáció

Egyoldalas weboldal Eszter Dalos segítői praxisának: mediáció, coaching, egyéni konzultáció.
A design a bedeanna.com letisztult, meleg szerkesztői stílusát követi; tartalom és képek
a zagonidalos.squarespace.com alapján.

## Futtatás

```bash
# lokálisan:
python3 -m http.server 8000
# majd: http://localhost:8000

# vagy csak nyisd meg az index.html-t böngészőben
```

## Kapcsolati űrlap

Az űrlap a [FormSubmit](https://formsubmit.co) ingyenes szolgáltatást használja,
célcím: `info@zagoniesdalos.hu`. Az első elküldés után **aktivációs e-mailt** küld
erre a címre — amíg azt nem erősítik meg, az üzenetek nem érkeznek meg.

## Deploy (GitHub Pages)

```bash
gh repo create zagoni-dalos --public --source=. --push
gh api repos/bicyclize/zagoni-dalos/pages -f build_type=legacy -f source[branch]=main -f source[path]=/
```
