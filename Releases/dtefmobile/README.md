# RELEASE NOTES

## Versão 2.7.10
    Descrição: versão 2.7.9.2 + 2.7.7.1 + features + bugfixes
    Data: 26/03/2024

### Correções e implementações
- Incluído suporte ao totem Gertec SK-210.
- Incluído suporte ao terminal Gertec GPOS-780.
- Incluído campo de identificação do terminal para enviar ao GatewayPOS.
- Correção no fluxo de frota (relacionado ao tipoAbastecimento e valorTotal).
- Correção de ocorrência de exception após carga de tabelas.

### Binários
- [dtefmobile-v2.7.10](https://grupolinx-my.sharepoint.com/:u:/g/personal/ped_payhub_tef_linx_com_br/EdOPic2g9mtFr1MAlhunhr8BU29PQlTZUNM-gmgxiJbUrA?e=MxBaAa)

## Versão 2.7.9.3
    Descrição: versão 2.7.9.2 + features
    Data: 09/04/2024

### Correções e implementações
- Incluídos novos parâmetros para permitir a automação informar os dados de parcelamento no débito Banrisul.

## Versão 2.7.9.2
    Descrição: versão 2.7.9.1 + bugfix
    Data: 22/02/2024

### Correções e implementações
- Incremento do buffer de processamento das tabelas.

### Binários
- [dtefmobile-v2.7.9.2](https://grupolinx-my.sharepoint.com/:u:/g/personal/ped_payhub_tef_linx_com_br/Ef7Qh5TZjglEuKVKo7sCLE4BjEN8BJ3si9q_Q-PMBz6vvQ?e=CodfJO)

## Versão 2.7.9.1
    Descrição: versão 2.7.9 + bugfix
    Data: 07/02/2024

### Correções e implementações
- Correção de ocorrência de exception após carga de tabelas.

### Binários
- [dtefmobile-v2.7.9.1](https://grupolinx-my.sharepoint.com/:u:/g/personal/ped_payhub_tef_linx_com_br/EfVYvkEbEhBPsPgGsjeBqYQBRYIWpN1jW7hDdK2kgOHRmA?e=4I9Wpw)

## Versão 2.7.9
    Descrição: versão 2.7.8 + features
    Data: 22/01/2024

### Correções e implementações
- Incluído suporte ao totem Samsung Khadas.
- Incluído suporte ao terminal Adyen.
- Alteração para compatibilizar a resposta dos logs (comando 45) com a versão do GatewayPOS
Verti.

### Binários
- [dtefmobile-v2.7.9](https://grupolinx-my.sharepoint.com/:u:/g/personal/ped_payhub_tef_linx_com_br/EWgGlHn9FklDlZ2smVed-IQBVF-uCKfbznVvwVRr5OmeXA?e=rCzECs)

## Versão 2.7.8.2
    Descrição: versão 2.7.8.1 + bugfix
    Data: 21/03/2024

### Correções e implementações
- Alteração para não retornar o campo NSU Rede Adicional no campo NSU Rede.

## Versão 2.7.8.1
    Descrição: versão 2.7.8 + bugfix
    Data: 07/02/2024

### Correções e implementações
- Correção de ocorrência de exception após carga de tabelas.

## Versão 2.7.8
    Descrição: versão 2.7.7 + features
    Data: 22/12/2023

### Correções e implementações
- Incluído suporte ao totem GS300.
- Incluído comando para reset da USB em caso de falha de comunicação com o pinpad USB.

## Versão 2.7.7.2
    Descrição: versão 2.7.7.1 + features
    Data: 11/03/2024

### Correções e implementações
- Implementação para compatibilidade com o GPOS760.
- Incluído suporte a mais de 99 registros por adquirente na carga da tabela (convertido o formato do
campo de índice da tabela para alfanumérico).

## Versão 2.7.7.1
    Descrição: versão 2.7.7 + bugfixes
    Data: 14/02/2024

### Correções e implementações
- Correção no fluxo de frota (relacionado ao tipoAbastecimento e valorTotal).
- Correção de ocorrência de exception após carga de tabelas.

## Versão 2.7.7
    Descrição: versão 2.7.6.1 + bugfixes na 2.7.5.x
    Data: 22/12/2023

### Correções e implementações
- Correções de roteamento bin (já certificadas na homologação da versão 2.7.5.3).
- Implementação para retornar o campo NSU REDE adicional (com até 32 dígitos para suportar o NSU REDE da STONE).

### Binários
- [dtefmobile-v2.7.7](https://grupolinx-my.sharepoint.com/:f:/g/personal/ped_payhub_tef_linx_com_br/Eimof-rBDapLqPYPi5-qrqIBnhJtq46lObYIbtJB9rUe2w?e=qVhKb8)

## Versão 2.7.6.1
    Descrição: versão 2.7.6 + bugfix
    Data: 05/12/2023

### Correções e implementações
- Correção na identificação do tamanho das tabelas de roteamento.

## Versão 2.7.6
    Descrição: versão 2.7.5 + certificação com a Rede
    Data: 29/11/2023

### Correções e implementações
- Inclusão da especificação L0701 da Rede.

## Versão 2.7.5.3
    Descrição: versão 2.7.5.2 + features
    Data: 21/12/2023

### Correções e implementações
- Alteração para priorizar o roteamento bin em relação ao contexto.
- Alteração para priorizar o contexto específico (diferente de zero).

## Versão 2.7.5.2
    Descrição: versão 2.7.5.1 + bugfix
    Data: 19/12/2023

### Correções e implementações
- Correção no processamento de roteamento bin.

## Versão 2.7.5.1
    Descrição: versão 2.7.5 + bugfix
    Data: 05/12/2023

### Correções e implementações
- Correção na identificação do tamanho das tabelas de roteamento.

## Versão 2.7.5
    Descrição: versão 2.7.4 + 2.7.3.4 + features
    Data: 20/11/2023

### Correções e implementações
- Inclusão de transação com cartão pré-pago.
- Inclusão de parâmetro para informar o produto desejado, possibilitando pagamento em carnê.

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
- [dtefmobile-v2.7.3.2](https://grupolinx-my.sharepoint.com/:u:/g/personal/ped_payhub_tef_linx_com_br/EZA4OJLz855DuN0Mz8KE05sBoXMDW7bxugB7LbJESpAwPQ?e=UOrG3e)

## Versão 2.7.3.1
    Descrição: versão 2.7.3 + MP15
    Data: 11/08/2023

### Correções e implementações
- Correções na PPComp referente à comunicação com pinpad bluetooth (certificação Cielo).

## Versão  2.7.3
    Descrição: versão 2.7.2.1 + Banrisul
    Data: 27/07/2023

### Correções e implementações
- Criptografia dos dados sensíveis com a chave do Banrisul.
- Implementação dos comandos 91 e 92 para viabilizar a criptografia em transação digitada.

## Versão 2.7.2.1
    Descrição: versão 2.7.2 + bugfix
    Data: 24/07/2023

### Correções e implementações
- Correção no processamento do retorno das tags emv na PP_GOONCHIP - ABECS.

## Versão 2.7.2
    Descrição: versão 2.7.1 + features
    Data: 20/07/2023

### Correções e implementações
- Implementação dos parâmetros frota via chamada de função.
- Transação especial para obter identificação do perfil do mapa de chaves.
- Correção da impressão para o P2 com perfil “parceiros”.

## Versão 2.7.1.1
    Descrição: versão 2.7.1 + bugfix
    Data: 24/07/2023

### Correções e implementações
- Correção no processamento do retorno das tags emv na PP_GOONCHIP - ABECS.

## Versão 2.7.1
    Descrição: versão 2.7.0 + certificação MP15 (Cielo)
    Data: 11/07/2023

### Correções e implementações
- Implementação do protocolo ABECS para suportar o campo SPE_TRNTYPE necessário para o 
  caso de teste MCD01.02.02. 

  - Obs.: a implementação do protocolo ABECS foi realizada na comunicação com pinpads 
  bluetooth. Para os demais dispositivos é utilizado a BC do fabricante.

## Versão 2.7.0
    Descrição: versão 2.6.5 + features
    Data: 05/05/2023

### Correções e implementações
- Implementação para suportar transações com a ticket log.
- Identificação da posição em que a chave da Stone está gravada a fim de determinar o perfil do mapa de chaves (padrão ou parceiros).
- Seleção automática do mapeamento das chaves de acordo com o perfil identificado.
- Reconhecimento do pinpad bluetooth MP-15.
- Implementação para permitir a leitura do KSN através da transação especial.

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

## Versão 2.6.6
    Descrição: versão 2.6.5 + features
    Observação: Em certificação Banrisul
    Data: 02/06/2023

### Correções e implementações
- Em certificação com o Banrisul.
- Customizações necessárias para o Sunmi K2.

## Versão 2.6.5-build-2306081649
    Descrição: versão 2.6.5 + features
    Observação: Build 2306081649
    Data: 08/06/2023

### Correções e implementações
- Incluído perfil “parceiros-stone” na inicialização do SmartPrinterService.

## Versão 2.6.5
    Descrição: versão 2.6.4 + features
    Data: 09/03/2023

### Correções e implementações
- Certificada pela Cielo.
- Inclusão do mapeamento das chaves da Cielo.

## Versão 2.6.4
    Descrição: versão 2.6.3 + features
    Data: 11/08/2022 

### Correções e implementações
- Certificada pela SafraPay.
- Inclusão do mapeamento das chaves da Safra.