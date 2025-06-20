# Port Scanner

This is the boilerplate for the Port Scanner project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/information-security/information-security-projects/port-scanner

Es posible que la solución funcione localmente y no en un repositorio externo. Se debe a un error asociado al tipo de puerto. Se puede usar el diccionario adjunto y llamarlo del modo como se describe en port_scanner_alt.py, que en vez de consultar por el servicio busca el puerto en el diccionario para obtenerlo.

Los errores de mensaje de advertencia no son errores, pero molestan. Se deben a que ante errores en el try catch el sockete abierto no es cerrado, se abre pero no alcanza a llegar a la linea de cierre. Esto puede ser solucionado de forma posterior sin embargo el debugger no reconoce que exista la variable de objeto s fuera del intento y por ello no deja compilar, incluso si se utiliza el condicional y se pregunta si está definida.