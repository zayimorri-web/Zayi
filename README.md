# DriverOS ONE

**One platform. Every drive.**

Plataforma web independiente para propietarios de Tesla, diseñada para funcionar en navegador y móvil. La primera beta reúne un directorio de aplicaciones, calculadoras manuales de energía y carga, planificación básica de viajes y un módulo opcional para conductores profesionales.

**Estado:** beta en preparación; la publicación, las pruebas en el vehículo y el dominio personalizado todavía deben verificarse. No hay conexión oficial con Tesla, Uber o Lyft.

## Desarrollo y pruebas

Proyecto estático HTML/CSS/JavaScript, sin dependencia de instalación para el frontend.

```bash
node --test tests/*.test.mjs
```

La publicación está preparada mediante GitHub Actions en `.github/workflows/pages.yml`. El propietario debe confirmar GitHub Pages y su ejecución exitosa.

## Documentos

- [Plan de lanzamiento](LAUNCH.md)
- [Lista de comprobación de publicación](RELEASE-CHECKLIST.md)
- [Información de privacidad de la beta](PRIVACY.md)
- [Despliegue](DEPLOY.md)
- [Seguridad](SECURITY.md)

## Seguridad

DriverOS ONE no sustituye los sistemas de seguridad del vehículo. Utilizar funciones interactivas y entretenimiento solo con el vehículo estacionado. No introducir credenciales, información financiera ni secretos. El proyecto no es oficial ni está afiliado con Tesla.

**Dominio objetivo:** DriverOSOne.com (compra y conexión pendientes).
