# Corregir credenciales de Git

Ejecuta estos comandos en orden:

```bash
# 1. Verificar la configuración actual
git config --global --list

# 2. Configurar el usuario correcto (el mismo que usas en GitHub Desktop)
git config --global user.name "leonar3"

# 3. Eliminar credenciales almacenadas
git config --global --unset credential.helper
git config --system --unset credential.helper

# 4. Actualizar la URL del repositorio
git remote set-url origin https://github.com/leonar3/Wcleaning-web.git

# 5. Intentar subir los cambios
git push -u origin main
```

Cuando Git solicite las credenciales:
1. Usuario: leonar3
2. Contraseña: usa tu contraseña de GitHub o un token de acceso personal
