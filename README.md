# CasaControle

Aplicativo web para administração de imóveis de aluguel próprios, com interface em português brasileiro, controle financeiro, contratos, inquilinos, manutenções, lembretes, relatórios e configurações.

## Status do projeto

A implementação funcional ainda não foi iniciada porque o repositório atualmente contém apenas este README.md e não possui a base da aplicação, configuração de build, rotas, componentes de interface ou backend conectado.

O CasaControle depende de um banco de dados conectado para persistir e proteger as informações de imóveis, inquilinos, contratos, cobranças, pagamentos, despesas, manutenções, lembretes e preferências do usuário. A conexão também permitirá calcular os indicadores do dashboard a partir de registros reais, criar os dados iniciais de demonstração sem duplicação e remover somente os registros de teste com segurança.

## Próxima etapa

Adicionar a estrutura inicial da aplicação React com TypeScript, o sistema de autenticação, a conexão com o backend PostgreSQL compatível e as entidades relacionadas com políticas de acesso por usuário. Depois disso, serão implementadas as rotas e operações funcionais do CasaControle.