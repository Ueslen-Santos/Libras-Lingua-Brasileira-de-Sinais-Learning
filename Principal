from playsound import playsound
import numpy as np
import cv2
import pandas as np



#Palavras que vão ser geradas de entrada
#Todas palavras são processadas de forma miniscula atraves do .lower e separadas por split
palavras = []
print('DIGITE SEU TEXTO ABAIXO:')
palavras = input().lower().split(" ")

comprimento = len(palavras)



#Remove os espaços em Branco
while '' in palavras:
    palavras.remove('')
print(f'O texto digitado foi: \n {palavras}')


#print(f'Vetor de palavras que foram digitadas {palavras}')
#print('Quantidade de Palavras')
quantidade_de_palavras = len(palavras)
print(f'Seu texto possui: {quantidade_de_palavras} palavras')


###############################################
###############################################
#Dicionario com as palavras da frase inserida
Frase = {}
for i in range(quantidade_de_palavras):
    Frase[i] = palavras[i]

#print(f'O dicionario de palavras de entrada e:\n {Frase} \n')



def Pasta_com_audios():
    ###############################################
    ###############################################
    # Dicionario de Falas
    dicionario_de_audios = {}


    #Numerais Ordinais
    #filename1 = 'primeiro.mp3'
    file_primeiro = 'Audios\\primeiro.mp3'
    file_segundo = 'Audios\\segundo.mp3'
    file_terceiro = 'Audios\\terceiro.mp3'

    dicionario_de_audios[file_primeiro] = 'primeiro'
    dicionario_de_audios[file_segundo] = 'segundo'
    dicionario_de_audios[file_terceiro] = 'terceiro'
    #print(f'Dicionario de audios \n {dicionario_de_audios}')

    #Nomes
    file_nomes = 'Audios\\milena.mp3'
    dicionario_de_audios[file_nomes] = 'nomes'

    #Sentimentos
    file_amo = 'Audios\\amo.mp3'
    dicionario_de_audios[file_amo] = 'amo'

    #Pronomes
    file_eu = 'Audios\\eu.mp3'
    file_a = 'Audios\\a.mp3'
    dicionario_de_audios[file_eu] = 'eu'
    dicionario_de_audios[file_a] = 'a'






    ###############################################
    ###############################################
    #Compara se a "Frase (palavra)" que foi dita/escrita esta dentro do "Dicionario_de_falas (palavra)
    for j in range(quantidade_de_palavras):

        #numeros ordinais
        if Frase[j] == dicionario_de_audios[file_primeiro]:
         playsound('Audios\\primeiro.mp3')

        elif Frase[j] == dicionario_de_audios[file_segundo]:
         playsound('Audios\\segundo.mp3')
        elif Frase[j] == dicionario_de_audios[file_terceiro]:
         playsound('Audios\\terceiro.mp3')



        #pronomes
        elif Frase[j] == dicionario_de_audios[file_a]:
         playsound('Audios\\a.mp3')

        elif Frase[j] == dicionario_de_audios[file_eu]:
         playsound('Audios\\eu.mp3')




        #Nomes
        elif Frase[j] == dicionario_de_audios[file_milena]:
         playsound('Audios\\nomes.mp3')




        #Sentimentos
        elif Frase[j] == dicionario_de_audios[file_amo]:
          playsound('Audios\\amo.mp3')


        #Verbos


        else:
            playsound('Audios\\A_palavra_nao_foi_encontrada.mp3')
            print(f"A palavra ({Frase[j]}) não foi encontrada")






Pasta_com_audios()
