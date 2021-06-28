# Exercise7

#calculating an average score for a student, using name + 2 elements(oral and written test)
m = input ('digite o modulo correspondente  ')
aluno = input ('digite o nome do aluno  ')
o = float (input ('digite a nota da prova oral  '))
e = float (input ('digite a nota da prova escrita  '))

media = ((o + e) / 2)
if media > 69.99:
    print ('o aluno {} teve uma media de {} no module {}, estando apto parair para o proximo nivel' .format (aluno , media, m ))
else:
    print('o aluno {} teve uma media de {} no modulo {}, estando inapto para o proximo nivel'.format(aluno, media, m))
