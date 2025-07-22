# 🗓️ Calendário Trimestral (Jul-Set 2025)

Este é um projeto de front-end simples que exibe um calendário estático para os meses de **Julho, Agosto e Setembro de 2025**. 

O objetivo é demonstrar o uso de tabelas (`<table>`) em HTML para organizar informações de forma estruturada, além de técnicas básicas de layout e estilização.

## ✨ Funcionalidades

* **Visualização Trimestral:** Apresenta os calendários dos três meses lado a lado para fácil consulta.
* **Datas em Destaque:** Eventos e feriados importantes são destacados visualmente na cor vermelha.
* **Tooltips Informativos:** Ao passar o mouse sobre uma data destacada, uma pequena caixa de texto (tooltip) aparece com a descrição do evento, utilizando o
* atributo `title` do HTML.
* **Legenda Explicativa:** Uma legenda no final da página lista todos os eventos marcados para fácil referência.
* **Layout Flexível:** Utiliza `display: flex` para que os calendários se ajustem de forma organizada na página.

## 🏛️ Estrutura do Código

O projeto consiste em um único arquivo **HTML**.

* Cada mês é representado por uma tag `<table>`.
* Os dias da semana formam o cabeçalho da tabela (`<thead>`), e os dias do mês preenchem o corpo (`<tbody>`).
* Um `<div>` principal com `display: flex` envolve as três tabelas para alinhá-las horizontalmente.
* A estilização é feita diretamente no HTML (**CSS inline**) para manter o projeto simples e autocontido.

### Eventos Marcados no Calendário

* **20 de Julho:** Aula HTML/CSS - Infinity School
* **16 de Agosto:** Feriado: Dia do Estudante
* **07 de Setembro:** Feriado: Independência do Brasil

## 🚀 Como Visualizar

Para ver o calendário, você não precisa de nenhum servidor ou ferramenta. Apenas siga os passos:

1.  Faça o download do arquivo `index.html` (ou clone o repositório).
2.  Ou acesse: https://bettograpiuna.github.io/calendario/
3.  Abra o arquivo diretamente no seu navegador de internet (como Chrome, Firefox, etc.).

E pronto! A página com os calendários será exibida.
