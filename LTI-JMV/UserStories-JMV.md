# Historias de Usuario para LTI Applicant-Tracking System (ATS)

## Historia de Usuario 1: Gestión de Candidatos

### Como reclutador,
quiero ingresar, organizar y dar seguimiento a los perfiles de los candidatos,
para que pueda gestionar eficientemente el proceso de selección y contratación.

### Descripción:
Esta funcionalidad permitirá a los reclutadores añadir nuevos candidatos al sistema, organizar su información y realizar un seguimiento detallado de cada uno durante las diferentes etapas del proceso de selección.

### Criterios de Aceptación:
1. **Dado que** un reclutador tiene las credenciales adecuadas, **cuando** accede al sistema, **entonces** debería poder añadir un nuevo perfil de candidato con campos como nombre, experiencia, habilidades y currículum adjunto.
2. **Dado que** un candidato ha sido añadido al sistema, **cuando** el reclutador lo selecciona, **entonces** debería poder ver y editar la información del candidato, así como agregar notas y documentos adicionales.
3. **Dado que** un reclutador está gestionando múltiples candidatos, **cuando** accede al panel de candidatos, **entonces** debería poder filtrarlos y organizarlos según diferentes criterios como etapa del proceso, calificación o fecha de aplicación.

### Notas Adicionales:
- Considerar la implementación de alertas o recordatorios para el seguimiento de candidatos en etapas críticas.
- Asegurar la protección de datos sensibles de los candidatos conforme a las regulaciones de privacidad aplicables.

### Historias de Usuario Relacionadas:
- **Historia de Usuario 2:** Flujos de Trabajo Personalizados
- **Historia de Usuario 3:** Análisis Predictivo

## Historia de Usuario 2: Flujos de Trabajo Personalizados

### Como gerente de recursos humanos,
quiero crear flujos de trabajo personalizados para las etapas del proceso de selección,
para que el proceso se adapte a las necesidades específicas de cada equipo o cliente.

### Descripción:
Esta funcionalidad permitirá a los gerentes de recursos humanos definir y configurar diferentes etapas en el proceso de selección, ajustándose a los requerimientos particulares de distintos departamentos o clientes.

### Criterios de Aceptación:
1. **Dado que** un gerente de recursos humanos tiene las credenciales adecuadas, **cuando** accede a la configuración del sistema, **entonces** debería poder crear un nuevo flujo de trabajo definiendo las etapas específicas del proceso de selección.
2. **Dado que** se ha creado un flujo de trabajo personalizado, **cuando** un reclutador inicia un nuevo proceso de selección, **entonces** debería poder seleccionar el flujo de trabajo adecuado según el equipo o cliente correspondiente.
3. **Dado que** un flujo de trabajo está en uso, **cuando** un gerente de recursos humanos necesita realizar cambios, **entonces** debería poder editar las etapas del flujo de trabajo y aplicar los cambios a los procesos en curso si es necesario.

### Notas Adicionales:
- Incluir la opción de clonar flujos de trabajo existentes para facilitar la creación de nuevos con modificaciones menores.
- Permitir la asignación de responsables específicos para cada etapa dentro del flujo de trabajo.

### Historias de Usuario Relacionadas:
- **Historia de Usuario 1:** Gestión de Candidatos
- **Historia de Usuario 3:** Análisis Predictivo

## Historia de Usuario 3: Análisis Predictivo

### Como analista de reclutamiento,
quiero que el sistema utilice inteligencia artificial para analizar los perfiles de los candidatos,
para que pueda recibir recomendaciones basadas en patrones de contratación anteriores y mejorar la calidad de las contrataciones.

### Descripción:
Esta funcionalidad permitirá al sistema emplear algoritmos de inteligencia artificial para evaluar los perfiles de los candidatos y sugerir aquellos que mejor se ajusten a las posiciones disponibles, basándose en datos históricos y patrones de éxito en contrataciones previas.

### Criterios de Aceptación:
1. **Dado que** el sistema cuenta con datos históricos de contrataciones, **cuando** un nuevo candidato es añadido, **entonces** debería analizar su perfil y asignarle una puntuación de adecuación para las posiciones abiertas.
2. **Dado que** un reclutador está revisando candidatos para una posición específica, **cuando** accede a la lista de candidatos, **entonces** debería ver recomendaciones destacadas basadas en el análisis predictivo del sistema.
3. **Dado que** se han realizado contrataciones exitosas, **cuando** el sistema actualiza sus datos, **entonces** debería ajustar sus algoritmos para mejorar futuras recomendaciones basadas en los nuevos patrones identificados.

