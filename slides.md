---
theme: seriph
background: none
class: 'text-center'
highlighter: shiki
lineNumbers: false
info: |
  ## Mi travesía en el Desarrollo Web
  Una historia de aprendizaje continuo y crecimiento profesional.
drawings:
  persist: false
css: unocss

---

<div class="relative z-10">

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Mi travesía en el Desarrollo Web</span>

<span class="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-pink-400">Una historia de código, aprendizaje y perseverancia</span>

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Inicia el viaje 🚀 <carbon:arrow-right class="inline"/>
  </span>
</div>

</div>

---
layout: image-right
image: ./images/linkedin-profile-min.jpg
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">¿Quién soy?</span>

<v-clicks>

- 👋 Soy Francisco J. Lopez
- 💻 Full Stack Developer (8 años de experiencia)
- 🎯 Especializado en Frontend
- 🎓 Egresado del ITSTB en Sistemas Comunicacionales
- 🔐 Activista por la Privacidad y la Seguridad Digital
-  Entusiasta de Bitcoin y Blockchain

</v-clicks>

---
layout: two-cols
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Mi Experiencia Universitaria</span>

Lo que me llevé de la universidad:
<v-clicks>

- 🔥 Fundamentos sólidos de programación
- 🎯 Programación Orientada a Objetos
- 📊 Metodologías Ágiles (Scrum)
- 💎 Principios SOLID
- ⛁ Base de Datos
- 🧠 Patrones de Diseño

</v-clicks>

::right::

<div class="ml-4">
<v-click>

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-purple-400">Mi Mantra 🧘‍♂️</span>

<div class="text-center mt-4">
  <div class="text-xl text-blue-500">
    "Aprender a programar es fácil y divertido"
  </div>
</div>

</v-click>

<div v-click class="mt-8">
<img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHVtemtyZDZqY3JmZWR2dm52bDgweXQzdDYwN2NyNHNzNGd0cTV6bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/jtiGPJsGGXGD9edyb9/giphy.gif" class="rounded-lg shadow-xl" />
</div>
</div>

---
layout: cover
background: 'linear-gradient(135deg, #000428 0%, #004e92 100%)'
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Experiencia Laboral</span>

<div class="grid grid-cols-2 gap-4 mt-4">
<v-clicks>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(59,130,246,0.1)">
  <h3>Numenarts</h3>
  <p class="text-sm">Full Stack Developer</p>
  <p class="text-xs">HTML/CSS/JS, PHP, MySQL</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>BBVA</h3>
  <p class="text-sm">Full Stack Developer</p>
  <p class="text-xs">Web Components, Polymer, Java</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(236,72,153,0.1)">
  <h3>Linko</h3>
  <p class="text-sm">Frontend Developer</p>
  <p class="text-xs">Vue, React, TypeScript</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(139,92,246,0.1)">
  <h3>SkyAirlines</h3>
  <p class="text-sm">Frontend Developer</p>
  <p class="text-xs">Microfrontends, Storybook, Vue 3, ButterCMS</p>
</div>

</v-clicks>
</div>

---
layout: image-left
image: https://images.pexels.com/photos/3183150/pexels-photo-3183150.jpeg
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Evolución Profesional</span>

<v-clicks>

- 🌐 Transición al trabajo remoto post-pandemia (uso de herramientas digitales)
- 📚 Nunca pares de aprender
- 📈 Certificaciones y cursos en línea
- 🔍 Investigación de tendencias del mercado
- 💼 LinkedIn como herramienta fundamental
- 🤖 Talently: IA en la búsqueda laboral

</v-clicks>

<div v-click class="mt-4">
<img src="https://media.giphy.com/media/13GIgrGdslD9oQ/giphy.gif" class="w-48 rounded-lg shadow-xl" />
</div>

---
layout: two-cols
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Ejemplo Práctico: Proyecto de Cómics de Marvel</span>

<div class="text-sm">
  <p>Desarrollé una aplicación web que consume la API de Marvel para mostrar una lista de cómics. La aplicación incluye:</p>
  <ul>
    <li>Interfaz responsiva y estética.</li>
    <li>Lista de cómics con imágenes y títulos.</li>
    <li>Navegación a detalles del cómic con descripción y imagen ampliada.</li>
    <li>Optimización para velocidad y escalabilidad.</li>
  </ul>
  <p>Instrucciones y requerimientos:</p>
  <ol>
    <li>Diseño y estructura a discreción.</li>
    <li>Funciones para mejorar la experiencia del usuario.</li>
    <li>Código reutilizable y optimizado.</li>
  </ol>
</div>

::right::

<div class="ml-4">
  <a href="https://marvel-comics-explorer.netlify.app" target="_blank">Tienda de Comics de Marvel</a>
  <img src="./images/marvel-store.png" alt="Resultados del Proyecto" class="rounded-lg shadow-xl" />
  <img src="./images/marvel-store-2.png" alt="Resultados del Proyecto" class="rounded-lg shadow-xl mt-2" />
</div>

---
layout: center
background: 'radial-gradient(circle at center, #4a148c 0%, #311b92 100%)'
---

<div class="text-center">
  <h1 class="text-6xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-purple-400 via-pink-500 to-red-500 mb-8">
    Mapa de Ruta para el Éxito
  </h1>
  <div class="animate-bounce mt-4">
    <carbon:arrow-down class="text-4xl text-blue-400"/>
  </div>
