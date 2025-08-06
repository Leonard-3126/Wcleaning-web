# Cambiar a cuenta Leonard-3126

1. Actualizar configuración git:
```bash
# Configurar la cuenta correcta
git config --global user.name "Leonard-3126"
git config --global user.email "dukethar@gmail.com"

# Actualizar el repositorio remoto
git remote remove origin
git remote add origin https://github.com/Leonard-3126/Wcleaning-web.git

# Verificar la configuración
git remote -v

# Subir los cambios
git push -u origin main
```

2. Verificar en GitHub:
- Usuario: Leonard-3126
- Repositorio: Wcleaning-web
- URL: https://github.com/Leonard-3126/Wcleaning-web
