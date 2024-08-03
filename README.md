# resolvedor-de-fatorial

numero= int(input('digite um número:'))
fatorial= numero
print('Fatorial de' ,numero,'->',numero,end=' ')
while True:
    numero = numero-1
    fatorial = fatorial *numero
    print('*',numero,end=' ')
    if numero == 1:
        break

print('=',fatorial)
