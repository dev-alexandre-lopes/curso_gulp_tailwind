# Curso Gulp + TailwindCSS 

<p align="center">
  <a href="https://gulpjs.com">

![gulp_tailwind](https://user-images.githubusercontent.com/64049906/105233567-670ef480-5b40-11eb-841f-0ce63f1c4419.jpg)

  </a>
  <p align="center"><strong>Automatizando o Workflow para o Desenvolvimento WEB com o Framework TailwindCSS</strong></p>
</p>

O **Gulp** é um automatizador de tarefas rápido na sua execução, simples de usar e de fácil aprendizado. Ele usa como base a plataforma node.js para interpretar seu código e requer conhecimento de Javascript para criar suas tarefas.

Essas tarefas podem ser qualquer coisa que você precisa fazer de forma repetida ou que vai consumir muito do seu tempo. Por exemplo, **_minificar imagens_**, **_copiar diretórios_**,**_concatenar arquivos_**, **_compilar Javascript_** etc. Todas essas são tarefas que, se forem feitas manualmente, irá consumir muito tempo e trabalho; e o Gulp cuida de tudo isso.

O **TailwindCSS** é um framework que utiliza uma abordagem de escrita e uso do CSS em que se procura, primeiramente, fazer uso das chamadas classes utilitárias (Utility First), classes estas que representam atributos do CSS, como border, background, border-radius e uma série de outras propriedades. Essa abordagem possui inúmeros sinônimos: Immutable CSS, Functional CSS, Atomic CSS entre outros.

## Boas Referências e a Documentação Oficial:

[Website](https://gulpjs.com/) - Website Gulp

[Website](https://tailwindcss.com) - Website do Framework TailwindCSS

[Repositório](https://github.com/lazymozek/gulp-with-tailwindcss) - Repositório Gulp + Tailwind (Referência)

[Repositório](https://github.com/tailwindcss/tailwindcss) - Repositório Oficial do Framework TailwindCSS.

[Documentação](https://gulpjs.com/docs/en/getting-started/quick-start/) - Getting Started com o Gulp

## Conteúdo do Curso

* Conceitos Importantes;

* Plugin Gulp para HTML: 
    * gulp-htmlmin;

* Plugins Gulp para CSS:
    * gulp-purgecss; 
    * gulp-postcss;
    * gulp-autoprefixer;
    * gulp-cssnano;

* Plugins Gulp para JavaScript:
    * gulp-babel;
    * gulp-terser;

* Plugin Gulp para Imagens:
    * gulp-imagemin

* Plugins Gulp Genéricos:
    * gulp-concat;
   
## Passo a Passo da Configuração do Ambiente:

1. Baixar os arquivos ou fazer o clone do projeto;

2. Instalar as dependências no package.json
```sh
npm install
```
3. Para iniciar o desenvolvimento:
```sh
npm run start
```
4. Para gerar os arquivos minificados,optimizados e individuais na pasta dist:
```sh
gulp htmlmin 
```
```sh
gulp styles 
```
```sh
gulp babel
```
```sh
gulp imgemin
```
5. Para gerar os arquivos minificados,optimizados para produção em servidor na pasta build:
```sh
npm run build 
```