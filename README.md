
# Guía de Ejercicios Físicos

**Guía de Ejercicios Físicos** es un proyecto que tiene como objetivo crear una colección de ejercicios físicos clasificados por tipo. Cada tipo de ejercicio se desarrolla en una rama independiente, donde los usuarios pueden realizar múltiples `commits` documentando diferentes aspectos del ejercicio. Al final, todas las ramas se fusionan en la rama principal para formar una guía completa y coherente.

## Problemática

El desafío principal de este proyecto es la gestión eficaz de ramas y `commits` en Git. Los usuarios deben asegurarse de que cada rama represente adecuadamente un tipo de ejercicio y que los cambios realizados sean significativos y bien documentados. Durante el proceso de fusión de ramas, pueden surgir conflictos que requieren resolución. Esta experiencia no solo fortalece las habilidades en el uso de Git, sino que también ilustra la importancia de una buena documentación al organizar información.

En este ejercicio, practicarás la creación de hasta **10 ramas** en tu proyecto **Guía de Ejercicios Físicos**, cada una dedicada a un tipo diferente de ejercicio. Cada rama deberá contener al menos **`5 commits`** relacionados con el ejercicio correspondiente, y al final se realizará una fusión de todas las ramas en la rama principal (`main`), integrando todos los ejercicios en un solo documento final.

## Instrucciones

1. Crear la Carpeta y la Estructura del Proyecto
   - Crea una carpeta llamada `ejercicios/` en la raíz del proyecto donde se guardarán los archivos para cada tipo de ejercicio. La carpeta raíz se llamará `GuiaDeEjercicios`.
2. Crear Hasta 10 Ramas para los Tipos de Ejercicio
   - Los tipos de ejercicio pueden incluir: `Cardio`, `Fuerza`, `Flexibilidad`, `Entrenamiento Funcional`, `Yoga`, `Pilates`, `Ciclismo`, `Natación`, `Boxeo`, y `CrossFit`.
   - Pista: Utiliza un comando para crear una nueva rama y cambiarte a ella al mismo tiempo.
3. Agregar una Entrada para Cada Ejercicio con Múltiples Commits
   - En cada rama, crea un archivo `Markdown` para el tipo de ejercicio correspondiente.
   - Realiza al menos 5 commits en la rama, añadiendo cambios incrementales al archivo. Por ejemplo:
     - Primer `commit`: Agregar el título del ejercicio.
     - Segundo `commit`: Descripción del ejercicio.
     - Tercer `commit`: Beneficios del ejercicio.
     - Cuarto `commit`: Instrucciones de cómo realizarlo.
     - Quinto `commit`: Consejos y precauciones.
   - Pista: Realiza los cambios en el archivo y utiliza los comandos para agregar y registrar los cambios en el historial.
   - **Nota**: recuerda que cada `commit` se realizará siguiendo el formato de **`conventional commits.`**
4. Repetir para Cada Tipo de Ejercicio
   - Cambia de rama y repite los pasos para cada uno de los 10 tipos de ejercicio, asegurándote de hacer al menos **5 `commits`** incrementales en cada rama.
5. Fusionar Cada Rama a la Rama Principal (`main`)
   - Cambia a la rama principal (`main`) y realiza la fusión de cada rama de ejercicio.
   - Pista: Asegúrate de estar en la rama principal antes de realizar la fusión.
   - Si se producen conflictos, resuélvelos manualmente y confirma los cambios.
6. Subir los Cambios al Repositorio Remoto
   - Sube la rama principal y las demás ramas al repositorio remoto para consolidar todos los cambios.
   - Asegúrate de que el repositorio esté público y compartido.
     

# Contenido del `cardio.md` de la Rama `cardio`:

```markdown
# Ejercicio Cardio

## Descripción
Los ejercicios de cardio son actividades que aumentan tu frecuencia cardíaca y mejoran la resistencia.

## Beneficios
- Aumenta la capacidad cardiovascular.
- Ayuda a quemar calorías.
- Mejora el estado de ánimo.

## Instrucciones
1. Comienza con un calentamiento de 5-10 minutos.
2. Realiza la actividad (correr, nadar, andar en bicicleta) durante al menos 30 minutos.
3. Termina con un enfriamiento y estiramientos.

## Consejos
- Mantén una hidratación adecuada.
- Escoge un ritmo que puedas mantener.
```



