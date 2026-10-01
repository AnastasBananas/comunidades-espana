# Comunidades de España

Juego de geografía para aprender las 17 comunidades autónomas de España (y, si se activa, Ceuta y Melilla).

**Jugar:** https://anastasbananas.github.io/comunidades-espana/

## Cómo se juega

- **Escribe el nombre.** Toca una comunidad en el mapa y escribe cómo se llama. Las tildes no son obligatorias; si hay una pequeña falta de ortografía, el juego avisa con «¡Casi!».
- **Encuéntrala en el mapa.** El juego dice un nombre y hay que tocar la comunidad correcta. Si fallas dos veces, la comunidad parpadea.
- **Pista** descubre el nombre letra a letra. **No lo sé** enseña la respuesta.
- Al terminar, **Repasar** vuelve a preguntar solo las que fallaste.
- La interfaz está en español, ruso e inglés. Los nombres siempre se escriben en español.

Funciona en ordenador, tablet y móvil.

## Privacidad

No hay registro, anuncios ni cookies, y la página no carga nada de otros sitios: el mapa y las tipografías están en este repositorio. En el navegador solo se guardan el idioma, el sonido y la opción de Ceuta y Melilla.

## Créditos

- Límites de las comunidades: © Instituto Geográfico Nacional de España, licencia [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), a través de [es-atlas](https://github.com/martgnz/es-atlas).
- Países vecinos: [Natural Earth](https://www.naturalearthdata.com/) (dominio público), a través de [world-atlas](https://github.com/topojson/world-atlas).
- Tipografías Nunito y Unbounded: SIL Open Font License 1.1 (licencias en `fonts/`).

## Para editar

Todo el juego está en `index.html`. El archivo `map-data.js` se genera a partir de los datos del IGN:

```bash
cd tools
npm install
npm run build-map
```
