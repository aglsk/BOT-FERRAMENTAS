# Documentação do Bot Telegram

## Introdução
Este é um bot Telegram construído em Python usando a biblioteca Pyrogram. Ele possui várias funcionalidades, incluindo:

1. Consulta de registros de saúde brasileiros usando uma API específica.
2. Geração de texto com modelos GPT.
3. Geração de imagens usando a API Sexy AI.

## Configuração
Antes de executar o bot, certifique-se de ter as seguintes configurações:

1. Python 3.9 ou superior instalado em seu sistema.
2. Instalação das bibliotecas necessárias, incluindo Pyrogram e requests. Você pode instalá-las usando o pip:
3. pip install pyrogram requests
4. Credenciais necessárias para acessar APIs, como o token de autenticação para a API de registros de saúde e suas credenciais para a API Sexy AI.

## Funcionalidades

### Consulta de Registros de Saúde (CPF)
O bot permite consultar registros de saúde brasileiros usando o CPF de um cidadão brasileiro. Para usar esta funcionalidade, digite o comando `/cpf <CPF>` em uma conversa privada com o bot, substituindo `<CPF>` pelo CPF do cidadão que deseja consultar.

Exemplo de uso:
/cpf 12345678900

### Geração de Texto com Modelos GPT
O bot pode gerar texto usando modelos GPT. Para usar esta funcionalidade, digite o comando `/gpt <texto>` em qualquer conversa com o bot, substituindo `<texto>` pelo conteúdo que deseja que o modelo GPT gere.

Exemplo de uso:
/gpt Gere um texto sobre inteligência artificial.

### Geração de Imagens Sexy AI
O bot pode gerar imagens usando a API Sexy AI. Para usar esta funcionalidade, digite o comando `/sexy <prompt>` em qualquer conversa com o bot, substituindo `<prompt>` pela descrição do que deseja que a imagem contenha.

Exemplo de uso:
/sexy Uma imagem sexy de uma praia.

## Execução
Para executar o bot, execute o script Python fornecido. Certifique-se de fornecer as credenciais necessárias para acessar as APIs, como o token de autenticação para a API de registros de saúde e suas credenciais para a API Sexy AI.

## Limitações e Considerações
1. Este bot foi projetado para fins educacionais e de demonstração. Não o utilize para acessar dados sensíveis sem permissão adequada.
2. Certifique-se de seguir os termos de serviço das APIs utilizadas para evitar violações.
3. Este bot pode não estar completamente livre de bugs ou vulnerabilidades. Certifique-se de revisar e testar o código antes de usar em um ambiente de produção.

