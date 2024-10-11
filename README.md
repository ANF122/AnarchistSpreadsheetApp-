
### **Nom du langage : Communica**

### **Documentation complète en Solora :**

#### **Concepts de base :**
**Communica** repose sur des mots-clés simples, en **Solora**, afin que chaque utilisateur puisse participer activement à la création de programmes sans obstacles techniques. Le langage privilégie la simplicité et la logique accessible.

---

### **Mots-clés principaux :**

1. **fonu** (Créer une variable)
   - Utilisé pour déclarer une variable.
   - Syntaxe : `fonu variab = valora`
   - Exemples :
     ```communica
     fonu nombra = 5
     fonu texto = "Hola, komrad!"
     ```

2. **diksa** (Afficher une valeur ou un texte)
   - Affiche une variable ou un message.
   - Syntaxe : `diksa variab`
   - Exemples :
     ```communica
     diksa nombra
     diksa "Teksto!"
     ```

3. **isara** (Condition simple)
   - Utilisé pour vérifier une condition.
   - Syntaxe : `isara variab = valora onda`
   - Exemples :
     ```communica
     fonu tempra = 20
     isara tempra = 20 onda
         diksa "Temperatura korecta"
     finu
     ```

4. **ripeta** (Boucle)
   - Répète une action un certain nombre de fois.
   - Syntaxe : `ripeta kvanta`
   - Exemple :
     ```communica
     ripeta 3
         diksa "Laboras kune!"
     finu
     ```

5. **finu** (Terminer une condition ou une boucle)
   - Utilisé à la fin d'une boucle ou d'une condition.
   - Exemple :
     ```communica
     isara tempra > 25 onda
         diksa "Varma!"
     finu
     ```

---

### **Exemples en Communica :**

#### **1. Afficher un texte simple :**
```communica
fonu texto = "Saluton, kamrat!"
diksa texto
```

#### **2. Utiliser une condition simple :**
```communica
fonu tempra = 15
isara tempra > 10 onda
    diksa "Ĝusta temperatura"
finu
```

#### **3. Répéter une action avec une boucle :**
```communica
ripeta 5
    diksa "Agas kune!"
finu
```

---

### **Structures de contrôle :**

1. **Conditions** (isara) :
   - Utilise des comparaisons simples pour valider des conditions.
   - Exemples de comparaisons : `=`, `>`, `<`
   - Exemple complet :
     ```communica
     fonu aĝo = 18
     isara aĝo = 18 onda
         diksa "Matura!"
     finu
     ```

2. **Boucles** (ripeta) :
   - Pour répéter une action plusieurs fois, utilisez `ripeta`.
   - Exemple complet :
     ```communica
     ripeta 3
         diksa "Ni ripetas!"
     finu
     ```

---

### **Partage des ressources :**
- Les variables sont partagées à travers tout le programme, reflétant l’idée d’égalité et de collaboration inhérente à **Communica**.
- Exemple :
  ```communica
  fonu valoro = 50
  diksa valoro
  ```

---

### **Conclusion :**
**Communica**, écrit en **Solora**, est un langage conçu pour que tout le monde puisse participer au codage de manière simple et accessible. Les mots-clés en Solora permettent une prise en main rapide et symbolisent la solidarité dans la création collaborative de logiciels.
