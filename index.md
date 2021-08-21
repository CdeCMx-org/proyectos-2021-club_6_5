# **Los fármacos después de Lipinski**

Hace veinte años, un químico curioso y apasionado por su trabajo, revolucionó el descubrimiento de nuevos fármacos. Su nombre es **Crhistopher Lipinski** y su _Regla de los cinco_ constituye hoy en día el primer paso para evaluar el potencial de cualquier compuesto para ser procesado de manera adecuada por el cuerpo humano. 

![Image](src https://dlnxb30bca8mp.cloudfront.net/wp-content/uploads/2019/08/Lipinski-2.jpg)

El Dr. Lipinski es un ejemplo del poder de una persona que disfruta su profesión. En 2005 publicó  _"Advanced Drug Delivery Reviews"_, texto que se ha convertido en el texto químico más citado en la actualidad, principalmente haciendo referencia a la _Regla de los cinco_, misma que llego a la comunidad científica en este documento. 

# **Cinco, el número de la suerte**

La hoy famosa _Regla de los cinco_ establece las reglas empíricas que un fármaco debe cumplir para llegar a ser utilizado como medicina. Las reglas establecen que:
1. Debe tener un peso molecular inferior a 500 g/mol.
2. No debe tener más de cinco donadores de puentes de hidrógeno. 
3. No debe tener más de 10 aceptores de puentes de hidrógeno. 
4. Debe tener un partición octanol-agua (logP) inferior a 5.

Como se puede observar, cada regla incluye un parámetro que es múltiplo de cinco, factor que dio origen al nombre de la regla misma. Estas reglas, se han convertido en la base para la evaluación del potencial de un fármaco para convertirse en medicina. Su importancia radica en que permite diferenciar fácilmente los compuestos sin probabilidad de éxito de aquellos que son viables, lo que a su vez brinda la posibilidad de enfocar las pruebas físicas y biológicas en fármacos que el cuerpo humano es capaz de procesar y utilizar para su beneficio.


# **Evaluar para elegir, elegir para decidir**


```markdown

#Variable que guarda la regla de donadores de enlaces de hidrógenos
dH = input('Número de donadores de enlaces de hidrógenos: ')
dH = int(dH)
if dH <= 5:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda la regla de aceptores de enlaces de hidrógenos
aH = input('Número de aceptores de enlaces de hidrógenos: ')
aH = int(aH)
if aH <= 10:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda la regla del peso molecular
pM = input('Peso molecular en Da: ')
pM = int(pM)
if pM <= 500:
  print('Cumple con las reglas')
else:
  print('No cumple con las reglas')

#Variable que guarda el coeficiente de reparto octanol-agua
logP = input('Coeficiente de partición logP: ')
logP = int(logP)
if logP <= 5:
  print('Cumple con las reglas')
else:
   print('No cumple con las reglas')
```


### Referencias
- Chris Lipinski. Nat Rev Drug Discov 4, 184 (2005). [https://doi.org/10.1038/nrd1686](https://doi.org/10.1038/nrd1686)
- Dr. Christopher A. Lipinski. Melior Discovery. 2021. [https://www.meliordiscovery.com/christopher-lipinski/](https://www.meliordiscovery.com/christopher-lipinski/)





You can use the [editor on GitHub](https://github.com/CdeCMx-org/proyectos-2021-club_6_5/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/CdeCMx-org/proyectos-2021-club_6_5/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
