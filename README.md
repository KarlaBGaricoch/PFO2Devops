# Proyecto Web Dockerizado

Este proyecto contiene una aplicación web desarrollada previamente en la carrera, ahora dockerizada para facilitar su ejecución.

## 🐳 Servicios Utilizados

- **Docker Compose**: Orquestador que permite ejecutar los servicios con un solo comando.

## 🧱 Estructura del Proyecto

```
.
├── public/                        
├── imagen/                        
├── docker-compose.yml         
└── default.conf                 
```

---

## 🚀 Cómo ejecutar el proyecto

### 1. Clonar el repositorio

```bash
git clone https://github.com/KarlaBGaricoch/PFO2Devops
```

### 2. Ejecutar Docker Compose

```bash
docker-compose up -d
```

Esto descargará las imágenes necesarias (si no están) y levantará los servicios en segundo plano.

### 3. Acceder a la aplicación

Abre tu navegador en:

```
http://localhost:8080
```

## ✍ Autor

Karla Garicoch
