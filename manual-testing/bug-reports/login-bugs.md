# Bug Reports - Login (SauceDemo)

### BUG-001 - El mensaje de error esta mal recortado desde el Frontend, esto da una disyuntiva visual que

**Resumen**
Al Ingresar con una password no cierta, sale el mensaje de error el cual se ve mal recortado desde el fronted

**Severidad** Baja
**Prio** Baja

**Pasos para reproducir:**
1. Ir a https://www.saucedemo.com
2. Ingresar cualquier Username
3.Ingresar cualquier password
4. Hacer Click en "Login"

**Resultado Actual**
Se muestra un mensaje de error pero mal recortado desde el aspecto visual del fronted

**Resultado Esperado:**
El mensaje de error deberia ser visible de manera correcta y con mas cuidado al recortarlo

**Entorno**
- Navegador: Opera GX
- SO: Windows 11
- Resolucion: 1920x1080
- Fecha: 31/1-/2025

## BUG-002 - El mensaje de error quiere mostrar un emoji pero esta mal llamado desde el codigo

**Resumen**
Al ingresar solo el usuario muestra el nmensaje de error 'Epic sadface: Password is required" lo cual da a entender que la intencion era empezar con un emoji al principio el mensaje pero este no fue llamado de la manera debida.

**Severidad** Media
**Prio** Baja

**Pasos para reproducir:**
1. Ir a https://www.saucedemo.com
2. Ingresar con cualquier Username
3. No ingresar Password
4. Hacer Click en "Login"

**Resultado Actual**
Se muestra un mensaje de error el cual tiene mal la implementacion de un emoji al principio de este.

**Resultado Esperado**
El mensaje de error deberia mostrar de manera efectiva y visual el emoji que aparece al principio del pop up.

**Entorno**
- Navegador: Opera GX
- SO: Windows 11
- Resolucion: 1920x1080
- Fecha: 31/1-/2025
