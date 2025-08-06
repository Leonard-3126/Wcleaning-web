# Verificación de credenciales Git

1. Verificar configuración actual:
```bash
# Ver todas las configuraciones
git config --global --list

# Ver usuario actual
git config --global user.name
```

2. Actualizar a la cuenta correcta:
```bash
# Configurar el usuario que aparece en GitHub Desktop
git config --global user.name "leonar3"

# Limpiar credenciales almacenadas en Windows
git config --global --unset credential.helper
```

3. Verificar el remote:
```bash
# Ver la URL del repositorio
git remote -v
```
