# SPEC-000 — Foundation

## 1. Propósito
Definir la base técnica inicial de **TaskFlow Lite**, estableciendo la estructura del proyecto, las restricciones tecnológicas, convenciones de nombres y criterios técnicos mínimos que permitan construir el producto de manera incremental.

## 2. Alcance
Esta especificación cubre únicamente la fundación técnica del proyecto. Define la estructura inicial, tecnologías permitidas, reglas de organización y convenciones de trabajo.

En esta etapa **no se implementarán historias funcionales**.

## 3. Estructura inicial del proyecto

```text
taskflow-lite/
├── index.html
├── src/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── main.js
│   └── assets/
│       ├── images/
│       └── icons/
├── docs/
│   ├── product-goal.md
│   ├── product-backlog-init.md
│   └── specs/
│       └── SPEC-000-foundation.md
├── .gitignore
└── README.md
```

## 4. Restricciones técnicas
- HTML5, CSS3 y JavaScript ES Modules.
- Sin frameworks.
- Sin backend.
- Persistencia futura utilizando `localStorage`.
- Debe poder ejecutarse localmente desde Visual Studio Code.
- El código se organizará dentro de `src/`.
- No se implementarán todavía historias funcionales.

## 5. Convenciones de nombres
- Carpetas en minúsculas, sin espacios ni acentos.
- Archivos descriptivos en minúsculas.
- Para nombres compuestos se utilizará `kebab-case`.
- Variables y funciones JavaScript en `camelCase`.
- Constantes globales en `UPPER_SNAKE_CASE` cuando corresponda.
- Clases CSS descriptivas en `kebab-case`.

## 6. Convenciones de Git
- La rama principal será `main`.
- Los commits deben ser pequeños y estar relacionados con un solo cambio.
- Los mensajes de commit deben ser breves y describir claramente la acción realizada.
- No mezclar cambios no relacionados dentro del mismo commit.

## 7. Definition of Done técnica inicial
La fundación técnica se considera terminada cuando:
- Existe la estructura inicial del proyecto.
- Los archivos base se encuentran en las rutas definidas.
- El proyecto puede abrirse y ejecutarse localmente desde Visual Studio Code.
- JavaScript queda preparado para utilizar ES Modules.
- No se han agregado frameworks.
- No existe backend.
- No se han implementado historias funcionales.

## 8. Fuera de alcance
- Implementación de historias funcionales.
- Backend.
- APIs.
- Base de datos.
- Autenticación.
- Persistencia funcional con `localStorage` en esta etapa.
- Frameworks.
- Pruebas funcionales de características todavía no implementadas.
