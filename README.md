# proyectoFinalMecatronica
 controlMotor Lazo Cerrado (LC)


Se realiza la programación de una placa stm32f103c8 para el control de 2 motores de corriente continua.
La idea es implementar el codigo en dos placas controladoras. 
Perifericos que se utilizan: 

-	TIMER 1: Como base de muestreo para los encoders de los motores
-	TIMER 2: Para generar pwm necesario para el control del driver l298d y posterior manejo de motores.
-	TIMER 3: En modo encoder para leer las señales en cuadratura de 1 encoder
-	TIMER 4 : En modo encoder para leer las señales en cuadratura del 2 encoder
-	UART 2: En primera instancia para poder detectar el comportamiento según los comandos entregados por un puerto serie. 

