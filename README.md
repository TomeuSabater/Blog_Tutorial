# Blog Tutorial

Repositorio para albergar los tutoriales de Laravel para la construcción de un BackOffice
Se crea el BackOffice para blog
El historial de comandos I y VI no se imparten 


# Historial de Comandos Tutorial I

  Instalación y Configuración de Herramientas
  Creación del Entorno y Primeros pasos
  Creación y Gestión de la DDBB


# Historial de Comandos Tutorial II

MVC en Laravel
	Se explicará el paradigma MVC en Laravel
	Se muestra la creación e interrelación de las Routes, View y Controllers 
	MVC: Una Route -> Controller(método) <-> Model -> View(Model')  

Routes (routes>web.php)
	Routes con parámetros 
	Routes con restricciones 
	Routes con restricciones en AppServiceProvider
	Routes con redirecciones
	Agrupación de Routes
	Routes enlazadas con Models (app>Models)
	Routes que cargan View (resources>views) 
	Route raíz (/)
	Route automáticas para Controller CRUD

Ejemplos de MVC
	User -> Route -> Model -> User 
	User -> Route -> View(Model) -> User
	User -> Route -> Controller -> Model -> Controller(Model') -> View(Model') -> User

View (resources>views)
	Ejemplos de View
	View con parámetros desde Route
	View que muestran un Model
	View CRUD

Controller (app>Http>Controllers) 
	Controller custom
	Controller para CRUD

Request (app>Http>Requests)
	Request para validaciones y mensajes

Rules (app>Rules)
	Rules custom 

Comenzamos la codificación del CRUD para blog
	create()
	store()


# Historial de Comandos Tutorial III

Repaso Models

Repaso Conexión con la DDBB Ejemplos:
	SQL directo
	Query Builder
	Eloquent
	pluck

Finalización del CRUD con funcionalidade básica
Todavía no se aplicará la renderización final 

	index()
	show()
	edit()
	update()
	destroy()


# Historial de Comandos Tutorial IV

Mejoras en el Front, aplicar un diseño más avanzado y refinado

Uso del Motor de plantillas BLADE
	Tailwindcss (Problemas y resolución) 
	Anonymous Components
	Class Based Components
	Dynamic Components
	Layout


# Historial de Comandos Tutorial V

Finalización del CRUD

	- Navegación 
    	- CKEditor 
	- Relaciones (de entidades) y Middleware
	- Relaciones: 1:1, 1:N, N:M (Desplegables)


# Historial de Comandos Tutorial V

API Rest / API Controllers  / API Resources / API Authentication



# Acciones que se toman para que el repositorio funcione OK
