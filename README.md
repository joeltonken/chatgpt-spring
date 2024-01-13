# chatgpt-spring

Este projeto é uma aplicação Spring Boot construída com Java 17 que se conecta com a API do ChatGPT. A aplicação permite que os usuários interajam com o modelo de linguagem GPT-3.5.

## Pré-requisitos

- Java 17
- Spring Boot
- Insomnia ou Postman

## Configuração

Primeiro, você precisará obter uma chave de API do ChatGPT. Você pode fazer isso seguindo as instruções [nesse link](https://www.hashtagtreinamentos.com/como-usar-a-api-do-chatgpt-python).

Depois de obter sua chave de API, você precisará configurá-la em sua váriaveis de ambiente do sistema. Para configurar a chave de API em suas variáveis de ambiente, siga estas etapas:

1. No Windows, vá para Painel de Controle -> Sistema e Segurança -> Sistema -> Configurações avançadas do sistema -> Variáveis de ambiente.
2. Clique em 'Novo' sob 'Variáveis de usuário'.
3. Digite `OPENAI_API_KEY` no campo 'Nome da variável' e cole sua chave de API no campo 'Valor da variável'.
4. Clique em 'OK' para salvar as alterações.