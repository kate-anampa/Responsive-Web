# RESPONSIVE WEB
 
Es para adaptar nuestras aplicaciones web a la mayor cantidad de pantallas ya sea tablet, smartphone 📱 y desktop 🖥️.


## Media Queries

El media queries es un módulo de css que hace posible al responsive design, se encarga de adaptar la representación del contenido a características del dispositivo.

**Estructura del Media Querie**:

```css
@media media type and (condición) { }
```

**Ejemplos**:

```css
/* Todas las pantallas con con un ancho inferior o igual a 768px cumplen esta condición */
@media screen and (max-width: 768px) { }

/* Todas las pantallas con un ancho de 480px hasta 768px cumplen esta condición */
@media screen and (max-width: 768px)  and (min-width: 480px) { }
```

**Mobile**

Usa min-width  
min-width = desde

```css
@media screen and (min-width: 320px)  { }
@media screen and (min-width: 480px)  { }
@media screen and (min-width: 768px)  { }
@media screen and (min-width: 1024px)  { }
```

**Desktop**

Usa max-width  
max-width = hasta

```css
@media screen and (max-width: 1024px)  { }
@media screen and (min-width: 768px)  { }
@media screen and (min-width: 480px)  { }
@media screen and (min-width: 320px)  { }
```


## 🛠 Skills
HTML, CSS, SCSS...

## Authors

- [@Katherin-Anampa](https://www.github.com/kate-anampa)