#  App de Geolocalización con React y Node.js

 Este es mi primer proyecto utilizando **React** para el frontend y **Node.js** para el backend.  
La aplicación muestra información de geolocalización en tiempo real utilizando:  
- **API de IP-API** para obtener datos basados en la dirección IP.  
- **API de Geolocalización del navegador** para obtener la ubicación exacta del usuario.  
- Un mapa interactivo con **Leaflet**.  

---

##  Características
Obtiene información de la IP del usuario (país, ciudad, proveedor de internet).   Muestra la ubicación exacta del usuario en un mapa interactivo.  
Diseño moderno y responsivo con animaciones.  
Backend simple con Node.js y Express.  

---

## Tecnologías Utilizadas
- **Frontend:** React, Leaflet, Axios.  
- **Backend:** Node.js, Express.  
- **APIs:** IP-API, Geolocalización del navegador.  
- **Estilos:** CSS moderno con variables y animaciones.  

---

## Requisitos Previos
para empezar, asegúrate de tener instalado:  
- [Node.js](https://nodejs.org/) (versión 16 o superior).  
- [Git](https://git-scm.com/) (opcional, pero recomendado).  
- Un navegador moderno (Chrome, Firefox, Edge).  

---


### 1 Instalar dependencias del backend
```bash
cd backend
npm install
```

### 2 Iniciar el backend
```bash
node server.js
```
El backend estará disponible en `http://localhost:5000`.

---

###  Instalar dependencias del frontend
En otra terminal:
```bash
cd frontend
npm install
```

### 5️⃣ Iniciar el frontend
```bash
npm start
```
El frontend se abrirá automáticamente en `http://localhost:3000`.

---

##  Estructura del Proyecto
```
mi-app/
├── backend/
│   ├── node_modules/
│   ├── package.json
│   └── server.js
└── frontend/
    ├── node_modules/
    ├── public/
    │   ├── index.html
    │   ├── favicon.ico
    │   └── ...
    ├── src/
    │   ├── App.css
    │   ├── App.js
    │   ├── index.css
    │   └── index.js
    ├── package.json
    └── ...
```

---

##  Comandos Útiles

### Backend
| Comando            | Descripción                          |
|--------------------|--------------------------------------|
| `npm install`      | Instala las dependencias del backend |
| `node server.js`   | Inicia el servidor del backend       |

### Frontend
| Comando             | Descripción                                   |
|---------------------|-----------------------------------------------|
| `npm install`       | Instala las dependencias del frontend         |
| `npm start`         | Inicia la aplicación en modo desarrollo       |
| `npm run build`     | Compila la aplicación para producción         |
| `npm test`          | Ejecuta las pruebas (si las hay)              |

---


## 📝 Notas Importantes
  - La API de **IP-API** es pública y no requiere clave.  
  - La **Geolocalización del navegador** requiere permiso del usuario.  

---

