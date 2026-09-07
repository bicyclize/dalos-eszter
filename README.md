# Dalos Eszter — mediáció · coaching · konzultáció

Egyoldalas weboldal Eszter Dalos segítői praxisának: mediáció, coaching, egyéni konzultáció.


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
gh repo create dalos-eszter --public --source=. --push
gh api repos/bicyclize/dalos-eszter/pages -f build_type=legacy -f source[branch]=main -f source[path]=/
```

Éles URL: https://bicyclize.github.io/dalos-eszter/
