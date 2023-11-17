---
title: Chuleta Markdown
date: 2023-11-17 11:00
categories: [Blog]
tags: [Tips, Markdown]
img_path: /assets/img/commons/1/
image: https://camo.githubusercontent.com/3e88f9f08b8d24d07a6fbffbac8e58ad2384cd500264dd80b30a144911088fb8/68747470733a2f2f692e696d6775722e636f6d2f575756707153392e706e67
pin: true
---

## Principal

---

Este es un mensaje de prueba para ver como se puede estructurar un post con markdown [^1].

En los siguientes bloques vamos a estructurar para poder sacar el scroll de contenido

## Formato de texto

---

Este texto está en cursiva: _hola_

Este texto está en negrita **hola**

Este texto está tachado: ~~The world is flat.~~

**Creamos una cita:**

> Estamos escribiendo una cita para destacar

**Creamos listas:**

- lista 1
- lista 2

1. hola
2. adios

**Enlaces:**

- [Adobe](https://www.adobe.com)

## Ejemplos de código

---

**Codigo en linea:**

`inline code part`

**Expandimos el código:**

```php
<?php
    echo 'hola mundo';
?>
```

```javascript
function holaMundo() {
  return "hola Mundo";
}
```

```sql
SELECT * FROM Users WHERE 1 == 1
```

{: .nolineno }

```bash
echo 'No vamos a poner números de línea en el código!'
```

**Anunciamos el fichero:**

{: file="./example.sh" }

{% raw %}

```javascript
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```

{% endraw %}

**Checklist seleccionado:**

- [x] Write the press release [^2]
- [ ] Update the website
- [ ] Contact the media

## Ejemplos embed

---

{% include embed/youtube.html id='H-B46URT4mg' %}
{% include embed/twitch.html id='1634779211' %}

## Definiciones

---

[^1]: Markdown es un estilo de formato...
[^2]: Esta es una segunda definición
