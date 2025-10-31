# Casos de Prueba - Login (SauceDemo)

## Historia de Usuario relacionada
**Como** usuario del e-commerce  
**quiero** poder iniciar sesion ingresando mis credenciales validas  
**para** acceder a mi cuenta y ver los productos disponibles.

---

## Matriz de Casos de Prueba

| ID | Titulo del Caso de Prueba | Precondiciones | Pasos | Datos de Prueba | Resultado Esperado | Severidad | Prioridad |
|----|-----------------------------|----------------|--------|-----------------|--------------------|------------|------------|
| TC001 | Login exitoso con credenciales validas | Estar en la pagina de login | 1. Ingresar username valido<br>2. Ingresar password valido<br>3. Clic en Login | standard_user / secret_sauce | Redirige al inventario correctamente | Alta | Alta |
| TC002 | Login con contraseña incorrecta | Estar en la pagina de login | 1. Ingresar username valido<br>2. Ingresar password incorrecto<br>3. Clic en Login | standard_user / 12345 | Muestra mensaje de error “Epic sadface: Username and password do not match” | Media | Alta |
| TC003 | Login con campos vaciios | Estar en la pagina de login | 1. Dejar username y password vacoios<br>2. Clic en Login | — | Muestra mensaje de error “Epic sadface: Username is required” | Baja | Media |
| TC004 | Login con usuario bloqueado | Estar en la pagina de login | 1. Ingresar username bloqueado<br>2. Ingresar password correcto<br>3. Clic en Login | locked_out_user / secret_sauce | Muestra mensaje de error “Epic sadface: Sorry, this user has been locked out.” | Alta | Alta |
| TC005 | Validar visibilidad de elementos | Estar en la pagina de login | — | — | Los campos de usuario, contraseña y botón Login son visibles | Baja | Baja |
