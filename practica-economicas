#practica
#qué imprime este programa?
#ejercicio 1
precio = 1000
descuento = 0.1

precio_descontado = precio*(1-descuento)

print('1_prueba',precio_descontado, precio, descuento)

#ejercicio 2
precio = 1000
descuento = 0.1

precio_descontado = precio*(1-descuento)
precio = precio + 100
descuento = descuento + 0.1

print('2_prueba',precio_descontado, precio, descuento)

#ejercicio 3
sueldo = 20000
puntualidad = sueldo * 0.1
evaluacion = sueldo * 0.2

sueldo_final = sueldo
sueldo_final = sueldo_final + puntualidad
sueldo_final = sueldo_final + evaluacion

print('3_prueba',sueldo_final)

#ejercicio 4
cant_hijos = 4

if cant_hijos <= 2:
  descuento = 100
else:
  descuento = 200

print('4_prueba', descuento)

#ejercicio 5
cant_hijos = 4
conyuge = 'si'
descuento = 0

if cant_hijos > 2 and conyuge == 'no':
  descuento = 100
else:
  descuento = 50

print('5_prueba', descuento)

#ejercicio 6
cant_hijos = 1
conyuge = 'si'
descuento = 0

if cant_hijos > 2 and conyuge == 'no':
  descuento = 100
else:
  descuento = 50


if cant_hijos <= 1 and conyuge == 'si':
  descuento = 10

print('6_prueba', descuento)

#ejercicio 7
cant_hijos = 3
conyuge = 'no'
descuento = 0

if cant_hijos > 2:
  if conyuge == 'no':
    descuento = 100
  else:
    descuento = 20
else:
  descuento = 50

print('7_prueba', descuento)

#ejercicio 8
precio = 12000
cliente_vip = 1
paga_tarjeta = 1
descuento = 0

if cliente_vip == 0:
  descuento = 10
  if paga_tarjeta == 1:
    descuento = descuento + 5

print('8_prueba:', 'El precio con descuento es:' , precio*(1-descuento/100))

#ejercicio 9
precio = 12000
cliente_vip = 1
paga_tarjeta = 1
descuento = 0

if cliente_vip == 0:
  descuento = 10

if paga_tarjeta == 1:
  descuento = descuento + 5

print('9_prueba:', 'El precio con descuento es:' , precio*(1-descuento/100))

# blockmayus+ windows+s es captura parcial de patalla
#ejercicio 10
cant_hijos = 'hola'
conyuge = 'no'
descuento = 0

if cant_hijos != 2:
  if conyuge == 'no':
    descuento = 100
  else:
    descuento = 20
else:
  descuento = 50

print('10_prueba', descuento)

#ejercicio 11
inversion_inicial = 125000
cantidad_bonos_inicial = 125
precio_individual_inicial = inversion_inicial/cantidad_bonos_inicial

importe_final = 220000
cantidad_bonos_final = 185
precio_individual_final = importe_final/cantidad_bonos_final

#indice de rentabilidad redondeado
print('11_prueba', round((precio_individual_final/precio_individual_inicial)-1,2))

#ejercicio 12
'''El costo normal del producto es de $1000
El costo del envio es de $300 por producto para envio normal.
Para envio express el costo es de $700 por producto.
Si el cliente lleva mas de 5 productos el envio es gratis.
Si paga con efectivo se aplica un 10% en toda la compra (no aplica sobre el costo de envio)'''

cant_productos = 8
envio = 'express'
cobro = 'efectivo'

precio_producto = 1000
envio_normal = 500*cant_productos
envio_express = 1000*cant_productos
pago_efectivo = 1-0.1

if envio == 'normal':
  costo_envio = envio_normal
elif envio == 'express':
  costo_envio = envio_express

#en un if aparte porque no se relaciona con lo que analizo
if cant_productos >5:
  costo_envio=0

if cobro == 'efectivo':
  precio_producto = precio_producto*pago_efectivo

# devuelve el precio final segun envio y tipo de pago
print('12_prueba', precio_producto*cant_productos+costo_envio )

#ejercicio 13
'''El salario anual de una persona es de $10000.
El impuesto es el 20% del sueldo anual.
Si tiene mas de 2 hijos, tiene un descuento adicional de 5% por hijo en el impuesto.
Si tiene un conyuge a cargo, tiene un descuento adicional de 7% del impuesto .
Como minimo debe pagar un 15% de su salario en impuestos despues de los descuentos'''

cant_hijos = 3
conyuge = 1

salario_anual = 10000
dto = 0.2
dto_hijo = 1-(0.05*cant_hijos)
dto_conyuge = 1-0.07

if cant_hijos > 2:
  dto= dto*dto_hijo

if conyuge == True:
  dto = dto*dto_conyuge

if dto < 0.15:
  dto = 0.15

# devuelve el sueldo neto
print('13_prueba', round(salario_anual*dto,2))
