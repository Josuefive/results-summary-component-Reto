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
![](./assets/images/movil.png)

### Enlaces

- Solución en GitHub: [Ver código aquí](https://github.com/Josuefive/results-summary-component-Reto)
- Sitio en vivo (Live Site): [Ver página web aquí](https://josuefive.github.io/results-summary-component-Reto/)

## Mi proceso

### Tecnologías usadas

- HTML5 semántico
- CSS (Propiedades personalizadas / Variables)
- Flexbox
- CSS Grid
--El metodo BEM para las el nombre de las clases

### Qué aprendí

En este proyecto reforcé mis conocimientos sobre CSS moderno. Algunos de los puntos clave que aprendí fueron:

1. **Uso de gradientes:** Aprendí la diferencia entre `background-color` y `background` para aplicar `linear-gradient` correctamente.

```css
.resultados {
  background: linear-gradient(to bottom, var(--light-slate-blue), var(--light-royal-blue));
}
