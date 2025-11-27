# Results summary component - Solución

Esta es mi solución al desafío [Results summary component de Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV).

## Tabla de contenidos

- [Descripción general](#descripción-general)
  - [El desafío](#el-desafío)
  - [Captura de pantalla](#captura-de-pantalla)
  - [Enlaces](#enlaces)
- [Mi proceso](#mi-proceso)
  - [Tecnologías usadas](#tecnologías-usadas)
  - [Qué aprendí](#qué-aprendí)
- [Autor](#autor)

## Descripción general

### El desafío

Los usuarios deben poder:

- Ver el diseño óptimo para la interfaz según el tamaño de pantalla de su dispositivo.
- Ver estados de "hover" y "focus" para todos los elementos interactivos en la página.

### Captura de pantalla

![](./assets/images/screenshot.png)
*(Nota: Asegúrate de tomar una captura de tu web final, guardarla en la carpeta assets/images con el nombre screenshot.png y subirla al repo para que se vea aquí)*

### Enlaces

- Solución en GitHub: [PON AQUÍ EL LINK DE TU REPOSITORIO]
- Sitio en vivo (Live Site): [PON AQUÍ EL LINK DE GITHUB PAGES]

## Mi proceso

### Tecnologías usadas

- HTML5 semántico
- CSS (Propiedades personalizadas / Variables)
- Flexbox
- CSS Grid
- Mobile-first workflow

### Qué aprendí

En este proyecto reforcé mis conocimientos sobre CSS moderno. Algunos de los puntos clave que aprendí fueron:

1. **Uso de gradientes:** Aprendí la diferencia entre `background-color` y `background` para aplicar `linear-gradient` correctamente.

```css
.resultados {
  background: linear-gradient(to bottom, var(--light-slate-blue), var(--light-royal-blue));
}