## Instrucciones Visuales

### Rama `cardio`



```less
GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md  # Commit 1: Crea el archivo y agrega el título.
└── README.md

GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md  # Commit 2: Agrega la descripción del ejercicio.
└── README.md

GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md  # Commit 3: Añade los beneficios del ejercicio.
└── README.md

GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md  # Commit 4: Incluye las instrucciones para realizar el ejercicio.
└── README.md

GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md  # Commit 5: Agrega consejos y precauciones.
└── README.md
```

### Rama `fuerza`

```less
GuiaDeEjercicios/
├── ejercicios/
│   ├── fuerza.md  # Commit 1: Crea el archivo y agrega el título.
└── README.md
```

(El proceso de `commits` incrementales se repite para los otros tipos de ejercicio.)

### Rama `main`

Después de fusionar todas las ramas (`cardio`, `fuerza`, `flexibilidad`, etc.) en la rama `main`, la estructura del proyecto se verá así:

```less
GuiaDeEjercicios/
├── ejercicios/
│   ├── cardio.md        # Contenido final fusionado desde la rama `cardio`.
│   ├── fuerza.md        # Contenido final fusionado desde la rama `fuerza`.
│   ├── flexibilidad.md   # Contenido final fusionado desde la rama `flexibilidad`.
│   ├── entrenamiento_funcional.md
│   ├── yoga.md
│   ├── pilates.md
│   ├── ciclismo.md
│   ├── natacion.md
│   ├── boxeo.md
│   └── crossfit.md
└── README.md
```

Cada archivo en la carpeta `ejercicios/` contendrá la versión final de cada tipo de ejercicio, resultado de los `commits` en las ramas correspondientes. La fusión en `main` integrará todos los cambios, consolidando el proyecto.

# Contenido del `README.md` de la Rama `main`

El `README.md` en la rama `main` podría tener un contenido que vincule a los archivos de cada ejercicio, con un enfoque especial en los ejercicios de cardio. Aquí tienes un ejemplo de cómo podría ser el contenido:

```markdown
# Guía de Ejercicios Físicos

Bienvenido a nuestra guía de ejercicios físicos, donde compartimos descripciones y beneficios de diferentes tipos de ejercicios.

## Tipos de Ejercicio

- [Ejercicio Cardio](ejercicios/cardio.md): Mejora tu resistencia y salud cardiovascular.
- [Ejercicio de Fuerza](ejercicios/fuerza.md): Aumenta la masa muscular y la fuerza.
- [Ejercicio de Flexibilidad](ejercicios/flexibilidad.md): Mejora la movilidad y reduce el riesgo de lesiones.
- [Ejercicio de Entrenamiento Funcional](ejercicios/entrenamiento_funcional.md): Mejora la fuerza en movimientos cotidianos.
- [Ejercicio de Yoga](ejercicios/yoga.md): Fomenta la relajación y la flexibilidad.
- [Ejercicio de Pilates](ejercicios/pilates.md): Fortalece el núcleo y mejora la postura.
- [Ejercicio de Ciclismo](ejercicios/ciclismo.md): Gran ejercicio cardiovascular de bajo impacto.
- [Ejercicio de Natación](ejercicios/natacion.md): Trabaja todos los grupos musculares de manera suave.
- [Ejercicio de Boxeo](ejercicios/boxeo.md): Mejora la coordinación y la resistencia.
- [Ejercicio de CrossFit](ejercicios/crossfit.md): Entrenamiento intensivo y funcional.

¡Esperamos que encuentres útiles estos ejercicios y te inspires para mantenerte activo y saludable!
```

#######################################################################
    DESARROLLADO POR STIVEN MARTINEZ VILLAMIZAR        CC 1096064595       
 #######################################################################