# tipo-cambio-bccr

Proyecto para publicar el tipo de cambio del dólar del BCCR con GitHub Pages y GitHub Actions.

## Archivos incluidos
- `index.html`
- `tipocambio.json`
- `.github/workflows/actualizar-tipocambio.yml`

## Horarios programados
El workflow está configurado para ejecutarse todos los días a:
- 3:00 a. m. hora de Costa Rica
- 6:00 a. m. hora de Costa Rica
- 9:00 a. m. hora de Costa Rica

## Secret requerido
Debe existir en GitHub:
- Nombre: `BCCR_TOKEN`
- Valor: token del BCCR

## Publicación
Después de subir estos archivos:
1. Verifique que GitHub Pages esté activo.
2. Verifique que el workflow exista en `.github/workflows`.
3. Haga una prueba manual con `Run workflow`.
