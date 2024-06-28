# Irina Mezentseva

## Contact information:

### phone number: +79832177946

### email: 91miablond@gmail.com

---

## Briefly About Myself:

    I want to be a developer. I haven't decided what I want to do yet, so I'm studying both web technologies and python.

    I hope to gain practical skills and gain an understanding of the direction in which I want to move.

---

## Skills and Proficiency:

- HTML5, CSS3
- JavaScript Basics
- Python Basics

---

## Code example:

Kata from CODEWARS: Pete likes to bake some cakes. He has some recipes and ingredients.
Unfortunately he is not good in maths. Can you help him to find out, how many cakes he could bake considering his recipes?

Write a function cakes(), which takes the recipe (object) and the available ingredients (also an object) and returns the maximum number of cakes Pete can bake (integer).
For simplicity there are no units for the amounts (e.g. 1 lb of flour or 200 g of sugar are simply 1 or 200). Ingredients that are not present in the objects, can be considered as 0.

**Python code:**

```
def cakes(recipe, available):
    for k, v in recipe.items():
        if k not in available.keys():
            return 0
    cakes = []
    for k in recipe.keys():
        cakes.append(available[k] // recipe[k])
    return min(cakes)
```

---

## Courses:

Udemy: [The Complete Python Bootcamp From Zero to Hero in Python](https://www.udemy.com/course/complete-python-bootcamp/learn/lecture/20345231?start=0#overview)

---

## Languages:

- **Russian** - Native
- **English** - B1
- **German** - A2
