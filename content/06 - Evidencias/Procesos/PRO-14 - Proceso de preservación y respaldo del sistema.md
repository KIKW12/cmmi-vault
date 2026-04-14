---
tipo: evidencia
categoria: "proceso"
id: "PRO-14"
nombre: "Proceso de preservación y respaldo del sistema"
tags:
  - cmmi
  - evidencia
  - "proceso"
---

# 📙 PRO-14 — Proceso de preservación y respaldo del sistema

| Propiedad | Valor |
|-----------|-------|
| **ID** | PRO-14 |
| **Tipo** | 📙 Proceso |

---

## Subprácticas CMMI Relacionadas

- [[CM SP 1.2 - Establecer un sistema de gestión de configuración|CM 1.2]]

---

## Contenido

📙Proceso de preservación y respaldo del sistemaRevisado porEmptyCMMI - SubpracticasCM 1.2IDPRO - 14Creado porLLilian Rodríguez UribeFecha de creaciónApril 10, 2026Fecha de modificaciónEmptyValidadoEmptyModificado porEmptyTítulo de proceso: Proceso de preservación y respaldo del sistema1. IDENTIFICACIÓN DEL PROCESOCampoValorNombre del procesoProceso de preservación y respaldo del sistemaCódigo / IDPRO - 14Versión1.0Área de proceso CMMICMPráctica(s) mapeada(s)CM 1.2ElaboróLilian Rodríguez UribeAprobóFecha de aprobación2. PROPÓSITO Y ALCANCE2.1 PropósitoEstablecer los pasos sistemáticos para realizar, verificar y almacenar copias de seguridad (backups) de los activos organizacionales y de los productos de trabajo de los equipos, garantizando la preservación y rápida recuperación de la información en caso de contingencias, pérdida de datos o fallos en las plataformas.2.2 AlcanceEste proceso afecta a todo el entorno de Notion (espacios departamentales y de proyectos), a los repositorios de GitHub y al almacenamiento en Google Drive. Debe ser ejecutado de forma periódica (mensualmente o al finalizar un momento clave del proyecto).3. ENTRADAS (INPUTS)#Nombre del Input1Workspace completo de Notion (Bases de datos, páginas, políticas y artefactos de proyectos).2Repositorios de código fuente de los equipos alojados en GitHub.4. SALIDAS (OUTPUTS)#Nombre del Output1Archivo .zip con la exportación completa de Notion (formato Markdown/CSV).2Archivos comprimidos (.zip) del código fuente de la rama principal de cada repositorio en GitHub.3Respaldo consolidado y almacenado de forma segura en la carpeta Respaldos_Departamentales en Google Drive.Pasos:pasoActividadDescripciónResponsableCMMI - Subprácticas1Exportación de NotionAcceder a la configuración del Workspace de Notion, seleccionar la opción "Export all workspace content" (formato Markdown & CSV) y descargar el archivo .zip resultante.Project ManagerCM 1.22Descarga desde GitHubIngresar al repositorio de cada equipo en GitHub, ubicarse en la rama principal protegida (ej. main, develop) y descargar el código usando la opción "Download ZIP".TL AOCM 1.23Almacenamiento en DriveCrear una subcarpeta en Respaldos_Departamentales dentro de Google Drive nombrada con la fecha actual (ej. Backup_2026-04-09). Subir los archivos .zip obtenidos en los pasos 1 y 2.PM TL AOCM 1.2Changelog VersionDescripción de cambiosResponsable de cambiosFecha de cambioRevisado por1.0Creación del proceso de respaldos para cumplir con la preservación del sistema de gestión de configuración.LLilian Rodríguez UribeApril 10, 2026Como eliminar o actualizar este artefactoEste artefacto se puede por eliminar o modificar si no cumple con las políticas de calidad📕Política de calidad de artefactos
