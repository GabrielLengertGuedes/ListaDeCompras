# Lista de Compras

Aplicação web desenvolvida com **HTML5, CSS3 e JavaScript** para praticar **manipulação do DOM**, modularização de scripts e interatividade em páginas web.

O projeto permite adicionar itens dinamicamente a uma lista de compras, marcar itens como concluídos e registrar a data e o horário em que cada item foi criado.

## Tecnologias utilizadas

- HTML5  
- CSS3  
- JavaScript (ES6 Modules)

## Conceitos praticados

- Manipulação do DOM  
- Modularização de código com `import` e `export`  
- Criação dinâmica de elementos com `createElement()`  
- Eventos com `addEventListener()`  
- Validação de campos  
- Exibição condicional de mensagens na interface  
- Formatação de data e hora com `toLocaleDateString()` e `toLocaleTimeString()`

## Funcionalidades

- Adição dinâmica de itens na lista de compras  
- Validação de entrada para impedir inserção de itens vazios
- Marcação de itens comprados com checkbox  
- Alteração visual dos itens concluídos com `line-through`  
- Exibição da data e hora de criação de cada item  
- Mensagem automática quando a lista está vazia  

## Estrutura do projeto
```bash
ListaDeCompras/
├── index.html
├── index.js
├── styles.css
├── README.md
├── img/
│   ├── bag.png
│   ├── delete.svg
│   └── edit.svg
└── scripts/
    ├── criarItemDaLista.js
    ├── gerarDiaDaSemana.js
    └── verificarListaVazia.js
```

## Como executar o projeto

1. Clone ou baixe este repositório  
2. Abra a pasta do projeto no VS Code  
3. Execute com a extensão **Live Server**

Ou, se preferir, abra o arquivo `index.html` diretamente no navegador.

## Objetivo do projeto

Praticar fundamentos de **JavaScript aplicado ao desenvolvimento web**, com foco em criação dinâmica de elementos, organização de código em módulos e interação com o usuário.

## Aprendizados com o projeto

Durante o desenvolvimento deste projeto foram praticados conceitos importantes de front-end, como:

- separação de responsabilidades em arquivos JavaScript  
- atualização dinâmica da interface  
- validação de entradas do usuário  
- organização de código para facilitar manutenção  

## Autor

**Gabriel Lengert Guedes**

Estudante de Engenharia de Software  
GitHub: https://github.com/GabrielLengertGuedes