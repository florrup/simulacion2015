# 75.26 Simulación - Trabajo Práctico


## Consultas

* Cuando se recibe un pedido telefónico, ¿el llamado se transfiere a la persona del mostrador? ¿O quienes arman los pedidos (2 personas) también deben poder recibir las llamadas?
* Cuando se tiene un pedido de, por ejemplo, 13 piezas (menor a 20), ¿insume el mismo tiempo de 3+-1 segundo, o solo insume ese tiempo al tener un grupo de 20 piezas?

## To do 

- [ ] Análisis del reporte del modelo
- [ ] Principales inconvenientes del reporte

## Propuestas

* Facility 2, mostrador. Tiempo de uso promedio 241,989. Hay que buscar disminuir el tiempo de atención.
* Cola PREPARAR, del storage de preparación. Tiempo promedio en cola 250,287. Si agregamos otro empleado más en el storage, seguramente este tiempo baje considerablemente.
* Facility 1, teléfono. Tiempo de uso promedio 217,321. Que el que atiende el teléfono sea el que toma el pedido. O que el del mostrador sea el único que toma el pedido. Probar la propuesta de interrumpir la atención en el mostrador para priorizar el llamado.
