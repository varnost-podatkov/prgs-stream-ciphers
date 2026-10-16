# Psevdonaključni generatorji in tokovne šifre

Laboratorijska vaja pri predmetu Varnost in zasebnost. Navodila, ogrodja funkcij in javni testi so v zvezku **`assignment.ipynb`**.

V vaji implementirate dva psevdonaključna generatorja, dva razlikovalca, šifriranje in dešifriranje tokovne šifre ter napad na šifro z generatorjem LCG.
Implementacije so namenjene učenju in niso primerne za uporabo v praksi.

## Priprava okolja in zagon

Potrebujete sodobni Python (priporočeno 3.12 ali novejši) in pakete `jupyterlab` in `matplotlib`. Namestite jih z:

```sh
pip install -r requirements.txt
```

Nato iz korena repozitorija odprite zvezek:

```sh
jupyter lab assignment.ipynb
```

Zvezek in podatkovna mapa morata ostati skupaj:

```text
assignment.ipynb
data/
└── http-post-req.bin
```

Za samo kodo nalog zadostuje standardna knjižnica Python.

## Reševanje in preverjanje

- Dopolnite sedem funkcij v celicah z oznako `# VAŠA REŠITEV`.
- Ohranite podpise funkcij, imena, metapodatke zvezka in priložene teste. Po potrebi lahko dodajate svoje celice.
- Celice izvajajte po vrsti. Dokler rešitve niso dopolnjene, je `NotImplementedError` pričakovan. Napaka v pomožni funkciji lahko povzroči tudi neuspeh celic, ki jo uporabljajo.
- Javni testi so primeri za sprotno preverjanje; rešitev naj upošteva vse dogovore iz navodil, tudi robne primere.
- Izmerjene prednosti razlikovalcev so naključne ocene in med zagoni nihajo.

## Oddaja

Pred oddajo ponovno zaženite jedro in izvedite vse celice od začetka (**Restart Kernel and Run All Cells**). Preverite, da ni nepričakovanih napak.

V Moodle oddajte samo izpolnjeni **`assignment.ipynb`**. Mape `data/` in virtualnega okolja ne oddajajte.
