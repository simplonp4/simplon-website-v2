## Pour bien demarer
- Pour initialiser le projet avec toutes les dependance
    - ```npm install```

- Pour builder en mode development : 
    - ```npm run devBuild```
- Pour ne pas rebuilder à chaque modification :
    - ```npm run watch```

## L'hierarchie du projet

|_ src

    |_scripts les fichiers js
    
    |_scss les fichiers style (doivent etre ecrit en sass)
    
|_ assets les resources

    |_images
    
|_ dist les fichiers buider
    
    
## Utilisation de Sass
>le chemin absolu des fichiers est necessaire pour la compilation

- Pour Compiler un fichier sans la mode watch :
    - 
    ```shell 
    sass index.scss index.css
    ```

    -Pour Compiler un fichier main.scss dans main.min.css :
        ``` sass ./src/scss/main.scss ./dist/css/main.min.css```
- Pour Compiler un fichier avec la mode watch :
    - 
    ```shell
    sass --watch index.scss:index.css
    ```

    -Pour Compiler un fichier main.scss dans main.min.css avec la mode watch:

    ``` sass ./src/scss/main.scss ./dist/css/main.min.css```
    


    
