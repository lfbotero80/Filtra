# Filtra — Reestructuración y planeación estratégica 2026-2031

Repositorio de trabajo del proceso de reestructuración de **Filtración y Análisis S.A.S.**

Contiene los insumos que entregó la empresa, los análisis hechos sobre ellos, los planes y el backlog de ejecución, el manual de funciones y las políticas aprobadas.

## Cómo está organizado

La numeración de las carpetas es la misma del Drive del proyecto, para que los dos se lean igual.

| Carpeta | Qué contiene |
|---|---|
| `0-insumos-empresa/` | Todo lo que entregó la empresa. Es fuente y no se edita: si una cifra está mal, se pide el archivo nuevo, no se corrige este. |
| `0-insumos-empresa/0.1-estados-financieros/` | Estado de resultados auditado 2016-2025 y ventas mensuales 2026. Base de toda cifra que se cite. |
| `0-insumos-empresa/0.2-diagnostico-areas/` | Respuestas escritas de las tres líderes de área, el consolidado de las tres, y las respuestas de Pacho al cuestionario de agosto. |
| `0-insumos-empresa/0.3-documentos-corporativos/` | Planeación estratégica de junio-julio de 2024 y presentación corporativa. Ver nota abajo. |
| `1-analisis/` | Documentos que leen los insumos y sacan conclusiones. Distinguen hecho verificado, inferencia razonable e hipótesis sin confirmar. |
| `2-planeacion-y-backlog/` | Documentos operativos vigentes. El backlog es el que se revisa en la reunión mensual. |
| `3-estructura-y-manual-de-funciones/` | Organigrama, manual de funciones de los trece cargos, y los borradores que lo originaron. |
| `4-politicas/` | Políticas aprobadas por la gerencia. |
| `_proyecto/` | Memoria del proceso y herramientas de trabajo del asesor. No son entregables. |

## Por dónde empezar

Si es la primera vez que abres el repositorio:

1. `2-planeacion-y-backlog/backlog-2026.md` — el estado actual de todo el proceso, ítem por ítem.
2. `1-analisis/verificacion-bloque2-linea-base.md` — qué dicen los datos de ventas, margen y clientes.
3. `3-estructura-y-manual-de-funciones/manual-de-funciones.md` — quién hace qué y con qué indicadores.

## Formatos

Cada documento de trabajo está en `.md` y en `.docx`.

El `.md` es la fuente: se lee directamente en GitHub, se puede comparar entre versiones y es el que se edita. El `.docx` es la copia para leer o imprimir en Word y se genera a partir del `.md`. Si los dos difieren, manda el `.md`.

## Archivos que no están aquí

**Los dos PDF corporativos** (`PLANEACIÓN ESTRATEGICA.pdf` y `PRESENTACION FyA.pdf`) están en el Drive, en `0.3 Documentos corporativos previos`. No se incluyeron en el repositorio porque su propietario es Pacho.

**Los dos archivos grandes de ventas por línea, segmento y cliente** (`Ventas x línea, segmento.xlsx` y `Ventas 242526 Clientes Marcas.xlsx`) están en el Drive. Pesan cerca de 14 MB cada uno y también son de Pacho. Los análisis del bloque 2 salen de ellos.

## Correspondencia con el Drive

El Drive tiene hoy tres carpetas que no corresponden a esta numeración y conviene alinearlas para que los dos repositorios se lean igual:

| Carpeta actual en Drive | Debería quedar en |
|---|---|
| `4. Manual de funciones` | `3. Estructura y manual de funciones` |
| `5. Financiero` | El análisis va a `1. Análisis`; los archivos de datos a `0.1 Estados financieros` |
| `6. Comercial` | `4. Políticas` |

## Convención para agregar documentos

Un documento entra por la carpeta que corresponde a su naturaleza, no por la fecha en que se creó. Si es fuente de la empresa va en `0`, aunque llegue en noviembre. Si es una conclusión nuestra va en `1`, aunque se haya escrito el primer día.

Los archivos de `0-insumos-empresa/` no se editan ni se reemplazan. Si llega una versión corregida, entra como archivo nuevo con la fecha en el nombre y se conserva la anterior, porque varias conclusiones del proceso están amarradas a cifras de una versión concreta.

Nombres de archivo en minúscula, sin tildes, sin espacios y separados por guiones. No es cosmético: macOS y Windows guardan las tildes distinto y un archivo con tilde creado en Mac puede aparecer duplicado o ilegible al clonarlo en Windows.
