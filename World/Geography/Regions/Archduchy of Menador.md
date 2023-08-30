---
Nation: Cheliax, Menador
Capital: Kantaria
Ruler: House Narikopolus
tag: 🗺️
---

> Named for the [[Menador Mountains]] that stretch across much of the region, the **Archduchy of Menador** encompasses a strip of northern [[Cheliax]] from [[Devil's Perch|Devils Perch]] in the west to [[Isger]] in the east. The archduchy lines Cheliax's northern border along the Menador Mountains, while the [[Barrowood]], [[Fields of Chelam]], and [[Whisperwood]] form the archduchy's southern border. Its capital is [[Kantaria]], located on the [[Sedna River]] north of the Barrowood, where [[House Narikopolus]] maintains its rule over the region under [[House Thrune]].



## Geography

<br>

![[Cheliax Map]]

<br>

### Settlements

```dataview
table
alignment,
size,
population,
region,
nation


from "World/Geography/Cities"
where contains(Nation, "Menador")
```

### Other Places

```dataview
table without id
file.link AS "Place"

from "World/Geography" AND -"World/Geography/Cities"
where contains(Nation, "Menador")
```








