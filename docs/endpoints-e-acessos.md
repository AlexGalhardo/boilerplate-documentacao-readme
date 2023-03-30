# Endpoints e Acessos

IMPORTANTE: caso você seja responsável por manter esse código, certifique-se que você tenha os acessos necessários para acessar esses links

## Essa API se comunica com os serviços

- <https://github.com/company_name/frontend_exemplo>
- <https://github.com/company_name/frontend_dois_exemplo>
- <https://github.com/company_name/serviço_backend_exemplo>

## Endpoints desse serviço

- Endpoint Produção: <https://exemplo-api.company.com.br>
- Endpoint Staging: <https://exemplo-api-stg.company.com.br>

## Deploys

- Deploy desse serviço no GCP em ambiente staging: <https://console.cloud.google.com/company/service_name/staging>
- Deploy desse serviço no GCP em ambiente staging produção: <https://console.cloud.google.com/company/service_name/production>

## Observabilidade (Sentry, Datadog, Newrelic, Amplitude, etc)

- URL para checar logs de erros no Sentry: <https://sentry.io/company/exemplo>
- URL para checar logs de erros no DataDog: <https://datadog.com/company/exemplo>
- URL para checar logs de erros no NewRelic: <https://newrelic.com/company/exemplo>

## Documentações externas

- Confluence Squad NOME_DA_SQUAD_AQUI: <https://company.atlassian.net/wiki/spaces/SAESAA/overview>
- Onboarding Novos Colaboradores: <https://company.atlassian.net/wiki/spaces/TECH/pages/1475641470/Onboarding+Novos+Colaboradores>
- Backstage
  - [Primeiros Passos com Backstage e Ambiente Dev](https://company.atlassian.net/wiki/spaces/devops/pages/1676640557/Primeiros+Passos+com+Backstage+e+Ambiente+Dev)
  - [Grupos do GitHub](https://oraculo.company.com.br/#/Platform/Grupos%20do%20Github/HOME)
  - [Estruturando um arquivo de Helm Chart](https://company.atlassian.net/wiki/spaces/devops/pages/1607008260/Estruturando+um+arquivo+de+Helm+Chart)
  - [Estrutura C4 Model do Backstage](https://oraculo.company.com.br/#/Platform/Ambientes%20de%20Contexto%20(GCP)/Backstage/HOME)
  - [Containers C4 Model](https://oraculo.company.com.br/#/Platform/Ambientes%20de%20Contexto%20(GCP)/Backstage/Containers/HOME)
  - [Contexto C4 Model](https://oraculo.company.com.br/#/Platform/Ambientes%20de%20Contexto%20(GCP)/Backstage/Containers/HOME)

---
Porque é importante documentar isso?

- Fica fácil para novos colaboradores:
  - Identificarem quais outros serviços (repositórios de código) da empresa esse serviço depende/se comunica.
  - Identificarem todos os acessos necessários que eles precisam ter acesso.
  - Saberem quais os principais endpoints e urls desse serviço eles vão utilizar.
  - Saberem quais documentações externas eles vão utilizar.
- Para outras squads:
  - Entenderem melhor o contexto desse serviço e sanar possíveis dúvidas técnicas.
