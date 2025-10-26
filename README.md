## 🧩 Workflow del equipo

- **main** → Rama de producción (solo merges desde `develop`)
- **develop** → Rama de integración
- **feat/** → Ramas de desarrollo individual (DevPess y JojoDev)

### Flujo de trabajo
1. Crear rama desde `develop`:  
   `git checkout -b feat/feature-name`
2. Trabajar y hacer commit
3. Subir cambios:  
   `git push origin feat/feature-name`
4. Crear un Pull Request hacia `develop`
5. Revisar y fusionar
6. Solo cuando `develop` esté estable, se hace merge hacia `main`

### Reglas
- No se hacen commits directos a `main` ni a `develop`.
- Todos los cambios deben pasar por un Pull Request revisado.