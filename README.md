# Simulacion-Medico-de-Software
Nombre: Ethan Nienhuser V
Seccion: 1

### Desarrollo

## Diagrama de caso de uso
### Correccion
![image](https://github.com/user-attachments/assets/98388212-ed6f-4279-9523-536e897c999d)

-No posee nomenclatura de 'include' ni 'extend' en las relaciones
-El usuario tiene acceso al historial de otros usuarios
-No existe un inicio de sesion que permita diferenciar un login de estudiante al de un admin
-La notificacion por correo se aplica solo cuando se aprueba una reserva y el admin puede emitirla

## Diagrama de clases
-La clase 'Reserva' no posee ningua relacion con las demas clases
-La clase 'Administrador' no posee atributos
-Existen dos metodos 'notificar()' en dos clases distintas lo cual resulta redundante

## Diagrama de implementacion
- 
