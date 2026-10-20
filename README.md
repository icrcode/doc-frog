# 🐸 doc-frog

**doc-frog** é um indexador de documentações oficiais feito para ajudar os alunos a consultar a documentação das ferramentas usadas em aula de forma rápida e **totalmente offline**.

O aluno digita o que procura (por exemplo `mysqli`, `array_map`, `SELECT` ou `for`) e o doc-frog mostra onde aquele assunto está na documentação oficial. Com um clique, o PDF abre na página certa, em **português** ou no **original em inglês**.

## Documentações incluídas

- PHP
- JavaScript
- Python
- HTML
- CSS
- MySQL
- MySQL Workbench
- DBeaver
- XAMPP

> MySQL, MySQL Workbench e DBeaver não possuem tradução oficial para o português, por isso estão disponíveis apenas em inglês.

## Como usar

1. Copie a pasta `doc-frog` para o computador (ou pendrive).
2. Abra o arquivo `index.html` no navegador (Chrome, Edge ou Firefox).
3. Digite o que deseja pesquisar e clique em **Português** ou **Inglês (original)**.

Não precisa de internet, servidor nem instalação.

**Atalhos:** `/` vai para a busca e `Enter` abre o primeiro resultado.

## Estrutura

```
doc-frog/
├── index.html                 # página de busca
├── assets/                    # índice de busca, logos e ícone
├── documentacao-original/     # PDFs em inglês
└── documentacao-portugues/    # PDFs em português
```

## Licença e Download

[Baixar](/icrcode/doc-frog/archive/refs/heads/main.zip)

O doc-frog é software livre, distribuído sob a licença **GNU General Public License v3.0 (GPL-3.0)**. Você pode usar, estudar, modificar e compartilhar, desde que mantenha a mesma licença.

As documentações em PDF pertencem aos seus respectivos autores e mantêm as licenças originais: php.net, MDN Web Docs, Python Software Foundation, Oracle/MySQL, DBeaver e Apache Friends.

---

Projeto de caráter educacional e não comercial. Desenvolvido por [@icrcode](https://github.com/seu-usuario/icrcode).
