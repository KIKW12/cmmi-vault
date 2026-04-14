---
tags:
  - nivel-4
  - filtro
---

# Nivel 4 — Gestionado Cuantitativamente

Áreas de proceso: OPP, QPM

---

## Áreas de Proceso (Nivel 4)

```dataview
TABLE nombre AS "Área de Proceso", categoria AS "Categoría"
FROM ""
WHERE tipo = "area-de-proceso" AND nivel_madurez = 4
SORT sigla ASC
```

---

## Todas las Prácticas Específicas (Nivel 4)

```dataview
TABLE area_de_proceso AS "PA", meta_especifica AS "SG", estado_implementacion AS "Estado"
FROM ""
WHERE tipo = "practica-especifica" AND nivel_madurez = 4
SORT area_de_proceso ASC, numero ASC
```

---

## Subprácticas por Estado de Implementación

### Pendientes
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 4 AND estado_implementacion = "pendiente"
SORT area_de_proceso ASC, practica_especifica ASC, numero ASC
```

### En Proceso
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 4 AND estado_implementacion = "en proceso"
SORT area_de_proceso ASC
```

### Completadas
```dataview
TABLE area_de_proceso AS "PA", practica_especifica AS "SP"
FROM ""
WHERE tipo = "subpractica" AND nivel_madurez = 4 AND estado_implementacion = "completo"
SORT area_de_proceso ASC
```
