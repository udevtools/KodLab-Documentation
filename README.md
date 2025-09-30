# 🎮 KodLab - La console virtuelle

**Console de programmation ludique pour apprendre l'algorithmique en créant des jeux 2D**

---

## Introduction

### Qu'est-ce que KodLab ?

KodLab est un environnement de développement éducatif conçu pour apprendre la programmation en créant des jeux 2D. Il combine :

- **Un langage simplifié (.kod)** : Syntaxe intuitive inspirée de Python et Pascal
- **Un compilateur intelligent** : Traduit automatiquement le code .kod en JavaScript ES6
- **Un émulateur intégré** : Console virtuelle avec rendu Canvas HTML5
- **Une collection d'exemples** : Jeux de référence pour apprendre

### Pourquoi KodLab ?

✅ **Simplicité** : Pas de configuration complexe, tout fonctionne dans le navigateur  
✅ **Apprentissage** : Syntaxe accessible aux débutants  
✅ **Immédiat** : Voir le résultat en temps réel  
✅ **Ludique** : Apprendre en créant des jeux  
✅ **Portable** : Fonctionne sur n'importe quel navigateur moderne  

### Exemples de Code

**Hello World animé :**
```kod
let x = 0

function start()
    clearScreen("#000033")
end

function update()
    clearScreen("#000033")
    x = x + 2
    if x > 400
        x = 0
    end
    drawCircle(x, 150, 20, "#FF6600")
    drawText("Hello KodLab!", 100, 100, "#FFFFFF")
end
```
