# Del ADN a la proteína

## Ejercicio 1. Replicación del ADN

**Objetivo:** comprender el mecanismo semiconservativo y las enzimas implicadas.

### Instrucciones

#### 1. Considera la siguiente secuencia de ADN

```text
5′-ATG CCG TT A GCT-3′
3′-TAC GGC AA T CGA-5′
```

Sin espacios: `ATGCCGTTAGCT` y `TACGGCAATCGA`. Las bases se emparejan A-T y C-G.

#### 2. Realiza una ronda de replicación

**Nuevas hebras:** cada hebra original sirve de molde para formar su complementaria. Se obtienen dos moléculas:

```text
Molécula hija 1
Original  5′-ATGCCGTTAGCT-3′
Nueva     3′-TACGGCAATCGA-5′

Molécula hija 2
Nueva     5′-ATGCCGTTAGCT-3′
Original  3′-TACGGCAATCGA-5′
```

Cada molécula hija contiene una hebra original y una nueva: esa es la replicación semiconservativa.

**Función de las enzimas:**

| Enzima | Función |
| --- | --- |
| Helicasa | Separa las dos hebras de ADN. |
| Primasa | Coloca cebadores de ARN para iniciar la síntesis. |
| ADN polimerasa | Añade bases complementarias a las hebras nuevas. |
| Ligasa | Une los fragmentos de ADN. |

#### 3. Reflexiona: ¿qué ocurriría si la ADN polimerasa cometiera un error en una base y no se corrigiera?

El error podría convertirse en una mutación heredada por una célula hija. Según dónde esté, podría no tener efecto o alterar la proteína producida.

### Extensión con Biopython

El [notebook del ejercicio 1](ejercicio_1_replicacion.ipynb) genera la hebra complementaria de una cadena de ADN con Biopython y comprueba que coincide con el resultado manual `TACGGCAATCGA`.
