Descripción del Proyecto

Planificador de Gastos es una aplicación web desarrollada con Vue.js que permite a los usuarios administrar sus finanzas personales de manera sencilla y eficiente. Con esta herramienta, los usuarios pueden:

Definir un presupuesto: Establecer un monto inicial para gestionar sus gastos.
Registrar gastos: Añadir nuevos gastos, categorizarlos y asignarles un monto.
Editar y eliminar gastos: Modificar o eliminar gastos registrados.
Visualizar resumen financiero: Ver el total gastado, el presupuesto disponible y un desglose de gastos por categoría.
Filtrar gastos: Explorar gastos específicos por categoría (ahorro, comida, transporte, etc.).
Persistencia de datos: Los datos se guardan en el localStorage del navegador, permitiendo que la información persista incluso después de recargar la página.

Características Técnicas:
Desarrollado con Vue.js: Utiliza la reactividad de Vue para una experiencia de usuario fluida.
Componentes reutilizables: La aplicación está estructurada en componentes como Presupuesto, ControlPresupuesto, Modal, Gasto y Filtros.
Gestión de estado: Emplea ref, reactive, watch y computed para manejar el estado de la aplicación.
Persistencia de datos: Usa localStorage para guardar el presupuesto y los gastos, asegurando que los datos no se pierdan al recargar la página.
Diseño responsivo: Interfaz amigable y fácil de usar en dispositivos móviles y de escritorio.

Funcionalidades Implementadas

Definición de presupuesto:
El usuario ingresa un monto inicial, que se utiliza para calcular el saldo disponible.

Registro de gastos:
Los gastos se registran con un nombre, cantidad, categoría y fecha.
Se valida que el gasto no supere el presupuesto disponible.

Edición y eliminación de gastos:
Los gastos pueden ser editados o eliminados mediante un modal interactivo.

Filtrado de gastos:
Los gastos pueden filtrarse por categoría para un análisis más detallado.

Resumen financiero:
Muestra el presupuesto inicial, el total gastado y el saldo disponible.

Persistencia de datos:
Los datos se guardan en el navegador, permitiendo que el usuario retome su planificación donde la dejó.

Tecnologías Utilizadas

Vue.js: Framework principal para la construcción de la interfaz y la lógica de la aplicación.
JavaScript: Lenguaje de programación para la lógica del proyecto.
HTML y CSS: Para la estructura y el diseño de la interfaz.
LocalStorage: Para la persistencia de datos en el navegador.
Vite: Entorno de desarrollo rápido para Vue.js.
