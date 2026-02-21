
# Proyecto: Organizador Financiero


### 1. El Problema <br>
• **¿Qué duele?**: Me gasté mi última quincena en 3 días.<br><br>
• **Frecuencia**: Es un problema recurrente ya que la mayoria voto entre 4 y 3. <br> <br>
• **La Solución Soñada**: Mandar una alerta si excedo un presupuesto, mostrar el saldo total y que me bloquee un monto de mi dinero para administrarme mejor. <br> <br>
• **Resultados de la Sonda**: <br><br>
---------------------| [Encuesta de Optimización de Procesos](https://docs.google.com/spreadsheets/d/1gLMafPEXDfeensKZ_wbRI_yAOAwsRdJFyzzU8YO-yNU/edit?usp=sharing) |---------------------- <br> <br>
• **Resumen**: En estas respuestas podemos encontrar que el 60% de los participantes tienen problemas con la gestión del dinero, y que la mayoria de estos no saben en que gastan su dinero o no saben como administrarlo para poder ahorrar y no excederse.

### 2. Definición Funcional Historia de Usuario Principal
Como estudiante y empleado, quiero poder establecer un limite de gasto semanal, para tener un control de mi sueldo y no gastarlo de manera desorganizada.

### 3. Criterios de Aceptación
1. El limite maximo permitido debe ser del 80% del monto disponible. <br>
2. La notificación tiene que ser en tiempo real, apenas se detecte que esta cerca de cumplirse el limite tiene que recibir la alerta.<br>
3. En caso de emergencia solo se podra sacar como maximo un 15% extra del monto diponible.

### 4. Requisitos Funcionales
1. **RF-01**: Calcular de manera correcta el porcentaje del limite establecido con respecto al monto dispoible.<br>
2. **RF-02**: Modulo de inteligencia artificial que analice los gastos más comunes del usuario y le de recomendaciones de limites a usar.
3. **RF-03**: Generar un PDF donde este detallado semanalmente la cantidad gastada y en que fue gastado.