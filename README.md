<div align="center">
  <img src="hotel_nebula_banner_elaborado.svg" width="100%" alt="VirtualDream Banner"/>
</div>
<br/>

# 🌌 Hotel Nebula
 
> Sistema de gerenciamento hoteleiro modelado com banco de dados NoSQL (MongoDB), focado em estrutura de dados flexível e escalável para controle de hóspedes, quartos e reservas.
---

## 📋 Sobre o projeto
 
O **Hotel Nebula** é um projeto de banco de dados desenvolvido para simular o gerenciamento de um hotel. A modelagem foi feita utilizando MongoDB, explorando os conceitos de documentos aninhados, referências entre coleções e consultas NoSQL.
## 🗂️ Coleções
 
O banco de dados é composto pelas seguintes coleções:
 
| Coleção | Descrição |
|---|---|
| `hospedes` | Dados cadastrais dos hóspedes |
| `quartos` | Informações e disponibilidade dos quartos |
| `reservas` | Registro de reservas vinculando hóspedes e quartos |
| `funcionarios` | Equipe do hotel |
| `servicos` | Serviços adicionais disponíveis |
 entre outras...
---
## 📁 Estrutura do banco
 
### `hospedes`
```json
{
  "_id": ObjectId,
  "nome": "string",
  "cpf": "string",
  "email": "string",
  "telefone": "string",
  "endereco": {
    "rua": "string",
    "cidade": "string",
    "estado": "string",
    "cep": "string"
  },
  "data_cadastro": ISODate
}
```
