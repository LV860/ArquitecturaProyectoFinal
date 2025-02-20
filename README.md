# Proyecto de Análisis de Archivos en Ensamblador MIPS

## Descripción
Este proyecto en ensamblador MIPS procesa dos archivos de texto:
1. **Archivo de datos**: Contiene registros con direcciones IP, nombres de usuario y datos de época.
2. **Archivo de configuración**: Contiene una lista de IPs y nombres de usuario de interés.

El programa extrae la información relevante de ambos archivos, almacena los datos en memoria y los organiza para su uso posterior.

## Características
- **Lectura de archivos**: Abre, lee y cierra archivos mediante llamadas al sistema MIPS.
- **Procesamiento de datos**: Extrae direcciones IP, nombres de usuario y datos de época.
- **Tokenización**: Separa y almacena datos de manera organizada.
- **Gestor de alertas**: Identifica coincidencias entre los datos extraídos y los valores definidos en el archivo de configuración.


## Requisitos
- **MARS (MIPS Assembler and Runtime Simulator)**: [Descargar MARS](http://courses.missouristate.edu/kenvollmar/mars/)

## Instrucciones de Uso
1. **Abrir el código en MARS**.
2. **Ejecutar la simulación** en MARS.
3. **Verificar la salida** en los registros de memoria donde se almacenan los datos extraídos.

## Notas Adicionales
- El código maneja delimitadores como `'` (39 ASCII), `|` (124 ASCII) y `*` (42 ASCII) para procesar los archivos correctamente.
- Se requiere que los archivos de entrada estén en el mismo directorio que el ensamblador para una lectura exitosa.

## Autor
- Leonardo Velázquez Colin
- Gustavo Ortiz Loaiza

