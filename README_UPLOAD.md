# Ladislav Kupkovič — GitHub Pages upload-ready package

Nahraj celý obsah tohto priečinka do rootu repozitára `bofedo/kupkovic`.

Očakávaná štruktúra:

```
/index.html
/sk/index.html
/de/index.html
/images.jpeg
/favicon.svg
/robots.txt
/sitemap.xml
```

Súbory `images.jpeg` a `favicon.svg` musia zostať v roote repozitára. Tento balík ich nemení.

Po nahratí over:

```bash
curl -L https://www.ladislav-kupkovic.com/sk/ | grep "bTFi3DqmbTs"
curl -L https://www.ladislav-kupkovic.com/de/ | grep "bTFi3DqmbTs"
curl -L https://www.ladislav-kupkovic.com/sk/ | grep "rCvfuwzazqA"
```