### Notas Adicionales:
- Asegurar la transparencia en las recomendaciones, permitiendo a los reclutadores ver los factores que contribuyeron a la puntuación de cada candidato.
- Implementar mecanismos de retroalimentación para que los reclutadores puedan informar al sistema sobre la precisión de las recomendaciones y mejorar continuamente el algoritmo.

### Historias de Usuario Relacionadas:
- **Historia de Usuario 1:** Gestión de Candidatos
- **Historia de Usuario 2:** Flujos de Trabajo Personalizados


# Backlog de Producto - LTI ATS

## 📌 Priorización de Historias de Usuario

| #  | Historia de Usuario | Valor del Negocio | Urgencia | Dependencias | Coste de Implementación | Riesgo | Prioridad |
|----|--------------------|------------------|---------|-------------|----------------------|--------|-----------|
| 1  | Gestión de Candidatos | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | Alta | Medio | Bajo | 🔥 Alta |
| 2  | Flujos de Trabajo Personalizados | ⭐⭐⭐⭐ | ⭐⭐⭐ | Media | Alto | Medio | 🚀 Media |
| 3  | Análisis Predictivo | ⭐⭐⭐⭐ | ⭐⭐ | Baja | Alto | Alto | 🎯 Baja |

---

## 🔥 1. Historia de Usuario: Gestión de Candidatos (Prioridad Alta)

### **Tareas**
1. Diseñar la interfaz para la gestión de candidatos.
2. Implementar la funcionalidad de creación y edición de candidatos.
3. Desarrollar el sistema de filtrado y organización de candidatos.
4. Crear la base de datos para almacenar la información de candidatos.
5. Implementar validaciones de datos y protección de información sensible.
6. Realizar pruebas de usuario para verificar la funcionalidad.

### **Justificación de Prioridad**
- **Alto valor de negocio**: Es el núcleo del ATS, permitiendo a los reclutadores gestionar el talento.
- **Alta urgencia**: Necesario para empezar a operar con el sistema.
- **Alta dependencia**: Otras funcionalidades requieren que los candidatos existan en la plataforma.
- **Bajo riesgo**: Funcionalidad estándar en la mayoría de ATS.

---

## 🚀 2. Historia de Usuario: Flujos de Trabajo Personalizados (Prioridad Media)

### **Tareas**
1. Diseñar la interfaz para la configuración de flujos de trabajo.
2. Implementar la funcionalidad de creación y edición de flujos.
3. Permitir la asignación de responsables en cada etapa.
4. Habilitar la opción de clonar flujos de trabajo existentes.
5. Integrar con la gestión de candidatos.
6. Realizar pruebas de usuario con reclutadores.

### **Justificación de Prioridad**
- **Alto valor de negocio**: Permite personalización para diferentes clientes y procesos.
- **Media urgencia**: No es imprescindible para el funcionamiento inicial, pero agrega valor competitivo.
- **Alta dependencia**: Necesita que la gestión de candidatos esté implementada.
- **Riesgo medio**: Requiere flexibilidad en la arquitectura para soportar diferentes configuraciones.

---

## 🎯 3. Historia de Usuario: Análisis Predictivo (Prioridad Baja)

### **Tareas**
1. Definir los algoritmos de análisis predictivo a utilizar.
2. Integrar la base de datos de candidatos con los algoritmos.
3. Desarrollar la funcionalidad de puntuación de candidatos.
4. Diseñar la interfaz de recomendaciones basadas en IA.
5. Implementar un sistema de feedback para mejorar las predicciones.
6. Evaluar la precisión del modelo con datos reales.

### **Justificación de Prioridad**
- **Alto valor de negocio**: Agrega diferenciación y mejora la calidad de selección.
- **Baja urgencia**: No es crítico para la funcionalidad inicial del ATS.
- **Baja dependencia**: Puede desarrollarse después de que la gestión de candidatos esté en marcha.
- **Alto riesgo**: Requiere datos históricos y validaciones constantes para evitar sesgos.

---

## 📌 Conclusión
El backlog prioriza primero la gestión de candidatos, seguida por la configuración de flujos de trabajo y, finalmente, el análisis predictivo. Este orden asegura que el sistema sea funcional rápidamente y luego evolucione con más capacidades avanzadas.


# 📌 Tickets de Trabajo - Gestión de Candidatos

---

## 🎟️ Ticket 1: Diseñar la interfaz para la gestión de candidatos

### 📖 Descripción Detallada
**Propósito:**  
Crear una interfaz intuitiva y eficiente que permita a los reclutadores visualizar, añadir y gestionar candidatos fácilmente.

