# TCP/IP

## O que é
TCP/IP vai garantir uma comunicação confiavel

## Oque eu entendi sobre
IP vai garantir que o arquivo chegue para o dispositivo certo e o TCP vai garantir que os dados seja enviado corretamente separando em pacotes menores e colocando numeros sequenciais, caso o cliente não recebe 1 pacote ele avisa ta faltando pacote 2 não chegou, fazendo que tudo chegue. E tem uma comunicação **Handshake** Que ele vai fazer um aperto de tres vias, Cliente pergunta com SYN para o servidor querendo saber se ele está lá logo após servidor responde com SYN/ACK para o cliente, Então cliente confirma com ACK para dar inicio, apos todos recebimentos dos dados a conexão precisa se fechar, então cliente manda um FIN para o servidor, então o servidor responde com um FIN/ACK confirma o fechamento para o cliente, e o cliente fecha a conexão com uma resposta de ACK para o servidor