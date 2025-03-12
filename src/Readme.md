# · Examen COD

## Pasos:
### Solicitud Pull Request de las ramas
```bash
# Desde la rama datos ejecutar los siguientes comandos para mergearla con la rama main
git checkout main
git merge datos
git add src\BD.java
git commit -m "Pull request para Mergear Datos con Main"
- Posteriormente haremos un push para que se suba a github.
```
Repetir el mismo proceso para la rama interface
```bash
# Desde la rama interface ejecutar los siguientes comandos para mergearla con la rama main
git checkout main
git merge interface
git add src\Interface.java
git commit -m "Pull request para Mergear Interface con Main"
- Posteriormente haremos un push para que se suba a github.
```
