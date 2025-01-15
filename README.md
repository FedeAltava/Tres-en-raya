# Tres en Raya

Este es un proyecto simple en React que implementa el clásico juego de **Tres en Raya (Tic-Tac-Toe)**. Permite a dos jugadores turnarse para jugar, ver el historial de movimientos y volver a jugadas anteriores.

## Características

- **Juego para dos jugadores**: Alterna entre "X" y "O" automáticamente.
- **Detección de ganador**: Identifica al ganador del juego cuando se completa una línea horizontal, vertical o diagonal.
- **Historial de movimientos**: Los jugadores pueden regresar a jugadas anteriores y continuar desde allí.
- **Estado de juego persistente**: El historial y el estado del tablero se gestionan utilizando React Hooks.

## Estructura del proyecto

- **`Game`**: Componente principal que gestiona el historial de movimientos, el estado actual y permite navegar entre jugadas.
- **`Board`**: Componente que representa el tablero del juego y contiene la lógica para determinar el estado de cada casilla.
- **`Square`**: Componente que representa una casilla individual en el tablero.