</div>

---
layout: default
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Perfiles en Demanda</span>

<div class="grid grid-cols-3 gap-4 mt-4">
<v-clicks>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(59,130,246,0.1)">
  <h3>Frontend</h3>
  <p class="text-sm">HTML/CSS/JS, Vue, React, Astro, UI/UX,</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>Backend</h3>
  <p class="text-sm">Node.js, Python, BDD, APIs</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(139,92,246,0.1)">
  <h3>DevOps</h3>
  <p class="text-sm">CI/CD Tools, Docker, Linux (Bash), Nginx, Cloud Providers</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(234,179,8,0.1)">
  <h3>Mobile</h3>
  <p class="text-sm">Android, iOS, React Native, Flutter</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(239,68,68,0.1)">
  <h3>AI Engineer</h3>
  <p class="text-sm">ML, Deep Learning, Big Data</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(249,115,22,0.1)">
  <h3>Data Analyst</h3>
  <p class="text-sm">SQL, Python, Tableau</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(20,184,166,0.1)">
  <h3>Cloud Architect</h3>
  <p class="text-sm">AWS, Azure, GCP</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(236,72,153,0.1)">
  <h3>Security Engineer</h3>
  <p class="text-sm">Cybersecurity, Pentesting</p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(99,102,241,0.1)">
  <h3>Blockchain Dev</h3>
  <p class="text-sm">Solidity, Web3.js</p>
</div>

</v-clicks>
</div>

---
layout: center
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Frontend Developer Roadmap</span>
### Basado en [roadmap.sh](https://roadmap.sh)

```mermaid {scale: 0.7}
graph TD
    A[HTML/CSS/JS] --> B[Framework]
    B --> C[React]
    B --> D[Vue]
    B --> E[Angular]
    A --> F[Build Tools]
    F --> G[Vite]
    F --> H[Webpack]
    A --> I[State]
    I --> J[Zustand]
    I --> K[Pinia]
    A --> L[Testing]
    L --> M[Vitest]
    L --> N[Jest]
```

---
layout: cover
background: 'linear-gradient(135deg, #000428 0%, #004e92 100%)'
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Recursos de Aprendizaje</span>

<div class="grid grid-cols-2 gap-4 mt-4">
<v-clicks>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(59,130,246,0.1)">
  <h3>🎓 Plataformas</h3>
  <ul class="text-sm" style="list-style-type: none;">
    <li>Udemy</li>
    <li>Platzi</li>
    <li>freeCodeCamp</li>
    <li>Code With Mosh</li>
  </ul>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>📚 Libros</h3>
  <ul class="text-sm" style="list-style-type: none;">
    <li>"Eloquent JavaScript" - Marijn Haverbeke</li>
    <li>"You Don’t Know JS" - Kyle Simpson</li>
    <li>"Clean Code" - Robert C. Martin</li>
    <li>"Javascript para programadores impacientes" - Dr. Axel Rauschmayer</li>
  </ul>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(236,72,153,0.1)">
  <h3>👥 Comunidades</h3>
  <ul class="text-sm" style="list-style-type: none;">
    <li>Dev.to</li>
    <li>Stack Overflow</li>
    <li>GitHub</li>
    <li>Meetup</li>
    <li>Midudev</li>
  </ul>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(139,92,246,0.1)">
  <h3>📜 Certificaciones</h3>
  <ul class="text-sm" style="list-style-type: none;">
    <li>AWS Certified</li>
    <li>Azure Fundamentals</li>
    <li>Google Cloud</li>
  </ul>
</div>

</v-clicks>
</div>

---
layout: default
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">Redes</span>

<div class="grid grid-cols-2 gap-4 mt-4">
<v-clicks>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>📧 Contacto</h3>
  <p class="text-sm">Si tienes preguntas o deseas más información, no dudes en contactarme:</p>
  <p class="text-xs">Email: <a href="mailto:fcojavierlpz91@gmail.com">fcojavierlpz91@gmail.com</a></p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>📞 Número de Contacto</h3>
  <p class="text-sm">Puedes llamarme o enviarme un mensaje al siguiente número:</p>
  <p class="text-xs">Número: <a href="tel:+527776356753">+52 777 635 6753</a></p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>🔗 LinkedIn</h3>
  <p class="text-sm">Conéctate conmigo en LinkedIn:</p>
  <p class="text-xs">Perfil: <a href="https://www.linkedin.com/in/francisco-j-lopez-developer" target="_blank">in/francisco-j-lopez-developer</a></p>
</div>

<div class="p-4 rounded backdrop-blur-sm" style="background: rgba(16,185,129,0.1)">
  <h3>🌐 Página Web</h3>
  <p class="text-sm">Visita mi página web para más información:</p>
  <p class="text-xs">Sitio: <a href="https://fcojavierlpz.online" target="_blank">fcojavierlpz.online</a></p>
</div>

</v-clicks>
</div>

---
layout: center
class: text-center
---

# <span class="text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-emerald-400">¡Gracias por su atención!</span>

<div class="pt-12 space-y-4">
  <p class="text-xl">
    "El único modo de hacer un gran trabajo es amar lo que haces" - Steve Jobs
  </p>
  <div class="pt-4">
    <span class="px-4 py-2 rounded bg-blue-500 text-white">
      ¿Preguntas? 🤔
    </span>
  </div>
</div>