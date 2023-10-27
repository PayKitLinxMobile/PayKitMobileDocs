# RELEASE NOTES

## Versão 2.7.4
    Descrição: versão 2.7.3.2 + features
    Data: 25/08/2023

### Correções e implementações
- Inclusão da transação de Split de Pagamento.

### Binários
- [dtefmobile-v2.7.4](https://grupolinx-my.sharepoint.com/:f:/r/personal/ped_payhub_tef_linx_com_br/Documents/Instaladores-DevCenterMobile/sdk-mobile/releases/v2.7.4?csf=1&web=1&e=x98WQ3)

## Versão 2.7.3.4
    Descrição: versão 2.7.3.4 + features + bugfixes
    Data: 13/10/2023

### Correções e implementações
- Inclusão de parâmetro para informar o tipo da transação a ser cancelada na transação de cancelamento.
- Inclusão de callback para passagem de dados para automação durante o fluxo da transação.
- Alteração no fluxo de frota, tornando opcional o parâmetro de tipo de abastecimento, para realizar coleta quando não informado no JSON.
- Correções no processamento da lista de produtos no fluxo de Frota.
- Correção para não permitir a entrada do cartão digitado após cenário de “Modo inválido”, quando a opção de permitir digitação está desabilitada.
- Implementação de parâmetro para permitir que a automação informe o(s) produto(s) cielo desejados (desde que habilitados na inicialização).

## Versão 2.7.3.3
    Descrição: versão 2.7.3.3 + features
    Data: 14/09/2023

### Correções e implementações
- Inclusão de melhorias na conexão com Pinpad Bluetooth.

## Versão 2.7.3.2
    Descrição: versão 2.7.3.1 + bugfix
    Data: 21/08/2023

### Correções e implementações
- Removida permissão incluída para leitura dos dados do chip. Estava provocando crash na aplicação quando o usuário não concede a permissão de telefone.

### Binários
- [dtefmobile-v2.7.3.2](https://grupolinx-my.sharepoint.com/:f:/r/personal/ped_payhub_tef_linx_com_br/Documents/Instaladores-DevCenterMobile/sdk-mobile/releases/v2.7.3.2?csf=1&web=1&e=GcmhiS)

## Versão 2.7.3.1
    Descrição: versão 2.7.3 + MP15
    Data: 11/08/2023

### Correções e implementações
- Correções na PPComp referente à comunicação com pinpad bluetooth (certificação Cielo).

### Binários
- [dtefmobile-v2.7.3.1]()

## Versão  2.7.3
    Descrição: versão 2.7.2.1 + Banrisul
    Data: 27/07/2023

### Correções e implementações
- Criptografia dos dados sensíveis com a chave do Banrisul.
- Implementação dos comandos 91 e 92 para viabilizar a criptografia em transação digitada.

### Binários
- [dtefmobile-v2.7.3]()

## Versão 2.7.2.1
    Descrição: versão 2.7.2 + bugfix
    Data: 24/07/2023

### Correções e implementações
- Correção no processamento do retorno das tags emv na PP_GOONCHIP - ABECS.

### Binários
- [dtefmobile-v2.7.2.1]()

## Versão 2.7.2
    Descrição: versão 2.7.1 + features
    Data: 20/07/2023

### Correções e implementações
- Implementação dos parâmetros frota via chamada de função.
- Transação especial para obter identificação do perfil do mapa de chaves.
- Correção da impressão para o P2 com perfil “parceiros”.

### Binários
- [dtefmobile-v2.7.2]()

## Versão 2.7.1.1
    Descrição: versão 2.7.1 + bugfix
    Data: 24/07/2023

### Correções e implementações
- Correção no processamento do retorno das tags emv na PP_GOONCHIP - ABECS.

### Binários
- [dtefmobile-v2.7.1.1]()

## Versão 2.7.1
    Descrição: versão 2.7.0 + certificação MP15 (Cielo)
    Data: 11/07/2023

### Correções e implementações
- Implementação do protocolo ABECS para suportar o campo SPE_TRNTYPE necessário para o 
  caso de teste MCD01.02.02. 

  - Obs.: a implementação do protocolo ABECS foi realizada na comunicação com pinpads 
  bluetooth. Para os demais dispositivos é utilizado a BC do fabricante.

### Binários
- [dtefmobile-v2.7.1]()

## Versão 2.7.0
    Descrição: versão 2.6.5 + features
    Data: 05/05/2023

### Correções e implementações
- Implementação para suportar transações com a ticket log.
- Identificação da posição em que a chave da Stone está gravada a fim de determinar o perfil do mapa de chaves (padrão ou parceiros).
- Seleção automática do mapeamento das chaves de acordo com o perfil identificado.
- Reconhecimento do pinpad bluetooth MP-15.
- Implementação para permitir a leitura do KSN através da transação especial.

### Binários
- [dtefmobile-v2.7.0]()

## Versão 2.6.6.2
    Descrição: versão 2.6.6 + features
    Data: 26/10/2023

### Correções e implementações
- Inclusão no MobileSDK da inicialização passando o context.

## Versão 2.6.6.1
    Descrição: versão 2.6.6 + bugfix
    Data: 03/08/2023

### Correções e implementações
- Correção da mensagem "Retire o cartão" na transação por aproximação (K2).

### Binários
- [dtefmobile-v2.6.6.1]()

## Versão 2.6.6
    Descrição: versão 2.6.5 + features
    Observação: Em certificação Banrisul
    Data: 02/06/2023

### Correções e implementações
- Em certificação com o Banrisul.
- Customizações necessárias para o Sunmi K2.

### Binários
- [dtefmobile-v2.6.6]()

## Versão 2.6.5-build-2306081649
    Descrição: versão 2.6.5 + features
    Observação: Build 2306081649
    Data: 08/06/2023

### Correções e implementações
- Incluído perfil “parceiros-stone” na inicialização do SmartPrinterService.

### Binários
- [dtefmobile-v2.6.5-2306081649]()

## Versão 2.6.5
    Descrição: versão 2.6.4 + features
    Data: 09/03/2023

### Correções e implementações
- Certificada pela Cielo.
- Inclusão do mapeamento das chaves da Cielo.

### Binários
- [dtefmobile-v2.6.5]()

## Versão 2.6.4
    Descrição: versão 2.6.3 + features
    Data: 11/08/2022 

### Correções e implementações
- Certificada pela SafraPay.
- Inclusão do mapeamento das chaves da Safra.

### Binários
- [dtefmobile-v2.6.4]()