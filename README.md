# Calculadora con Tailwind CSS v4

Una calculadora simple y moderna desarrollada con HTML, JavaScript vanilla y Tailwind CSS v4.

## Características

- Operaciones básicas: suma, resta, multiplicación y división
- Interfaz moderna con gradientes y animaciones
- Diseño responsivo
- Efectos hover y de escala en los botones

## Requisitos Previos

- Node.js instalado en tu sistema
- npm (viene incluido con Node.js)

## Instalación

Sigue estos pasos para configurar el proyecto en tu máquina local:

### 1. Navega a la carpeta del proyecto

```bash
cd nombre-de-tu-carpeta
```

### 2. Inicializa npm

```bash
npm init -y
```

### 3. Instala Tailwind CSS v4

```bash
npm install tailwindcss @tailwindcss/cli
```

### 4. Crea la estructura de CSS

Crea una carpeta `css` y dentro de ella un archivo `styles.css`:

```bash
cd css
```

Crea el archivo `styles.css` con el siguiente contenido:

```css
@import "tailwindcss";
```

### 5. Compila Tailwind CSS

Regresa a la carpeta raíz del proyecto y ejecuta:

```bash
npx @tailwindcss/cli -i css/styles.css -o css/output.css --watch
```

El flag `--watch` mantendrá el proceso activo y recompilará automáticamente los estilos cuando hagas cambios.

### 6. Abre el proyecto

Abre el archivo `index.html` en tu navegador y ¡listo! La calculadora estará funcionando.

## Estructura del Proyecto

```
proyecto/
│
├── css/
│   ├── styles.css      # Archivo fuente de Tailwind
│   └── output.css      # Archivo compilado (generado automáticamente)
│
├── js/
│   └── script.js       # Lógica de la calculadora
│
├── index.html          # Estructura HTML
├── package.json        # Dependencias del proyecto
└── README.md           # Este archivo
```

## Uso

- Haz clic en los números para ingresarlos
- Usa los operadores (+, -, x, /) para realizar operaciones
- Presiona "=" para obtener el resultado
- "AC" limpia toda la operación
- "Del" elimina el último carácter

## Tecnologías

- HTML5
- CSS3 (Tailwind CSS v4)
- JavaScript vanilla

## Notas

Este proyecto es una práctica enfocada en la implementación de Tailwind CSS v4, demostrando el uso de:
- Sistema de utilidades de Tailwind
- Gradientes personalizados
- Transiciones y transformaciones
- Grid layout responsivo
- Estados hover y active

---

Desarrollado como práctica de Tailwind CSS v4