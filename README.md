# Simulacro de examen de Plpgsql

1. Dada una tabla "Clientes" con los campos "id", "nombre" y "email". Si queremos evitar que se ingresen correos electrónicos duplicados deberías crear un disparador que impida la inserción de un nuevo cliente si el correo electrónico ya existe en la tabla. Implementa dicho disparador.
2. Dada una tabla "Pedidos" con los campos "id", "cliente_id", "producto", "cantidad" y "fecha_ultima_modificacion". Si queremos que el campo "fecha_ultima_modificacion" se actualice automáticamente cada vez que se actualice un pedido, deberemos crear un disparador que se encarge de ello. Implementa dicho disparador.
3. Crea una tabla "LogCambios" que registre cada cambio realizado en la anterior tabla "Pedidos". Deberá almacenar "id_pedido", "fecha_cambio", "campo_modificado", "valor_antiguo" y "valor_nuevo". Crea un disparador para esto.
