  REACT/TS TEMPLATE  (Prettier-ESlint formatter)
  
 
how to deploy app in gh-pages

ja ir uztaisīts aps, bet nav ielikts repositorijā, tad daram tā: 
1. uztaisi jaunu repository githubā

2. atveram appu VSC, tad atveram  SOURCE CONTROL, tad add remote uz repository. ...-> Remote-> addRemote -> pievienojam izveidoto repp
https://gyazo.com/441d1662710d8bf366898e78bb9ccb72

3. commit changes 
https://gyazo.com/2159295ba4a9508c6ab0f9d12c5cd277

4. ... -> push
https://gyazo.com/74d5f60f9c8929da52aa1ea6ef5f05c2


ja gribam update repository pēc kkādām izmaiņām appā.
1. commit changes
2. ... -> push



lai deployotu @gh-pages

1. iekš  package.json
"homepage": "http://{github-name}.github.io/{repository-name}"
"homepage": "http://mikusmikus.github.io/animal-animal"

2. commit changes
3. ... -> push

4. terminālī =>>>>>>>>  npm run deploy 

5. Pēctam dodas uz gh-> savu repository -> settings -> tinot uz leju būs links uz app interneta page (pēc deploy ~5min laikā sāks strādāt)
