## Layout

Access the layout

[> Open layout](https://www.figma.com/)

## Online example

Access the site

[> Open site](https://project_name-front.surge.sh)

## Building

Install Node.js if you do not already have it installed on your machine.
Install Gulp CLI. Run the below command in your terminal. This will install Gulp CLI globally.

```
    yarn add gulp-cli
```

In the project folder install dependences:

```
	yarn
```

In the project folder run:

```
	yarn start
```

Access the project through `http://localhost:3000/`

Compiles and exports the project to the /dist folder:

```
	yarn run dist
```

It will watch and automatically compile the project to the /dist folder each time you edit and save a file inside the /src folder

```
	yarn run watch
```

Publish /dist in surge url

```
	yarn deploy
```

# Link para encodificar o SVG e usá-lo como background
## https://www.asiteaboutnothing.net/c_decode-url.html

# Importante para uso
## Ao encodificar o SVG se atente a hashtag, pois ela também é encodificada e para isso na variavel, como exemplo na $primary eu crio uma $primary-svg removendo a hashtag, uma vez que ela sera encodificada na estrutura original. 