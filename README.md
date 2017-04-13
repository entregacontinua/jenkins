# Jenkins

## Integração com slack

Informações gerais podem ser obtidas em url: https://github.com/jenkinsci/slack-plugin

Resumindo,
acessar url: https://my.slack.com/services/new/jenkins-ci
e configirar o jenkins no slack.

Seguir instruções de configuração


## Autenticação com github

Informações gerais podem ser obtidas em:
 
  * https://jenkins.io/solutions/github/
  * https://wiki.jenkins-ci.org/display/JENKINS/Github+OAuth+Plugin#GithubOAuthPlugin-Setup
 
 Resumindo,
 
* Visite https://github.com/settings/applications/new para registrar uma nova aplicação.
* Os valores para "application name", "homepage URL" e "application description" não importam. Podem ser customizados como desejado They can be customized however.
* Entretanto, a url do retorno de autorização (authorization callback URL) deve ter um valor específico. Ela deve parecer com https://jenkins.example.com/securityRealm/finishLogin onde jenkins.example.com é a localização do seu servidor jenkins.
