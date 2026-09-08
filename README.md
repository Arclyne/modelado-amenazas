# Modelado de amenazas — Sitio web de la biblioteca universitaria

Repositorio de la práctica **"Elaboración del reporte de modelado de amenazas"** de la asignatura *Programación Segura*, Licenciatura en Ingeniería de Software, Universidad Veracruzana.

El modelo se construyó con la metodología **STRIDE** en [OWASP Threat Dragon](https://www.threatdragon.com/), a partir del sistema de ejemplo *Sitio web de la biblioteca universitaria*.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Sitio web de la biblioteca universitaria.json` | Modelo de amenazas en formato Threat Dragon (v2). Se abre directamente desde la herramienta con **Abrir un modelo de amenazas existente → GitHub**. |

## Diagramas incluidos

1. **Diagrama de flujo de datos para el sitio web de la biblioteca universitaria** — flujo general entre usuarios, bibliotecario, el sitio web, la base de datos y el almacenamiento en disco.
2. **Diagrama de flujo de datos de inicio de sesión del usuario** — detalle del proceso de autenticación (controlador web y proceso de login).

Cada diagrama define sus fronteras de confianza y marca como *fuera de alcance* los flujos que no forman parte del análisis.

## Resumen de amenazas

| Métrica | Total |
|---|---|
| Amenazas identificadas | 24 |
| Mitigadas | 7 |
| Abiertas | 17 |
| Abierto / Prioridad alta | 8 |
| Abierto / Prioridad media | 6 |
| Abierto / Prioridad baja | 3 |

Las 24 amenazas se identificaron aplicando STRIDE a cada actor, proceso, flujo de datos y almacén de los dos diagramas, con su tipo, prioridad, estado y mitigación correspondiente.

## Cómo consultar el modelo

1. Entra a [threatdragon.com](https://www.threatdragon.com/) e inicia sesión con GitHub.
2. Selecciona **Abrir un modelo de amenazas existente**.
3. Elige este repositorio (`modelado-amenazas`) y el archivo del modelo.
4. Desde ahí puedes ver los diagramas, editar amenazas o generar el reporte en PDF (**Reporte → Print**).

## Información del modelo

- **Propietario:** Angel Gabriel Aguilar Hernandez
- **Revisor:** Guillermo Vera
- **Colaboradores:** Lorena Rojas, Roberto Ochoa
- **Versión:** 1.0
