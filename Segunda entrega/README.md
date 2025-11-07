# Gestor de Finanzas - Proyecto De SOftware - Corporacion Universitaria Iberoamericana

Aplicación web para la gestión de **ingresos, gastos y balance personal**, desarrollada con el stack **MERN (MongoDB, Express, React, Node.js)**.  
Permite a los usuarios autenticarse, registrar movimientos financieros y visualizar su balance de manera sencilla.

---

##  Arquitectura del Sistema

El proyecto sigue una **arquitectura cliente-servidor** basada en el stack MERN:

- **Frontend (React):** Gestiona la interfaz de usuario y el manejo de estado global con Context API.  
- **Backend (Node.js + Express):** Expone una API RESTful que procesa las peticiones, valida los datos y gestiona la autenticación mediante JWT.  
- **Base de datos (MongoDB):** Almacena la información de usuarios y finanzas usando esquemas definidos con Mongoose.  

Esta separación permite un desarrollo modular, escalable y mantenible.

---

##  Tecnologías Utilizadas

###  Frontend
- React.js  
- Context API  
- Axios  
- React Router DOM  
- CSS / Tailwind  

###  Backend
- Node.js  
- Express.js  
- Mongoose  
- JSON Web Tokens (JWT)  
- bcrypt.js  

###  Base de Datos
- MongoDB (Atlas o local)

---

##  Estructura del Proyecto

### Frontend
/Frontend
├── src/
│ ├── components/
│ ├── context/
│ ├── pages/
│ ├── api/
│ └── App.jsx
└── package.json
### Backend
├── src/
│ ├── controllers/
│ ├── libs/
│ ├── middlewares/
│ ├── modelos/
│ ├── routes/
│ ├── modelos/ 
│ ├── schemas/ 
│ ├──app.js
│ ├──config.js
│ ├──db.js
│ ├──index.js 
└── package.json

## Instalación y Ejecución

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/tuusuario/gestor-finanzas.git

2. **Instalar dependencias**
    cd  backend
    npm install
    npm run dev


    cd frontend
    npm install
    npm run dev


    
## Funcionalidades

    Registro e inicio de sesión de usuarios.
    Registro de ingresos y gastos.
    Cálculo automático del balance.
    Actualización y eliminación de movimientos.
    Protección de rutas con autenticación JWT.
        
## Autores
LUZ NEYDA FLOREZ CARRASCAL -- Estudiante
EMMANUEL GELVES TORRES -- Estudiante
NICOLAS ANDRES ROMERO CARREÑO -- Estudiante
