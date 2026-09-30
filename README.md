# PokeScript - Juego por Terminal en Bash

PokeScript es un juego de combate por turnos inspirado en Pokémon, desarrollado completamente en Bash.  
Se juega desde la terminal
---

## 📁 Estructura del proyecto

```
── combate.sh        # Sistema de combate
── funciones.sh      # Funciones auxiliares utilizadas
── jugar.sh          # Las opciones a realizar durante la partida
── pktipos.sh        # Menu de los tipos Pokémon
── pokemon.sh        # Script principal para iniciar el juego y fase de "creacion" del Pokemon
── tablatipos.txt    # Tabla de efectividades entre tipos
── partidas/         # Carpeta donde se guardan las partidas
```

---

## ▶️ Cómo jugar

1. Abre una terminal.
2. Asegura tener la carpeta `juego/` y todo lo que contiene
3. Ejecuta el script principal `pokemon.sh`
   
   ```bash
   bash juego/pokemon.sh
   ```
4. Sigue las instrucciones en pantalla para comenzar la partida.
5. Tener en cuenta que para moverte a traves de los menus se utilizan las teclas `w` y `s`

---

## 💾 Guardado de partidas

- Las partidas se guardan en la carpeta `partidas/`.
- Si se desea visualizar una partida es preferible usar el comando `cat` ya que este permite visualizar colores.

---

## 🚧 Estado del proyecto

- [x] Combate por turnos
- [x] Creacion de Pokémon
- [x] Guardado de partidas
- [ ] Doble tipos

---

## 📜 Requisitos

- Terminal compatible con colores (opcional pero recomendado)
- Descargar los comandos cowsay y lolcat en caso de no tenerlos

---

## Autor

Desarrollado por Orion1206.
