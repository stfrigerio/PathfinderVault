---
Nation: Cheliax, Longmarch
Capital: Corentyn
Ruler: House Charthagnion
tag: 🗺️
---

> The **Archduchy of Longmarch** (often referred to just as **Longmarch**) is the south-westernmost of the six archduchies of the nation of [[Cheliax]]. It encompasses the [[Inner Sea]] coast of the nation from the [[River Iseld]] in the east, all the way through the [[Hespereth Strait]] to the delta of the [[Maiestas River]] on the [[Arcadian Ocean]], and includes the province of [[Kharijite]] in northern [[Garund]].



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
where contains(Nation, "Longmarch")
```

### Other Places

```dataview
table without id
file.link AS "Place"

from "World/Geography" AND -"World/Geography/Cities"
where contains(Nation, "Longmarch")
```





