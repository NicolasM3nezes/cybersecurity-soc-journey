# Modelo OSI

## O que é
Ele é a estrutura que fornece como receberão, enviarão e interpretarão os dados

## Camada 1 - Física
Está camada ela fica a parte do hardware onde fica conectado os cabo ethernet

## Camada 2 - Enlace de Dados
Essa camada faz as transferência de dados em grupos ou quadros entre os dispositivos da mesma rede

## Camada 3 - Network
Essa camada ela vê por onde os dados vao percorrer fazendo as pergunta, qual o caminho mais confiavél, qual e o caminho mais curto, qual tem a conexão mais rápida

## Camada 4 - Transport
Esssa á camada mais vital para transmissão de dados que tem dois tipos de protocolo

**TCP:** O protocolo TCP ele vai garantir total recebimento dos dados completo, usando uma conexão direta a outra dispositivo, e isso pode fazer que os dados cheguem com mais lentidão, muito usado para envio de arquivos, email e navegação na internet.

**UDP:** O protocolo UDP não tem muitos recursos, qualquer dados enviados via UDP a mensagem é enviada para o computador caso chega faltando, é por que ele não cria um conexão estabelecida diretamente com o computador então pode ocorrer as perda de pacotes,
ele é bastante usado para Streaming.

## Camada 5 - Sessão
Uma sessão é criada assim que uma conexão é estabelecida, essa camada ela fica responsável também caso a conexão não esteja sendo usado ou sejá perdido ele tem alguns checkpoint fazendo que você precise apenas dos ultimos dados enviados.

## Camada 6