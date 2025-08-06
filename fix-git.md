# Corregir Permisos de Git

Ejecuta estos comandos en orden:

```bash
# 1. Ver usuario actual configurado
git config --global user.name

# 2. Cambiar al usuario correcto de GitHub
git config --global user.name "leonar3"

# 3. Eliminar credenciales guardadas en Windows
git config --global --unset credential.helper

# 4. Actualizar la URL del repositorio (usando HTTPS)
git remote set-url origin https://github.com/leonar3/Wcleaning-web.git

# 5. Intentar push nuevamente
git push -u origin main
```

Cuando Git solicite credenciales:
- Usuario: leonar3
- Contraseña: tu contraseña de GitHub o token de acceso personal
