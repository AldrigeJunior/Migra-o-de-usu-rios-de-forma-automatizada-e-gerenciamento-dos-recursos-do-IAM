<p align="center">
  <h1 align="center">Migração de usuários de forma automatizada e gerenciamento dos recursos do IAM (Identity and Access Management) da AWS</h1>
</p>

![Capa](PORTFOLIOPROJETOSAWSMODULO2_CAPA-220608-211757.png)

## Descrição do projeto:
Nesse projeto baseado em um cenário real, tive que atuar como Especialista Cloud para realizar a migração de usuários de forma automatizada e gerenciar os recursos do IAM (Identity and Access Management) da AWS.
 Haviam 100 usuários que precisaram ser migrados e ter o MFA - Autenticação por múltiplos fatores (Multi-factor Authentication) habilitado nas contas, pois esta é uma melhor prática de segurança.
 Para não ser uma tarefa repetitiva e manual na console da AWS, precisei ter o pensamento voltado a automatizar os processos.
 Fazendo uso do GitBash com AWS CLI e Shell Script na IAM da AWS.

![Arquitetura](PORTFOLIOPROJETOAWSMODULO2_ARQUITETURA-220608-211757.png)

Passo 1 - Ajustar a planilha com todos os usuários para que o script possa executá-la.
De:
![Planilha antes](image.png)
Para:
![Planilha depois](image-1.png)
Passo 2 -  Instalar as ferramentas necessarias no bash:
![Script de instalação](image-2.png)
Passo 3 - Dar permissão de execução ao script:
![Script de permissão](image-3.png)
Passo 4 - Rodar o script.sh dentro da pasta com o projeto:
![Script de automação rodando](image-4.png)

Resultado:
Aqui temos alguns dos usuários criados dentro no IAM da AWS com SUCESSO!

![suários criados](image-5.png)
