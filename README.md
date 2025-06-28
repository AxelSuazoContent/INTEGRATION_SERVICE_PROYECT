![Status](https://img.shields.io/badge/status-active-brightgreen) ![License](https://img.shields.io/github/license/AxelSuazoContent/INTEGRATION_SERVICE_PROYECT)
![License](https://img.shields.io/github/license/tuusuario/datawarehouse-integration)
---

## 🎥 Demo en Video
<!-- Inserta aquí el enlace al video de demostración -->
[![Demo Integration Service](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://youtu.be/7zITgZt66KI)

---

## 📖 Descripción
El **Integration Service** automatiza la ingesta (ETL) de datos desde múltiples fuentes (SQL Server, PostgreSQL, APIs REST, CSV/JSON) y los carga en tu Data Warehouse.

---

## 📂 Estructura de Carpetas
```
INTEGRATION_SERVICE_PROYECT/
├─ .gitattributes
├─ .gitignore
├─ PROYECTO_BD2.sln
└─ PROYECTO_BD2/
   ├─ Controllers/
   ├─ Models/
   ├─ Services/
   └─ appsettings.json
```

---

## ⚙️ Características Destacadas
- Conectores para SQL Server y PostgreSQL.
- Transformaciones usando LINQ y ADO.NET.
- Logs detallados y manejo de errores.
- Orquestación con cron o Airflow (opcional).
- Parámetros configurables en `appsettings.json`.

---

## 🚀 Instalación y Ejecución
```bash
# Clonar el repositorio
git clone https://github.com/AxelSuazoContent/INTEGRATION_SERVICE_PROYECT.git
cd INTEGRATION_SERVICE_PROYECT

# Restaurar y compilar
dotnet restore PROYECTO_BD2.sln
dotnet build PROYECTO_BD2.sln

# Ejecutar el servicio
dotnet run --project PROYECTO_BD2/PROYECTO_BD2.csproj
```

---

## 🔧 Configuración (appsettings.json)
```jsonc
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=<host>;Database=<db>;User Id=<user>;Password=<pass>;"
  },
  "Logging": {
    "LogLevel": { "Default": "Information" }
  }
}
```

---

_Desarrollado por **Axel Gerónimo** (axelgeronimo0@gmail.com)_

---
