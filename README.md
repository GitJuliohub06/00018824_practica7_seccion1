# 00018824_practica7_seccion1

# Autenticación y Autorización con JWT

## 1. ¿Cuál es la diferencia entre autenticación y autorización?

### Autenticación
**"Quien es?"**
Es verificar la identidad del usuario. El usuario envía email y contraseña, el sistema valida que sean correctas y genera un token JWT.

### Autorización
**"¿Qué se puede hacer?"**
Es verificar si el usuario tiene permiso para acceder a un recurso. Se valida el token JWT antes de permitir el acceso.

---

## 2. ¿Cuál es la función del token JWT en la guía?

El JWT es como un pase de acceso digital que:

1. Se genera cuando el usuario hace login exitosamente
2. Se guarda en localStorage del navegador
3. Se envía en cada petición a rutas protegidas
4. Se valida en el servidor para permitir o denegar acceso
