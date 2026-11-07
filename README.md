# 🐈‍⬛ Programa con Lúa · Programación Tangible y Pensamiento Computacional Infantil

### Mascota STEAM de bloques · Algoritmos tangibles desconectados · Sets modulares de Construye con Lúa · Realidad Aumentada local · Refuerzo visual y háptico sensorial

![C++17](https://img.shields.io/badge/C%2B%2B-17-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Placa V1 Circular](https://img.shields.io/badge/placa%20oficial-V1%20·%20ESP32--C3%20·%20GC9A01%20redondo-0a7d54?style=flat-square&logo=espressif&logoColor=white)
![STEAM](https://img.shields.io/badge/eje%20vertebrador-STEAM-00c4be?style=flat-square)
![Pensamiento Computacional](https://img.shields.io/badge/pedagog%C3%ADa-algoritmos%20tangibles-7b1fa2?style=flat-square)
![Hardware V5](https://img.shields.io/badge/hardware-V5%20bloques%20(dise%C3%B1o%20activo)-f0a500?style=flat-square)
![Sin Altavoz ni Micro](https://img.shields.io/badge/audio-silencio%20cl%C3%ADnico%20estructural-b3261e?style=flat-square)
![Zero PHI](https://img.shields.io/badge/Zero--PHI-estructural-0a7d54?style=flat-square)
![Offline](https://img.shields.io/badge/red-100%25%20offline-blue?style=flat-square)

---

> **«La app decide. Lúa reacciona. Los bloques los mueve el niño. El adulto media siempre.»**

**Programa con Lúa** es una iniciativa de tecnología educativa abierta dentro del ecosistema **Earlify Health** (*Valeria+*, *Descubre con Lúa*, *Construye con Lúa*). Su propósito es acercar las bases de la **programación, el pensamiento computacional y la lógica algorítmica** a niños y niñas de **0 a 6 años**, sustituyendo las pantallas interactivas por **bloques físicos manipulables**, la compañía expresiva del juguete **Lúa** y el andamiaje afectivo de una persona adulta mediadora (docente, terapeuta o familia).

---

## 1. ¿Qué es Lúa y qué NO es?

Para evitar falsas expectativas tecnológicas y preservar una rigurosa higiene sensorial, la mascota física Lúa se define a través de fronteras de diseño innegociables:

```
                    UNIDAD ELECTRÓNICA SELLADA DE LÚA (fabricación masque3d, Orense)
        ┌──────────────────────────────────────────────────────────────────────────┐
        │  Cabeza versión 4 (PLA) + placa oficial V1 (ESP32-C3 · LCD redondo       │
        │  GC9A01 Ø32,4 mm · 240×240 px · 27 fps) + batería integrada en cuello   │
        │  + Anillo de 4 luces direccionales (delante / detrás / izq. / dcha.)     │
        │  SIN altavoz · SIN micrófono · SIN motores · BLE GATT periférico         │
        │  Debajo del cuello: anti-espigas estándar de bloque grande               │
        └──────────────────────────────────┬───────────────────────────────────────┘
                                           │ encaje con orientación forzada (llave asimétrica)
        ┌──────────────────────────────────┴───────────────────────────────────────┐
        │  CUERPO DE BLOQUES PASIVOS (lo arma el niño)                             │
        │  Tronco, patas, patín guía y cola montados con bloques pasivos.          │
        │  Cero cables, cero imanes, cero tornillos, lavables e intercambiables.   │
        └──────────────────────────────────────────────────────────────────────────┘
```

### Tabla de Capacidades y Restricciones Estructurales

| Lúa **SÍ** hace | Lúa **NO** hace |
|---|---|
| Muestra expresiones afectivas en píxel art (24×24), pictogramas de comando, insignias y estados en su pantalla circular de 240×240 px | **No habla, no emite pitidos ni reproduce música:** carece físicamente de altavoz o zumbador piezoeléctrico. El silencio clínico es una garantía de hardware. |
| Enciende 4 luces direccionales en el cuello para indicar rumbos algorítmicos (*avanza, gira a la izquierda, gira a la derecha*) | **No escucha ni graba sonido:** carece de micrófono, garantizando la privacidad absoluta (Zero-PHI). |
| Ejecuta opcodes inmediatos (`MOOD`, `PICTO`, `CELEBRATE`, `LIGHT`, `AWARD`) recibidos por BLE | **No se desplaza sola:** no tiene ruedas ni servomotores. El niño es quien la mueve físicamente. |
| Mantiene la atención visual compartida y valida el éxito de las secuencias construidas | **No puntúa, no juzga ni almacena historiales:** actúa como espejo afectivo inmediato del proceso. |

> **Ubicación de la voz:** La voz y las consignas verbales residen **única y exclusivamente en la tableta del adulto**. De este modo, la voz digital jamás compite con la voz humana del mediador ni enmascara la audición de niños con audífonos o implantes cocleares.

---

## 2. ¿Qué son los Sets y cómo enseñan a programar?

Los **Sets de Construye con Lúa** son ecosistemas modulares de bloques tangibles diseñados en dos escalas con encaje mutuo 2:1 (Escala Grande **G** para 0–3 años sin piezas pequeñas según EN 71-1; Escala Estándar **E** para 3–6 años).

En este proyecto, los bloques físicos dejan de ser simples juguetes de construcción para convertirse en **instrucciones de código tangible**:

```
        CÓDIGO TANGIBLE                      PROGRAMA RESULTANTE                   EJECUCIÓN FÍSICA
 ┌───────────────────────────┐          ┌───────────────────────────┐         ┌──────────────────────────┐
 │ Baldosas con ranura guía  │          │ Secuencia lineal sobre    │         │ El niño desliza a Lúa    │
 │ + Fichas de comando:      │ ───────► │ la alfombra o mesa        │ ──────► │ paso a paso siguiendo    │
 │ [AVANZA] [GIRA] [PARA]    │          │ (Algoritmo desconectado)  │         │ la ruta programada       │
 └───────────────────────────┘          └───────────────────────────┘         └──────────────────────────┘
```

### El Set Nuclear: Set 1 · El Camino de Lúa (*Lúa's Stepping Trail*)
Es el eje central de la enseñanza de programación temprana:
1. **Baldosas rectas lisas y rugosas (`S1-REC-LIS-G`, `S1-REC-RUG-G`):** Definen la instrucción básica de desplazamiento lineal (`AVANZA`). La textura rugosa introduce diferenciación propioceptiva y pausas temporales.
2. **Curvas de 90° e Intersecciones en T (`S1-CUR-G`, `S1-TEE-G`):** Modelan giros angulares, cambios de rumbo y estructuras condicionales (bifurcaciones `IF/ELSE`).
3. **Fichas de comando hápticas (`S1-CMD-*`):** Piezas que se insertan a presión en los laterales de las baldosas. Cada ficha posee un icono en relieve reconocible al tacto que programa una acción para Lúa en ese segmento:
   - `CMD_AVANZA` ➔ Seguir recto.
   - `CMD_GIRA_IZQ` / `CMD_GIRA_DCHA` ➔ Cambio de orientación espacial en 90°.
   - `CMD_PARA` ➔ Detención obligatoria (condición de parada).
   - `CMD_SALTA` ➔ Transición especial o pausa motriz.
4. **Zócalos universales (`K-ZOCALO-G`) con placas intercambiables:** Definen el punto de entrada `INICIO` (equivalente a `main()` o evento `onStart`) y el objetivo `META` (condición de finalización exitosa).

### Interoperabilidad con los demás Sets STEAM
Los otros mundos de Construye con Lúa amplían el paradigma computacional a través de fenómenos físicos:
- **Set 3 (Rampas y Gravedad):** Parámetros de velocidad y bucles de prueba y error.
- **Set 2 (Estación de Sonido):** Bucles rítmicos (`LOOPS`) y temporizadores.
- **Set 5 (Puente de Equilibrio):** Operadores relacionales (`<`, `>`, `==`) mediante masas y brazos de palanca.
- **Set 6 (Jardín del Sol y la Semilla):** Secuencias cronológicas de estado (máquinas de estados finitos: semilla ➔ brote ➔ flor).

---

## 3. Pilares del Aprendizaje de Programación en Primera Infancia

La metodología traslada conceptos abstractos de las ciencias de la computación a experiencias corporales y manipulativas:

### A. Del Cuerpo al Bloque, del Bloque al Robot (Enfoque TPR)
Antes de construir con bloques, el niño vive el algoritmo con su propio cuerpo mediante respuestas físicas completas (*Total Physical Response*):
> *«Step forward, step forward, stop!»* ➔ El niño da dos pasos y se detiene. Luego traslada esa misma secuencia colocando dos baldosas rectas y una ficha de parada, y finalmente desliza a Lúa por el camino para comprobarlo.

### B. Lateralidad y Perspectiva Unificada
Uno de los mayores obstáculos para niños de 3 a 5 años es el giro en espejo (la izquierda del robot frente a la suya). Por diseño, **Lúa se opera mirando desde atrás**: la izquierda y derecha de Lúa coinciden estrictamente con la izquierda y derecha del niño, eliminando la sobrecarga cognitiva de rotación mental.

### C. Depuración Tangible (*Debugging*)
Cuando una baldosa está mal orientada o el camino queda interrumpido (`S1.CAMINO_ROTO`), el algoritmo físico falla de forma natural: el patín de Lúa se topa con el corte de la ranura. La sesión fomenta la resolución colaborativa mediante tres roles rotatorios:
- **Guía:** Detecta visualmente el punto donde se corta el camino.
- **Proveedor:** Identifica y entrega la pieza requerida (*«Give me the turn block»*).
- **Constructor:** Ajusta la pieza en el circuito y ejecuta el testeo.

---

## 4. Contrato de Interacción y Refuerzo Positivo

Toda acción en el sistema sigue una cadena estricta de 5 eslabones:

```
  1. EVENTO FÍSICO  ──►  2. DETECCIÓN      ──►  3. DECISIÓN     ──►  4. REACCIÓN   ──►  5. PALABRA
  (El niño coloca,       (RA en tableta /       (La app evalúa       (Lúa pantalla      (Voz en tableta
   desliza o encaja)      toque del adulto)      el algoritmo)        y Ronroneo)        del adulto)
```

### Refuerzo Visual Inmediato en Lúa
Cuando el niño ejecuta correctamente un paso o completa una secuencia:
- **Pantalla Circular:** Lúa pasa de `MOOD(atenta)` a una explosión de animación `CELEBRATE` o despliega un pictograma de logro `AWARD`.
- **Luces Direccionales:** Al realizar un giro correcto, la luz del cuello del lado del giro (`LIGHT(DIR_IZQ)` o `LIGHT(DIR_DCHA)`) se ilumina suavemente, reforzando la confirmación de rumbo.

### Refuerzo Háptico Sensorial (Bloque Ronroneo)
Para reforzar el acto de forma multisensorial, se incorpora de manera opcional el bloque **Ronroneo** (para mayores de 3 años):
- **Hardware Independiente:** Un bloque físico cerrado con batería propia, microcontrolador ESP32-C3 y actuador lineal resonante (LRA con driver háptico DRV2605L).
- **Vibración Terapéutica y de Refuerzo:** Al completar la meta o un hito motor, Ronroneo emite una pulsación suave de confirmación (`CELEBRA_CORTO`). En momentos de calma o descanso, sincroniza un latido lento (`RONRONEO`).
- **Reglas Hápticas Estrictas:**
  1. Nunca vibra ante un fallo o error.
  2. Nunca vibra durante el turno verbal del niño.
  3. El adulto puede detenerlo o modular su intensidad en cualquier instante desde la aplicación.

### El Mandato del Error Neutro
En la pedagogía de Lúa **no existe el castigo ni el estímulo negativo**:
- No hay zumbadores de error, ni luces rojas parpadeantes, ni expresiones de tristeza o reproche.
- Si una pieza no encaja o el camino no llega a la meta, la consecuencia es puramente física (el juguete se detiene). Lúa permanece serena y expectante (`MOOD(espera_serena)`), invitando a probar otra solución sin frustración.

---

## 5. El Rol de la Realidad Aumentada (RA) Local

La tableta del adulto no sustituye el juego: actúa como un **sensor ciego local y herramienta de andamiaje**:

```
        TABLETA DEL ADULTO (Sensor ciego local)
        ┌──────────────────────────────────────────────────────────────────────────┐
        │  • ARCore (Imágenes Aumentadas / Marcadores de baldosa)                  │
        │  • MediaPipe (Detección de gestos manuales / contacto)                   │
        │  • Google Filament (Renderizado liviano de capas explicativas < 100 KB)  │
        │  • Cero subida de vídeo · Cero conexión a servidores (100% offline)      │
        └──────────────────────────────────┬───────────────────────────────────────┘
                                           │
                                           ▼
        VISUALIZACIÓN DE LA CAPA INVISIBLE DEL CÓDIGO
        En la fase de ampliación posterior a la manipulación, el adulto puede apuntar
        al camino: la pantalla dibuja sobre las baldosas una línea vectorial fluida
        con flechas direccionales, haciendo visible el «flujo del programa».
```

> **Invariante de Accesibilidad:** Ningún evento depende exclusivamente de la cámara de la tableta. La persona adulta siempre dispone de un botón táctil en pantalla para validar manualmente cualquier paso. La RA facilita la detección, pero jamás condiciona la sesión.

---

## 6. Progresión Pedagógica de Retos

| Reto / Nivel | Edad | Hito de Programación | Acción Física | Reacción de Lúa y Refuerzo |
|---|---|---|---|---|
| **1. Causa y Efecto** | 0–2 años | Evento unitario (1 paso) | Deslizar a Lúa de un zócalo a una baldosa contigua | `MOOD(atenta)` ➔ `CELEBRATE`. Tableta: *«Step!»* |
| **2. Secuencia Lineal** | 2–3 años | Cadena de instrucciones ordenadas | Unir baldosas lisas y rugosas hasta la meta | Luz delantera activa. Vibración suave al llegar a meta |
| **3. Comandos Explícitos** | 3–4 años | Parametrización con fichas (`AVANZA`, `GIRA`) | Insertar fichas en los laterales de las baldosas | Lúa muestra en pantalla el pictograma del comando insertado |
| **4. Bifurcación / Decisión** | 4–5 años | Condiciones `IF/THEN` según destino | Cruce en T hacia dos zócalos (`CAMA` o `PARQUE`) | Lúa solicita un destino; el niño programa el desvío correspondiente |
| **5. Depuración en Equipo** | 5–6 años | *Debugging* y trabajo cooperativo | Corregir un circuito roto planteado por el adulto | Detección del corte, sustitución del bloque y celebración grupal |

---

## 7. Arquitectura del Repositorio

```
programa-con-lua/
├── README.md                  # Este documento (visión general, pedagogía y arquitectura)
├── STATUS.md                  # Estado empírico de pruebas, gates y despliegue
├── .gitignore                 # Filtros de entorno y temporales
├── docs/
│   ├── SETS.md                # Catálogo técnico de piezas y mundos STEAM
│   ├── CONTRATO-EVENTOS.md    # Especificación de eventos (S1.LUA_AVANZA, opcodes)
│   ├── PEDAGOGIA-CODIGO.md    # Guía metodológica para docentes y terapeutas
│   └── SEGURIDAD-EN71.md      # Directivas de seguridad mecánica y límites de tamaño
├── assets/
│   └── brand/                 # Rejilla canónica de pictogramas y expresiones 24×24
└── src/                       # Lógica de emparejamiento, grafo de camino y contratos BLE
```

---

## 8. Gobernanza, Privacidad y Licencia

- **Ecosistema:** Earlify Health S.L.
- **Entorno de Aplicación:** Educativo (LOMLOE infantil, escuelas 0–6) y apoyo familiar/clínico (*Valeria+*).
- **Protección de Datos:** Arquitectura Zero-PHI estructural. Sin perfiles de menores, sin recolección biométrica y sin transmisión por red.
- **Contacto Legal e Institucional:** `frank.alberto.betances.reinoso@gmail.com`
- **Licencia:** Código y especificaciones abiertas bajo Licencia Apache 2.0 / MIT.
