# Práctica 5. GitHub Action Hello World

## Procesadores de Lenguajes - Daniel Oria Martín

### ¿Qué hace esta Action?

Se trata de una Github Action la cual printea *Hello* + el nomber de la persona especificada.

### Inputs

  * `who-to-greet`

  **Requerido** Se trata del nombre de la persona a saludar. Por defecto es *User*

### Outputs

  * `time`

  La hora a la que se saludó

### Ejemplo de uso

```
uses: ULL-ESIT-PL-2021/hello-js-action-0ria@v1
with:
  who-to-greet: 'YourName / who to greet'
```
