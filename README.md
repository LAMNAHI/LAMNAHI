- 👋 Hi, I’m @LAMNAHI
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
LAMNAHI/LAMNAHI is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def somme_nombres_pairs(n):
    somme = 0
    for i in range(0, n+1, 2):
        somme += i
    return somme

# Demander à l'utilisateur d'entrer un nombre 84
nombre_limite = int(input("Entrez un nombre entier : "))

# Calculer la somme des nombres pairs jusqu'au nombre donné
resultat = somme_nombres_pairs(nombre_limite)

# Afficher le résultat
print("La somme des nombres pairs jusqu'à", nombre_limite, "est :", resultat)
# Ce script calcule la somme des nombres pairs jusqu'à un nombre donné

def somme_nombres_pairs(n):
    somme = 0
    for i in range(0, n+1, 2):
        somme += i
    return somme

# Nombre donné
nombre_limite = 80

# Calculer la somme des nombres pairs jusqu'au nombre donné
resultat = somme_nombres_pairs(nombre_limite)

# Afficher le résultat
print("La somme des nombres pairs jusqu'à", nombre_limite, "est :", resultat)
# Ce script calcule la somme des nombres pairs jusqu'à un nombre donné, ainsi que la variance et le CMUP

def somme_nombres_pairs(n):
    somme = 0
    for i in range(0, n+1, 2):
        somme += i
    return somme

def variance_nombres_pairs(n):
    variance = 0
    for i in range(0, n+1, 2):
        variance += (i - moyenne)**2
    return variance / (n/2)

# Nombre donné
nombre_limite = 80

# Calculer la somme des nombres pairs jusqu'au nombre donné
resultat_somme = somme_nombres_pairs(nombre_limite)

# Calculer la moyenne
moyenne = resultat_somme / (nombre_limite/2)

# Calculer la variance
variance = variance_nombres_pairs(nombre_limite)

# Calculer le CMUP
cmup = resultat_somme / nombre_limite

# Afficher les résultats
print("La somme des nombres pairs jusqu'à", nombre_limite, "est :", resultat_somme)
print("La variance des nombres pairs jusqu'à", nombre_limite, "est :", variance)
print("Le CMUP (Coût Moyen Unitaire Pondéré) est :", cmup)
