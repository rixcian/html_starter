# HTML Starter Project

This repository is starting project for creating static web designs. It's using **Parcel** for bundling all assets, PostCSS for transforming (SCSS) and minimizing (cssnano, purgecss) style sheets and  **TailwindCSS** as CSS framework.



## Setup

Firstly, you have to install **Parcel** using yarn (or npm). On Linux you have to add `sudo` before the command.

`$ yarn global add parcel-bundler` or `$ npm install -g parcel-bundler`



## Initialization

Get this repository to your local PC and change directory. 

`$ git clone <repo_url> && cd html_starter `

Install all dependencies.

`$ yarn install` or `$ npm install`



## Running dev server

By using this command parcel will bundle all assets in *./src* folder and starts dev server on `http://localhost:1234` .

`$ yarn run dev`