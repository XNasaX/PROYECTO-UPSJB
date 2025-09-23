# 🎯 Simulador de Tiro Parabólico - Juego Educativo DEMO V 0.15.1

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

Un simulador interactivo de física que enseña los principios del tiro parabólico a través de un juego divertido y educativo. Perfecto para estudiantes, profesores y cualquier persona interesada en aprender física de manera práctica.

![Simulador de Tiro Parabólico](screenshot.png)

## 🚀 Características Principales

### 🎮 **Modos de Juego**
- **📚 Tutorial** - Aprende los controles básicos paso a paso
- **🎯 Práctica** - Modo libre para experimentar sin límites  
- **⚡ Desafío** - Misiones con objetivos específicos y restricciones
- **🔬 Experimento** - Cambia variables físicas y observa los resultados

### 🔬 **Educación Interactiva**
- **Física en Tiempo Real** - Visualiza velocidades, componentes y energía
- **Análisis de Disparos** - Feedback detallado de cada tiro
- **Predicción de Trayectoria** - Ve el camino antes de disparar
- **Cálculos Reales** - Ecuaciones físicas auténticas
- **Variables Ajustables** - Modifica gravedad, ángulo y velocidad

### 🎯 **Sistema de Misiones**
- **Tutorial Básico** - Primer contacto con el simulador
- **Misión de Precisión** - Destruye blancos con disparos limitados
- **Desafío Físico** - Usa solo ciertos rangos de ángulos
- **Eficiencia Máxima** - Obtén la mayor puntuación con menos disparos
- **Experimento Gravitacional** - Juega con diferentes valores de gravedad

## 🎲 **Mecánicas de Juego**

### Controles
- **Ratón/Touch**: Ajustar parámetros con sliders
- **Teclado**: 
  - `↑/↓` - Ajustar ángulo
  - `←/→` - Ajustar potencia
  - `ESPACIO` - Disparar
  - `R` - Reiniciar
  - `1-4` - Cambiar modo de juego

### Física Implementada
- Movimiento proyectil con gravedad variable
- Componentes de velocidad (Vx, Vy)
- Cálculo de trayectoria en tiempo real
- Energía cinética y potencial
- Tiempo de vuelo y altura máxima

## 📋 Requisitos del Sistema

- Navegador web moderno (Chrome, Firefox, Safari, Edge)
- JavaScript habilitado
- Canvas HTML5 compatible
- Resolución mínima: 800x600px

## 🚀 Instalación y Uso

### Opción 1: Uso Directo
1. Descarga el archivo `index.html`
2. Abre el archivo en cualquier navegador web moderno
3. ¡Comienza a jugar y aprender!

### Opción 2: Clonar Repositorio
```bash
git clone https://xnasax.github.io/PROYECTO-UPSJB/
cd simulador-tiro-parabolico
```

