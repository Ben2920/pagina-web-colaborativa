# pagina-web-colaborativa
La página contiene secciones como:  Header y navegación  Sobre nosotros  Servicios  Contacto  Footer
pagina-web-colaborativa/
│
├── index.html
├── style.css
├── script.js
└── README.md
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Página Colaborativa</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- Header por Benito -->
  <header>
    <h1>Bienvenidos a nuestra página colaborativa</h1>
    <nav>
      <a href="#nosotros">Sobre Nosotros</a>
      <a href="#servicios">Servicios</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <!-- Sobre Nosotros por Kevin -->
  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>Contenido escrito por Kevin.</p>
  </section>

  <!-- Servicios por Ulises -->
  <section id="servicios">
    <h2>Servicios</h2>
    <p>Contenido escrito por Ulises.</p>
  </section>

  <!-- Contacto por Alejandro -->
  <section id="contacto">
    <h2>Contacto</h2>
    <form>
      <input type="text" placeholder="Tu nombre" required />
      <input type="email" placeholder="Tu correo" required />
      <textarea placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <!-- Footer por Miguel -->
  <footer>
    <p>&copy; 2025 Proyecto colaborativo</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header, footer {
  background-color: #333;
  color: white;
  padding: 1em;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 1em;
  text-decoration: none;
}

section {
  padding: 2em;
}
// JS simple por Miguel
document.querySelector("form").addEventListener("submit", function(e) {
  e.preventDefault();
  alert("Formulario enviado con éxito.");
});
// JS simple por Miguel
document.querySelector("form").addEventListener("submit", function(e) {
  e.preventDefault();
  alert("Formulario enviado con éxito.");
});
# Página Web Colaborativa

Este es un proyecto colaborativo desarrollado por el equipo como práctica de trabajo en grupo utilizando GitHub.

## 🚀 Instrucciones de instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/usuario/pagina-web-colaborativa.git

---

### ✅ **5. Resumen individual (cada uno hace uno)**

#### 📄 `resumen-benito.md`
```markdown
# Resumen de Benito Andre Serrano



Aprendí a usar GitHub en equipo, cómo hacer commits, crear ramas y hacer pull requests. También entendí cómo dividir un proyecto web para trabajar en colaboración.

## Opinión

Me pareció una herramienta útil y profesional. Me gustó cómo podemos ver el trabajo de todos y colaborar sin pisarnos los cambios.

## Experiencia

Tuve algunos problemas al principio con los conflictos, pero aprendí a resolverlos. Me gustó mucho trabajar de forma organizada y ver el resultado final en equipo.
