# 🤝 Sistema Manos Solidarias
### Módulo de Registro ONG | Aplicación de Escritorio en C#

## 📖 Descripción del Proyecto

**Sistema Manos Solidarias** es una aplicación de escritorio diseñada para centralizar y optimizar el registro de voluntarios y donaciones de la organización *Manos Solidarias*.

El proyecto está enfocado en la escalabilidad, la arquitectura limpia y el uso de buenas prácticas de ingeniería de software, funcionando también como un proyecto académico y demostrativo.

---

## ✨ Características Principales

- 🎨 **Interfaz intuitiva**  
  Formularios dinámicos optimizados para una buena experiencia de usuario.

- 🏗️ **Arquitectura limpia**  
  Separación clara de responsabilidades para facilitar mantenimiento y escalabilidad.

- 🗄️ **Persistencia robusta**  
  Integración directa con SQL Server para un manejo seguro y eficiente de datos.

---

## 🛠️ Stack Tecnológico

| Componente | Tecnología |
|-----------|------------|
| Lenguaje | C# (.NET 7.0) |
| Interfaz Gráfica | Windows Forms (WinForms) |
| Base de Datos | SQL Server 2022 |
| Acceso a Datos | Microsoft.Data.SqlClient |
| IDE | Visual Studio code |

---

## 🏗️ Patrones de Diseño Aplicados

### 🔹 Factory Pattern
**Archivo:** `UsuarioFactory.cs`  

Desacopla la creación de objetos de usuario, permitiendo extender nuevos tipos de perfiles sin modificar la lógica central del sistema.

### 🔹 Singleton Pattern
**Archivo:** `DatabaseConnection.cs`  

Garantiza que exista una única instancia de conexión a la base de datos durante toda la ejecución de la aplicación, optimizando el uso de memoria y recursos del sistema.

---

## 🚀 Instalación y Uso

### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/SistemaManosSolidarias.git
