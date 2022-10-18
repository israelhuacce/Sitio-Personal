---
{"dg-publish":true,"permalink":"/documentacion/asientos-contables-comunes/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false,"dgShowInlineTitle":false}
---


Base imponible : se le tiene que sacar IGV "Más IGV" "afecto a IGV"
Importe = Precio, ya está incluido el IGV

### Almacenamiento y desalmacenamiento
[[cuentas para producción|cuentas para producción]]
``` 
---Almacenamiento de mercaderías---
2011 XXX
6111    XXX
```
Se dan cuando se reciben mercaderías
```
---Desalmacenamiento de mercaderías---
6111 xxx
2011     xxx
```
Cuando hay devoluciones o operaciones no vinculadas a las ventas
```
---Almacenamiento de materias primas---
2411 xxx
6121     xxx
```
Su desalmacenamiento es a la inversa
```
---Almacenamiento de repuestos---
253  xxx
6133    xxx 
```

### Anticipos recibidos de clientes
```
---Por el anticipo recibido---
101  xxx
1221     xxx
Cuando le entregamos la mercadería
---Entrega de mercadería---
1221 xxx
7012    xxx
---Por el costo de ventas---
6911 xxx
2011     xxx
```
### Ajuste por costo de ventas
```
---Por el ajuste de costo de ventas, en una empresa comercial---
69  xxx
61      xxx
---Por el ajuste de costo de ventas, en una empresa de servicios---
69  xxx
71      xxx
```
### Cambio de factura a letra por pagar con interés
```
---Por la aceptación de letra por pagar con interés---
3731  interés
40111 igv
4212  factura por pagar
423                     letra por pagar
```
### Capitalización de donaciones, reservas y utilidades no repartidas
Capitalización es aumentar la cantidad de capital mediante la conversión.
```
---Por la capitalización de donaciones---
561 xxx
501    xxx
---Por la capitalización de reservas---
582 xxx
501    xxx
---Por la capitalización de utilidades no repartidas---
591 xxx
501    xxx
```
### Compra de activo fijo
```
---Por la compra del activo fijo---
33     xxx
40111  xxx
4654       xxx
---Por el pago---
4654   xxx
1041       xxx
```
### Compra de inventarios
[[Inventarios|Inventarios]]
```
---Por compra de mercaderías---
6011  xxx
40111 xxx
4212     xxx
COMPRA DE SUMINISTROS :
1. CONSUMO INMEDIATO
---Compra de suministros---
656   xxx
40111 xxx
4212      xxx
y su debido destino
---Por el destino del uso de los suministros---
9..   xxx
79        xxx
2. CONSUMO POCO A POCO
---Por la compra de suministros---
6032  xxx
40111 xxx
4212      xxx
---Por el almacenamiento---
252   xxx
6121      xxx
Cuando se empieza a consumir
---Por el consumo---
656   xxx
252       xxx
y su debido destino
---Por el destino del consumo de los suministros--
9..   xxx
79        xxx
```
### Compra o servicio hecha pero factura pendiente
```
-----Por los servicios realizados---
6311  xxx
167   xxx
4211     xxx
Cuando nos emiten la factura
---Por la recepción de la factura---
4211  xxx
4212     xxx
---Por el IGV a acreditar
40111  xxx
167       xxx
```
### Constitución de una empresa
```
---Por el acuerdo de constitución de empresa---
1421 xxx
5221    xxx
---Por el cobro de los aportes a los socios---
1041 xxx
1421    xxx
---Por la formalización del capital---
5221 xxx
5011    xxx
```
### Construcción de edificaciones
```
---Por la construcción de un edificio---
3391 xxx
7221    xxx
```
### Costo de ventas
[[costo de ventas|costo de ventas]]
```
---Por el costo de ventas---
69xx   xxx
2xxx      xxx
```
### Cuentas de cobranza dudosa
```
---Por la provisión---
6671  xxx
1911      xxx
---Por el destino---
94    xxx
78       xx
---Por el castigo---
1911  xxx
1212      xxx
```
### Depreciación
```
---Por la depreciación del periodo
68xx  xxx
39xx      xxx
```

### Descuentos concedidos y obtenidos
[[Nota de débito y crédito|Nota de débito y crédito]]
```
DESCUENTOS CONCEDIDOS
---Por el cobro de la factura con descuento concedido---
101  xxx
675   xxx
1212     xxx
--- Por el descuento concedido con igv---
675   xxx
40111 xxx
1212     xxx
DESCUENTOS OBTENIDOS
---Por descuentos, rebajas y bonificaciones fuera de factura---
4212  xxx
40111 xxx
731      xxx
Ojo: Al igual que usamos la 73, podemos usar la 75 o 77
```
### Desvalorización de mercaderías
```
---Por la desvalorización de mercaderías---
695 xxx
29      xxx
```
### Devengamiento de servicios pagados por adelantado
```
---Por el devengamiento de servicios pagados por adelantado---
63xx  xxx
18xx      xxx
```
### Flete con mercaderías
```
---Por el flete---
60911 xxx
40111 xxx
4212     xxx
Incrementamos al costo de la mercadería
---Por el almacenamiento---
2011 xxx
6111    xxx
Ojo: en el 2011, va la cantidad de la 60911
```
### Gasto por servicios
```
---Por el gasto por el servicio de ...---
63xx  xxx
40111 xxx
4212     xxx
```
### Gasto por multa tributaria e intereses
```
---Por el gasto por multas tributarias---
64511 intereses
64531 multas
10411           xxxx
---Por su destino---
```




### Pago con retención de 4ta categoría
Generalmente por asesorías, solo aplica para montos mayores a 1500 soles (8%)
```
63   xxx
40172    xxx(8%)
424      xxx (92%)
Se paga ambos
40172  xxx
424    xxx
1041      xxx
OTRA FORMA
63   XXX
424     XXX
----pago con retención---
424   xxx
40172    xxx
1041     xxx
SE LE DEBE DEPOSITAR 
40172  XXX
1041      XXX
```
### Pago por dividendos a los accionistas
```
---Por el acuerdo de distribución de los dividendos---
5911 xxx
40185    xxx(5% de 5911)
4412     xxx
---Por el pago---
4412 xxx
1041    xxx

```
### Planilla de remuneraciones
```
---Por la planilla de remuneraciones---
6211 (sueldo bruto)        xxx
622 (Asignación familiar)  xxx
6271 (essalud)             xxx
4017 (I.renta 5cat)            xxx
4031 (essalud)                 xxx
4032 (ONP)                     xxx
4111 (Sueldo neto)             xxx
4171 (AFP)                     xxx   
--- Destino--
---Pago ---
```

### Prestación de servicios
```
---Por la prestación de servicios--
1212  xxx
40111 xxx
7032     xxx
```
### Préstamos otorgados al personal
```
---Por el préstamo---
1411 xxx
1041    xxx
---Por el reconocimiento de los intereses generados---
1631 xxx
4931    xxx
AHORA CUANDO SE COBRA
---Por el cobro---
1041 xxx
1411     xxx
1631     xxx
--- Por el devengamiento de interés del préstamo
4931 xxx
772     xxx
```
### Préstamos a accionistas y directores
```
---Por el préstamo al accionista
142  xxx
1041    xxx
---por el préstamo al director
143  xxx
1041    xxx
SI ES QUE HABRÍA INTERESES
---Por el reconocimiento de intereses
173   XXX
4931      XXX
---Por el devengamiento
4931 xxx
772     xxx
```
### Préstamos otorgados a otras empresa
```
---Por el préstamo otorgado---
1712 xxx
1041    xxx
---Por el reconocimiento de intereses
1731  XXX
4931      XXX
---Por el devengamiento de intereses
4931 xxx
772     xxx
```
### Préstamos recibidos de una entidad financiera
```
---Por el préstamo recibido---
1041 xxx
4511    xxx
---Por los intereses acordados---
3731 xxx
4551    xxx
AL MOMENTO DE PAGAR
---Por el pago de capital e intereses---
4511 xxx
4551 xxx 
1041    xxx
---Por el devengamiento del interés---
6731 xxx
3731    xxx
```
### Provisiones por contingencias
```
6896 xxx
486     xxx
---Asiento de destino---
94  xxx
78     xxx
```
### Reconocimiento de obligaciones por dividendos
```
591 xxx
451    xxx
```
### Suscripciones de accionistas
```
144 xxx
501    xxx
```
### Siniestro de mercaderías
```
---Por el siniestro de mercaderías---
659   xxx
20111    xxx
---Por el derecho a la indemnización---
1621 xxx
7592    xxx
---Por el cobro de la indeminización--
1041 xxx
1621    xxxx
```
### Venta de mercaderías
```
Por la venta
1212 xxx
4011    xxx
7012    xxx
Costo de ventas
6911  xxx
2011     xxx
```
### Venta de un activo fijo y su baja
```
---Por la baja del activo ----
65 xxx    Valor en libros
39    xxx  Depreciación acumulada
33    xxx  Costo del activo inicial
---Por la venta---
Tener en cuenta si se gana o se pierde será 7 o 6
165  xxx
4011     xxx  
756      xxx
```
### Devolución de mercaderías vendidas
```
709  xxx
4011 xxx
1212    xxx
```
### Resultados del periodo
```
---Utilidad---
891 xxx
591    xxx
---Pérdida---
591 xxx
892    xxx
```