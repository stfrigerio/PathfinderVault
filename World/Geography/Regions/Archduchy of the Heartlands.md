---
Nation: Cheliax
Capital: Egorian
tag: 🗺️
---

> The **Archduchy of the Heartlands** (often referred to just as the **Heartlands**) is the largest of the six archduchies of [[Cheliax]]. Located in the central section of the nation, the Heartlands is the nation's breadbasket and contains Cheliax's capital, [[Egorian]].

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
where contains(Nation, "Heartlands")
```

### Other Places

```dataview
table without id
file.link AS "Place"

from "World/Geography" AND -"World/Geography/Cities"
where contains(Nation, "Heartlands")
```




