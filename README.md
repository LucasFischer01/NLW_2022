# NLW_2022
Projeto NLW 2022. Mão na massa.


## Aprendizados

O que você aprendeu construindo esse projeto? Quais desafios você enfrentou e como você superou-os?

1. Criar back-end com node;
* npm init -y (-y flag para yes em todas as etapas)
* Instalar framework 'express': yarn add express;
* Criar pasta src para meu server.js e configurar no package main: server.js;
* acessar express forma antiga: const express = require('express');
* acessar da forma mais atual: Setar no pachage "type": "module" e usar meu arquivo principal com .mjs;
* import express from "express" > const app = express()
* Usar typescript:
    1. yarn add typescript -D (-D para instalar na parte de desenvolvimento);
    2. Renomear arquivo principal para .ts;
    3. Acrescentar em package.json/"scripts": "build": "tsc";
    4. Criar arquivo de configuração para o "tsc": npx tsc --init;
    5. yarn run build: Converter meu tsc em js;
    6. Em "tscconfig": mudar dir para ler tudo da "src" e outDir para gerar meu ts em "/build";
    7. express não tem suporte direto a TS: yarn add @types/express -D > tscconfig "moduleResolution": "node";
    
