# Universidad / Mural

**Proyecto Final - Programación WEB | ITLA**

Tools:

- React (JavaScript ES6)
- Firebase Authentication
- Cloud Firestore
- React Router DOM
- Context API de React
- HTML5 y CSS3
- Visual Studio Code
- Git y GitHub

Universidad Mural es una aplicación web desarrollada como proyecto final para la materia de Programación WEB del ITLA. Consiste en un muro interactivo donde los visitantes pueden ver todas las publicaciones realizadas por los usuarios sin necesidad de autenticarse. Para publicar nuevos posts, los usuarios deben crear una cuenta proporcionando su nombre, apellido, correo electrónico y contraseña, y posteriormente iniciar sesión. La aplicación está construida utilizando React con JavaScript ES6 como framework principal del frontend, Firebase como tecnología de backend para la autenticación de usuarios y la base de datos en tiempo real Firestore, y React Router DOM para la navegación entre las diferentes vistas de la aplicación.

La estructura del proyecto está organizada de manera modular para facilitar su mantenimiento y escalabilidad. Dentro de la carpeta src se encuentran los componentes reutilizables como la barra de navegación, las tarjetas de publicaciones y las rutas protegidas. El contexto de autenticación maneja el estado global del usuario permitiendo que toda la aplicación conozca si hay una sesión activa. Las páginas principales incluyen el muro público donde se muestran todas las publicaciones en orden cronológico inverso, los formularios de registro e inicio de sesión, y un panel de control exclusivo para usuarios autenticados donde pueden crear nuevos posts que se almacenan inmediatamente en Firestore y se reflejan en tiempo real en el muro principal.

Para ejecutar este proyecto localmente es necesario instalar las dependencias con `npm install`. La configuración local de Firebase se guarda en `.env.local`, archivo que está excluido de Git mediante `.gitignore`. El archivo `.env.example` muestra las variables necesarias sin publicar valores reales. Una vez instaladas las dependencias, el comando `npm start` levantará el servidor de desarrollo y la aplicación estará disponible en [http://localhost:3000](http://localhost:3000).

Este proyecto cumple con todos los requisitos establecidos para la Opción 1 del documento de proyectos finales: permite ver publicaciones sin autenticación, crear cuentas de usuario almacenando nombre, apellido y credenciales, iniciar sesión mediante Firebase Authentication, y publicar nuevos posts exclusivamente para usuarios autenticados. La combinación de React y Firebase proporciona una experiencia fluida y en tiempo real, demostrando los conocimientos adquiridos durante el curso de Programación WEB en el ITLA.

# IMÁGENES

<img width="886" height="529" alt="image" src="https://github.com/user-attachments/assets/5e8ea49f-1abd-495c-8a69-51c49d2bcbb8" />
<img width="886" height="575" alt="image" src="https://github.com/user-attachments/assets/fb14d0ad-202b-4690-90ed-ce5a39b426ed" />
<img width="1531" height="1027" alt="image" src="https://github.com/user-attachments/assets/1f44cee6-3598-4d7f-94d5-c4ce3675067e" />
<img width="886" height="592" alt="image" src="https://github.com/user-attachments/assets/7fedb4f6-ea7b-4fd6-bd1d-9fa28e7dc275" />




