
# Simple Form Builder

A lightweight tool to create custom forms and generate HTML code.

## Description

Easily build forms by adding input fields through a simple interface. The tool generates HTML code that you can copy and use in your projects.

## How It Works

1. Choose input type and enter label
2. Click "Add Field" to generate HTML
3. Copy generated code to clipboard

Key function:
```javascript
const div = `<input type=${type} id="${label}"> <label for="${label}">${label}</label>`;
navigator.clipboard.writeText(code);
```

## Acknowledgments

Special thanks to our cohort and Harkirat for their support and guidance throughout this project.

![Image](https://utfs.io/f/9174ecc0-b9c4-454c-9db6-2d6f1ed6138d-ng35bm.png)





