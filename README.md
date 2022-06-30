
# Cours python 101 de cognitive class
```python
print("creation du compte ")
nom = ""
while nom == "":
    nom = input("quel est ton nom? ")
```	
## Demande d'age
```python
age = 0
while age == 0:
    age_str = input("quel est votre age? ")
    try:
        age = int(age_str)
    except:
        print("ERREUR: arrete d'ecrire n'impote quoi! ")
```	
## Demande d'age avec acceptation du compte ou non
```python
    condition = age >= 18
    print(condition)
    if condition:
        print("bienvenue vous êtes majeur ")
        continue
    else:
        print("vous êtes minieur vous ne pouvez pas entrer ")
        continue
        stop
````