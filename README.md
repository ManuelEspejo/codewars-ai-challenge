# Codewars Python Quest: Humano + IA

Este proyecto es una exploración de cómo los programadores humanos y las inteligencias artificiales podemos complementarnos para alcanzar resultados excepcionales. Aquí comparto mis avances, reflexiones y aprendizajes clave en este viaje.

## ¿Qué quiero lograr con este proyecto?

### Objetivo principal

Busco demostrar que la colaboración entre humanos y la IA puede ser más poderosa que cualquiera trabajando por separado. Mi misión es perfeccionar mis habilidades de programación, comprender mejor cómo piensa una IA y aprender a trabajar con ella de manera eficiente.

Cada vez la IA programa mejor, y se viene diciendo desde hace tiempo que ya no es buena idea estudiar programación, porque ahora las máquinas pueden hablar como nosotros.

Entiendo el punto, pero esta situación me hace preguntarme algunas cosas:

- ¿De verdad somos completamente innecesarios en esta área?
- ¿Hay algún aporte que con mi enfoque humano pueda aportar para que la IA funcione mejor?
- ¿Qué es lo que se le da mejor a la IA? ¿Hay algo que se le pueda dar mejor a un programador humano?
- ¿Cómo podemos conseguir trabajar juntos de la mejor manera posible? (al menos adaptado a mi caso de uso)
- ¿Qué podemos aprender de cómo la IA resuelve problemas para mejorar nuestras habilidades?

Tengo muchas más dudas, por eso he decidido arrancar este proyecto, para entender mejor cómo pienso yo a la hora de diseñar una solución a problemas de programación, cómo piensa la IA, qué hace ella mejor y en qué podemos complementarnos.

Este es otro proyecto más enfocado a lo que todo apunta que es el futuro de la humanidad: la evolución humana mediante la fusión con la tecnología.

### Mis reglas del juego

He escogido la plataforma codewars, porque la he probado antes y me gusta, pero podría ser cualquier otra plataforma que disponga de retos de programación.

Codewars nos ofrece un sistema por niveles o rangos, estos van desde el kyu 8 hasta el kyu 1, siendo el kyu 1 el más difícil de obtener. Estos niveles a su vez están formados por retos de programación: los katas. Al superar un kata, consigues puntos, y cuando completas varios, subes de rango (esto aplica para los distintos lenguajes de programación admitidos por codewars, en mi caso me enfocaré en Python).

Las reglas que he establecido son las siguientes:

1. Resolver cada kata utilizando mi conocimiento y la documentación disponible en internet, pero sin buscar asistencia de la IA para generar código.
2. Cuando obtenga una solución, pediré a un LLM (específicamente el modelo `o1` de OpenAI) que genere su solución propia al reto (sin mostrarle mi solución) y le haré preguntas, y charlaremos un rato para reflexionar sobre ambos enfoques.
3. Documentar cada paso del proceso: desde el planteamiento inicial hasta las reflexiones finales, con el objetivo de sacar conclusiones valiosas sobre la colaboración entre humanos e IA.

## Estructura del repositorio

- **`problems/`**: Contiene los problemas organizados por nivel de dificultad (de Kyu 6 a Kyu 1). (He dejado el kyu 8 y 7 fuera, porque en mi cuenta ya pasé estos rangos en su momento)
  - Cada problema incluye:
    - `solution.py`: Mi solución al problema.
    - `analysis.md`: Una explicación detallada de mi razonamiento para resolver el problema.
    - `gpt_solution.py`: La solución generada por la IA.
    - `comparison.md`: Comparativa entre ambas soluciones y debate final.
    - `diagram.png`: Esquema visual de la lógica del código (si aplica)
- **`assets/`**: Recursos adicionales, como diagramas y visualizaciones.

### Documentación reflexiva

Este repositorio también incluye reflexiones sobre:

- Lo que aprendo de cada problema y de la comparación con la IA.
- Estrategias que funcionan (y las que no).
- Mejores prácticas para programadores humanos e IA trabajando en conjunto.

## Colaboración

Te invito a explorar este repositorio y seguir mis avances y reflexiones para ver qué descubrimos juntos.

También me encantaría ver cómo replicas este reto o lo adaptas a tu caso de uso. Estaría muy bien ver qué descubrimos entre todos, y en vez de tener rechazo o miedo con la IA y su potencial capacidad de sustituirnos, empezar a ver cómo podemos trabajar en conjunto para mejorar lo que podemos hacer.

Si tienes ideas, comentarios o sugerencias, no dudes en contactarme.

## Metas a futuro

1. Alcanzar el Rango 1 en Codewars en Python.
2. Profundizar en cómo los humanos e IA pueden colaborar para resolver problemas complejos de manera efectiva.
3. A partir de esta reflexión, diseñar mi estrategia de pair programming con IA, que aplicaré al resto de mis proyectos (siempre evaluando y mejorando en base a nuevos descubrimientos).
