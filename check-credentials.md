# Verificación de Credenciales Git

## Verifica la configuración actual:

```bash
# Ver el nombre de usuario configurado
git config --global user.name
# Debería mostrar: leonar3

# Ver el email configurado
git config --global user.email

# Ver la URL del repositorio remoto
git remote -v
# Debería mostrar: https://github.com/leonar3/Wcleaning-web.git

# Ver todas las configuraciones
git config --global --list
```

## Si las credenciales son correctas, deberías ver:
- Usuario: leonar3
- URL del repositorio: https://github.com/leonar3/Wcleaning-web.git

Ejecuta estos comandos y muestra los resultados para verificar si todo está configurado correctamente.
