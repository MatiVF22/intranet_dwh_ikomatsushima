## 📝 Descripción del cambio

<!-- Explica brevemente qué se hizo y por qué. -->
Ejemplo: Se agregó un filtro de búsqueda por título en la vista de actividades para facilitar el acceso a contenido específico.

---

## ✅ Cambios realizados

- [x] Se agregó campo de búsqueda en el frontend (React)
- [x] Se integró filtro en la API de Django (`icontains` sobre el título)
- [x] Se actualizó Redux para gestionar los filtros
- [x] Se probó en vista móvil y escritorio

---

## 🧪 ¿Cómo probarlo?

<!-- Instrucciones para testear este cambio localmente -->
1. Ir a `/actividades`
2. Usar el campo de búsqueda con una palabra clave
3. Confirmar que los resultados se filtran correctamente

---

## 🔒 Consideraciones de seguridad

<!-- Menciona si se tocaron datos sensibles o autenticación -->
- No se tocaron credenciales, sesiones ni tokens
- No hay exposición de información privada

---

## 📸 Capturas (opcional)

<!-- Si aplica, incluye capturas del antes y después -->

---

## 🛑 Checklist antes de hacer merge

- [ ] El código compila sin errores
- [ ] Se corrieron las pruebas necesarias
- [ ] Los cambios fueron revisados (por mí o por un compañero)
- [ ] No se subieron archivos innecesarios (logs, .env, etc.)

---

## 🚀 ¿A qué rama se hace merge?
- [ ] `development`
- [ ] `production` (solo si ya fue probado y aprobado en `development`)
