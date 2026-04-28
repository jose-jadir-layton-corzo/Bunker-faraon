# 🛡️ BUNKER-FARAON: Gestión Avanzada y Decepción Táctica

Este proyecto es un ecosistema blindado de gestión personal y empresarial. Lo que comenzó como un sistema de organización (ERP) ha evolucionado hacia una infraestructura de **Ciberseguridad Activa**, utilizando técnicas de **Honeypot (Señuelo)** para neutralizar intrusos.

## 🧠 Visión General
*   **Backend:** Node.js + Express + NeDB (Persistencia ligera).
*   **Frontend:** SPA modular con JavaScript Vanilla, Chart.js y exportación a PDF.
*   **Infraestructura:** Dockerizado con política de auto-arranque y exposición segura mediante **Cloudflare Tunnels**.

## 🌀 Capacidades Operativas
1.  **Bitácora 24/7:** Control exhaustivo semanal de misiones, estados y niveles de importancia.

3.  **Telemetría de Rendimiento:** Gráficos dinámicos de uso de tiempo y productividad por áreas.
4.  **Gestión de Objetivos:** Desglose táctico de tareas vinculado a solicitudes reales.

## ⚔️ Estrategia de Decepción (Honeypot)
El Búnker protege la información real mediante un **"Laberinto de Espejos"**:
*   **Login Engañoso:** El sistema nunca muestra errores de credenciales. Si un atacante falla, recibe un **Token JWT Falso** y es redirigido silenciosamente al **Shadow Dashboard**.
*   **Shadow Dashboard:** Una interfaz señuelo con datos volátiles generados aleatoriamente. Mientras el atacante analiza información falsa, el sistema registra su IP y comportamiento en `sospechosos.db`.
*   **Eliminación de "Flash" del Frontend:** Gracias al uso de cookies **HttpOnly**, el código real nunca se descarga en el navegador a menos que el rol sea `master`.

## 🔐 Blindaje Técnico
*   **Protección CSRF:** Validación obligatoria de tokens en cada petición mutable.
*   **Sanitización NoSQL:** Mitigación total de inyecciones mediante tipado estricto de entradas.
*   **Defensa en Profundidad:** Rate limiting (limitador de intentos) y headers de seguridad configurados.
*   **Gestión Privada:** Los usuarios reales solo pueden crearse mediante un **Endpoint Secreto** protegido por clave maestra.

---
*Búnker-Faraon: "Omnia Custodit"*
