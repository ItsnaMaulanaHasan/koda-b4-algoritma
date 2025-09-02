# Flowchart untuk program menentukan bilangan ganjil dan genap

```mermaid
---
    title: Menentukan bilangan ganjil dan genap
---
flowchart TD
    id1((Start))
    id2[/bilangan/]
    id1 --> id2
    id3[hasil = bilangan % 2]
    id2 --> id3
    id4{hasil = 0}
    id3 --> id4
    id5[/''ganjil''/]
    id6[/''genap''/]
    id7(((stop)))
    id4 -- True --> id6 --> id7
    id4 -- False --> id5 --> id7
```