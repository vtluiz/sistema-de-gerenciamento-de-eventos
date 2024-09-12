# Sistema de Gerenciamento de Eventos

Este projeto gerencia eventos, participantes e inscrições usando SQL. Permite a criação, consulta, atualização e remoção de eventos e suas inscrições.

## Estrutura do Banco de Dados

- **Eventos**: Armazena informações dos eventos.
- **Participantes**: Registra informações dos participantes.
- **Inscricoes**: Relaciona participantes com eventos.

## Funcionalidades

1. **Criação de Banco de Dados e Tabelas**: O script `create_tables.sql` cria as tabelas necessárias.
2. **Inserção de Dados**: O script `insert_data.sql` insere dados iniciais.
3. **Consultas**: Use `queries.sql` para visualizar eventos e inscrições.
4. **Atualizações e Deleções**: O script `update_delete.sql` contém exemplos de atualizações e remoções.
5. **Funcionalidades Extras**: O script `extra_features.sql` lista participantes com múltiplas inscrições.

## Requisitos

- MySQL ou outro SGBD compatível.
