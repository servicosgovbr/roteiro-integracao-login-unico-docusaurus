---
sidebar_label: 'Procedimentos para integração'
sidebar_position: 1
---

# Procedimentos para integração

É possível provar que um cidadão está vivo **sem** usar as transações (API) da Prova de vida. Nesse caso, utiliza-se o serviço do Login Único, o qual verifica quais selos de confiabilidade a conta do cidadão possui. Para realizar a Prova de vida dessa forma, a aplicação cliente deve estar **obrigatoriamente** integrada ao sistema do **[Login Único](https://manual-roteiro-integracao-login-unico.servicos.gov.br/pt/stable/index.html)** ![Site externo](/img/site-ext.gif).

Para provar a vida consumindo os serviços da API descrita nesta documentação, há necessidade de liberar o ambiente de **homologação** para que a aplicação cliente possa utilizar. Essa liberação ocorre por meio do envio das informações listadas abaixo:


Credenciais de acesso aos serviços de Homologação:

  - **CPF** de um representante do orgão ou entidade dona do serviço a ser integrado
  - **E-mail** do representante do orgão ou entidade 
  - **CPNJ** do orgão ou entidade


Para pessoas que realizarão testes no Aplicativo (Validação Facial), e não constam na base do TSE, deve-se enviar as informações abaixo para cadastro da biometria facial:

  
  - **Nome**
  - **CPF**
  - **Foto** no formato 3X4


Para liberação de acesso ao APP de Homologação, deve-ser enviar a informação:

  - Email do Google ou e-mail AppleID

Essas informações deverão ser encaminhadas para o e-mail: `int-provavida-govbr@economia.gov.br`, por um representante do **órgão** ou **entidade**. O representante ficará responsável pelas **credenciais** de acesso geradas por integrantes da `Secretaria de Governo Digital` (**SGD**) do `Ministério da Economia` (**ME**).

