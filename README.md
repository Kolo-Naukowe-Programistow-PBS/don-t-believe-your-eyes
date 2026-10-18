# 👀 Nie wierz własnym oczom!

## 1. Wymagania

- **Python 3.10–3.13 (64-bit)**
- **JupyterLab** albo **PyCharm**
- kamera (wbudowana albo USB)
- ok. 3 GB wolnego miejsca
- internet przy pierwszym uruchomieniu (albo gotowy folder `modele` z pendrive'a)


## 2. Pliki

Wszystko w jednym folderze:

```
warsztaty/
├── main.ipynb                       # notebook
├── answers.ipynb                    # odpowiedzi
├── tlo.jpg                          # tło do rundy 1 
├── modele/                          # modele AI
├── zdjecia/                         # zdjęcia kapibar 
│   ├── kapibara_garnitur.png
│   └── kapibara_trawa.jpg
└── probki/                          # filmy do rundy 6 (ai_….mp4, prawda_….mp4)
```

## 3. Instalacja (raz)

```bash
pip install jupyterlab
```

Resztę bibliotek (`mediapipe`, `pillow`, `transformers`, `torch`) instaluje sama pierwsza komórka notebooka.

> Laptop **bez karty NVIDIA**: w pierwszej komórce ustaw `KARTA_NVIDIA = False`. Inaczej na Windowsie pobierze się ok. 2 GB niepotrzebnej wersji `torch`.

## 4. Uruchomienie

Zalecane jest uruchomienie w przeglądarce JupyterLab

```bash
cd warsztaty
jupyter lab
```

1. W przeglądarce otwórz `main.ipynb`.
2. Kliknij pierwszą komórkę z kodem (komórka silnika) i naciśnij `Shift + Enter`.
3. Gdy przeglądarka zapyta o kamerę, kliknij **„Zezwól”**.
4. Pod komórką pojawi się test kamery. Widzisz siebie? Wszystko działa.