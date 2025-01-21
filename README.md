# Proyecto-WEB

Este proyecto es una aplicación web completa que consiste en un backend desarrollado con FastAPI y un frontend construido con Svelte. El propósito de la aplicación es gestionar solicitudes para visitas a sitios específicos, con un sistema de autenticación de usuarios y un panel de administración para gestionar estas solicitudes.

## Tabla de Contenidos
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Ejecución](#ejecución)

## Tecnologías Utilizadas

- **Backend**: FastAPI, SQLAlchemy, PostgreSQL
- **Frontend**: Svelte, Axios
- **Base de Datos**: PostgreSQL (TimescaleDB)
- **Despliegue**: Uvicorn

## Instalación

### Prerrequisitos

- Python 3.10 o superior
- Node.js y npm
- PostgreSQL

### Clonación del Repositorio

Clona el repositorio 

```bash
git clone https://github.com/AvilesDanie/Proyecto-WEB-.git
cd proyecto-web
```

## Configuración

### Backend

1. **Variables de Entorno**:
   - Crea un archivo `.env` en la carpeta `BackEnd` y agrega la configuración de la base de datos:

     ```plaintext
     DATABASE_URL=postgresql+psycopg2://usuario:contraseña@host:puerto/nombre_db?sslmode=require
     ```


2. **Instalación de Dependencias**:
   - Instala las dependencias necesarias usando `pip`:

     ```bash
     pip install -r requirements.txt
     ```

### Frontend

1. **Instalación de Dependencias**:
   - Instala las dependencias necesarias usando `npm`:

     ```bash
     cd FrontEnd
     npm install
     ```

## Ejecución

### Backend

Para ejecutar el backend usa el siguiente comando en la carpeta `BackEnd`:

```bash
uvicorn main:app --reload
```

### Frontend

Para ejecutar el frontend usa el siguiente comando en la carpeta `Frontend`:

```bash
npm run dev
```

