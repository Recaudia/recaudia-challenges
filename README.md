
# Prueba Técnica :rocket:

Gracias por considerar a Recaudia como parte de su trayectoria profesional. 

Te compartimos toda la información necesaria para que puedas realizar tu prueba sin ningún inconveniente. 

¿Qué evaluamos?

1. Arquitectura del sistema.
2. Dependencias a usar.
3. Lógica para resolver problemas.
4. Cómo reutilizas tu código.

Tecnologías a usar.
1. Frontend: Angular
2. Backend: NodeJs

Recuerda siempre usar versiones LTS y escribir tu código en ingles. 

## Frontend :eyeglasses:

Crear una aplicación web para Recaudia dado el siguiente diseño: [Ver](https://nebuladiag.blob.core.windows.net/challenges/prueba.pdf)

La aplicacion debe contar con las siguientes caracteristicas:

1. Pantalla de Login (Sólo Maqueta)
2. Listado de Personas
3. Detalle de una persona

Consumir API 

### Datos de Conexión 
URL: https://test-api-nebula.recaudia.com/

### Enpoint para buscar personas
/person/search

### Authorization: 

Bearer TjUVdA1QOATIwiZ7Cp
  
### Método 
  POST

  # Body 
  ```javascript
  {
    "conditions": {

    },
     "page_number": INTEGER,             // Optional
     "number_entries": INTEGER           // Optional
}
```

### Deseable:  :boom:
1. El diseño deberá ser lo mas similar posible a la maqueta presentada anteriormente.
2. Agregar responsive a las pantallas
3. Manejo de Lazy Loading



## Backend :minidisc:

Para Recaudia lo más importante es poder contar con una API que tenga una disponibilidad 24/7 y sea segura. 

Es por eso que nos vemos en la necesidad de construir una que cumpla con las siguientes caracteristicas: 

1. Login.
2. Registrar,actualizar y eliminar datos de una persona, donde los campos obligatorio son: email, nombre y apellido. Los campos opcionales son: telefono , género y fecha de cumpleaños. Todas las personas al crearlas en nuestra API se le debe asignar el estatus de Prospecto pero tambien debe existir los estatus de Activos e Inactivo.
3. Las peticiones deben contar con un token de seguridad.
4. CRUD de los estatus de persona.

### Deseable:  :boom:
1. Permitir registrar un avatar a los usuarios del sistema.
2. Permitir descargar un reporte de personas en excel.

# Al terminar tu desafío envía un correo donde nos compartas tu CV, link público del repositorio y los insumos necesarios para poder evaluarlo.
