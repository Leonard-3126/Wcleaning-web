# Pasos para subir el código

Ejecuta estos comandos en orden:

```bash
# Eliminar el remote anterior
git remote remove origin

# Agregar el nuevo remote con el nombre exacto del repositorio
git remote add origin https://github.com/leonar3/Wcleaning-web.git

# Verificar que se configuró correctamente
git remote -v

# Subir los archivos
git push -u origin main
```

Si GitHub pide credenciales:
1. Usuario: leonar3
2. Para la contraseña, usa un token de acceso personal
3. O autentícate usando el navegador si git te lo solicita
