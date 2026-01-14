# Interactive Math Experiences

Colección de experiencias interactivas de matemáticas diseñadas para enseñar conceptos de forma visual y participativa. Cada experiencia es un archivo HTML standalone que puede abrirse directamente en cualquier navegador moderno.

## 🎯 Propósito

Estas experiencias demuestran cómo la interactividad puede mejorar el aprendizaje matemático, permitiendo a los estudiantes:
- Explorar conceptos manipulando elementos visuales
- Ver relaciones matemáticas en tiempo real
- Descubrir propiedades a través de la experimentación
- Completar desafíos que refuerzan el aprendizaje

## 📁 Estructura

```
interactive-math/
├── README.md
└── examples/
    └── geometry-puzzle.html    # Puzzle interactivo de geometría
```

## 🚀 Cómo Usar

### Opción 1: Abrir Directamente
1. Navega a la carpeta `examples/`
2. Abre cualquier archivo `.html` en tu navegador
3. ¡Listo! No necesitas servidor ni dependencias

### Opción 2: Servidor Local (Recomendado)
```bash
# Desde la carpeta interactive-math
python3 -m http.server 8000
# O con Node.js
npx serve examples
```
Luego abre `http://localhost:8000/geometry-puzzle.html` en tu navegador.

## 📤 Cómo Compartir

### GitHub Pages
1. Sube la carpeta `interactive-math/` a un repositorio de GitHub
2. Ve a Settings > Pages
3. Selecciona la rama y carpeta `interactive-math/examples/`
4. Comparte el link: `https://tu-usuario.github.io/repo/geometry-puzzle.html`

### Netlify Drop
1. Ve a [netlify.com/drop](https://app.netlify.com/drop)
2. Arrastra la carpeta `examples/`
3. Obtén un link instantáneo para compartir

### Vercel
```bash
cd examples
vercel
```

### Como Archivo
Simplemente comparte el archivo `.html` - funciona completamente offline.

## 🎮 Experiencias Disponibles

### Geometry Puzzle (`geometry-puzzle.html`)

**Conceptos Enseñados:**
- Propiedades de triángulos
- Cálculo de ángulos y lados
- Tipos de triángulos (equilátero, isósceles, escaleno, rectángulo)
- Área de triángulos
- Relaciones geométricas

**Características:**
- ✅ Arrastrar puntos para construir triángulos
- ✅ Medidas en tiempo real (lados, ángulos, área)
- ✅ Detección automática del tipo de triángulo
- ✅ Modo libre y modo desafío
- ✅ Visualización de ángulos con arcos
- ✅ Feedback visual al interactuar

**Cómo Usar:**
1. Arrastra los puntos rojos (A, B, C) para mover los vértices
2. Observa cómo cambian las medidas en tiempo real
3. Prueba el Modo Desafío para completar objetivos específicos
4. Usa el botón "Ejemplo" para ver un triángulo equilátero

## 🛠️ Tecnologías Utilizadas

- **HTML5 Canvas**: Para renderizado de gráficos
- **JavaScript Vanilla**: Sin dependencias externas
- **CSS3**: Estilos modernos con gradientes y animaciones
- **requestAnimationFrame**: Para animaciones suaves

## 📚 Conceptos Matemáticos Cubiertos

### Geometría
- Distancia euclidiana entre puntos
- Cálculo de ángulos usando producto punto
- Área de triángulos (fórmula del determinante)
- Clasificación de triángulos por lados y ángulos
- Propiedades de triángulos especiales

## 🎨 Principios de Diseño

Estas experiencias siguen principios de diseño de aprendizaje interactivo:

1. **Manipulación Directa**: Los estudiantes interactúan directamente con los conceptos matemáticos
2. **Feedback Inmediato**: Los cambios se reflejan instantáneamente
3. **Visualización Clara**: Elementos visuales que ayudan a entender relaciones
4. **Progresión Guiada**: Desafíos que guían el descubrimiento
5. **Exploración Libre**: Modo libre para experimentación sin restricciones

## 🔮 Próximas Experiencias

- Explorador de funciones cuadráticas
- Visualización de derivadas
- Transformaciones de funciones
- Círculo unitario interactivo
- Explorador de probabilidad

## 📝 Notas para Desarrolladores

Cada archivo HTML es completamente autocontenido:
- No requiere build process
- No tiene dependencias externas
- Funciona offline
- Compatible con todos los navegadores modernos

El código está comentado para facilitar la comprensión y modificación.

## 🤝 Contribuir

Para agregar nuevas experiencias:
1. Crea un nuevo archivo HTML en `examples/`
2. Sigue la estructura de los ejemplos existentes
3. Actualiza este README con la descripción
4. Asegúrate de que sea standalone y funcione offline

## 📄 Licencia

Este proyecto es parte del portfolio de experiencias educativas interactivas.

---

**Creado para demostrar habilidades en diseño de aprendizaje interactivo y visualización matemática.**



