# Notebook: Piratería de Juegos

## 1. Introducción
Este documento analiza la **piratería de videojuegos**, sus causas, consecuencias y métodos de prevención.  
Se enfoca en cómo afecta a la industria, a los desarrolladores y a los jugadores.

## 2. Objetivo
- Entender qué es la piratería de juegos y por qué ocurre.
- Identificar los impactos económicos, legales y sociales.
- Explorar métodos y estrategias de prevención.

## 3. Requisitos previos
- Conocimientos básicos sobre la industria de los videojuegos.
- Conceptos legales relacionados con propiedad intelectual.
- Familiaridad con términos como DRM (Digital Rights Management) y cracks.

## 4. Procedimiento paso a paso
1. **Definición de piratería de juegos:** estudiar qué constituye la piratería en el contexto de videojuegos.
2. **Tipos de piratería:**  
   - Copias ilegales de juegos completos.  
   - Modificaciones y cracks que evaden sistemas de protección.  
   - Distribución no autorizada en plataformas digitales.
3. **Impacto en la industria:** analizar pérdidas económicas, reducción de empleo y efecto en estudios independientes.
4. **Impacto en los jugadores:** riesgos de malware, pérdida de soporte y experiencia de juego limitada.
5. **Medidas de prevención:** DRM, licencias digitales, actualizaciones constantes y educación del usuario.
6. **Casos de estudio:** ejemplos de juegos afectados por piratería y medidas tomadas.

## 5. Ejemplo(s) de código en Python
```python
# Simulación de impacto económico aproximado de la piratería
import matplotlib.pyplot as plt

# Datos ficticios: ventas legales vs piratería estimada
juegos = ['Juego A', 'Juego B', 'Juego C', 'Juego D']
ventas_legales = [500000, 750000, 300000, 600000]
pirateria_estim = [200000, 400000, 150000, 250000]

plt.bar(juegos, ventas_legales, label='Ventas legales')
plt.bar(juegos, pirateria_estim, bottom=ventas_legales, label='Piratería estimada', color='red')
plt.ylabel('Unidades')
plt.title('Impacto económico estimado de la piratería de juegos')
plt.legend()
plt.show()
