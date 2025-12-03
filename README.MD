# Cifrado Hill - Implementación Web

## 📋 Información
**Alumno:** Francisco Emilio Esquivel Torres  
**Grupo:** 1B  
**Materia:** Fundamentos de Álgebra  
**Maestro:** Jorge Javier Pedroza Romero  

## 🚀 Descripción
Implementación web del **Cifrado Hill** usando HTML/CSS/JS. Encripta/desencripta mensajes con matrices 2x2 módulo 26.

## 📁 Archivos
- `index.html` - Interfaz principal
- `style.css` - Estilos
- `script.js` - Lógica del cifrado

## 🖥️ Cómo Usar
1. Abrir `index.html` en navegador
2. Escribir mensaje (máx. 30 letras)
3. Ingresar matriz clave 2x2
4. Click en "Encriptar" o "Desencriptar"

### 🔐 Clave Ejemplo:

## 🧮 Matemáticas
- **A=0, B=1, ..., Z=25**
- **Encriptar:** `C = K × P (mod 26)`
- **Desencriptar:** `P = K⁻¹ × C (mod 26)`
- **Inversa:** Solo si `det(K)` es coprimo con 26

## ⚙️ Funciones
- `hacerClaveInvertible()` - Ajusta clave automáticamente
- `matrizInversa()` - Calcula inversa módulo 26
- `mod()` - Módulo positivo

## 📝 Notas
- Solo letras A-Z (mayúsculas)
- Espacios se preservan
- Padding con 'X' si es impar