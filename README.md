# 75.26 Simulación - Trabajo Práctico


## Consultas

* Cuando se recibe un pedido telefónico, ¿el llamado se transfiere a la persona del mostrador? ¿O quienes arman los pedidos (2 personas) también deben poder recibir las llamadas?
* Cuando se tiene un pedido de, por ejemplo, 13 piezas (menor a 20), ¿insume el mismo tiempo de 3+-1 segundo, o solo insume ese tiempo al tener un grupo de 20 piezas?

## Para revisar

* Queue LLAMADOS. ¿Qué representa? Es un pedido que parte cuando pasa al mostrador o al preparado. Pero no está representando a la linea en si. Fijate que lo que representa la linea propiamente dicha es el *5 (una facility que se mantiene ocupada mientras haya un llamado en ella).
COLOCARLO EN EL ANÁLISIS.

## To do 

- [x] Análisis del reporte del modelo
- [x] Principales inconvenientes del reporte
- [ ] Implementación y descripción detallada de las propuestas

## Propuestas

* Facility 2, mostrador. Tiempo de uso promedio 241,989. Hay que buscar disminuir el tiempo de atención.
* Cola Facility 2, mostrador. Tiempo promedio de espera fue de 244,964. Podríamos agregar otro empleado en el mostrador para que la espera no sea tanta.
* Cola PREPARAR, del storage de preparación. Tiempo promedio en cola 531,098. Si agregamos otro empleado (o más) en el storage, seguramente este tiempo baje considerablemente. Además acá van a parar los pedidos telefónicos también.
* Facility 1, teléfono. Tiempo de uso promedio 217,321. Que el que atiende el teléfono sea el que toma el pedido. O que el del mostrador sea el único que toma el pedido. Probar la propuesta de interrumpir la atención en el mostrador para priorizar el llamado.
* Facility 1, teléfono. Hay 30 llamados que no son pedidos. Debería reducirse el tiempo promedio de atención de los no pedidos, cosa de poder recibir más pedidos (tal vez no vaya a ayudar en cuanto la atención, ya que tendremos más pedidos, pero si estaríamos facturando más).
