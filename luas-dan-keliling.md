# Algoritma

## Algotrima Luas dan Keliling Lingkaran

## Deskriptif

Membuat Algoritma menghitung luas dan keliling lingkaran

1. Mulai
2. definisikan konstanta phi dengan 3,14
3. masukan nilai jari jari lingkaran
4. definisikan rumus luas lingkaran yaitu Luas dengan 3,14 dikali jari-jari pangkat dua
5. definisikan rumus keliling lingkaran dengan 2 dikali 3,14 dikali nilai jari-jari
6. Tampilkan hasil luas dan keliling lingkaran
7. selesai

## Flowchart

Membuat Algoritma menghitung luas dan keliling lingkaran

```mermaid

    flowchart TD

    a@{ shape: circle, label: "Mulai" }
    b@{ shape: rect, label: "TT = 3,14" }
    c@{ shape: lean-r, label: " r" }
    d@{ shape: rect, label: "L = 3,14 x r x r " }
    e@{ shape: rect, label: "K = 2 x 3,14 x r " }
    f@{ shape: lean-r, label: "'{L}'" }
    g@{ shape: lean-r, label: "'{K}'" }
    h@{ shape: dbl-circ, label: "Stop" }

    a --> b
    b --> c
    c --> d
    d --> e
    e --> f
    f --> g
    g --> h

```
