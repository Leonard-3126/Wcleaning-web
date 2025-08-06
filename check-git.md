# Verificar y corregir configuración de Git

1. Verificar la configuración actual:
```bash
# Ver usuario configurado
git config --global user.name

# Ver email configurado
git config --global user.email

# Ver credenciales almacenadas
git config --global --list
```

2. Si ves "Leonard-3126", actualiza a "leonar3":
```bash
# Configurar el nombre de usuario correcto
git config --global user.name "leonar3"

# Configurar tu email de GitHub
git config --global user.email "TU-EMAIL@ejemplo.com"

# Limpiar cache de credenciales
git config --global --unset credential.helper
```

3. Verificar cambios:
```bash
git config --global --list
```
