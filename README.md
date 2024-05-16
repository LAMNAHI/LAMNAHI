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
