---
tipo: evidencia
categoria: "guia"
id: "GUI-16"
nombre: "Guía de configuración departamental y accesos"
tags:
  - cmmi
  - evidencia
  - "guia"
---

# 📗 GUI-16 — Guía de configuración departamental y accesos

| Propiedad | Valor |
|-----------|-------|
| **ID** | GUI-16 |
| **Tipo** | 📗 Guía |

---

## Subprácticas CMMI Relacionadas

- [[CM SP 1.2 - Establecer un sistema de gestión de configuración|CM 1.2]]

---

## Contenido

📗Guía de configuración departamental y accesosCMMI - SubpracticasCM 1.2Fecha de creaciónApril 9, 2026Fecha de modificaciónEmptyIDGUI - 16PersonLLilian Rodríguez UribeValidado porEmpty1. IDENTIFICACIÓN DE LA GUÍACampoValorNombre de la guíaGuía de configuración departamental y accesosCódigo / IDGUI - 16Versión1.0Área de proceso CMMICMPráctica(s) mapeada(s)CM 1.2ElaboróLilian Rodríguez UribeAprobóFecha de aprobación2. OBJETIVOEstablecer una estructura estándar de almacenamiento y la matriz de niveles de acceso (permisos) para todos los roles del departamento dentro del Sistema de Gestión de Configuración (Notion, GitHub y Google Drive). Esto garantiza la protección de las líneas base y la integridad de los productos de trabajo.3. CUÁNDO USARLAAl configurar el entono de trabajo para un equipo o proyectoAl ejecutar el proceso de transición de roles (PRO - 08) para asignar o revocar accesos.Como referencia para que cualquier miembro del equipo conozca sus permisos y sepa dónde almacenar correctamente sus artefactos.4. PASOS: (1)pasoActividadDescripciónResponsableCMMI - Subprácticas1Asignar accesos en NotionOtorgar permisos según la matriz: • PM: Administrador del Workspace (acceso total). • PO / TL / AO / TM: Permiso de "Edición" (pueden editar bases de datos y colaborar en activos organizacionales registrando en el Changelog). • Socio Formador: "Solo Lectura" (mediante link compartido si aplica).Project Manager Team Leader Architecture Owner Product OwnerCM 1.22Asignar accesos en GitHubConfigurar roles en el repositorio o la organización del equipo: • PM: Admin / Owner (para auditoría). • TL / AO: "Maintainer" o "Admin" del repositorio de su respectivo equipo. • TM / PO: "Write" / "Developer" en su repositorio respectivo.Project Manager Team Leader Architecture OwnerCM 1.23Gestionar Google Drive DepartamentalMantener el orden en el Drive departamental existente, asegurando el uso correcto de la carpeta exclusiva "Respaldos_Departamentales" (a la cual solo los PMs tienen acceso) para salvaguardar copias de seguridad de Notion y GitHub.Project ManagerCM 1.24Proteger ramas de integraciónAplicar candados en GitHub: Configurar la rama principal de entregas del equipo como Protected Branch, requiriendo obligatoriamente un Pull Request para integrar código nuevo.Team Leader Architechture OwnerCM 1.25Bloqueo de líneas baseProteger entregables aprobados en Notion: Una vez que un documento clave es aprobado (Control Formal), el autor o el TL debe activar la función "Lock Page" para evitar alteraciones accidentales.Todos los rolesCM 1.25. CONSIDERACIONES IMPORTANTESPrincipio de Menor Privilegio: Ningún miembro del equipo debe tener permisos de Administrador u "Owner" fuera de sus responsabilidades definidas, para evitar borrados accidentales de los espacios de trabajo.Prohibición de Almacenamiento Local: Queda estrictamente prohibido mantener versiones finales de código, gráficas o documentos exclusivos del proyecto únicamente en las computadoras personales. Todo debe estar en el Sistema de Gestión (Notion, GitHub o Drive).Auditoría de Accesos: Es responsabilidad de los Project Managers revisar periódicamente que los accesos en GitHub y Drive correspondan a los roles vigentes del equipo.Changelog VersionDescripción de cambiosResponsable de cambiosFecha de cambioRevisado por1.0Creación de la guía para estandarizar accesos y repositorios.LLilian Rodríguez UribeApril 9, 2026Como eliminar o actualizar este artefactoEste artefacto se puede por eliminar o modificar si no cumple con las políticas de calidad📕Política de calidad de artefactos
