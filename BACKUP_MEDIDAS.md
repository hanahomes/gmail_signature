# Backup de Medidas Originales - Gmail Signature

## Medidas Anteriores (antes de la reducción del 25%)

### Contenedor Principal
- **max-width**: 630px
- **padding contenedor**: 15px

### Texto Principal
- **Nombre**: 28px
- **Título**: 16px
- **Enlaces contacto**: 14px

### Iconos y Espaciado
- **Iconos contacto**: 16px width
- **Margen iconos**: 10px right
- **Espaciado entre filas**: 6px bottom

### Redes Sociales
- **Botones sociales**: 50px × 80px
- **Iconos dentro**: 24px × 24px
- **Separación entre botones**: 8px

### Columnas
- **Padding columna nombre**: 30px right
- **Padding columna contacto**: 15px right
- **Min-width tabla contacto**: 180px

## CSS Transform Anterior (no funcionaba en Gmail)
```css
@media only screen and (min-width: 601px) {
  .signature-container {
    transform: scale(0.75);
    transform-origin: left top;
    width: 75%;
  }
}
```

## Medidas Actuales (reducidas 25%)
- **max-width**: 472px
- **Nombre**: 21px
- **Título**: 12px
- **Enlaces**: 10.5px
- **Iconos**: 12px
- **Botones sociales**: 37px × 60px
- **Iconos sociales**: 18px × 18px
- **Padding**: 11px
- **Separación botones**: 6px

Para restaurar las medidas originales, usar los valores de la sección "Medidas Anteriores".