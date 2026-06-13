# PRIMEPCMOD - Modelado de PRIME PC (UCM)

Proyecto universitario de la UCM para la asignatura **MS (Modelado de Software)**.

Este repositorio contiene el **trabajo de modelado en IBM RSAD (Rational Software Architect Designer)** del sistema PRIME PC, un gestor de tienda de componentes de ordenador.

## Descripcion

PRIMEPCMOD recoge los artefactos de modelado del mismo dominio funcional de PRIME PC, centrados en el analisis y diseno del sistema.

En este repositorio se incluyen modelos para:

- Dominio del negocio
- Modelo general del sistema
- Diagramas de despliegue

## Artefactos principales

- `PrimePc.emx`
- `Modelo del Dominio.emx`
- `Diagramas de Despliegue.emx`

## Tecnologias y entorno

- IBM Rational Software Architect Designer (RSAD)
- Eclipse Project metadata (`.project`, `.classpath`, `.settings`)
- Librerias de soporte JPA en `lib/` (EclipseLink/Jakarta)

> Nota: este repositorio esta orientado al **modelado**. La implementacion funcional completa de la aplicacion se encuentra en el repositorio de codigo (`MS_PRIMEPC_COD`).

## Estructura del proyecto

```text
MS_PRIMEPC_MOD/
|- PrimePc.emx
|- Modelo del Dominio.emx
|- Diagramas de Despliegue.emx
|- lib/
|- .project
|- .classpath
\- .settings/
```

## Requisitos

- IBM RSAD instalado
- JDK configurado en el entorno Eclipse/RSAD

Segun la configuracion del proyecto, el classpath apunta a **JavaSE-1.7**.

## Como abrir el proyecto en RSAD

1. Clona el repositorio:

	```bash
	git clone https://github.com/adribot23/MS_PRIMEPC_MOD.git
	```

2. En RSAD/Eclipse:
	- `File > Import... > Existing Projects into Workspace`
	- Selecciona la carpeta `MS_PRIMEPC_MOD`
	- Finaliza el import

3. Abre los modelos `.emx`:
	- `PrimePc.emx`
	- `Modelo del Dominio.emx`
	- `Diagramas de Despliegue.emx`

4. Si no aparecen vistas de modelado:
	- Cambia a la perspectiva UML/Modeling de RSAD
	- Asegura que los plugins de modelado estan habilitados

## Relacion con PRIMEPC_COD

- `MS_PRIMEPC_MOD`: modelos y diseno (RSAD)
- `MS_PRIMEPC_COD`: implementacion Java, GUI, persistencia y tests

Ambos repositorios forman parte del mismo trabajo academico para MS.

