# Hello_Markdown
## ¿Que es Markdown?
Es un lenguaje de marcado ligero (poder generar documentos a partir de una sintaxis) como html o xml
Github la utiliza para escribir documentaciones, readme, etc.
Aprender esta sintaxis será util al momento de generar documentos de manera más rápida.

Es posible convertir markdown a html, existen conversores para ello
VSC tiene un visualizador para markdown
se accede a ella con F1 o ctrl + shift + p (>markdown open preview)

<!-- Coments-->

<!-- Headings-->
los titulos...
# Mi titulo
## Mi titulo h2
### Mi titulo h3
#### Mi titulo h4
##### Mi titulo h5
###### Mi titulo h6

<!-- some texts-->
*italic text*

**strong text**

~~texto techado~~

<!-- Unorder list-->
* eggs
    * eggs for breakfast
* milk
    * chocolate
    * vanila
* pencil
    * red
    * blue

<!-- Order list-->
1. uno
    1. uno punto uno
2. dos
3. tres

<!-- links-->
[google.com](https://www.google.com.mx/)

[google.com](https://www.google.com.mx/ "Google crazy")


<!-- quotes-->
> this is the way 


<!-- lines-->
---
___


<!-- codes-->
`console.log('hello world') `


```
def draw_tree(height):
  # Draw the base of the tree
  for i in range(height):
    print(" "*(height-i-1) + "*"*(2*i+1))
 
  # Draw the stand
  print(" "*(height-1) + "***")

# Test the function
draw_tree(5)


```


<!-- codes in a specific language-->

```python
import random

# Set the number of positions in the cylinder
num_positions = 6

# Choose a random position for the bullet
bullet_position = random.randint(1, num_positions)

# Prompt the user to enter their guess
guess = int(input("Which position do you think the bullet is in? (1-{}): ".format(num_positions)))

# Check if the user's guess is correct
if guess == bullet_position:
  print("You win!")
else:
  print("You lose!")
```

<!--  create tables-->
|   Car  |  Model   |   Color   |
|--------|----------|-----------|
|Honda   |  NSX     |   Blue    |
|Mazda   |  RX7     |   Orange  |
|Toyota  |  AE86    |   White   |


<!--  generate images-->
![Cool penguin](https://wallpaperaccess.com/full/1238544.jpg)


<!--    Github markdown -->
* [x] Task 1
* [] Task 2
* [] Task 3
* [x] Task 4