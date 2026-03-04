# aws-it-ops-automator

AutoDiag: Cloud-Scale Hardware Analytics
Sistema automatizado para el procesamiento y análisis de reportes de hardware utilizando una arquitectura orientada a eventos en AWS.

Fase 1: Ingesta de Datos
Amazon S3: Utilizado como punto de entrada para logs de diagnóstico en formato JSON.

Seguridad: Implementación de acceso privado y etiquetado (Tagging) para control de costos y auditoría.

Notificaciones: El sistema utiliza AWS Lambda para el procesamiento automático de logs mediante S3 Event Notifications.
