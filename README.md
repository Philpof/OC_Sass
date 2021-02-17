# OC_Sass

Notes : 
Dans le package.json, il y a le script suivant qui peut prendre un "--style" si besoin.
 "scripts": {
    "sass": "sass --watch ./sass/main.scss:./public/css/style.css --style expanded"
  },
"--style" peut prendre 4 valeurs différentes:
- nested (le CSS indique le nesting),
- compressed (moins de place mais moins lisible),
- expanded (similaire à du CSS classique),
- compact (peu de place mais illisible)

Par defaut, donc sans indiquer "--style", sa valeur est "nested".