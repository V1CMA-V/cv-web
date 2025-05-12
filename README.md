

<div align="center">
<img src="VICMA-Logo-WEB.webp" height="90px" width="auto" />
<h2>
    CV Web Personal
</h2>
<p>
Un currículum vitae web moderno y minimalista, optimizado para impresión en PDF
</p>

<p>
Utiliza el estándar <a href="https://jsonresume.org/schema/">JSON Resume</a> para estructurar la información
</p>
</div>

<div align="center">
    <a href="#🚀-empezar">
        Empezar
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🧞-comandos">
        Comandos
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="#🔑-licencia">
        Licencia
    </a>
    <span>&nbsp;✦&nbsp;</span>
    <a href="https://midu.dev">
        Personal
    </a>

</div>

<p></p>

<div align="center">

![Astro Badge](https://img.shields.io/badge/Astro-BC52EE?logo=astro&logoColor=fff&style=flat)
![GitHub stars](https://img.shields.io/github/stars/midudev/minimalist-portfolio-json)
![GitHub issues](https://img.shields.io/github/issues/midudev/minimalist-portfolio-json)
![GitHub forks](https://img.shields.io/github/forks/midudev/minimalist-portfolio-json)
![GitHub PRs](https://img.shields.io/github/issues-pr/midudev/minimalist-portfolio-json)

</div>
## Inspiracion

![Inspiration](https://github.com/midudev/minimalist-portfolio-json)

## 🛠️ Características

- **Diseño Minimalista**: Interfaz limpia y profesional
- **Responsive**: Adaptable a todos los dispositivos
- **Modo Oscuro**: Cambio automático según preferencias del sistema
- **Exportación a PDF**: Versión optimizada para impresión
- **SEO Optimizado**: Mejor visibilidad en buscadores

## 💻 Tecnologías

- [**Astro**](https://astro.build/) - Framework web ultrarrápido y ligero
- [**Typescript**](https://www.typescriptlang.org/) - Desarrollo robusto y tipado
- [**Ninja Keys**](https://github.com/ssleptsov/ninja-keys) - Navegación rápida por teclado


## 🚀 Empezar

### 1. Configuración Inicial

```bash
# Instala las dependencias
pnpm install

# O si prefieres usar npm
npm install
```

### 2. Personalización

Edita el archivo `cv.json` en la raíz del proyecto para actualizar tu información personal:

```json
{
  "basics": {
    "name": "Tu Nombre",
    "label": "Tu Profesión",
    "email": "tu@email.com"
  },
  ...
}
```
### 3. Lanza el servidor de desarrollo:

```bash
# Disfruta del resultado
pnpm dev
```


1. Abre [**http://localhost:4321**](http://localhost:4321/) en tu navegador para ver el resultado 🚀


## 🧞 Comandos

|     | Comando          | Acción                                        |
| :-- | :--------------- | :-------------------------------------------- |
| ⚙️  | `dev` o `start` | Lanza un servidor de desarrollo local en  `localhost:4321`.  |
| ⚙️  | `build`          | Comprueba posibles errores y hace un empaquetado de producción en `./dist/`.      |
| ⚙️  | `preview`        | Vista previa en local `localhost:4321` |



## 🔑 Licencia

[MIT](LICENSE.txt) - Desarrollado con ❤️ usando Astro



