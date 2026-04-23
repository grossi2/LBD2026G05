# 🚚 SiniLog - Sistema de Gestión de Siniestros

## Descripción

**SiniLog** es un sistema diseñado para la gestión integral de siniestros en empresas de logística. Permite registrar, administrar y dar seguimiento a reclamos asociados a envíos o despachos.

El sistema se integra con un **Sistema de Paquetes Externo (SPE)**, desde el cual los clientes inician los reclamos.

---

## Objetivos:

* Centralizar la gestión de siniestros
* Mejorar el seguimiento de reclamos
* Facilitar la comunicación entre clientes y operadores
* Generar reportes e indicadores para supervisión

---

## Actores del sistema:

* **Cliente**

  * Inicia reclamos desde el sistema externo (SPE)

* **Administrador**

  * Gestiona usuarios y configuración del sistema

* **Operador**

  * Gestiona reclamos, documentos y novedades

* **Supervisor**

  * Consulta estadísticas e informes

---

## Funcionalidades principales

* 📥 Registro de reclamos
* 📎 Carga de documentos y recursos (imágenes, videos)
* 🔔 Gestión de novedades (notificaciones internas)
* 📊 Panel de control con métricas
* 📄 Generación de reportes (PDF)
* 👥 Gestión de usuarios y roles

---

* **Base de Datos**

  * MySQL

* **Integraciones**

  * Sistema de Paquetes Externo (SPE)
  * Sistema de notificaciones (Mailgun vía sistema externo)

---

## 🔄 Flujo básico

1. El cliente inicia un reclamo desde el SPE
2. SiniLog registra el reclamo
3. Un operador gestiona el caso
4. Se agregan documentos, recursos y novedades
5. El supervisor monitorea métricas y reportes

---

## 🧪 Estado del proyecto

🚧 En desarrollo

---

## 📝 Decisiones de diseño

* No se eliminan usuarios con datos críticos asociados
* Se evita el uso de ENUM para mayor portabilidad
* Integración desacoplada para envío de notificaciones

---

## 👨‍💻 Equipo

* Grupo 05 - LBD 2026

---

## 📄 Licencia

Este proyecto es de uso académico.
