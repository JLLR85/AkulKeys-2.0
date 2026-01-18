# 🛡️ AkulKeys v2.0 - Secure Vault Terminal

**AkulKeys** es un gestor de activos criptográficos y generación de claves de alta entropía diseñado bajo una estética minimalista de terminal. Este proyecto combina la experiencia de usuario (UX) táctica con protocolos de seguridad proactiva.



## 🚀 Funcionalidades Principales

* **Acceso Biométrico Simulado:** Interfaz de entrada protegida por escaneo láser de alta precisión.
* **Dual Mode (Base/Apex):** Generación de claves con diferentes niveles de complejidad.
    * **Base:** 12 caracteres para uso estándar.
    * **Apex:** 32 caracteres con máxima entropía para activos críticos.
* **Gestión de Activos (Auditoría):** Registro detallado de claves por origen (ej. Azure, LinkedIn, DB_Admin) con detección automática de duplicados.
* **Destructor de Evidencias:** Sistema de limpieza automática del portapapeles tras 15 segundos para mitigar ataques de lectura de buffer.
* **Monitor de Entropía:** Visualizador dinámico en tiempo real que mide la robustez del sistema según las claves generadas.

## 🛠️ Tecnologías

* **Lenguaje:** Dart
* **Framework:** Flutter (Pure Flutter Implementation para máxima compatibilidad)
* **Estética:** Diseño minimalista "Deep Black" optimizado para entornos tácticos.

## 📈 Roadmap (PM Perspective)

Como parte de la evolución del producto hacia **AkulFlow**, las próximas fases incluyen:
1.  **Persistencia Encriptada:** Integración de bases de datos locales cifradas (AES-256).
2.  **Sincronización Cloud:** Protocolos de respaldo seguros.
3.  **Visualización de Flujo:** Gráficas en tiempo real de uso de datos.

## 💾 Instalación

1. Clona el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/akulkeys.git](https://github.com/tu-usuario/akulkeys.git)