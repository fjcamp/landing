# `landing` — Handoff de repositorio legado/no asignado

**Fecha de corte:** 2026-08-31  
**Repositorio:** `fjcamp/landing`  
**Rama:** `main`  
**Estado:** repositorio público basado en el template “Netlify Developer Portfolio Starter (auto-annotated)”. No se identificó como producto JoinHook activo ni como fuente canónica de `joinhook.cl`.

---

## 0. Regla para otra IA

1. No desplegar este repo sobre `joinhook.cl` ni asumir que es la web corporativa actual.
2. No migrar contenido desde aquí hacia `fjcamp/joinhook` sin revisar propiedad/licencia y utilidad real.
3. Antes de trabajar, decidir con evidencia si el repo debe: archivarse, reutilizarse como sandbox/template o eliminarse en una etapa posterior.
4. No borrar el repositorio durante una sesión de continuidad; preservar historial hasta que exista backup local y decisión explícita.
5. No confundir dependabot/Renovate updates de 2025 con trabajo de producto.

---

## 1. Estado verificable

El README sigue describiendo un starter de Netlify/Stackbit/Next.js para portfolio con Visual Editor.

Los commits más recientes observados son actualizaciones automáticas de dependencias de marzo de 2025, incluyendo Next.js 15.2.x y tipos/ESLint.

No se encontró evidencia de que sea la fuente actual de JoinHook, SnowWise, Mi Gestión, JoinOps, CGE u otro producto activo.

---

## 2. Valor posible

Solo tiene valor si se decide reutilizarlo como:

- sandbox de visual editing;
- referencia de template;
- laboratorio de Netlify;
- base para un sitio futuro separado.

No tiene una propuesta de negocio propia identificada.

---

## 3. Riesgos

- publicar accidentalmente un template genérico;
- confundir dependencias viejas con stack corporativo;
- mantener superficie pública innecesaria;
- duplicar funcionalidad de `fjcamp/joinhook`.

---

## 4. Pendientes

### P0

- verificar si existe deployment conectado;
- verificar dependencias/vulnerabilidades si se va a conservar activo;
- decidir `ARCHIVE`, `SANDBOX` o `REUSE`.

### Si se archiva

- asegurar backup Git/local;
- documentar razón;
- archivar en GitHub, no borrar de inmediato.

### Si se reutiliza

- crear nueva rama;
- eliminar contenido demo/licenciado que no corresponda;
- actualizar dependencias;
- definir nuevo propósito y README;
- CI/build desde cero.

---

## 5. Bitácora resumida

### 2025-03

Última actividad visible: actualizaciones automáticas de dependencias/template.

### 2026-08-31

Se clasifica como **legado/no asignado** en el inventario de continuidad. No se modifica runtime ni se decide aún el archivado.

---

## 6. Instrucción lista para otra IA

```text
Estoy revisando fjcamp/landing.
No lo trates como la web activa de JoinHook. Primero verifica deployments y propósito. El repo es un template legado/no asignado.
No borres ni publiques nada. Propón ARCHIVE, SANDBOX o REUSE con evidencia y espera decisión humana antes de una acción irreversible.
```

**Fin del handoff — corte 2026-08-31.**
