
Script SQL para Análisis de Reservas de Hoteles y Pagos con Tarjeta de Crédito
Este script SQL está diseñado para analizar y extraer información relevante sobre las reservas de hoteles realizadas en la ciudad de Nápoles y los pagos efectuados mediante tarjetas de crédito. A través de una serie de consultas, se obtienen datos sobre los titulares de las tarjetas, las entidades financieras, los hoteles y otros detalles relacionados.

Requisitos
Motor de base de datos compatible con SQL.
Base de datos con las tablas clientes, hoteles, hotelesxreserva, reservas, pagos, tarjeta, entidad_financiera y metodospago, con sus respectivas relaciones y campos.
Consultas Realizadas
Datos de Tarjetas de Crédito en Reservas de Hoteles en Nápoles

Selecciona el nombre del titular, número de tarjeta, entidad financiera, nombre del hotel y fecha de checkin para las reservas de hoteles en Nápoles que se pagaron con tarjetas de crédito.
Información de Pagos con Tarjeta de Crédito en Reservas

Lista el número de pago, cantidad de cuotas, número de tarjeta, nombre y país de la entidad financiera para las reservas pagadas con tarjetas de crédito cuyo precio no supera los 1500.
Cantidad de Pagos por Entidad Financiera

Muestra la cantidad total de pagos realizados por cada entidad financiera.
Reservas Pagadas con Tarjeta de Crédito

Lista todas las reservas de clientes que realizaron el pago a través de tarjetas de crédito.
Reservas de Hoteles con Tarjetas de Banco de la Provincia de Buenos Aires

Muestra información sobre las reservas de hoteles realizadas con tarjetas de crédito emitidas por el Banco de la Provincia de Buenos Aires, incluyendo el nombre de la entidad financiera, número de tarjeta, titular de la tarjeta, nombre y ciudad del hotel.
Cantidad de Reservas por Método de Pago y Cliente

Enumera la cantidad de reservas realizadas según el método de pago y muestra el nombre completo de los clientes involucrados.
Uso del Script
Asegúrate de tener acceso a una base de datos que contenga las tablas requeridas con datos válidos.
Copia y pega cada consulta en tu cliente de base de datos SQL o entorno de consulta.
Ejecuta las consultas para obtener los resultados correspondientes.
Nota: Este script es proporcionado con fines educativos y de referencia. Asegúrate de comprender las consultas y ajustarlas según sea necesario para tu contexto y estructura de base de datos.

¡Importante! Siempre realiza copias de seguridad antes de ejecutar consultas en una base de datos en producción. Las consultas SQL pueden tener un impacto significativo en los datos.
# busqueda-SQL
