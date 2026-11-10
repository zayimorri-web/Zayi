# DriverOS ONE — Plan de lanzamiento

## Objetivo
Publicar una beta web segura, accesible desde el navegador Tesla y teléfonos, con dominio propio DriverOSOne.com cuando su propietario lo registre. No es software oficial de Tesla ni controla el vehículo.

## Estado de la beta
- Lanzador y directorio de aplicaciones web externas.
- Calculadoras manuales de energía, coste y carga.
- Planificador manual de viaje con enlaces a mapas.
- Módulo Driver Pro opcional para estimaciones de ingresos.
- Datos de preferencias almacenados localmente; exportación/importación según las herramientas disponibles.
- PWA básica. Sin cuentas, backend ni acceso oficial a datos del automóvil.

## Lista de comprobación de salida
- [ ] Confirmar que el repositorio y el dominio pertenecen al propietario.
- [ ] Revisar nombre y marcas registradas antes de invertir en promoción.
- [ ] Ejecutar `node --test tests/*.test.mjs` y corregir fallos.
- [ ] Revisar navegación, teclado, contraste, móvil y navegador Tesla con vehículo estacionado.
- [ ] Comprobar enlaces externos, formularios, cálculos y persistencia local.
- [ ] Verificar que GitHub Actions despliega correctamente.
- [ ] Confirmar que la URL temporal responde con HTTPS.
- [ ] Registrar DriverOSOne.com desde una cuenta controlada por el propietario.
- [ ] Configurar dominio personalizado en GitHub Pages, registros DNS y HTTPS.
- [ ] Verificar www y dominio raíz, redirección y certificado.
- [ ] Publicar aviso de privacidad y condiciones adecuados a los servicios realmente usados.
- [ ] Crear canal de comentarios y reportes de errores.
- [ ] Hacer prueba final real en Tesla Model Y 2024 estacionado.

## Dominio (NO configurar hasta comprar)
El dominio objetivo es `driverosone.com`. La configuración de GitHub Pages depende de la verificación del dominio y del registrador. No crear `CNAME` ni cambiar DNS antes de confirmar la compra y la configuración en GitHub Pages. Referencia oficial: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Bloqueos reales
No podemos verificar la compra del dominio, la titularidad, la configuración DNS privada, la activación de GitHub Pages ni las pruebas en el Tesla sin los accesos y verificaciones correspondientes. La publicación y el estado de GitHub Actions deben confirmarse antes de anunciar lanzamiento.

## Después de la beta
Integración Tesla Fleet API solo con OAuth, consentimiento del propietario, backend seguro y permisos mínimos. No guardar tokens en el frontend. Audio y entretenimiento únicamente con el vehículo estacionado; nunca evadir restricciones de seguridad.
