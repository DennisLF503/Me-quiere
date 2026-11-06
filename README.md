# Me-quiere 🌼

**¿Me quiere o no me quiere?** — un juego de una sola página: toca los pétalos de la margarita y descubre el veredicto.

## Cómo jugar

1. Abre `index.html` en cualquier navegador (no necesita servidor ni dependencias).
2. Opcionalmente escribe un nombre en *¿De quién?*.
3. Toca los pétalos — o usa el botón *Quitar un pétalo* — hasta que no quede ninguno.
4. Cada pétalo alterna entre **Me quiere** 💛 y **No me quiere** 🥀; el último pétalo da el veredicto final.

## Características

- Flor generada con 9–21 pétalos aleatorios (¡cada partida es distinta!).
- Animación de pétalos que caen (se respeta `prefers-reduced-motion`).
- Modo oscuro automático según el sistema, con alternancia por `data-theme`.
- Accesible: pétalos enfocables con teclado, `aria-live` para el resultado.
- Totalmente responsiva, sin frameworks ni build.
