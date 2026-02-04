# ⚠️ Importante sobre el Token de Baserow

## Para estudiantes

Este proyecto usa un token de Baserow que estará visible en GitHub. **Esto está bien para proyectos educativos** sin datos sensibles, pero debes tomar estas precauciones:

### ✅ Configuración segura del token

1. **En Baserow, al crear tu token:**
   - Ve a Settings → API tokens
   - Crea un token nuevo
   - **IMPORTANTE:** Marca SOLO permisos de **LECTURA** (Read only)
   - NO marques permisos de escritura, edición o eliminación
   - Guarda el token

2. **En tu config.js:**
   - Pega el token en la propiedad `token`
   - El token solo podrá leer datos, no modificarlos

### 🔒 Buenas prácticas

✅ **SÍ está bien:**

- Usar token de solo lectura en proyectos educativos
- Compartir datos públicos (proyectos, portafolios, etc.)
- Aprender y experimentar

❌ **NO hagas esto:**

- Usar tokens con permisos de escritura
- Guardar datos personales sensibles en Baserow
- Compartir información privada o confidencial

### 💡 Alternativa profesional

Para proyectos profesionales con datos sensibles, debes:

- Crear un backend/API que oculte el token
- Usar variables de entorno en el servidor
- Nunca exponer tokens con permisos de escritura

Este proyecto está diseñado para aprendizaje y prototipos rápidos, no para aplicaciones con datos sensibles.
