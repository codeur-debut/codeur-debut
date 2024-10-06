choix1 = input("Ajouter un contact")
choix2 = input("Chercher un contact")
choix3 = input("Modifier un contact")
choix4 = input("supprimer un contact")

if choix1 :
  
nom = input(" Quel est votre nom de famille ?")
prenom = input(" Quel est votre prénom ? " )
numero = input(" Quel est votre numéro ? " )

tableau = []
tableau.append(nom,prenom,numero)
print(tableau)

if choix2:
for i in range(len(tableau)):
    print(tableau[i])

if choix3:
    tableau[0] = 5
print(mon_tableau)
