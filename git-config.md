# Configuración de Git

Ejecuta estos comandos en orden:

```bash
# Configurar credenciales
git config --global user.name "leonar3"
git config --global user.email "TU-EMAIL-DE-GITHUB"

# Limpiar cache de credenciales
git config --global --unset credential.helper

# Actualizar URL del repositorio
git remote set-url origin https://leonar3@github.com/leonar3/Wcleaning-web.git

# Intentar push nuevamente
git push -u origin main
```

Cuando git solicite la contraseña, usa el token de acceso personal que generaste.
