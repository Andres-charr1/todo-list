# To-Do List App

Este es un proyecto de una aplicación de lista de tareas desarrollada en Angular. La aplicación utiliza Firebase Firestore Database para almacenar y gestionar las tareas de los usuarios.

## Requisitos previos
Antes de ejecutar este proyecto, asegúrate de tener instalado:

- [Node.js](https://nodejs.org/)
- [Angular CLI](https://angular.io/cli)
- Una cuenta de [Firebase](https://firebase.google.com/)

## Instalación

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Andres-charr1/todo-list.git
   cd todo-list

2. Instalar dependencias: npm install
3. Configurar Firebase:
Crear un proyecto en Firebase.
Habilitar Firestore Database en modo "Start in test mode".
Copiar la configuración de Firebase y agregarla en src/environments/environment.ts
firebaseConfig: {
    apiKey: "AIzaSyB8NOBlyiXe9ju0SY-2fQx4YRGAFJl_MYk",
    authDomain: "crud-3a708.firebaseapp.com",
    projectId: "crud-3a708",
    storageBucket: "crud-3a708.firebasestorage.app",
    messagingSenderId: "578167496346",
    appId: "1:578167496346:web:cdb1bea8901ebc25d64923",
    measurementId: "G-7SJS1711NK"
  }

};

4. Agregar una tarea, Obtener las tareas, Actualizar una tarea, Eliminar una tarea:
   ![image](https://github.com/user-attachments/assets/97ec4be2-41d7-4d00-a499-eb29e721f9ce)

5. Ejecucion: Ionic serve
   ![image](https://github.com/user-attachments/assets/1b3d10e2-1543-492c-bb3a-36f1cb298ec0)
   ![image](https://github.com/user-attachments/assets/17e6414d-1166-4041-9031-f743e3614a18)



   
