# Regex-validaciones
**Proyecto del Bootcamp sobre Expresiones Regulares**

A. Se solicitó investigar las expresiones regulares correctas para validar:
  1. Un email
  2. Un número de teléfono (español)
  3. Un DNI
  
  Tras validar, leer e intentar comprender conseguí:
  
  * Para el Email: `^[a-zA-Z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,}$`
  * Para el número de teléfono: `^[+34|0034|34]+[ -]?([0-9]{3}[ -]?)([0-9]{1,3}[ |-| .]?))$`
  * Para el DNI: `^(([X-Z]{1})([-]?)(\d{7})([-]?)([A-Z]{1}))|((\d{8})([-]?)([A-Z]{1}))`
  

B. En este ejercicio se ha solicitado crear un formulario donde se muestren:
  1. Nombre
  2. Apellido
  3. DNI
  4. Correo electrónico 
  5. Dirección
  
  
