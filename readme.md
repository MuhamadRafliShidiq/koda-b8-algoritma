Program yang akan kalian dibuat di mulai algoritma deskriptif, flowchart, dan pseudocode

# Algoritma Menghitung total biaya parkir

## Deskriptif

Memecahkan masalah menghitung total biaya parkir

1. Mulai
2. input jamMasuk dan jamKeluar
3. input jenis kendaraan 1 dengan motor dan 2 dengan mobil
4. hitung durasi dengan jika jamKeluar kurang dari jamMasuk maka asumsikan durasi ditambah 24
5. jika durasi kurang dari sama dengan 1 jam maka biaya untuk motor 2000, dan untuk mobil 5000
6. jika durasi lebih dari 1 jam
7. jika motor maka totalBiaya dengan 2000 ditambahkan dengan hasil dari durasi dikurang 1 dikali 1000
8. jika mobil maka totalBiaya dengan 5000 ditambahkan dengan hasil dari durasi dikurang 1 dikali 3000
9. Tampilkan totalBiaya parkir
10. selesai

## Flowchart

Memecahkan masalah menghitung total biaya parkir

```mermaid

    flowchart TD
    a@{ shape: circle, label: "Mulai" }
    b@{ shape: lean-r, label: "jamMasuk" }
    c@{ shape: lean-r, label: "jamKeluar" }
    d@{ shape: diamond, label: "jamKeluar < jamMasuk " }
    e@{ shape: rect, label: "durasi = (24 - jamMasuk) + jamKeluar" }
    f@{ shape: rect, label: "durasi = jamKeluar - jamMasuk" }
    g@{ shape: diamond, label: "durasi <= 1 " }
    h@{ shape: diamond, label: "jenisKendaraan == 1" }
    i@{ shape: diamond, label: "jenisKendaraan == 1" }
    j@{ shape: rect, label: "totalBiaya = 2000" }
    k@{ shape: rect, label: "totalBiaya = 5000" }
    l@{ shape: rect, label: "totalBiaya = 2000 + durasi  - 1" }
    m@{ shape: rect, label: "totalBiaya = 5000 + durasi  - 1" }
    n@{ shape: lean-r, label: "totalBiaya" }
    o@{ shape: dbl-circ, label: "Stop" }

    a --> b --> c --> d 

    d --True--> e 
    d --False--> f

    e --> g
    f --> g

    g --True--> h
    g --False--> i

    h --True--> j
    h --False--> k

    i --True--> l
    i --False--> m

    j --> n
    k --> n
    l --> n
    m --> n
    n --> o


```

## PSEUDO-CODE

```pseudo

    DECLARE jamMasuk, jamKeluar, durasi : INTEGER
    DECLARE totalBiaya : REAL
    
```
