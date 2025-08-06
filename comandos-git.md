# Comandos para configurar GitHub

1. Primero, verifica tu usuario configurado en git:
```bash
git config user.name
```

2. Si necesitas configurar tu usuario:
```bash
git config --global user.name "TU-NOMBRE-GITHUB"
git config --global user.email "TU-EMAIL-GITHUB"
```

3. Elimina el remote actual:
```bash
git remote remove origin
```

4. Añade el nuevo remote (reemplaza USUARIO con tu nombre real de GitHub):
```bash
git remote add origin https://github.com/USUARIO/wcleaningWEB.git
```

5. Verifica la configuración:
```bash
git remote -v
```

6. Intenta hacer push nuevamente:
```bash
git push -u origin main
```
