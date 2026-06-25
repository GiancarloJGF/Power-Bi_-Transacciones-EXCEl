# Power-Bi_-Transacciones-EXCEl

Se espera que, se consuma un documento de excel específico y en base a lo mencionado realizar una extracción desde POWER BI, y presentar un DASHBOARD que presente una organización de los datos solicitados.

La empresa de venta de mercancía diversa ha extraído un reporte con todas las ventas realizada en los últimos años, se espera que el técnico consuma ese mismo reporte generado en ese EXCEL provisto y presente los siguientes reportes:

### 1. Reporte total de ventas por producto
<img width="724" height="505" alt="image" src="https://github.com/user-attachments/assets/e72784de-09ea-46ac-9333-c66f9e58d9fa" />



### 2. Reporte de Movimiento de los productos a lo largo y ancho de por pais.
<img width="722" height="630" alt="image" src="https://github.com/user-attachments/assets/885f58ae-68c2-4879-b1ce-79d57be44a22" />



### 3. Reporte de Ganancias concebidas
<img width="711" height="632" alt="image" src="https://github.com/user-attachments/assets/5d98b0a9-2e51-41fa-8acf-cf4be2ce7c06" />



Se espera que el técnico limpie la información y la organice mediante POWER QUERIES, estableciendo los filtros por año.

# Medidas usadas 

1. Ventas Totales = SUM(Sheet1[Sales])
2. Ganancia Total = SUM(Sheet1[Profit])
3. Unidades Vendidas = SUM(Sheet1[Units Sold])
4. Margen % = DIVIDE([Ganancia Total], [Ventas Totales])
