# Contribuciones

El Sisdai es un proyecto de **software libre y de código abierto** por lo que las contribuciones son bienvenidas. 
Para poder hacerlo, por favor lee la siguiente guía de contribuciones.

---

## **📌 Antes de comenzar**

1. **Revisa los _issues_ existentes**. Asegúrate de que tu idea o corrección no esté ya reportada o en desarrollo. 
Puedes buscar en la [pestaña de _Issues_]() del repositorio.

2. **Abre un _issue_ (si aplica)**. Si planeas implementar una nueva funcionalidad o hacer un cambio significativo, 
por favor **abre un _issue_ primero** para discutirlo con los mantenedores. Esto evita trabajo duplicado y asegura 
que tu contribución se alinee con el objetivo del proyecto.

3. **Lee el Código de Conducta**. Todas las interacciones deben respetar nuestro
[Código de Conducta](CODE_OF_CONDUCT.md). Buscamos fomentar un entorno inclusivo, respetuoso y colaborativo.

---

## **🔧 ¿Cómo contribuir?**

1. **Haz un _fork_ del repositorio**  

2. **Clona tu _fork_ localmente**
   ```bash
   $ git clone https://github.com/tu-usuario/tu-proyecto.git
   
   $ cd tu-proyecto
   ```

3. **Configura el repositorio original como *upstream***  
   Esto te permitirá mantener tu _fork_ sincronizado con los cambios más recientes:
   ```bash
   $ git remote add upstream https://github.com/usuario-original/tu-proyecto.git
   ```

4. **Crea una rama para tu contribución**. Usa una convención clara para el nombre de la rama, según el tipo de cambio:

   | Tipo de contribución       | Prefijo de rama      | Ejemplo                      |
   |----------------------------|----------------------|------------------------------|
   | Corrección de errores      | `fix/`   ó `bugfix/` | `fix/login-error-404`        |
   | Nueva funcionalidad        | `feature/`           | `feature/user-profile-page`  |
   | Mejoras en documentación   | `docs/`              | `docs/update-readme-install` |
   | Refactorización            | `refactor/`          | `refactor/auth-module`       |
   | Pruebas                    | `test/`              | `test/add-unit-tests-api`    |
   | Tareas de mantenimiento    | `chore/`             | `chore/update-dependencies`  |

   Ejemplo:
   ```bash
   $ git checkout -b feature/pagina-perfil-usuaria
   ```

5. **Realiza tus cambios**
    - Sigue el estilo de código del proyecto (revisa los archivos `.editorconfig`, `eslint`, etc., si existen).
    - Escribe pruebas (si aplica).
    - Actualiza la documentación si tu cambio la afecta.

6. **Haz _commit_ de tus cambios**  
   Usa mensajes de _commit_ claros y concisos, siguiendo la convención 
[Commits Convencionales](https://www.conventionalcommits.org/es/v1.0.0/) si el proyecto lo requiere. Ejemplo:
   ```bash
   $ git add .
   $ git commit -m "feat: se agrega página de perfil de usuaria con opción de subir un ávatar"
   ```

7. **Sincroniza con el repositorio principal**  
   Antes de hacer _push_, asegúrate de que tu rama está actualizada:
   ```bash
   $ git pull --rebase upstream main
   ```

8. **Haz push a tu _fork_**
   ```bash
   $ git push origin feature/pagina-perfil-usuaria
   ```

9. **Abre un _pull request_ (PR)**

   1. **Ve a tu _fork_ en GitHub** y haz clic en _Compare & pull request_ (aparecerá automáticamente después del push).

   2. **Abre el PR contra la rama correcta del repositorio original**:
       - **_Base_**: Siempre a `develop` o puede ser a otra rama dependiendo de si hay algún acuerdo previo con los 
      mantenedores.
       - **_Compare_**: tu rama (ej. `feature/pagina-perfil.usuaria`).

   >    🔗 **URL directa para abrir un PR**:
   > 
   > Este es un ejemplo de como debe de ser la URL
   > 
   >    `https://github.com/usuario-original/tu-proyecto/compare/main...tu-usuario:feature/pagina-perfil-usuaria`

   3. **Completa la plantilla del PR** (si el proyecto la tiene):
       - Describe **qué** hace tu cambio y **por qué** es necesario.
       - Menciona cualquier _issue_ relacionado (ej. “Cierra #123”).
       - Incluye capturas de pantalla si es una mejora visual.
       - Confirma que has seguido las guías de estilo y pruebas.

   4. **Espera revisión**  
      Los mantenedores revisarán tu PR lo antes posible. Es posible que soliciten cambios menores, pero recuerda que 
   es parte del trabajo colaborativo y de hacer comunidad.

---

## **✅ Requisitos para que tu PR sea aceptado**

- Debe seguir las [Convenciones del Sisdai](CONVENCIONES_SISDAI.md):
  - Accesibilidad
  - En español
  - Con criterios de *Diseño de la información*
- El código debe pasar todas las pruebas automatizadas descritas en cualquiera de los archivos `README.md` o en 
las carpetas de `test` o alguna otra que aplique al proyecto.
- Debe incluir pruebas nuevas si añade o mejora alguna funcionalidad.
- La documentación debe estar actualizada.
- El nombre de la rama y los mensajes de commit deben seguir las convenciones del Sisdai como proyecto.
- Debe respetar el [Código de Conducta](CODE_OF_CONDUCT.md) en toda la comunicación.
- Debes de modificar el [_Changelog_](CHANGELOG.md`) de acuerdo a las convenciones que se describen en el mismo.


--- 

🙌 **¡Gracias por tu tiempo e interés en el Sisdai y el software libre!**  

