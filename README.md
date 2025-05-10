
# 🏎️ Oficina Mecânica - Modelo ER

## 📌 Visão Geral  
Este diagrama representa a estrutura de dados de uma **oficina mecânica**, organizando informações essenciais sobre clientes, veículos, serviços, equipes e peças.  

## 🛠️ Entidades Principais  
- **👨‍🔧 Mecânico** – Dados pessoais e especialidade.  
- **👥 Equipe** – Conjunto de mecânicos que realizam serviços.  
- **📝 Ordem de Serviço** – Registra cada atendimento, vinculando o veículo, equipe e serviços realizados.  
- **🔧 Serviço** – Lista de serviços oferecidos, incluindo descrição e valor por hora.  
- **🛒 Peça** – Catálogo de peças utilizadas nos reparos.  
- **🚗 Veículo** – Dados do automóvel, incluindo modelo, placa e dono.  
- **🧑‍💼 Cliente** – Informações sobre os clientes que possuem veículos na oficina.  

## 🔄 Relacionamentos Importantes  
- Uma **equipe** pode ter vários **mecânicos**.  
- Cada **ordem de serviço** pode conter múltiplos **serviços** e **peças**.  
- Um **veículo** pertence a um único **cliente**.  
- As **ordens de serviço** são atribuídas a **equipes** específicas.  

## 🎯 Objetivo do Modelo  
O modelo facilita a gestão eficiente da oficina, garantindo um **controle detalhado** sobre atendimentos, peças utilizadas e custos dos serviços prestados.
