# Proceso de Pago

## Requisitos

- Información de la tarjeta de crédito o débito
- Una cuenta de pago válida (por ejemplo, PayPal)
- SSL para asegurar la transferencia de datos

## Flujo de Pago

1. **Página de Pago**
   - Presentar un formulario para que el usuario ingrese su información de pago:

   ```html
   <form action="/process-payment" method="POST">
     <label for="cardNumber">Número de Tarjeta</label>
     <input type="text" id="cardNumber" name="cardNumber" required>
     
     <label for="expiryDate">Fecha de Vencimiento</label>
     <input type="text" id="expiryDate" name="expiryDate" required>

     <label for="cvv">CVV</label>
     <input type
