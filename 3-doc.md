# Controle de Branch no Git

Este arquivo é um exemplo de controle de branch no Git. Ele pode ser usado para registrar informações sobre as branches existentes em um repositório Git.

## Branches Atuais

- `master`: Branch principal do projeto.
- `develop`: Branch de desenvolvimento, onde as novas funcionalidades são integradas.
- `feature/login`: Branch para desenvolvimento da funcionalidade de login.
- `bugfix/issue-123`: Branch para correção do bug relacionado à issue #123.

## Fluxo de Trabalho

1. Crie uma nova branch a partir da branch `develop` para desenvolver uma nova funcionalidade ou corrigir um bug.
2. Faça as alterações necessárias na branch criada.
3. Realize testes e revise o código.
4. Faça o commit das alterações na branch.
5. Solicite uma revisão de código, se necessário.
6. Após a revisão, faça o merge da branch na `develop`.
7. A branch `develop` é periodicamente mesclada na branch `master` para lançamentos estáveis.

## Convenções de Nomenclatura

- Branches de funcionalidades: `feature/nome-da-funcionalidade`
- Branches de correção de bugs: `bugfix/issue-número-da-issue`

Lembre-se de sempre manter este arquivo atualizado com as informações relevantes sobre as branches do seu projeto.