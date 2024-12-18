# Sistema de Gerenciamento de Oficina Mecânica

## Descrição do Projeto
Este projeto é um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica. Ele foi projetado para registrar e organizar informações sobre clientes, veículos, serviços, peças, mecânicos e equipes.

### Contexto
- Os clientes levam seus veículos à oficina para consertos ou revisões.
- Cada veículo é designado a uma equipe de mecânicos, que avalia e executa os serviços.
- Uma Ordem de Serviço (OS) é criada para registrar os serviços e peças necessários.
- O valor total da OS é calculado com base nos serviços e peças utilizados.
- O sistema mantém o controle de status e datas das OS.

### Estrutura do Banco de Dados
O banco de dados é composto por tabelas que representam as principais entidades do sistema:
- **Cliente**: armazena informações dos clientes.
- **Veículo**: vincula os veículos aos clientes.
- **Ordem de Serviço (OS)**: registra as ordens de serviço, status e valores.
- **Serviço**: tabela de referência para serviços disponíveis.
- **Peça**: tabela de referência para peças utilizadas.
- **Equipe de Mecânicos**: organiza os mecânicos em equipes.
- **Mecânico**: registra os mecânicos e suas especialidades.

### Ferramenta Utilizada
MySQL
---

## Autor
[Patrick Matthew]
