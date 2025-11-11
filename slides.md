---
# try also 'default' to start simple
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background:(https://imgs.search.brave.com/5weH8k_axgFSKVai5UEAzI8TKgBs0f3MDASYzrA6WdU/rs:fit:860:0:0:0/g:ce/aHR0cHM6Ly9tZWRp/YS5pc3RvY2twaG90/by5jb20vaWQvOTM2/MzM4ODg0L3Bob3Rv/L2NvbXB1dGVyLW1h/bHdhcmUtYXR0YWNr/LmpwZz9zPTYxMng2/MTImdz0wJms9MjAm/Yz1tYmtON3BSVGZF/b3JrOUFqbXBnMndm/aW9rNXUtazd0ejB0/TTBqQkE2eHhnPQ)
# some information about your slides (markdown enabled)
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 35min
---

# Social Engineer
<!-- **Jatziri Castro Guzmán y Nelly Naranjo Hernández** -->
<h2 class="bg-black-500 text-white px-6 py-3 rounded">Jatziri Castro Guzmán y Nelly Naranjo Hernández</h2>

<div @click="$slidev.nav.next" class="mt-12 py-2 cursor-pointer hover:bg-white hover:bg-opacity-20 rounded transition">
  Pulsa <kbd>Espacio</kbd> para siguiente página <carbon:arrow-right class="inline ml-2" />
</div>

<div class="abs-br m-6 text-xl flex gap-4">
  <button @click="$slidev.nav.openInEditor()" title="Abrir en Editor" class="slidev-icon-btn opacity-80 hover:opacity-100">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" class="slidev-icon-btn opacity-80 hover:opacity-100">
    <carbon:logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: slide-right
---

# ¿Qué es la ingeniería social?

<br>

- La **ingeniería social** es el arte y la ciencia de manipular a las personas para que revelen información confidencial, otorguen acceso o realicen acciones que beneficien al atacante.
- Se basa en el conocimiento de la **psicología humana**, la comunicación y el comportamiento, no en fallos técnicos.
- Es la base del **phishing**, vishing, pretexting, etc.

- **Importante**: la ingeniería social **no siempre es mala**. Depende de las intenciones y la ética de quien la use. Puede emplearse en auditorías de seguridad (pentesting ético) o en estafas.

- Es una **amenaza real y creciente** tanto en el mundo digital como físico, que afecta a personas, empresas y gobiernos.

<br><br>

<div @click="$slidev.nav.next" class="mt-12 py-2 cursor-pointer hover:bg-white hover:bg-opacity-20 rounded transition">
  Pulsa <kbd>Espacio</kbd> para siguiente página <carbon:arrow-right class="inline ml-2" />
</div>

<style>
body {
  background: linear-gradient(135deg, #2B90B6 0%, #0f5269 100%) !important;
}
</style>

---
transition: fade-out
layout: image-right
image: ./image/Fishing.webp
---

# Tipos de ingeniería social

<br>

- **Phishing**: Ataque online que utiliza correos falsos, SMS (smishing) o páginas web fraudulentas que imitan fuentes legítimas (bancos, Netflix, etc.) para robar credenciales, datos financieros o instalar malware.

<style>
h1 {
  background: linear-gradient(45deg, #bb4ed4 10%, #8c146e 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
transition: fade-out
layout: image-right
image: ./image/Vishing2.webp
---

# Tipos de ingeniería social

<br>

- **Vishing** (voice phishing): Llamadas telefónicas donde el atacante se hace pasar por alguien de confianza (banco, soporte técnico, policía) para obtener datos o convencer a la víctima de realizar acciones (ej. “has ganado un premio, dame tus datos bancarios”).

<style>
h1 {
  background: linear-gradient(45deg, #d48c4e 10%, #8c5614 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
transition: slide-down
layout: image-left
image: ./image/Baiting.webp
---

# Tipos de ingeniería social

<br>

- **Baiting**: Ataque físico que consiste en dejar dispositivos infectados (USB, CD) en lugares públicos con la esperanza de que la víctima los recoja y conecte, liberando malware.

<style>
h1 {
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
transition: slide-up
layout: image-right
image: ./image/Imper.png
---

# Tipos de ingeniería social

<br>

- **Impersonation** (suplantación): Hacerse pasar físicamente por otra persona (técnico, repartidor, policía) para acceder a zonas restringidas o información confidencial.

<style>
h1 {
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
layout: image-left
image: ./image/Pretexting.webp
---

# Tipos de ingeniería social

<br>

- **Pretexting**: Crear una historia falsa (emergencia, investigación, encuesta) para justificar la solicitud de información o cooperación de la víctima.

<style>
h1 {
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
layout: image-right
image: ./image/Protección.jpg
---

# ¿Cómo protegerme de la ingeniería social?

- **<spam class="text-sm">Protege tu información</spam>**: <spam class="text-sm">nunca compartas contraseñas, datos bancarios ni documentos con desconocidos. Cambia tus contraseñas periódicamente y usa autenticación de dos factores (2FA).</spam>
- **<spam class="text-sm">Verifica siempre la fuente</spam>**: <spam class="text-sm">no abras enlaces ni respondas mensajes/correos sospechosos. Comprueba remitente, número de teléfono y enlaces.</spam>
- **<spam class="text-sm">Desconfía de la urgencia</spam>**: <spam class="text-sm">los atacantes crean presión (“tu cuenta será bloqueada en 5 minutos”).</spam>
- **<spam class="text-sm">Educación continua</spam>**: <spam class="text-sm">formación en ciberseguridad para ti y tu equipo.</spam>

<style>
h1 {
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# CLAY

<br>

Ejemplo realista en la película **CLAY**  
[Ver vídeo en YouTube](https://www.youtube.com/watch?v=7tb55R1WJ1M)

---
layout: image-left
image: ./image/Twitter.jpg
---

# Caso real: ataque a Twitter (julio 2020)

- Uno de los mayores ataques de ingeniería social de la historia.
- Los atacantes **llamaron a empleados** fingiendo ser del soporte técnico interno (técnica de **pretexting**).
- Convencieron a un empleado de darles acceso a herramientas internas.
- Tomaron control de cuentas verificadas:  
  Elon Musk, Bill Gates, Barack Obama, Apple, Uber, Jeff Bezos…

<style>
h1 {
  background: linear-gradient(45deg, #4EC5D4 10%, #146b8c 90%);
  background-size: 100%;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>

---
layout: center
class: text-center
---

# El mensaje fraudulento

> “Estoy devolviendo a la comunidad.  
> Envía 1000 USD en Bitcoin y te devuelvo el doble.”

- En pocas horas robaron **más de 120 000 USD** en criptomonedas.
- Los responsables: **tres jóvenes** (uno de 17 años) de EE.UU. y Reino Unido.
- **No usaron código avanzado**, solo **llamadas y engaños**.

<br>

**Lección**: hasta las empresas más grandes caen por el factor humano.

---
layout: end
---

# ¡Gracias!

<h2 class="mt-20">Jatziri Castro Guzmán<br>Nelly Naranjo Hernández</h2>

<div class="mt-20 text-6xl">
  🙏😂😂😂😂😂😂
</div>
