# README

Boilerplate per siti gestiti tramite Netlify CMS.
Per info: https://www.netlifycms.org/docs/intro/

## Config.yml
* In questo file vengono definite le configurazioni che saranno diverse per ogni sito.
* Puoi attivare il Workflow Editoriale, che aggiunge all'interfaccia capacità per drafting, reviewing e approving posts. Aggiungi `publish_mode: editorial_workflow`.
* Per altre info guarda i [docs](https://www.netlifycms.org/docs/intro/).

## Librerie esterne
### SASS
* Modular Scale
* Typi
* Susy

## Comandi
* `gulp dev`: esegue ambiente di sviluppo con browser-sync. Compila e controlla (watch) file `.pug`,`.scss` e `.js`.
* `gulp build --prod`: comando per la build.

## Sviluppo
### CSS
* Autoprefixer
* Strip comments
* Combine media queries
* Beautify CSS

## Produzione
### CSS
* Autoprefixer
* Uncss
* Combine media queries
* Useref

### JS
* Useref

### Immagini
* Imagemin

## ToDo
* Autoprefixer: definisci nel task i browser da supportare.
* Aggiorna a Gulp 4.
* Definisci ESLint.
