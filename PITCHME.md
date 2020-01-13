@snap[midpoint]
<img src="images/logo.png" width="251" height="59" alt="GitPitch logo" style="border:unset; background:unset; box-shadow:unset;"/>
@snapend

---

@snap[north-west]
## Inhoud
@snapend

* Wat is GitPitch?
* Slides maken
* Code in slides
* Media gebruiken
* Andere slides includen

---
@snap[north-west]
## Wat is GitPitch?
@snapend

* Markdown
* Thema's
* Op ontwikkelaars gericht
---
@snap[north-west]
## Slides maken
@snapend

```text
@snap[north-west]
## Een slide
@snapend

* Lijst
* Met
* Items
```
---
@snap[north-west]
## Een slide
@snapend

* Lijst
* Met
* Items
---
@snap[north-west]
## Code in slides
@snapend

```text
?code=src/example.kt&lang=kotlin&title=Syntax highlighting
@[2](Per regel)
```

@snap[south span-100]
Uit een apart bestand inladen
@snapend

---?code=src/example.kt&lang=kotlin&title=Syntax highlighting
@[2](Per regel)

---
@snap[north-west]
## Code in slides
@snapend

```text
@diff[span-100](23821e47df60bb851d553f9e66a715b83b64da0b)
```

@snap[south span-100]
Een diff uit Git tonen
@snapend
---

@diff[span-100](23821e47df60bb851d553f9e66a715b83b64da0b)

---
@snap[north-west]
## Media gebruiken
@snapend

```text
[Video](https://www.youtube.com/embed/3Kyre8R0DtI)
```

@snap[south span-100]
Een video van YouTube afspelen
@snapend

---
![Video](https://www.youtube.com/embed/3Kyre8R0DtI)

---
@snap[north-west]
## Media gebruiken
@snapend

```text
<canvas data-chart="bar">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[7,4,7,3,9,12,18],
    "label":"A",
    "backgroundColor":"rgba(20,20,220,.9)"
   },
   {
    "data":[6,5,7,8,3,2,1],
    "label":"B",
    "backgroundColor":"rgba(250,20,20,.9)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>
```

@snap[south span-100]
Een grafiek maken
@snapend
---
<canvas data-chart="bar">
<!--
{
 "data": {
  "labels": ["January"," February"," March"," April"," May"," June"," July"],
  "datasets": [
   {
    "data":[7,4,7,3,9,12,18],
    "label":"A",
    "backgroundColor":"rgba(20,20,220,.9)"
   },
   {
    "data":[6,5,7,8,3,2,1],
    "label":"B",
    "backgroundColor":"rgba(250,20,20,.9)"
   }
  ]
 },
 "options": { "responsive": "true" }
}
-->
</canvas>

---

@snap[north-west]
## Andere slides includen
@snapend

```text
?include=src/include.md
```

---?include=src/include.md

---

---

---