### Opción 3: GitHub Pages
Visita la versión en vivo: [https://tu-usuario.github.io/simulador-tiro-parabolico](https://xnasax.github.io/PROYECTO-UPSJB/)

## 🎯 Objetivos Educativos

### Conceptos Físicos Cubiertos
- **Cinemática**: Movimiento en dos dimensiones
- **Vectores**: Descomposición de velocidad
- **Gravedad**: Aceleración constante
- **Energía**: Transformación cinética-potencial
- **Balística**: Trayectoria de proyectiles
- **Optimización**: Ángulo óptimo para máximo alcance

### Habilidades Desarrolladas
- ✅ Análisis de datos en tiempo real
- ✅ Pensamiento crítico y resolución de problemas
- ✅ Comprensión de relaciones causa-efecto
- ✅ Aplicación práctica de matemáticas
- ✅ Experimentación científica

## 📊 Datos Técnicos

### Ecuaciones Implementadas
```javascript
// Componentes de velocidad
vx = v₀ * cos(θ)
vy = v₀ * sin(θ)

// Tiempo de vuelo
t = 2 * vy / g

// Altura máxima  
h_max = vy² / (2 * g)

// Alcance máximo
R = v₀² * sin(2θ) / g

// Energía cinética
Ek = ½ * m * v²
```

### Performance
- **FPS**: 60 fps constantes
- **Responsive**: Adaptable a móviles y tablets
- **Optimizado**: Canvas HTML5 con animaciones suaves
- **Ligero**: < 50KB total

## 🛠️ Estructura del Proyecto

```
📁 simulador-tiro-parabolico/
├── 📄 index.html          # Archivo principal del juego
├── 📄 README.md           # Este archivo
├── 📄 LICENSE             # Licencia MIT
├── 📁 assets/
│   ├── 🖼️ screenshot.png   # Captura de pantalla
│   └── 🖼️ demo.gif        # GIF demostrativo
└── 📁 docs/
    ├── 📄 physics.md      # Documentación de física
    ├── 📄 gameplay.md     # Guía de gameplay
    └── 📄 educational.md  # Guía educativa
```

## 🎨 Personalización

### Modificar Variables Físicas
```javascript
// En el código JavaScript, puedes ajustar:
game.physicsData = {
    mass: 1,        // Masa del proyectil (kg)
    gravity: 9.8    // Gravedad (m/s²)
};
```

### Crear Nuevas Misiones
```javascript
// Agregar al array de misiones:
{
    type: 'custom',
    description: 'Tu misión personalizada',
    target: 3,
    reward: 200,
    specialCondition: true
}
```

### Cambiar Apariencia
- Modifica los colores en las variables CSS
- Ajusta el tamaño del canvas
- Personaliza efectos visuales

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Por favor:

1. **Fork** el repositorio
2. **Crea** una rama para tu feature (`git checkout -b feature/nueva-caracteristica`)
3. **Commit** tus cambios (`git commit -am 'Agregar nueva característica'`)
4. **Push** a la rama (`git push origin feature/nueva-caracteristica`)
5. **Crea** un Pull Request

### Ideas para Contribuir
- 🎯 Nuevos modos de juego
- 🎨 Mejoras visuales
- 🔬 Más variables físicas
- 📚 Contenido educativo adicional
- 🌐 Traducciones a otros idiomas
- 📱 Mejoras responsive

## 🐛 Reportar Bugs

Si encuentras algún problema:
1. Ve a la pestaña **Issues**
2. Crea un **New Issue**  
3. Describe el problema detalladamente
4. Incluye pasos para reproducirlo
5. Agrega capturas de pantalla si es posible

## 📚 Documentación Adicional

- **[Guía Física](docs/physics.md)** - Explicación detallada de las ecuaciones
- **[Guía de Gameplay](docs/gameplay.md)** - Cómo jugar y estrategias
- **[Guía Educativa](docs/educational.md)** - Uso en aulas y objetivos de aprendizaje

## 🏆 Logros y Estadísticas

El juego incluye un sistema de seguimiento que permite:
- Seguimiento de precisión histórica
- Mejor tiro realizado
- Progreso en misiones
- Tiempo invertido aprendiendo
- Conceptos físicos dominados

## 🔮 Roadmap - Próximas Características

### Versión 0.20.1 (HTML5 Mejorado)
- [ ] Blancos móviles
- [ ] Efectos de viento
- [ ] Obstáculos en el terreno
- [ ] Multijugador local
- [ ] Guardado de progreso

### Versión 0.1.0 (Unity)
- [ ] Gráficos 3D
- [ ] Física avanzada (resistencia del aire)
- [ ] Diferentes planetas/gravedades
- [ ] Realidad virtual (VR) - IDEA SIN EJECUTAR
- [ ] Simulación de múltiples proyectiles

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

```
MIT License

Copyright (c) 2025 [DIBUJITOS DESING]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

## 👨‍💻 DIBUJITOS DESING

**[DIBUJITOS DESING]**
- GitHub: [@XNasaX](https://github.com/XNasaX)
- Email: naza.dr.off@gmail.com

## 🙏 Agradecimientos

- Inspirado por los principios de física de Newton
- Gracias a la comunidad educativa por el feedback
- Agradecimiento especial a profesores de física que validaron el contenido
- Canvas HTML5 y las tecnologías web que hacen esto posible
- PROFE DE CALCULO - I LOVE YOU FOR ORIUNDO

## ⭐ ¡Apoya el Proyecto!

Si te gusta este proyecto:
- ⭐ Dale una estrella en GitHub
- 🔄 Compártelo con otros educadores
- 🐛 Reporta bugs o sugiere mejoras  
- 🤝 Contribuye con código
- 💬 Deja feedback en las Issues

---

<div align="center">

**[🎯 JUGAR AHORA](https://xnasax.github.io/PROYECTO-UPSJB/) | [📚 DOCUMENTACIÓN](docs/) | [🐛 REPORTAR BUG](https://github.com/tu-usuario/simulador-tiro-parabolico/issues)**

*"La física es divertida cuando puedes experimentar con ella interactivamente"*

![Física](https://img.shields.io/badge/Física-Cinemática-blue?style=flat-square)
![Educación](https://img.shields.io/badge/Educación-Interactiva-green?style=flat-square)  
![Juego](https://img.shields.io/badge/Juego-Educativo-orange?style=flat-square)

</div>
