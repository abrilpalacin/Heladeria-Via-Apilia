# Heladería Via Apilia – Trabajo Final (Introducción a las APIs)

**Autora:** Abril Milagros Palacín  
**Materia:** Introducción a las APIs – DC, FCEyN, UBA (2024)  
**Docente:** G. De Caso  
**Spec:** `palacin_abril_heladeria_apilia.yaml` (OpenAPI 3.0.0)

---

## 1. Descripción técnica
La API REST de la **Heladería Via Apilia** modela la interacción entre clientes, pedidos y ahora también repartidores y sus vehículos.  
Permite:
- Consultar gustos de helado.
- Crear y gestionar pedidos, potes y el flujo de pago.
- **Extensión final:** agregar CRUD de **repartidores**, **vehículos** (con herencia) y su **asignación** a pedidos.

---

## 2. Cómo probar la API
Para validar la documentación y simular la API sin implementar código, se recomienda usar el editor oficial de Swagger:

👉 [https://editor.swagger.io/](https://editor.swagger.io/)

1. Entrar al enlace y borrar el contenido inicial.
2. Copiar el texto completo del archivo `palacin_abril_heladeria_apilia.yaml`.
3. Pegarlo en el panel del editor.
4. Automáticamente se generará la vista interactiva con todos los **endpoints** y sus **schemas**.

Esto permite explorar, testear y validar la API antes de escribir una sola línea de código, lo cual es clave en el diseño profesional de interfaces REST.

---

## 3. Importancia de documentar antes de implementar
Según el docente:
> “Las APIs, o Application Programmatic Interfaces, son la ventanilla por la que un programa deja que otros se comuniquen con él. Así como la UI permite que un usuario interactúe con un programa, las APIs son el análogo para programas interactuando con otros programas.”
>
> “Las APIs son un factor clave en el desarrollo de software moderno. Una buena API puede ser la diferencia entre el éxito o el fracaso de un framework, producto o servicio.”

Documentar antes de implementar permite:
- **Diseñar la interacción** entre sistemas de manera consistente y predecible.
- **Alinear equipos** de desarrollo frontend, backend y QA sin depender del código.
- **Evitar errores de integración** tempranamente.

En este curso se aborda el **modelado de APIs REST** con **OAS (OpenAPI Specification)** y **RAML**, junto con buenas prácticas de diseño, versionado y documentación.
