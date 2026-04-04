# Contribuir al Sitio Web del IDIT

¡Gracias por tu interés en contribuir al sitio web oficial del Instituto Dominicano de Innovación y Tecnología (IDIT)! Este documento te guiará en el proceso de contribución.

## 📋 Tabla de Contenidos

- [Código de Conducta](#código-de-conducta)
- [¿Cómo Puedo Contribuir?](#cómo-puedo-contribuir)
- [Proceso de Desarrollo](#proceso-de-desarrollo)
- [Guía de Estilo](#guía-de-estilo)
- [Reportar Bugs](#reportar-bugs)
- [Sugerir Mejoras](#sugerir-mejoras)

## 📜 Código de Conducta

Este proyecto y todos los que participan en él se rigen por el Código de Conducta del IDIT. Al participar, se espera que mantengas este código. Por favor, reporta comportamiento inaceptable a infoidit30@gmail.com.

## 🤝 ¿Cómo Puedo Contribuir?

### Reportar Bugs

Antes de crear un reporte de bug, por favor verifica que el problema no haya sido reportado anteriormente. Si el bug es nuevo:

1. **Usa un título claro y descriptivo** para el issue
2. **Describe los pasos exactos** para reproducir el problema
3. **Proporciona ejemplos específicos** de lo que esperabas y lo que obtuviste
4. **Incluye capturas de pantalla** si es posible
5. **Especifica el navegador y versión** donde ocurre el problema

### Sugerir Mejoras

Las sugerencias de mejoras son bienvenidas. Para proponer una:

1. **Usa un título claro y descriptivo** para el issue
2. **Proporciona una descripción detallada** de la mejora sugerida
3. **Explica por qué esta mejora** sería útil para el sitio
4. **Lista ejemplos** de cómo funcionaría la mejora

### Pull Requests

Sigue estos pasos para enviar tu contribución:

1. Haz un Fork del repositorio
2. Crea una rama desde `main` (`git checkout -b feature/MiMejora`)
3. Realiza tus cambios siguiendo la [Guía de Estilo](#guía-de-estilo)
4. Haz commit de tus cambios (`git commit -m 'Añadir nueva funcionalidad'`)
5. Push a la rama (`git push origin feature/MiMejora`)
6. Abre un Pull Request

## 💻 Proceso de Desarrollo

### Configuración Local

```bash
# Clona el repositorio
git clone https://github.com/ALSRD/idit-web.git

# Navega al directorio
cd idit-web

# Abre el archivo index.html en tu navegador
# O usa un servidor local como Live Server en VS Code
```

### Estructura del Proyecto

```
idit-web/
├── index.html          # Página principal
├── README.md           # Documentación del proyecto
└── CONTRIBUTING.md     # Esta guía
```

## 🎨 Guía de Estilo

### HTML

- Usa **indentación de 2 o 4 espacios** (mantén consistencia)
- Usa **etiquetas semánticas** cuando sea posible (`<section>`, `<article>`, `<nav>`)
- Incluye **atributos alt** en todas las imágenes
- Mantén las **líneas de código legibles** (máximo 120 caracteres)

### CSS

- Usa **estilos inline** solo cuando sea absolutamente necesario
- Mantén **consistencia** con los estilos existentes
- Usa **nombres de clase descriptivos** en español o inglés
- Organiza las propiedades CSS **alfabéticamente** cuando sea posible

### Accesibilidad

- Asegúrate de que **todos los elementos interactivos** sean accesibles por teclado
- Usa **contraste de color adecuado** (mínimo WCAG AA)
- Incluye **etiquetas ARIA** cuando sea necesario
- Prueba la **navegación con teclado**

### Contenido

- Usa **español formal** para todo el contenido
- Mantén un **tono profesional** y educativo
- Revisa la **ortografía y gramática** antes de enviar
- Asegúrate de que los **enlaces externos** funcionen correctamente

## 🐛 Reportar Bugs

Cuando reportes un bug, incluye:

- **Título descriptivo**: Resume el problema en una línea
- **Pasos para reproducir**: Lista detallada de cómo reproducir el bug
- **Comportamiento esperado**: Qué esperabas que sucediera
- **Comportamiento actual**: Qué sucedió realmente
- **Capturas de pantalla**: Si aplica
- **Entorno**: Navegador, versión, sistema operativo

### Ejemplo de Reporte de Bug

```markdown
**Título**: El botón de WhatsApp no abre la conversación correctamente

**Pasos para reproducir**:
1. Ir a la sección de contacto
2. Hacer clic en el ícono de WhatsApp
3. Observar el comportamiento

**Comportamiento esperado**: 
Debe abrir WhatsApp Web con el número del IDIT prellenado

**Comportamiento actual**: 
Se abre una nueva pestaña vacía

**Navegador**: Chrome 120.0.0
**Sistema Operativo**: Windows 11
```

## 💡 Sugerir Mejoras

Para sugerir mejoras:

1. **Verifica** que la mejora no esté ya propuesta o implementada
2. **Describe claramente** el problema que resuelve
3. **Proporciona ejemplos** de implementación
4. **Considera alternativas** y explica por qué tu propuesta es mejor

### Ejemplo de Sugerencia

```markdown
**Título**: Añadir sección de testimonios de estudiantes

**Descripción**: 
Añadir una nueva sección que muestre testimonios de estudiantes que han completado programas del IDIT.

**Beneficio**: 
Aumentará la confianza de potenciales estudiantes al ver experiencias reales.

**Propuesta de implementación**:
- Sección después de "Preguntas Frecuentes"
- Carrusel con 3-5 testimonios
- Incluir foto, nombre y programa del estudiante
```

## 📝 Commit Messages

Usa mensajes de commit claros y descriptivos:

- **feat**: Nueva funcionalidad (`feat: añadir sección de blog`)
- **fix**: Corrección de bug (`fix: corregir enlace de WhatsApp`)
- **docs**: Cambios en documentación (`docs: actualizar README`)
- **style**: Cambios de formato (`style: mejorar espaciado en hero`)
- **refactor**: Refactorización de código (`refactor: reorganizar secciones`)
- **test**: Añadir o modificar tests
- **chore**: Tareas de mantenimiento (`chore: actualizar dependencias`)

## 🔍 Proceso de Revisión

Todos los Pull Requests serán revisados por los mantenedores del proyecto:

1. **Revisión inicial**: Verificación de que cumple con las guías
2. **Feedback**: Comentarios y sugerencias de mejora
3. **Iteración**: Realizar cambios solicitados si es necesario
4. **Aprobación**: Una vez aprobado, se fusionará con `main`
5. **Despliegue**: Los cambios se publicarán automáticamente via GitHub Pages

## 📞 Contacto

Si tienes preguntas sobre cómo contribuir:

- **Email**: infoidit30@gmail.com
- **WhatsApp**: [Enviar mensaje](https://wa.me/18094388057)
- **Issues**: Abre un issue en GitHub con la etiqueta `question`

## 🙏 Agradecimientos

¡Gracias por contribuir al desarrollo de la plataforma educativa del IDIT! Tu aporte ayuda a mejorar la educación virtual en la República Dominicana.

---

*Última actualización: Enero 2025*
*Instituto Dominicano de Innovación y Tecnología (IDIT)*
