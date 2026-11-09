# Biopsia de próstata por fusión · visor 3D

Animación 3D interactiva para explicar a los pacientes la biopsia de próstata por fusión de resonancia y ecografía, por vía transperineal con grilla.

**Desarrollado por el Dr. William Baptista.**

Ver online: https://baptistaw.github.io/biopsia-fusion-3d/

## Qué muestra

1. **Quirófano:** el paciente en la mesa, el ecógrafo y la estación del software de fusión.
2. **Posición:** litotomía, con las piernas sobre perneras.
3. **Sonda y grilla:** la sonda biplanar entra en el recto montada en el stepper y la grilla se apoya en el periné. La piel se vuelve transparente y aparece la anatomía: próstata por zonas, vejiga, uretra con el pene, recto y pelvis ósea.
4. **Ecografía 3D:** la sonda barre la glándula y el software arma el modelo.
5. **Fusión con la resonancia:** el contorno de la resonancia se alinea y aparecen las lesiones con su PI-RADS.
6. **Planificación:** trayectorias dirigidas y sistemáticas, cada una por un orificio de la grilla.
7. **Punciones dirigidas** y 8. **Mapeo sistemático:** la aguja entra por la grilla y se ve en la ecografía transversal y sagital en tiempo real.
9. **Muestras:** un frasco rotulado por cada cilindro.
10. **Resultado:** el mapa con las muestras positivas en rojo y las negativas en verde.

Tiene controles para reproducir, pausar, ir a cualquier paso y volver al inicio. También se puede girar y hacer zoom, y funciona en el celular.

Las pantallas de la ecografía y del software de fusión se pueden agrandar en cualquier momento, incluso con la animación en marcha, para ver el detalle: se toca la pantalla o su botón de agrandar, se pasa de una a la otra con el botón de cambio y se vuelve con «Achicar» o la tecla Esc.

## Uso sin conexión

`index.html` es un único archivo autocontenido. Se puede descargar y abrir sin internet en cualquier navegador moderno con WebGL.

## Créditos

- Mallas anatómicas: Human Reference Atlas, HuBMAP / CCF (Visible Human Male, NLM), licencia CC BY 4.0.
- Lesiones, sectores de Ginsburg y colores de las muestras: módulo de render 3D de PBP Fusion.
- Caso de demostración ficticio (BX-2026-0142). No contiene datos de pacientes.

Animación esquemática con fines docentes; no apta para planificación.
