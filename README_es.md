# Keycloak

Keycloak es una solución de Gestión de Identidad y Acceso de código abierto para aplicaciones y servicios modernos.

Este repositorio contiene el código fuente del Servidor Keycloak, los adaptadores de Java y el adaptador de JavaScript.

## ¿De qué trata el proyecto?

Keycloak es una plataforma completa de gestión de identidades que proporciona:

### Características Principales

* **Autenticación Única (SSO)**: Permite a los usuarios iniciar sesión una vez y acceder a múltiples aplicaciones
* **Gestión de Identidades**: Administración centralizada de usuarios, roles y permisos
* **Federación de Identidades**: Integración con proveedores de identidad externos como LDAP, Active Directory, Google, Facebook, etc.
* **Protocolos Estándar**: Soporte completo para OAuth 2.0, OpenID Connect, SAML 2.0
* **Autorización Granular**: Control de acceso basado en roles y políticas avanzadas
* **Gestión de Sesiones**: Control de sesiones de usuario, logout único, políticas de timeout
* **Temas Personalizables**: Interfaz de usuario completamente personalizable
* **APIs REST**: APIs completas para administración y integración
* **Escalabilidad**: Arquitectura distribuida para alta disponibilidad

### Componentes del Proyecto

* **Servidor Keycloak**: El núcleo del sistema de gestión de identidades
* **Adaptadores Java**: Bibliotecas para integrar aplicaciones Java con Keycloak
* **Adaptador JavaScript**: Cliente JavaScript para aplicaciones web frontend
* **Ejemplos**: Aplicaciones de ejemplo que demuestran diferentes casos de uso
* **Documentación**: Guías completas de instalación, configuración y uso
* **Temas**: Temas predefinidos y personalizables para la interfaz de usuario

## Ayuda y Documentación

* [Documentación](https://www.keycloak.org/documentation.html)
* [Lista de Correo de Usuarios](https://groups.google.com/d/forum/keycloak-user) - Lista de correo para ayuda y preguntas generales sobre Keycloak

## Reportar Vulnerabilidades de Seguridad

Si has encontrado una vulnerabilidad de seguridad, por favor consulta las [instrucciones sobre cómo reportarla correctamente](https://github.com/keycloak/keycloak/security/policy)

## Reportar un Problema

Si crees que has descubierto un defecto en Keycloak, por favor abre [un issue](https://github.com/keycloak/keycloak/issues).
Recuerda proporcionar un buen resumen, descripción y los pasos para reproducir el problema.

## Comenzar a Usar Keycloak

Para ejecutar Keycloak, descarga la distribución desde nuestro [sitio web](https://www.keycloak.org/downloads.html). Descomprime y ejecuta:

    bin/kc.[sh|bat] start-dev

Alternativamente, puedes usar la imagen de Docker ejecutando:

    docker run quay.io/keycloak/keycloak start-dev
    
Para más detalles, consulta la [Documentación de Keycloak](https://www.keycloak.org/documentation.html).

## Construir desde el Código Fuente

Para construir desde el código fuente, consulta la guía de [construcción y trabajo con la base de código](docs/building.md).

### Pruebas

Para ejecutar las pruebas, consulta la guía de [ejecución de pruebas](docs/tests.md).

### Escribir Pruebas

Para escribir pruebas, consulta la guía de [desarrollo de pruebas](docs/tests-development.md).

## Contribuir

Antes de contribuir a Keycloak, por favor lee nuestras [guías de contribución](CONTRIBUTING.md).

## Otros Proyectos de Keycloak

* [Keycloak](https://github.com/keycloak/keycloak) - Servidor Keycloak y adaptadores Java
* [Documentación de Keycloak](https://github.com/keycloak/keycloak-documentation) - Documentación para Keycloak
* [QuickStarts de Keycloak](https://github.com/keycloak/keycloak-quickstarts) - Guías rápidas para comenzar con Keycloak
* [Keycloak Node.js Connect](https://github.com/keycloak/keycloak-nodejs-connect) - Adaptador Node.js para Keycloak
* [Cliente Admin de Keycloak Node.js](https://github.com/keycloak/keycloak-nodejs-admin-client) - Biblioteca Node.js para la API REST de administración de Keycloak

## Casos de Uso Comunes

### Para Desarrolladores
* Proteger aplicaciones web y móviles
* Implementar autenticación única en microservicios
* Integrar con sistemas de identidad existentes
* Personalizar flujos de autenticación y autorización

### Para Empresas
* Centralizar la gestión de usuarios y accesos
* Cumplir con regulaciones de seguridad y privacidad
* Integrar sistemas heterogéneos de identidad
* Escalabilidad para miles de usuarios y aplicaciones

### Para Administradores de TI
* Monitorear y auditar accesos de usuarios
* Gestionar políticas de seguridad centralizadas
* Automatizar procesos de aprovisionamiento de usuarios
* Implementar autenticación multifactor

## Licencia

* [Licencia Apache, Versión 2.0](https://www.apache.org/licenses/LICENSE-2.0)