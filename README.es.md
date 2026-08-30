# SGLE — Sistema de Gestión de Lista de Espera

[🇧🇷 Português](README.md) | [🇺🇸 English](README.en.md) | 🇪🇸 Español

**Inicio:** 2025  
**Versión:** 1.0.0  
**Estado:** En desarrollo continuo  
**Desarrollador:** Filipe Gimenes de Morais

## 💼 Origen del proyecto

SGLE surgió en **2025** a partir de la identificación de una **demanda acumulada** y de la necesidad de mejorar la organización y el seguimiento de personas que esperan plazas disponibles en actividades y servicios.

La necesidad se discutió inicialmente en una **reunión del comité de gestión**. A partir de ese contexto, la planificación de la solución se desarrolló junto con la **coordinación pedagógica**, y la elaboración de las reglas y necesidades del flujo contó con la colaboración de **dos profesionales del trabajo social**.

El desafío práctico de transformar un proceso predominantemente manual en un flujo digital estructurado fue uno de los factores que impulsaron el estudio de **automatización, Google Workspace y Google Apps Script**.

Por ello, SGLE reúne dos dimensiones:

- una respuesta a una necesidad real de gestión y organización;
- un proyecto práctico de aprendizaje y evolución en automatización.

Para preservar la privacidad y la identidad de la organización original, este repositorio utiliza un enfoque genérico y no identifica a la institución donde se observó la demanda.

## Objetivo

El Sistema de Gestión de Lista de Espera (SGLE) tiene como objetivo digitalizar y organizar el registro de personas que esperan disponibilidad de plazas en actividades y servicios con capacidad limitada.

El sistema sustituye el registro manual por un flujo integrado entre Google Forms y Google Sheets, con evolución prevista hacia automatizaciones con Google Apps Script, indicadores, paneles de control y apoyo a la gestión de plazas.

SGLE **no sustituye la inscripción presencial**.

## Misión

Transformar el proceso manual de registro de la lista de espera en un sistema simple, estandarizado y automatizado, reduciendo retrabajo, errores y tiempo administrativo, al mismo tiempo que mejora la calidad de los indicadores de gestión.

## Público objetivo

- ONG y organizaciones de la sociedad civil
- Proyectos sociales
- Instituciones educativas
- Centros comunitarios
- Organismos y entidades públicas

## Objetivos específicos

- Digitalizar el registro de la lista de espera.
- Estandarizar los datos recopilados.
- Registrar automáticamente fecha y hora.
- Calcular la edad automáticamente.
- Organizar la fila por fecha de inscripción.
- Apoyar la convocatoria para inscripción presencial.
- Registrar el estado del proceso.
- Generar indicadores de demanda acumulada.
- Analizar capacidad y disponibilidad de actividades.
- Permitir futuras evoluciones hacia módulos de inscripción, asistencia y gestión de actividades.

## Flujo operativo

```text
Familia / responsable
        ↓
Equipo responsable
        ↓
Registro en la lista de espera
        ↓
Google Forms
        ↓
Google Sheets
        ↓
Tratamiento y organización de datos
        ↓
Lista de espera / Demanda acumulada
        ↓
Aparece una plaza
        ↓
Convocatoria
        ↓
Proceso de inscripción presencial
        ↓
Actividades definidas según disponibilidad
```

## Arquitectura prevista

```text
Google Forms
      ↓
Google Sheets
      ↓
Google Apps Script
      ↓
Capa de datos / reglas de negocio
      ↓
Panel administrativo
      ↓
Informes
      ↓
PWA (futuro)
```

## Tecnologías

- Google Forms
- Google Sheets
- Google Apps Script
- HTML5
- CSS3
- JavaScript
- Google Charts
- Material Icons

## Regla fundamental

**Lista de Espera ≠ Inscripción.**

SGLE registra la intención de ingreso y organiza la demanda acumulada. La inscripción se realiza presencialmente cuando existe disponibilidad y después de los procedimientos definidos por el equipo responsable.

## Privacidad y protección de datos

El proyecto puede tratar información personal y potencialmente sensible. El repositorio público debe contener únicamente código, documentación y datos ficticios o de ejemplo.

Nunca deben publicarse en GitHub:

- nombres reales de participantes;
- nombres de responsables;
- teléfonos;
- direcciones o datos identificables;
- información de discapacidad o salud;
- hojas de cálculo reales del contexto original;
- credenciales, tokens o claves de API.

## Licencia

Proyecto desarrollado a partir de una necesidad real de gestión y organización, con fines prácticos, educativos y de demostración técnica. Una licencia abierta específica podrá definirse posteriormente si resulta adecuada.
