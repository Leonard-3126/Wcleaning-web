# Solución de Credenciales Git

## Pasos a seguir:

1. Primero, verifica el usuario actual:
```bash
git config --global user.name
```

2. Ya que muestra "leonar3", vamos a limpiar las credenciales almacenadas:
```bash
# Eliminar credenciales actuales
git config --global --unset credential.helper
```

3. Configura el remote con el token:
```bash
# Eliminar remote actual
git remote remove origin

# Agregar nuevo remote con el token
git remote add origin https://leonar3:TU-TOKEN@github.com/leonar3/Wcleaning-web.git
```

4. Intenta subir los cambios:
```bash
git push -u origin main
```

## Obtener Token de Acceso Personal:

1. Ve a GitHub.com
2. Settings → Developer Settings → Personal Access Tokens → Tokens (classic)
3. Generate new token
4. Selecciona el scope "repo"
5. Copia el token y úsalo en el paso 3
