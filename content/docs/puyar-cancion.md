---
title: Puyar una canción
weight: 1
next: /docs/correccions
prev: /docs
---

Las pachinas d'Acordes en aragonés siguen lo formato [Markdown](https://es.wikipedia.org/wiki/Markdown). Pa puyar la transcripción d'una canción, sigue los siguients pasos.

{{% steps %}}

### Copia la plantilla d'acordes

Copia la siguient plantilla en un procesador de texto como lo Bloc de notas u Word:

```
---
title: "Titulo d'a cancion"
date: 2024-01-01
authors:
  - name: autor
groups:
  - Grupo
years:
  - 2024 
genres:
  - Chenero
excludeSearch: false
draft: false
---

      C
Ta Boltaña he de baxar
      G7
dende Silbes a estudiar,
     C             F          G7
o maitin prenzipia ya a dispertar
```

### Replena la plantilla

Replena la plantilla con os siguients datos:

| Dato | Conteniu | Eixemplo |
| :--- | :------- | :------- |
| `title` | Títol d'a canción (entre cometas) | "L'alentar d'as Piedras" |
| `date` | Día que tu creas l'acorde (formato: anyo-mes-dia) | 2024-09-18 |
| `name` | Lo nombre que quiers que amaneixca en la publicación | lekinu |
| `groups` | Grupo u cantaire orichinal d'a canción | Isabel Marco |
| `years` | Anyo de publicación orichinal d'a canción | 2020 |
| `genres` | Chenero d'a canción (aproximau) | Pop |

Deixa los campos `excludeSearch` y `draft` como bi son. Dimpués, debaixo de las tres rayetas (`---`), prencipia a replenar la plantilla con a letra y acordes d'a canción. Ye muit important que los acordes dentren en lo momento exacto. Mira-te ista estrofa, per eixemplo:

```
F#m                D
 Buen día, María Loísa,
A                  E
 le fa goi d’amaitinar,
F#m              D
 ha sacau as gallinas
A                   E
 mesmo antes d’almorzar
```

En [iste enlaz](https://raw.githubusercontent.com/liugel/acordes-aragones/main/content/acordes/isabel-marco_alentar-das-piedras.md) puez veyer cómo quedaría una plantilla completa.

### Ninvía la plantilla

Ninvía la plantilla completa a [acordesaragones@gmail.com](mailto:acordesaragones@gmail.com). La plantilla será revisada y se te contactará si ye menester completar bel dato.

{{< callout type="warning" >}}
  Antes de ninviar la canción, revisa las [reglas d'uso](/docs/reglas).
{{< /callout >}}

Si la transcripción cumple las reglas d'uso y tien toz los datos necesarios, se t'avisará por correu electronico y se publicará en a web.

{{% /steps %}}
