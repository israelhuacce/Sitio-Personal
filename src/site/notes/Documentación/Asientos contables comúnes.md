---
{"dg-publish":true,"permalink":"/documentacion/asientos-contables-comunes/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":false,"dgShowLocalGraph":false,"dgShowInlineTitle":false}
---

Aquí encontrarás los asientos contables más comúnes.
>[!Recomendación]
>Si buscas un asiento en específico, presiona "Ctrl + f" y escribe tu palabra clave.

### Almacenamiento y desalmacenamiento
[[Documentación/Cuentas para producción|Cuentas para producción]]
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
Almacenamiento de suministros diversos
```
x/x Almacenamiento de suministros diversos
2511  xxx
6132     xxx
```
### Anticipos recibidos de clientes
```
---Por el anticipo recibido---
1041  xxx
4011     xxx
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
61  xxx
69      xxx
---Por el ajuste de costo de ventas, en una empresa de servicios---
71  xxx
69      xxx
```

^284fc8

### Cambio de factura a letra por pagar con interés
```
---Por la aceptación de letra por pagar con interés---
3731  interés
40111 igv
4212  factura por pagar
423                     letra por pagar
```
### Cambio de factura a letra por cobrar con interés
```
x/x Por el cambio de factura a letra por cobrar y reconocimiento de intereses
1231 (xxx+yyy*0.18)
1631 yyy
1212                xxx
4011                yyy(*0.18*) 
4931                yyy

x/X Por el reconocimiento de los intereses
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
### Compensación por tiempo de servicios (CTS)
```
x/x Por el reconocimiento del CTS
6291 xxx
4151     xxx
x/x Por el depósito del CTS
4151 xxx
1041    xxx
```
### Compra de acciones que cotizan en bolsa
[[Tratamiento de las acciones|Tratamiento de las acciones]]
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
[[Costo de ventas|Costo de ventas]]
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
### Ganancia por diferencia de cambio
Ejemplo : 

| fecha      | Cuenta por pagar | Valor en $ | Tipo de cambio | Valor en S/. |
| ---------- | ---------------- | ---------- | -------------- | ------------ |
| 01/04/2022 | Reconocimiento   | 5000       | 3.50           | 17500        |
| 01/05/2022 | Cancelación      | 5000       | 3.40           | 17000        |

Ganancia por diferencia de cambio : 17500 - 17000 = S/.500
```
EN COMPRA
x/x Por la compra de mercaderías
6012 14830.51
4011  2669.49
4212         17500
x/X Por el almacenamiento
2011 14830.51
6111         14830.51
x/x Por la ganancia por diferencia de cambio
4212 17500
1041      17000
7761        500

EN VENTA
Reconocimos en cierto tipo de cambio, pero a la hora de la cancelación el tipo de cambio subió y cobramos más 100 soles 

X/X Por la venta
1212 1180 
4011      180
7021     1000
x/x Por la ganancia por diferencia de cambio
1041 1280
7761      100
1212     1180
```
### Pérdida por diferencia de cambio

| fecha      | Cuenta por cobrar | Valor en $ | Tipo de cambio | Valor en S/. |
| ---------- | ---------------- | ---------- | -------------- | ------------ |
| 01/04/2022 | Reconocimiento   | 5000       | 3.50           | 17500        |
| 01/05/2022 | Cancelación      | 5000       | 3.40           | 17000        |

Pérdida por diferencia de cambio 17500-17000 = S/.500
```
EN VENTA
x/x Por la venta
1212 17500
4011       3150
7021      14350
x/x Por la pérdida por diferencia de cambio
1041 17000
6761   500
1212      17500


COMPRA
Reconocimos en cierto tipo de cambio, pero a la hora de la cancelación el tipo de cambio subió y pagamos más 100 soles 
EN COMPRA
X/X Por la compra
6021 1000
4011  180
4212     1180

x/x Por la pérdida por diferencia de cambio
4212 1180
6761  100
1041      1280
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
### Impuesto a la renta corriente
```
x/x Por el impuesto a la renta corriente
881    xxx
40171      xxx
```
### Impuesto a la renta diferido activo/pasivo
```
x/x Por el impuesto a la renta diferido activo
371  xxx
882     xxx

x/x Por el impuesto a la renta diferido pasivo
881 xxx
491     xxx
```
### Pagos a cuenta del impuesto a la renta
```
--- Por los PAC del periodo--
167 xxx
104     xxx
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
### Revaluación de Propiedad Planta y Equipo
```
x/x Por el registro del excedente de revaluación
33    xxx
39        xxx
57        xxx
x/x Contabilización del IR diferido pasivo
57  xxx
491    xxx
```

### Remesa de dinero de una matriz(No domiciliada) a una subsidiaria domiciliada
```
Ambas son la misma empresa, por lo que no afectará la cuenta patrimonial.
x/x Por el capital asignado recibido por la empresa matriz
1041  xxx
47911     xxx
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
### Reclasificación de un activo
Ponerlo listo para la venta
```
27 activos mantenidos para la venta
39  depreciación acumulada
33                         costo
```
### Enajenación de un activo
1. Ya estaba reclasificado
```
6551  xxx
27       xxx
```
2. No se reclasificó
```
6551  valor residual
39    xxx(depreciación acumulada)
33                                costo
```
### Venta de un activo (enajenado)
```
1653 xxx
4011      igv
7564      valor
```
### Servicios contratados por anticipado
```
18   xxx
4011  xx
4212    xx
 DEVENGAMIENTO MENSUAL O ANUAL
63,65...  XXX
18           XXX
```