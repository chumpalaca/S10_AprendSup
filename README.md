# S10_AprendSup
Descripción del proyecto<br>
Los clientes de Beta Bank se están yendo, cada mes, poco a poco. Los banqueros descubrieron que es más barato salvar a los clientes existentes que atraer nuevos.<br>

Necesitamos predecir si un cliente dejará el banco pronto. Tú tienes los datos sobre el comportamiento pasado de los clientes y la terminación de contratos con el banco.<br>

Crea un modelo con el máximo valor F1 posible. Para aprobar la revisión, necesitas un valor F1 de al menos 0.59. Verifica F1 para el conjunto de prueba. <br>

Además, debes medir la métrica AUC-ROC y compararla con el valor F1.<br>

Descripción de los datos
Puedes encontrar los datos en el archivo  /datasets/Churn.csv file. Descarga el conjunto de datos. <br>

Características<br>
RowNumber: índice de cadena de datos <br>
CustomerId: identificador de cliente único <br>
Surname: apellido <br>
CreditScore: valor de crédito <br>
Geography: país de residencia <br>
Gender: sexo <br>
Age: edad <br>
Tenure: período durante el cual ha madurado el depósito a plazo fijo de un cliente (años) <br>
Balance: saldo de la cuenta <br>
NumOfProducts: número de productos bancarios utilizados por el cliente <br>
HasCrCard: el cliente tiene una tarjeta de crédito (1 - sí; 0 - no) <br>
IsActiveMember: actividad del cliente (1 - sí; 0 - no) <br>
EstimatedSalary: salario estimado <br>

Objetivo<br>
Exited: El cliente se ha ido (1 - sí; 0 - no)
