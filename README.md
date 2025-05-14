
import random
prato_secreto=["Pizza","Lasanha","Fricassê","Carbonara","Sashimi","Kimchi","Mochi"]
prato = random.choice(prato_secreto).lower() #converte para minusculo
 
tentativa = 5
fichas = 1
 
while tentativa > fichas:
   
    descubra = str(input("Tente adivinhar qual é o prato secreto:").lower()) #converte para minusculo
    print(f"Tentativa {fichas} de {tentativa}")
    if tentativa == fichas:
        print("Suas tentativas acabaram!")
        break
 
    if descubra == prato:
        print("Você acertou o prato secreto! Fim de jogo!")
        break
 
 
    else:
        print("Você errou o prato secreto!")
 
 
 
    fichas += 1
print(f"O prato secreto é:{prato}")    
 
import random
prato_secreto=["Pizza","Lasanha","Fricassê","Carbonara","Sashimi","Kimchi","Mochi"]
prato = random.choice(prato_secreto).lower() #converte para minusculo
 
tentativa = 5
fichas = 1
 
while tentativa > 0:
    print(f"Tentativa {fichas} de {tentativa}")
    descubra = str(input("Tente adivinhar qual é o prato secreto:").lower()) #converte para minusculo
   
    if tentativa == fichas:
        print("Suas tentativas acabaram!")
        break
 
    if descubra == prato:
        print("Você acertou o prato secreto! Fim de jogo!")
        break
 
 
    else:
        print("Você errou o prato secreto!")
 
 
 
    fichas += 1
print(f"O prato secreto é:{prato}")    
 
