# 📱 Odoo Flutter Project

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Flutter Version](https://img.shields.io/badge/Flutter-3.13.0-blue.svg)](https://flutter.dev)

![Vista previa de la aplicación](ruta/a/imagen.png) <!-- Cambiar por una imagen real de la app -->

## 📖 Descripción

Este proyecto es una aplicación móvil desarrollada en **Flutter** que se conecta a un servidor **Odoo** para gestionar datos relacionados con el modelo `crm.lead`. La app permite a los usuarios autenticarse, visualizar una lista de clientes potenciales (leads), crear nuevos registros, editar información y eliminarlos según sea necesario.

El propósito de este proyecto es facilitar la gestión comercial en Odoo mediante una interfaz amigable y optimizada para dispositivos móviles.

## 📌 Tabla de Contenidos
- [🚀 Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [🛠 Puesta en Marcha](#-puesta-en-marcha)
- [🌍 Entornos](#-entornos)
- [📚 Documentación](#-documentación)
- [🖥️ Contribución](#️-contribución)
- [👥 Contribuidores](#-contribuidores)
- [🧪 Testing](#-testing)
- [🗺️ Roadmap](#️-roadmap)
- [📝 Changelog](#-changelog)
- [💬 Soporte](#-soporte)
- [💡 Inspiración](#-inspiración)
- [📜 Licencia](#-licencia)

## 🚀 Tecnologías Utilizadas

- **Flutter**: Framework para el desarrollo de aplicaciones móviles.  
- **Dart**: Lenguaje de programación utilizado en Flutter.  
- **Odoo**: Plataforma ERP con API para la gestión de datos.  
- **IntelliJ IDEA**: IDE recomendado para el desarrollo en Flutter.  

---

## 🛠 Puesta en Marcha

### 📌 Requisitos Previos
1. Tener instalado **Flutter** ([Guía de instalación](https://docs.flutter.dev/get-started/install)).  
2. Tener acceso a un servidor **Odoo** con los módulos necesarios activados.  
3. Configurar las credenciales en `lib/config.dart`.  

### 🔧 Instalación y Ejecución
```bash
# Clonar el repositorio
git clone https://github.com/PC-PJJGF/odoo_flutter_project.git
cd odoo-flutter-project

# Instalar dependencias
flutter pub get

# Ejecutar la app en un emulador o dispositivo
flutter run
```

## 🌍 Entornos
| Entorno | URL |
|---------|-----|
| Producción | https://odoo.tuempresa.com |
| Desarrollo | http://localhost:8069 |

## 📚 Documentación de Desarrollo
Para más detalles sobre la API de Odoo y su integración con Flutter, consulta la documentación oficial de Odoo: [Odoo API Docs](https://www.odoo.com/documentation).

Si el proyecto cuenta con documentación interna, agrégala en una **wiki** o en un archivo `docs/README.md`.

## 🖥️ Guía de Contribución
Si deseas contribuir al proyecto, por favor revisa las [Normas de Contribución](CONTRIBUTING.md).

## 👥 Contribuidores

| Contribuidor | Commits | Language | Followers |
|--------------|---------|--------|-----------|
|![carlos75357](https://github.com/carlos75357.png?size=40) [carlos75357](https://github.com/carlos75357) | ![commits](https://img.shields.io/github/commit-activity/t/PC-PJJGF/odoo_flutter_project?branch=develop) | ![language](https://img.shields.io/github/languages/top/PC-PJJGF/odoo_flutter_project) | ![followers](https://img.shields.io/github/followers/carlos75357?label=followers) |

## 🧪 Testing
Para ejecutar los tests del proyecto:
```bash
flutter test
```

## 🗺️ Roadmap
- [ ] Implementar autenticación OAuth
- [ ] Añadir soporte para notificaciones push
- [ ] Mejorar la interfaz de usuario

## 📝 Changelog
Para ver los cambios recientes, consulta el [CHANGELOG.md](CHANGELOG.md).

## 💬 Soporte
Si encuentras algún problema o tienes alguna pregunta, por favor abre un [issue](https://github.com/tu-usuario/odoo-flutter-project/issues) en GitHub.

## 💡 Inspiración
Este proyecto fue desarrollado para facilitar la integración de Flutter con Odoo y permitir la gestión eficiente de clientes potenciales.

## 📜 Licencia
Este proyecto se distribuye bajo los términos de la Licencia MIT. Para más información, revisa el archivo [LICENSE](LICENSE).
