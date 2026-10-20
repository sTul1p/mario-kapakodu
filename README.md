# Mario Käpakodu

## Kirjeldus

Mario Käpakodu on loomade varjupaiga veebirakendus, mis võimaldab külastajatel tutvuda varjupaigas olevate loomadega ning administraatoril hallata kogu varjupaiga infot.

Projekti praegune etapp (**Ülesanne 01**) on kasutajaliidese loomine HTML-i, CSS-i ja Bootstrap 5 abil. PHP ja MySQL lisatakse järgmistes peatükkides.

## Kasutatud tehnoloogiad

* HTML5
* CSS3
* [Bootstrap 5.3](https://getbootstrap.com/)
* [Font Awesome 7](https://fontawesome.com/)
* Git ja GitHub

## Projekti struktuur

```
mario-kapakodu/
├── index.html          # avaleht
├── all\_animals.html    # kõik loomad (otsing, filtrid, lehekülgede vahetamine)
├── animal.html         # looma detailvaade
├── contact.html        # kontaktileht
├── login.html          # sisselogimisleht
├── admin/
│   ├── index.html        # administraatori avaleht
│   ├── animals.html      # loomade haldamine
│   └── animal\_add.html   # looma lisamise/muutmise vorm
├── assets/
│   ├── css/style.css
│   └── images/
└── README.md
```

## Vaated

|Fail|Kirjeldus|
|-|-|
|`index.html`|Päis, hero, missioon, loomade kaardid, jalus|
|`all\_animals.html`|Kõik loomad kaartidena, otsing, filtrid, pagination|
|`animal.html`|Breadcrumb, looma pilt ja andmed, huvi avaldamise nupp|
|`contact.html`|Kontaktandmed ja kontaktivorm|
|`login.html`|Sisselogimisvorm|
|`admin/index.html`|Statistika, viimased loomad ja päringud|
|`admin/animals.html`|Loomade tabel, otsing, filtrid, Vaata/Muuda/Kustuta|
|`admin/animal\_add.html`|Looma andmete vorm koos pildi üleslaadimisega|

## Käivitamine

Ava `index.html` brauseris (topeltklõps või VS Code'i Live Server).
Bootstrap ja Font Awesome laetakse CDN-ist, seega on vaja internetiühendust.

## Hindamismudel

### Front-end ehk avalik osa

* \[x] Veebirakendusel on avaleht, kus kuvatakse loomade nimekiri koos piltidega
* \[x] Loomi saab otsida nime järgi (kasutajaliides)
* \[x] Loomi saab filtreerida (kasutajaliides)
* \[x] Looma valimisel kuvatakse tema detailvaade (kasutajaliides)
* \[x] Külastaja saab saata päringu kontaktivormi kaudu (kasutajaliides)
* \[x] Veebirakendus kohandub erinevate ekraanisuurustega
* \[x] Veebivormid sisaldavad kliendipoolset valideerimist (HTML5 `required`, `type="email"`)

### Back-end ehk haldus

* \[ ] Administraator saab sisse logida
* \[ ] Administraator saab hallata loomade andmeid (lisada, muuta ja kustutada CRUD)
* \[ ] Administraator saab hallata liikide andmeid
* \[ ] Administraator saab hallata tõugude andmeid
* \[ ] Administraator saab hallata kasutajate andmeid
* \[ ] Administraator saab hallata saabunud kontaktipäringuid
* \[ ] Administraator näeb veebirakenduse statistikat

### Tehnilised nõuded

* \[x] Veebirakendus kasutab HTML-i, CSS-i ja Bootstrapi
* \[ ] Veebirakendus kasutab PHP-d andmete töötlemiseks
* \[ ] Andmed salvestatakse MySQL andmebaasi
* \[x] Veebirakendus kohandub erinevate ekraanisuurustega (responsive disain)
* \[x] Veebivormid sisaldavad kliendipoolset valideerimist
* \[ ] Veebirakendus järgib kursuse jooksul õpitud turvalise programmeerimise põhimõtteid
* \[x] Lähtekood on korrektselt struktureeritud ja loetav
* \[ ] Projekt on hallatud Gitiga ja üles laaditud GitHubi
* \[x] Projekt sisaldab ajakohast README.md faili

## Autor

Sander Tulp

