# 🏭 Controle de Defeitos e Qualidade dos Teares

Sistema leve e responsivo desenvolvido para o monitoramento de defeitos em teares industriais. O projeto permite o cadastro, edição, exclusão e análise estatística de ocorrências, com exportação direta para PDF.

![Status do Projeto](https://img.shields.io/badge/Status-Finalizado-brightgreen)
![Tecnologias](https://img.shields.io/badge/Tecnologias-HTML%20%7C%20JS%20%7C%20Bootstrap-blue)

## 🚀 Funcionalidades

- **Cadastro de Ocorrências**: Registro de número do tear, artigo, defeito, data, hora e turno.
- **Gestão Completa (CRUD)**: Possibilidade de editar ou excluir registros salvos.
- **Armazenamento Local**: Utiliza `localStorage` do navegador (não precisa de banco de dados externo).
- **Relatório Profissional em PDF**: 
    - Listagem geral de todos os registros.
    - **Análise Estatística**: Tabela de resumo por dia com detalhamento de quantos defeitos ocorreram em cada turno (Manhã, Tarde e Noite).
- **Interface Responsiva**: Otimizado para uso em computadores, tablets e smartphones.

## 🛠️ Tecnologias Utilizadas

- [Bootstrap 5](https://getbootstrap.com/): Para o design responsivo e componentes de interface.
- [JavaScript Puro (Vanilla JS)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript): Para a lógica de negócio e manipulação de dados.
- [jsPDF](https://github.com/parallax/jsPDF): Biblioteca principal para geração dos arquivos PDF.
- [jsPDF-AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable): Plugin para criação de tabelas estruturadas no PDF.

## 📦 Como usar

Não é necessário instalar nenhuma dependência ou servidor (Node.js/Python).

1. Faça o download do arquivo `index.html`.
2. Abra o arquivo em qualquer navegador moderno (Chrome, Edge, Firefox).
3. (Opcional) Para usar no celular como um aplicativo:
   - Abra o arquivo no navegador do celular.
   - Vá nas opções do navegador e selecione **"Adicionar à tela inicial"**.

## 📊 Estrutura do Relatório PDF

O relatório gerado conta com uma seção de inteligência de dados que agrupa as informações da seguinte forma:

| Data | Detalhamento por Turno | Total Dia |
| :--- | :--- | :--- |
| 15/02/2026 | Manhã: 2 \| Tarde: 3 \| Noite: 0 | 5 |

## 📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.
