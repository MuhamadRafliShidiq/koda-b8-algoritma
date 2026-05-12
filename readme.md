Program yang akan kalian dibuat di mulai algoritma deskriptif, flowchart, dan pseudocode

# Algoritma Menghitung Luas dan Keliling Layang layang

## Deskriptif

Menghitung Luas dan Keliling Layang layang

1. Mulai
2. input/ masukan nilai diagonal satu
3. input/ masukan nilai diagonal dua
4. input/ masukan nilai a
5. input/ masukan nilai b
6. definisikan rumus luas Layang layang dengan 1/2 dikali diagonal satu dikali diagonal dua
7. definisikan rumus layang layang dengan 2 dikali (a ditambah b)
8. Tampilkan hasil luas dan keliling Layang layang
9. selesai

## Flowchart

Menghitung Luas dan Keliling Layang layang

```mermaid
    flowchart TD
    a@{ shape: circle, label: "Mulai" }
    b@{ shape: lean-r, label: "d1" }
    c@{ shape: lean-r, label: "d2" }
    d@{ shape: lean-r, label: "a" }
    e@{ shape: lean-r, label: "b" }
    f@{ shape: rect, label: "L = 1/2 x d1 x d2" }
    g@{ shape: rect, label: "K = 2 (a + b)" }
    h@{ shape: lean-r, label: "'{L}'" }
    i@{ shape: lean-r, label: "'{K}'" }
    j@{ shape: dbl-circ, label: "Stop" }

    a --> b --> c --> d --> e --> f --> g --> h --> i --> j
```

## PSEUDO-CODE

Menghitung Luas dan Keliling Layang layang

```pseudo
    DECLARE d1, d2, a, b : INTEGER

    INPUT d1, d2, a, b

    L <-- 1/2 * d1 * d2
        OUTPUT L
    K <-- 2 (a + b)
        OUTPUT K


```
