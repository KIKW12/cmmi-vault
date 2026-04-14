---
tags:
  - nivel-2
  - filtro
---

# Nivel 2 — Gestionado

Áreas de proceso: CM, MA, PMC, PP, PPQA, REQM, SAM

---

## Áreas de Proceso (Nivel 2)

```dataview
TABLE nombre AS "Área de Proceso", categoria AS "Categoría"
FROM ""
WHERE tipo = "area-de-proceso" AND nivel_madurez = 2
SORT sigla ASC
```

---

## Todas las Prácticas Específicas (Nivel 2)

```dataview
TABLE area_de_proceso AS "PA", meta_especifica AS "SG", estado_implementacion AS "Estado"
FROM ""
WHERE tipo = "practica-especifica" AND nivel_madurez = 2
SORT area_de_proceso ASC, numero ASC
```

---

## Subprácticas por Estado de Implementación

### Pendientes
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 2 AND estado_implementacion = "pendiente"
SORT area_de_proceso ASC, practica_especifica ASC, numero ASC
```

### En Proceso
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 2 AND estado_implementacion = "en proceso"
SORT area_de_proceso ASC
```

### Completadas
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 2 AND estado_implementacion = "completo"
SORT area_de_proceso ASC
```

---

## Evidencias Mapeadas a Nivel 2

```dataview
TABLE tipo AS "Tipo", file.folder AS "Carpeta"
FROM "06 - Evidencias"
WHERE contains(file.outlinks, [[CM]]) OR contains(file.outlinks, [[MA]]) OR contains(file.outlinks, [[PMC]]) OR contains(file.outlinks, [[PP]]) OR contains(file.outlinks, [[PPQA]]) OR contains(file.outlinks, [[REQM]]) OR contains(file.outlinks, [[SAM]])
SORT categoria ASC
```
