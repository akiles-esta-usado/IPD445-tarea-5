# Parte 1: Diseño del núcleo de la memoria SRAM

## Diseño del esquemático

Ante la duda de donde conectar el bulk de los transistores M5 y M6, los conecté al Source, y source está conectado al pin del bit.

## Verificar que La escritura sea correcta

Para una escritura, dejar las lineas de datos BIT y BIT_bar en niveles de tensión adecuados, posteriormente activar la línea de  palabra

## Verificar que la lectura sea correcta

Para la lectura, precargar las líneas de datos BIT y BIT_bar a Vdd/2.

## Verificar que no modifique el estado almacenado

La lectura no debe modificar el estado interno.
