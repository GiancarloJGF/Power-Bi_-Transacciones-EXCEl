# Power-Bi_-Transacciones-EXCEl

Se espera que, se consuma un documento de excel específico y en base a lo mencionado realizar una extracción desde POWER BI, y presentar un DASHBOARD que presente una organización de los datos solicitados.

La empresa de venta de mercancía diversa ha extraído un reporte con todas las ventas realizada en los últimos años, se espera que el técnico consuma ese mismo reporte generado en ese EXCEL provisto y presente los siguientes reportes:

### 1. Reporte total de ventas por producto
<img width="1173" height="828" alt="image" src="https://github.com/user-attachments/assets/8352cd78-0f2c-4d80-a8d4-b241410b7d2e" />


### 2. Reporte de Movimiento de los productos a lo largo y ancho de los estados unidos
<img width="1211" height="842" alt="image" src="https://github.com/user-attachments/assets/73bba005-9067-4b38-ab2c-e8ea4dbd81e8" />


### 3. Reporte de Ganancias concebidas
<img width="1198" height="848" alt="image" src="https://github.com/user-attachments/assets/c5e2e18d-83c6-43bd-b105-b282d362eed9" />


Se espera que el técnico limpie la información y la organice mediante POWER QUERIES, estableciendo los filtros por año.

### Medidas usadas 

Ventas Totales = SUM(Sheet1[Sales])
Ganancia Total = SUM(Sheet1[Profit])
Unidades Vendidas = SUM(Sheet1[Units Sold])
Margen % = DIVIDE([Ganancia Total], [Ventas Totales])
