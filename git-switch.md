# Cambiar cuenta de Git

```bash
# Actualizar a la otra cuenta
git config --global user.name "Leonard-3126"
git config --global user.email "dukethar@gmail.com"

# Eliminar remote actual
git remote remove origin

# Agregar nuevo remote con la cuenta correcta
git remote add origin https://github.com/Leonard-3126/Wcleaning-web.git

# Verificar configuración
git config --global --list

# Intentar subir cambios
git push -u origin main
```

Cuando Git solicite credenciales:
- Usuario: Leonard-3126
- Email: dukethar@gmail.com
- Contraseña: tu contraseña de GitHub
