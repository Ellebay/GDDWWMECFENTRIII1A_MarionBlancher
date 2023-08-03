# GDDWWMECFENTRIII1A_MarionBlancher - Développer la partie front-end d’une application web - 02-08-2023

## Démarche à suivre pour le déploiement en local ou en ligne

### Déploiement en local
1. Clone this repository:

git clone https://github.com/danurbanowicz/eleventy-netlify-boilerplate.git my-blog-name
2. Navigate to the directory

cd my-blog-name
Specifically have a look at .eleventy.js to see if you want to configure any Eleventy options differently.

3. Install dependencies locally

npm install @11ty/eleventy

5. Run Eleventy (builds the site)

npx @11ty/eleventy
Or build automatically when a template changes:

npx @11ty/eleventy --watch

### Déploiement en ligne