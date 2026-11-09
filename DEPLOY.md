# Publicación y pruebas DriverOS

1. Revisa que el repositorio no contenga credenciales ni datos personales.
2. En GitHub, abre Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
3. Espera la publicación y comprueba la URL en Settings > Pages. El alojamiento debe usar HTTPS.
4. En un navegador normal, verifica cálculos, almacenamiento y exportación. No asumas que GPS o almacenamiento funcionen en Tesla.
5. En el Tesla **estacionado**, abre la URL y comprueba botones, teclado, tamaño, almacenamiento, conectividad y restricciones.

## Limitaciones
- Sin backend, cuentas, sincronización ni integración Tesla/Uber/Lyft.
- Los datos locales pueden perderse al limpiar el navegador.
- El modo offline requiere un navegador que admita service workers y que haya cargado la aplicación previamente.
- Los costos y resultados son estimaciones antes de impuestos, no asesoría fiscal.
- No interactuar con esta aplicación durante la conducción.

## Seguridad
El repositorio es público. No guardar tokens OAuth, contraseñas, datos personales, identificadores del vehículo ni claves API en archivos públicos.
