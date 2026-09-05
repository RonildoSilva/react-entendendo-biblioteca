# React: entendendo como a biblioteca funciona

> Aplicativo de notas (CEEP) construído durante o curso da Alura sobre fundamentos do React: componentes de classe, estado, ciclo de vida e padrão Observable para fontes de dados.

![status](https://img.shields.io/badge/status-concluído-success) ![react](https://img.shields.io/badge/React-16-blue) ![cra](https://img.shields.io/badge/Create%20React%20App-3-lightgrey)

## Sobre
Curso concluído em setembro de 2020. O app permite cadastrar notas com título, texto e categoria, criar categorias e listar as notas agrupadas. As fontes de dados (`Notas`, `Categorias`) implementam inscrição e notificação de observadores, e os componentes se inscrevem em `componentDidMount` e se desinscrevem em `componentWillUnmount`.

## Estrutura de pastas
```text
ceep/src/
├── App.js                         monta formulário, lista de categorias e lista de notas
├── components/FormularioCadastro/ campos controlados e submissão
├── components/ListaDeCategorias/  adiciona categoria com Enter
├── components/ListaDeNotas/, CardNota/
├── dados/Notas.js, Categorias.js  fontes de dados observáveis
└── assets/css/                    Bootstrap e estilos
```

## Como executar
```bash
cd ceep && npm install && npm start   # http://localhost:3000
```

## Status
Concluído. Material de estudo; não recebe manutenção.

## Autor
Ronildo Silva · ronildo.comp@gmail.com
