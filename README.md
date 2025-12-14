# Pombero - Releases

![Banner](banner.png)

**Pombero** es un asistente digital que vigila tu hardware desde las sombras. Un guardián del sistema con personalidad folklórica que te ayuda a monitorear y diagnosticar tu computadora usando inteligencia artificial.

## 📦 Descarga

### Windows
- **Archivo:** `Pombero.exe`
- **Requisitos:** Windows 10 o superior

---

## 🚀 Instalación Rápida

1. **Descarga** el archivo `Pombero.exe` desde la sección de [Releases](../../releases)
2. **Ejecuta** el archivo haciendo doble clic
3. Si Windows muestra una advertencia de seguridad:
   - Haz clic en "Más información"
   - Luego en "Ejecutar de todas formas"
4. **Configura** tu API key de Google (solo la primera vez)

---

## 🔑 Primera Configuración

La primera vez que ejecutes Pombero, necesitarás configurar tu API key de Google Gemini.

### ¿Qué es una API key?

Es una clave gratuita que permite a Pombero usar los servicios de Google Gemini. Solo necesitas una cuenta de Google.

### Cómo obtener tu API key:

1. Visita: https://aistudio.google.com/app/apikey
2. Inicia sesión con tu cuenta de Google
3. Haz clic en "Crear API key" o "Create API key"
4. Copia la clave que aparece

### Configurar en Pombero:

1. Al ejecutar Pombero por primera vez, verás un mensaje pidiendo tu API key
2. Pega la clave que copiaste (Ctrl+V)
3. Presiona Enter
4. ¡Listo! Pombero guardará tu clave automáticamente

**Nota:** La clave se guarda de forma segura en tu computadora. Solo tú puedes verla.

---

## 🎮 Uso

Una vez configurado, Pombero está listo para usar.

### Hacer una pregunta:

1. Cuando veas el mensaje `Tú:`, escribe tu pregunta
2. Presiona Enter
3. Pombero analizará tu sistema y te responderá

### Ejemplos de preguntas:

- "¿Cuál es el estado actual de mi CPU?"
- "Muéstrame los procesos que más recursos usan"
- "¿Cuánta memoria RAM tengo disponible?"
- "Dame información sobre mi GPU"
- "Revisa si hay errores en los drivers"
- "Dame un resumen del estado de mi sistema"
- "¿Cuánto espacio tengo en disco?"
- "Muéstrame información de red"

### Salir de Pombero:

Para cerrar Pombero, escribe cualquiera de estos comandos:
- `silencio`
- `salir`
- `exit`
- `off`
- `basta`

---

## 🛠️ Funcionalidades

Pombero puede responder preguntas sobre:

- **Especificaciones del Sistema:** Sistema operativo, CPU, nombre del procesador, núcleos físicos y hilos lógicos
- **Métricas en Tiempo Real:** Porcentaje de uso de CPU, porcentaje y cantidad de RAM usada, RAM disponible
- **Procesos Top:** Los 5 procesos que más consumen CPU (con PID y nombre)
- **Información de Discos:** Lista de particiones y porcentaje de espacio usado por cada una
- **Información de GPU:** Nombre de la tarjeta gráfica, versión del driver y fecha (requiere WMI en Windows)
- **Información de Red:** Adaptadores de red físicos con direcciones MAC y fabricante (requiere WMI en Windows)
- **Errores de Drivers:** Detección de drivers con problemas o errores en el sistema

---

## ❓ Solución de Problemas

### Pombero no se ejecuta

- Si aparece "Windows protegió tu PC", haz clic en "Más información" y luego "Ejecutar de todas formas"
- Asegúrate de tener permisos de administrador si es necesario

### Error al configurar la API key

- Verifica que copiaste la clave completa (debe ser una cadena larga)
- Asegúrate de no haber copiado espacios adicionales
- Intenta obtener una nueva API key desde https://aistudio.google.com/app/apikey

### Pombero dice "Límite de cuota alcanzado"

- El plan gratuito de Google Gemini tiene un límite de 20 consultas por día
- Espera hasta el día siguiente o considera actualizar tu plan en: https://ai.google.dev/pricing

### Pombero no responde o tarda mucho

- Verifica tu conexión a internet
- Puede que hayas alcanzado el límite de consultas diarias
- Intenta cerrar y volver a abrir Pombero

---

## 🎭 Personalidad del Pombero

El Pombero habla con una mezcla de:
- **SysAdmin Cyberpunk:** Términos técnicos precisos
- **Gaucho Místico:** Folklore y expresiones argentinas

Ejemplos:
- "El silicio está caliente"
- "Hay gualichos en la RAM"
- "El horizonte está despejado" (cuando todo está bien)
- "La máquina está afiebrada" (CPU > 80%)

---

## 🔒 Privacidad y Seguridad

- Tu API key se guarda solo en tu computadora, en un archivo llamado `.env`
- Pombero no envía información personal a servidores externos (excepto a Google Gemini para procesar tus consultas)
- Puedes eliminar el archivo `.env` en cualquier momento para eliminar tu configuración

---

## 📝 Notas Importantes

- Pombero requiere conexión a internet (necesita conectarse a Google Gemini)
- La primera ejecución puede tardar unos segundos más mientras se configura
- En Windows, algunas funcionalidades avanzadas (GPU detallada, red completa) requieren WMI. Si no está disponible, Pombero usará métodos alternativos con información más limitada
- Pombero es un asistente técnico: te ayuda a entender tu hardware, pero no reemplaza a un técnico profesional si tienes problemas serios

---

## 📞 Obtener Ayuda

Si tienes problemas que no se resuelven con esta guía:

1. Revisa la sección de [Issues](../../issues) en GitHub
2. Crea un nuevo issue describiendo tu problema
3. Incluye información sobre tu sistema operativo y el error que ves

---

## 🔧 Para Desarrolladores

El repositorio principal de Pombero es privado por el momento, pero será liberado próximamente. Una vez público, podrás contribuir o compilar desde el código fuente.

---

## 🗺️ Próximos Pasos

Pombero está en constante evolución. Próximamente se agregarán:

### 🤖 Nuevos Proveedores de IA
- **Proveedores Gratuitos:** Groq (prioridad)
- **Proveedores de Pago:** Anthropic (Claude) y OpenAI (GPT)

### 🛠️ Mejoras y Nuevas Funcionalidades
- **Nuevas Tools:** Herramientas adicionales para diagnóstico y monitoreo
- **Optimizaciones:** Mejoras de rendimiento y eficiencia en las tools existentes

---

## 📝 Licencia

Este proyecto es de código abierto. Úsalo y modifícalo como quieras.

---

**"El Sistema te observa desde las sombras..."** 🕯️
