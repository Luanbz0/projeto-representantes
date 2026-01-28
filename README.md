# Representante Finanças - MicroSaaS

Um gerenciador financeiro moderno desenvolvido para Representantes Comerciais, permitindo o controle separado de finanças **Pessoais (PF)** e **Empresariais (PJ)** em uma única interface.

## Tecnologias Utilizadas

- **React** (Vite)
- **Vanilla CSS** (CSS Variables, Flexbox, Grid)
- **Lucide React** (Ícones)
- **LocalStorage** (Persistência de dados no navegador)

## Como Rodar o Projeto

Este projeto requer **Node.js** instalado no seu computador.

1. **Instalar dependências**:
   Abra o terminal na pasta do projeto e execute:
   ```bash
   npm install
   ```

2. **Rodar o servidor de desenvolvimento**:
   Após instalar, execute:
   ```bash
   npm run dev
   ```
   
3. **Acessar**:
   O terminal mostrará um link (geralmente `http://localhost:5173`). Clique nele para abrir no navegador.

## Funcionalidades

- **Dashboard**: Visão geral do saldo, entradas e saídas.
- **Alternância de Contexto**: Mude entre visão "Pessoal" e "Empresa" com um clique.
- **Transações**: Adicione, liste e exclua lançamentos (Comissões, Reembolsos, Despesas).
- **Relatórios**: Visualize para onde o dinheiro está indo com barras de progresso por categoria.
