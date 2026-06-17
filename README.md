Tu archivo `README.md` ha sido generado de manera integral, estructurado específicamente para documentar y blindar la arquitectura descrita en tu archivo **autor.pdf**. 

[file-tag: code-generated-file-0-1781659633484088578]

Aquí tienes una vista previa del contenido que se ha consolidado en el archivo para tu repositorio:

***

# Euniprincez Digital v2026.1-MRP.pk
## Core Sovereign Architecture & SGS Panel de Control

---

### 📜 Propiedad Intelectual y Licencia Maestra
* **[span_0](start_span)[span_1](start_span)Titular y Creador:** Juan Valentín García Espinoza[span_0](end_span)[span_1](end_span)
* **[span_2](start_span)[span_3](start_span)[span_4](start_span)ID Legal (CURP):** GAEJ940310HSPRSN02[span_2](end_span)[span_3](end_span)[span_4](end_span)
* **[span_5](start_span)[span_6](start_span)ID de Registro MEX:** 2608132112[span_5](end_span)[span_6](end_span)
* **[span_7](start_span)[span_8](start_span)[span_9](start_span)Clave de Control Vital (Licencia):** `GAESJN94031024H400`[span_7](end_span)[span_8](end_span)[span_9](end_span)
* **[span_10](start_span)[span_11](start_span)Algoritmo de Referencia / MRP PK:** `45x46-1-43-2026`[span_10](end_span)[span_11](end_span)

> **Aviso de Derechos de Autor:** > ©® 2026 JUAN VALENTÍN GARCÍA ESPINOZA. [span_12](start_span)[span_13](start_span)Todos los derechos reservados[span_12](end_span)[span_13](end_span).  
> [span_14](start_span)Este software y sus componentes asociados constituyen propiedad intelectual privada[span_14](end_span). [span_15](start_span)Queda estrictamente prohibida la alteración de metadatos, la reproducción parcial o total, o la ejecución del sistema fuera de entornos validados sin la firma de control activa[span_15](end_span). [span_16](start_span)La violación de estas disposiciones será sancionada conforme al marco legal aplicable[span_16](end_span).

---

## 🚀 Descripción del Ecosistema

**[span_17](start_span)[span_18](start_span)Euniprincez Digital** es un ecosistema resiliente de gestión y auditoría empresarial de alta seguridad que integra servicios web, interfaces locales y flujos automatizados en la nube[span_17](end_span)[span_18](end_span). [span_19](start_span)[span_20](start_span)[span_21](start_span)[span_22](start_span)Su núcleo operativo, el **SGS Panel de Control**, garantiza soberanía digital absoluta mediante la implementación de criptografía avanzada de extremo a extremo, validaciones matemáticas estrictas y auditorías transaccionales en tiempo real[span_19](end_span)[span_20](end_span)[span_21](end_span)[span_22](end_span).

---

## 🛠️ Módulos Integrados y Funcionalidades

### 1. SGS Panel de Control (Frontend & Carga CSD)
* **[span_23](start_span)[span_24](start_span)[span_25](start_span)Tecnología:** Python (Streamlit / Tkinter) e Interfaces Modernas en HTML5/CSS3[span_23](end_span)[span_24](end_span)[span_25](end_span).
* **[span_26](start_span)[span_27](start_span)[span_28](start_span)Función:** Proporciona un entorno seguro con soporte "Drag & Drop" para la carga e inspección de archivos del SAT (`.cer`, `.key`)[span_26](end_span)[span_27](end_span)[span_28](end_span).
* **[span_29](start_span)Seguridad:** Validación nativa en el cliente del formato criptográfico, verificación automatizada de la vigencia del Certificado de Sello Digital mediante la librería `cryptography` y resguardo temporal controlado en memoria[span_29](end_span).

### 2. Auditoría de Signos y Registro de Ventas (FF/FB)
* **[span_30](start_span)[span_31](start_span)Tecnología:** Python (Pandas / DataFrames)[span_30](end_span)[span_31](end_span).
* **[span_32](start_span)[span_33](start_span)Función:** Control analítico sobre transacciones comerciales discriminadas por Facturas de Ingresos (**FF**) y Notas de Crédito/Egreso (**FB**)[span_32](end_span)[span_33](end_span).
* **[span_34](start_span)[span_35](start_span)Bloqueo Aritmético:** Implementación de la **Ley de los Signos**[span_34](end_span)[span_35](end_span). [span_36](start_span)El sistema bloquea de manera inmediata e irreversible cualquier intento de registrar un ingreso (FF) con signo negativo, impidiendo la posterior generación y firma del documento XML[span_36](end_span).

### 3. API Bridge (Puente de Conexión SGS-SSMS)
* **[span_37](start_span)Tecnología:** FastAPI & `pyodbc`[span_37](end_span).
* **[span_38](start_span)[span_39](start_span)Función:** Actúa como un túnel seguro y de alta velocidad entre el Panel de Control y el motor de base de datos **SQL Server Management Studio (SSMS)**[span_38](end_span)[span_39](end_span).
* **[span_40](start_span)[span_41](start_span)Validación de Entropía:** Protocolo de autenticación doble mediante la inspección estricta de la longitud del token de seguridad (requiere un token SHA-256 exacto de 64 caracteres derivado de la clave maestra del autor)[span_40](end_span)[span_41](end_span).

### 4. Euniprincez-Shield (Backup Criptográfico Automatizado)
* **[span_42](start_span)[span_43](start_span)Tecnología:** Bash / OpenSSL / Google Cloud SDK (`gsutil`)[span_42](end_span)[span_43](end_span).
* **[span_44](start_span)[span_45](start_span)[span_46](start_span)[span_47](start_span)Función:** Compresión y cifrado simétrico diario (00:00 hrs) de la base de datos SSMS y los archivos de autenticación[span_44](end_span)[span_45](end_span)[span_46](end_span)[span_47](end_span).
* **[span_48](start_span)[span_49](start_span)Protocolo de Cifrado:** Uso del estándar de alta seguridad **AES-256-CBC** inyectado con el identificador del autor (`-k $ID_AUTOR`), garantizando almacenamiento inmutable y seguro en buckets de **Google Cloud Storage (GCS)**[span_48](end_span)[span_49](end_span).

### 5. Módulo de Alerta Crítica (Telegram Bot Integration)
* **[span_50](start_span)Tecnología:** API REST / Python (`requests`)[span_50](end_span).
* **[span_51](start_span)[span_52](start_span)Función:** Notificaciones inmediatas directas al dispositivo móvil del autor[span_51](end_span)[span_52](end_span).
* **[span_53](start_span)[span_54](start_span)Disparadores de Alerta:** Envío de estatus de respaldo exitoso (`BACKUP_OK`) o activación inmediata de alarmas silenciosas ante detecciones de anomalías lógicas o violaciones aritméticas en la ley de signos[span_53](end_span)[span_54](end_span).

---

## ⚙️ Instrucciones de Despliegue Rápido

### 1. Configuración de Seguridad Local
Cree el directorio restringido de credenciales y asigne los permisos Unix correspondientes para que únicamente tu usuario del sistema pueda interactuar con las llaves:
```bash
mkdir /Euniprincez_Auth/
chmod 600 /Euniprincez_Auth/