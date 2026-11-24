# Levantamento dos arquivos de contribuição

Consulta às branches padrão dos 24 repositórios públicos ativos do GovHub em
24/11/2026, antes da inclusão dos arquivos padrão nesta branch. O repositório
arquivado `gov-hubio` não foi incluído. Este levantamento registra a presença
de arquivos, não avalia a qualidade do seu conteúdo.

| Repositório | README na raiz | Guia de contribuição | Templates de issue | Template de PR |
| --- | :---: | :---: | :---: | :---: |
| `gov-hub-io` | Sim | Sim | Sim | Não* |
| `data-application-gov-hub` | Sim | Sim | Não | Sim |
| `.github` | Não** | Não | Não | Não |
| `continuous-deployment` | Sim | Não | Não | Não |
| `dados-desestruturados` | Sim | Não | Não | Não |
| `data-application-cidades` | Sim | Não | Sim | Sim |
| `data-governance-workshop` | Sim | Não | Não | Não |
| `openmetadata-declarative-governance` | Sim | Não | Não | Não |
| `govhub-research` | Sim | Sim | Não | Sim |
| `CI-CD-PowerBI-MIR` | Não | Não | Não | Não |
| `govhub-plataform` | Sim | Não | Não | Não |
| `data-application-mgi` | Sim | Não | Não | Não |
| `data-application-mir` | Sim | Sim | Não | Sim |
| `gov-hub` | Sim | Sim | Não | Sim |
| `gov-hub-skills` | Sim | Não | Não | Não |
| `graphrag-tais` | Sim | Não | Não | Não |
| `govhub-roadmap` | Sim | Não | Não | Não |
| `template-repositorio-govhub` | Sim | Sim | Sim | Sim |
| `data-application-minc` | Sim | Não | Sim | Sim |
| `skills-assets` | Não | Não | Não | Não |
| `dashboard-minc-project` | Sim | Não | Não | Não |
| `continuous-deployment-mir` | Sim | Não | Não | Não |
| `bot-telegram-issues` | Sim | Não | Não | Não |
| `coleta_mir` | Sim | Não | Não | Não |

* `gov-hub-io` tem um arquivo chamado `PULL_REQUEST_TEMPLATE.md` dentro de
`.github/ISSUE_TEMPLATE/`, que não é o local de um template de PR. Confirmar
o comportamento na interface antes de corrigi-lo no próprio repositório.

** O `.github` tem `profile/README.md`, usado no perfil da organização, mas
não um README na raiz.

O GitHub usa os arquivos desta organização como padrão quando um repositório
não tem o correspondente próprio. Uma pasta local `.github/ISSUE_TEMPLATE`
com templates válidos ou `config.yml` impede o uso de toda a pasta de templates
de issue padrão. Portanto, o MinC receberá o guia geral de contribuição, mas
continuará com seus próprios templates de issue e PR. Os arquivos padrão não
aparecem no clone ou histórico dos repositórios que os herdam.

Referência: [arquivos padrão de comunidade no GitHub](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).
