---
layout: default
title: Política de Privacidade do GPS Here
lang: pt-BR
---

# Política de Privacidade do GPS Here

**Última atualização:** 24 de novembro de 2026

Esta política explica como o aplicativo **GPS Here! Simule seu local** ("GPS Here", "o app"), publicado por
**Extrah, mantido por Fernando Thomas Schmidt** ("nós"), trata informações quando você o usa. Ela vale para o app
disponível no Google Play com o identificador `br.com.extrah.gpshere`.

## Resumo

- O GPS Here é uma ferramenta para testar apps com localizações simuladas.
- **Não temos servidores**: nada do que você faz no app é enviado para nós.
- Não há anúncios, análise de uso (analytics), conta de usuário nem venda de dados.
- Suas rotas gravadas ficam **somente no seu aparelho**.
- Para mostrar mapas e fazer buscas, o app se comunica diretamente com serviços de terceiros
  (OpenStreetMap e Google), descritos abaixo.

## 1. Informações tratadas no seu aparelho

| Informação | Para que é usada | Onde fica |
|---|---|---|
| **Localização precisa** (GPS e rede), com sua permissão | Mostrar onde você está no mapa, gravar rotas e confirmar a posição simulada | Usada no aparelho; não é enviada para nós |
| **Rotas gravadas** (pontos com coordenadas, altitude e horário) e uma imagem do mapa do ponto inicial | Reproduzir a rota depois | Armazenamento privado do app, no seu aparelho |
| **Arquivos que você abre** (GPX ou listas de coordenadas) | Simular a rota do arquivo | Lidos no aparelho; o app não guarda cópia |
| **Situação da compra do Pro** (sim/não) | Liberar os recursos pagos sem internet | Armazenamento privado do app |
| **Cache de mapas** | Evitar baixar o mesmo mapa de novo | Área de cache do app |

Você pode apagar rotas a qualquer momento no próprio app (aba **Gravações › Apagar**). Ao desinstalar o app,
o Android apaga todas essas informações. Quando você usa **Baixar GPX**, o arquivo é salvo no local que você
escolher e passa a ficar sob seu controle.

## 2. Informações enviadas a terceiros

O app não envia dados para nós, mas, para funcionar, faz pedidos diretamente aos serviços abaixo. Toda a
comunicação usa conexão criptografada (HTTPS). Em cada pedido, o serviço também recebe dados técnicos
da conexão, como o **endereço IP** e a identificação do app.

| Serviço | O que recebe | Quando | Para quê |
|---|---|---|---|
| **OpenStreetMap — servidores de mapa** (OpenStreetMap Foundation) | As coordenadas dos pedaços do mapa a exibir, que indicam a **região onde você está ou que está olhando** | Ao mostrar o mapa na tela inicial, ao escolher um ponto no mapa e ao gravar uma rota (imagem do ponto inicial) | Desenhar os mapas |
| **Nominatim** (busca do OpenStreetMap) | O **texto que você digita na busca** e a área do mapa visível no momento | Quando você busca um endereço ou lugar | Encontrar o lugar buscado |
| **Google** (serviço de busca de endereços do Android, o Geocoder) | O **texto da busca** e a área do mapa visível | Quando você busca um endereço ou lugar | Encontrar o lugar buscado |
| **Google Play Services** (provedor de localização) | Dados de localização, conforme as configurações de localização do seu aparelho | Quando o app lê sua localização ou envia a posição simulada | Obter e simular a localização |
| **Google Play** (faturamento) | Os dados da compra do Pro, tratados pelo Google | Quando você compra ou restaura o Pro | Processar o pagamento |

Esses serviços tratam as informações segundo as próprias políticas:

- OpenStreetMap Foundation: <https://osmfoundation.org/wiki/Privacy_Policy>
- Google: <https://policies.google.com/privacy>

Não temos acesso aos dados que esses serviços recebem.

## 3. Simulação de localização

Quando você inicia uma simulação, o app informa ao sistema Android uma localização fictícia. Enquanto ela está
ativa, **os outros apps do aparelho recebem a posição simulada** no lugar da real. A localização real volta assim
que você toca em **Parar**. Use a simulação apenas para testar apps e em situações em que isso seja permitido.

## 4. Permissões

- **Localização precisa e aproximada**: mostrar sua posição, gravar rotas e simular localização.
- **Local fictício** (nas opções do desenvolvedor, escolhido por você): substituir a localização do sistema.
- **Serviço em primeiro plano de localização** e **notificações**: manter a simulação ou a gravação ativa com o
  app em segundo plano e mostrar os controles de pausar e parar.
- **Internet**: carregar mapas, fazer buscas e processar compras.

O app **não** pede acesso à localização em segundo plano. Você pode retirar as permissões a qualquer momento
nas configurações do Android.

## 5. Base legal e seus direitos (LGPD)

Tratamos as informações descritas para executar as funções que você pede no app (art. 7º, V, da Lei 13.709/2018),
e a localização somente com sua permissão. Como não armazenamos seus dados em servidores próprios, você exerce o
controle diretamente no aparelho: apagando rotas, retirando permissões ou desinstalando o app. Para dúvidas ou
para exercer os direitos previstos na LGPD, fale com a gente pelo contato abaixo. Para os dados tratados pelo
OpenStreetMap e pelo Google, procure esses serviços.

## 6. Crianças

O app é uma ferramenta para desenvolvedores e não é direcionado a crianças menores de 13 anos.

## 7. Alterações nesta política

Podemos atualizar esta política quando o app mudar. A data da última atualização fica no topo, e mudanças
importantes também serão informadas na página do app no Google Play.

## 8. Contato

**Extrah**, mantido por **Fernando Thomas Schmidt**<br>
E-mail: [contato@extrah.com.br](mailto:contato@extrah.com.br)