**Detalles Específicos:**
- La interfaz debe incluir una lista de candidatos con opciones de filtrado y búsqueda.
- Debe permitir la creación, edición y eliminación de perfiles de candidatos.
- El diseño debe seguir la guía de estilos de la aplicación.

### ✅ Criterios de Aceptación
1. **Dado que** el reclutador accede al sistema, **cuando** abre la sección de candidatos, **entonces** debe ver una lista clara y ordenada de todos los candidatos disponibles.
2. **Dado que** el usuario necesita encontrar un candidato específico, **cuando** usa los filtros o la barra de búsqueda, **entonces** los resultados deben actualizarse en tiempo real.
3. **Dado que** el usuario visualiza un candidato, **cuando** hace clic en su perfil, **entonces** debe abrirse una vista detallada con toda su información.

### 🚦 Prioridad: Alta
### ⏳ Estimación de Esfuerzo: 5 puntos de historia
### 👥 Asignación: Equipo de UI/UX
### 🏷️ Etiquetas: `UI`, `Frontend`, `Diseño`
### 🔗 Enlaces o Referencias:
- [Guía de estilos](#)
- [Mockups del diseño](#)

---

## 🎟️ Ticket 2: Implementar la funcionalidad de creación y edición de candidatos

### 📖 Descripción Detallada
**Propósito:**  
Permitir a los reclutadores crear y actualizar perfiles de candidatos con información relevante.

**Detalles Específicos:**
- Se deben capturar datos como nombre, correo, teléfono, experiencia, habilidades y currículum adjunto.
- Validaciones obligatorias en campos clave (nombre, correo, teléfono).
- Posibilidad de editar la información una vez guardada.

### ✅ Criterios de Aceptación
1. **Dado que** el usuario desea agregar un candidato, **cuando** hace clic en "Añadir Candidato", **entonces** se debe abrir un formulario con los campos requeridos.
2. **Dado que** el usuario completa el formulario, **cuando** presiona "Guardar", **entonces** la información debe almacenarse correctamente y mostrarse en la lista de candidatos.
3. **Dado que** el usuario desea editar un candidato, **cuando** hace clic en "Editar", **entonces** debe poder modificar los datos y guardar los cambios.

### 🚦 Prioridad: Alta
### ⏳ Estimación de Esfuerzo: 8 puntos de historia
### 👥 Asignación: Equipo de Backend y Frontend
### 🏷️ Etiquetas: `Backend`, `Frontend`, `CRUD`
### 🔗 Enlaces o Referencias:
- [Especificaciones de base de datos](#)

---

## 🎟️ Ticket 3: Desarrollar el sistema de filtrado y organización de candidatos

### 📖 Descripción Detallada
**Propósito:**  
Permitir a los reclutadores encontrar y organizar candidatos rápidamente según distintos criterios.

**Detalles Específicos:**
- Implementar filtros por experiencia, habilidades, estado del proceso, etc.
- Opción de ordenar candidatos por fecha de aplicación o puntuación.
- Barra de búsqueda en tiempo real.

### ✅ Criterios de Aceptación
1. **Dado que** el usuario accede a la lista de candidatos, **cuando** aplica un filtro, **entonces** solo deben mostrarse los candidatos que cumplan los criterios seleccionados.
2. **Dado que** el usuario necesita encontrar un candidato específico, **cuando** usa la barra de búsqueda, **entonces** los resultados deben actualizarse dinámicamente.
3. **Dado que** hay múltiples candidatos listados, **cuando** el usuario selecciona una opción de ordenamiento, **entonces** la lista debe reorganizarse en función de ese criterio.

### 🚦 Prioridad: Media
### ⏳ Estimación de Esfuerzo: 5 puntos de historia
### 👥 Asignación: Equipo de Frontend
### 🏷️ Etiquetas: `Frontend`, `Búsqueda`, `UX`
### 🔗 Enlaces o Referencias:
- [Requerimientos UX](#)

---

## 🎟️ Ticket 4: Crear la base de datos para almacenar la información de candidatos

### 📖 Descripción Detallada
**Propósito:**  
Diseñar y estructurar la base de datos que almacene los perfiles de los candidatos de manera eficiente y segura.

**Detalles Específicos:**
- Definir las tablas y relaciones necesarias.
- Asegurar normalización y optimización de consultas.
- Incluir validaciones y restricciones para datos críticos.

### ✅ Criterios de Aceptación
1. **Dado que** el sistema necesita almacenar información de candidatos, **cuando** se registra un nuevo candidato, **entonces** sus datos deben guardarse en la base de datos correctamente.
2. **Dado que** el sistema requiere acceso rápido a los datos, **cuando** un usuario consulta candidatos, **entonces** la respuesta debe ser óptima en tiempo.
3. **Dado que** la información es confidencial, **cuando** se realiza una consulta o actualización, **entonces** debe seguirse el modelo de permisos adecuado.

### 🚦 Prioridad: Alta
### ⏳ Estimación de Esfuerzo: 6 puntos de historia
### 👥 Asignación: Equipo de Backend
### 🏷️ Etiquetas: `Backend`, `Database`
### 🔗 Enlaces o Referencias:
- [Modelo de datos](#)

---

## 🎟️ Ticket 5: Implementar validaciones de datos y protección de información sensible

### 📖 Descripción Detallada
**Propósito:**  
Garantizar que los datos de los candidatos sean correctos y proteger la información personal.

**Detalles Específicos:**
- Validaciones de formato en nombre, correo y teléfono.
- Cifrado de datos sensibles como currículums o identificaciones.
- Control de permisos para modificar o eliminar candidatos.

### ✅ Criterios de Aceptación
1. **Dado que** el usuario ingresa datos en el formulario, **cuando** introduce un correo no válido, **entonces** debe mostrarse un mensaje de error.
2. **Dado que** los datos de los candidatos son sensibles, **cuando** se almacenan en la base de datos, **entonces** la información confidencial debe estar cifrada.
3. **Dado que** no todos los usuarios deben modificar candidatos, **cuando** un usuario sin permisos intenta editar o eliminar, **entonces** debe denegarse la acción.

### 🚦 Prioridad: Alta
### ⏳ Estimación de Esfuerzo: 7 puntos de historia
### 👥 Asignación: Equipo de Backend y Seguridad
### 🏷️ Etiquetas: `Seguridad`, `Validaciones`, `Backend`
### 🔗 Enlaces o Referencias:
- [Política de seguridad de datos](#)

---

## 🎟️ Ticket 6: Realizar pruebas de usuario para verificar la funcionalidad

### 📖 Descripción Detallada
**Propósito:**  
Asegurar que la funcionalidad implementada sea intuitiva y efectiva para los reclutadores.

**Detalles Específicos:**
- Pruebas con usuarios reales en diferentes escenarios.
- Recopilación de feedback y ajustes según resultados.
- Validación de usabilidad y rendimiento.

### ✅ Criterios de Aceptación
1. **Dado que** el sistema está desarrollado, **cuando** un usuario lo prueba, **entonces** debe poder completar el proceso de gestión de candidatos sin problemas.
2. **Dado que** se recaba feedback, **cuando** se identifican problemas, **entonces** se deben registrar y priorizar para corrección.
3. **Dado que** la aplicación debe ser rápida, **cuando** un usuario interactúa con la lista de candidatos, **entonces** las respuestas deben ser inmediatas.

### 🚦 Prioridad: Media
### ⏳ Estimación de Esfuerzo: 4 puntos de historia
### 👥 Asignación: Equipo de QA
### 🏷️ Etiquetas: `QA`, `Pruebas`, `UX`
### 🔗 Enlaces o Referencias:
- [Casos de prueba](#)

---

# 📌 Estimación de Tickets - Gestión de Candidatos

## 🔢 Escala de Estimación (Fibonacci)
- 1 → Tarea muy pequeña, casi trivial.
- 2 → Tarea pequeña pero requiere algo de esfuerzo.
- 3 → Complejidad baja, pero requiere atención.
- 5 → Tarea moderada, con ciertos desafíos.
- 8 → Complejidad media-alta, requiere trabajo considerable.
- 13 → Alta complejidad, puede tomar mucho tiempo.
- 21 → Muy grande, debería dividirse en tareas más pequeñas.

---

## 🎟️ Estimación de Tickets

| #  | Ticket | Puntos de Historia |
|----|-----------------------------------------------|-------------------|
| 1  | Diseñar la interfaz para la gestión de candidatos | 5  |
| 2  | Implementar la funcionalidad de creación y edición de candidatos | 8  |
| 3  | Desarrollar el sistema de filtrado y organización de candidatos | 5  |
| 4  | Crear la base de datos para almacenar la información de candidatos | 8  |
| 5  | Implementar validaciones de datos y protección de información sensible | 8  |
| 6  | Realizar pruebas de usuario para verificar la funcionalidad | 3  |

---

## 🎯 Resumen de Estimación
- **Total de Puntos de Historia:** 37
- **Recomendación:** Se recomienda dividir las tareas de mayor tamaño si el equipo considera que pueden afectar la velocidad del sprint.


