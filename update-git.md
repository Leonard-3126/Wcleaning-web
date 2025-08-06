# Actualización de Credenciales Git

1. Verifica la configuración actual:
```bash
git config --global --list
```

2. Actualiza el email:
```bash
# Actualizar con el email que usas en GitHub
git config --global user.email "dukethar@gmail.com"

# Verificar el cambio
git config --global user.email
```

3. Intenta subir los cambios:
```bash
git push -u origin main
```

Si Git pide credenciales:
- Usuario: leonar3
- Email: dukethar@gmail.com
- Contraseña: tu contraseña de GitHub
