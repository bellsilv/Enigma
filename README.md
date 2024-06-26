while True:

 mapa  = {
    '6' : 'f',
    '3' : 'e',
    '50' : 'l',
    '1' : 'i',
    '26' : 'z',
    'mm' : '2000',
    'r' : '18',
 }
 mensagem = ['6350126 mmr']
 separado = mensagem[0].split()
 troca1 = separado[0].replace('6350126', 'feliz')
 troca2 = separado[1].replace('mmr', ' 2018')

 t = ''.join([troca1, troca2])
 print(t)
 break
