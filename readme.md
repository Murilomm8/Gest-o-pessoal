# Gestão Financeira Pessoal

Este projeto é um aplicativo web para gestão financeira pessoal. Ele foi desenvolvido inteiramente com HTML, CSS, JavaScript e utiliza o framework **Bootstrap 5** para um design responsivo, além de **Chart.js** para visualização de dados e **LocalStorage** para persistência dos registros.

## Descrição

O aplicativo tem como objetivo ajudar o usuário a:
- **Gerenciar transações financeiras**, tanto entradas (receitas) quanto saídas (despesas);
- **Cadastrar despesas fixas** e marcar quando elas forem pagas, criando automaticamente uma transação de saída;
- **Acompanhar o saldo atual** atualizado em tempo real, conforme novas transações são inseridas ou despesas fixas pagas;
- **Definir e acompanhar o orçamento mensal**: o sistema compara o total de despesas do mês com o orçamento definido e alerta se este for ultrapassado;
- **Filtrar transações por data** para análises mais detalhadas;
- **Visualizar relatórios avançados**, com gráficos:
  - Um gráfico de barras mostrando as despesas fixas mensais;
  - Um gráfico de pizza exibindo a distribuição das despesas (baseando-se nas transações de saída);
  - Um gráfico de linha demonstrando a evolução do saldo mensal nos últimos seis meses;
- **Exportar e importar dados** em formato JSON para facilitar backups e compartilhamento.

Além disso, o uso de modais do Bootstrap para edição de transações e despesas fixas melhora a experiência do usuário, dispensando prompts nativos.

## Funcionalidades

- **CRUD de Transações e Despesas Fixas**  
  Permite criar, editar e excluir transações (com data, descrição, valor e tipo) e despesas fixas.
  
- **Botão "Pagar" para Despesas Fixas**  
  Ao pagar uma despesa fixa, o sistema adiciona automaticamente uma transação do tipo "saída" e atualiza o saldo.
  
- **Orçamento Mensal**  
  O usuário pode definir um orçamento e o sistema verifica se o total de gastos do mês ultrapassa esse valor.
  
- **Relatórios e Gráficos Dinâmicos**  
  Utiliza o Chart.js para gerar gráficos de barras, pizza e linha, permitindo uma visão visual dos dados financeiros.
  
- **Filtragem de Transações por Data**  
  Permite ao usuário obter uma lista filtrada das transações em um intervalo de datas definido.
  
- **Exportação e Importação de Dados**  
  Possibilita exportar todos os dados (transações, despesas fixas e orçamento) para um arquivo JSON e importar dados do mesmo formato.

## Tecnologias Utilizadas

- **HTML5, CSS3 e JavaScript** – Base do projeto.
- **Bootstrap 5** – Framework responsivo e moderno para criação da interface.
- **Chart.js** – Criação dos gráficos que apresentam os dados financeiros.
- **Font Awesome** – Ícones modernos e reutilizáveis.
- **LocalStorage** – Persistência dos dados no navegador, sem necessidade de um backend.

## Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Murilomm8/Gest-o-pessoal.git
   cd Gest-o-pessoal
