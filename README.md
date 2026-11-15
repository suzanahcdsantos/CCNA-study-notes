# CCNA-study-notes
Notas de estudo segmentado por tópicos do próprio blueprint da Cisco

#01- IP Fundamentals


#0x- Routing
- Como o roteador decide qual rota é protocolo de roteamento utilizar? 
Ele segue essas regras abaixo:
1° Pela rota mais específica, ou seja, ele começa olhando a máscara e escolher a maior, que será a mais específica. 
Ex: 
10.10.10.0/24 
10.10.10.10/32 
Uma máscara /32 é a mais específica, onde identifica o endereço do host em si


#ACLs
Temos 2 tipos de ACLs:
ACL Standard
Ela é representada pelas ACLs de 1 a 99 e de 1300 a 1999.
Ela só filtra o IP de origem e deve ser usada o mais perto do destino. 

ACL Extended
Seu range é de 100 a 199 e de 2000 a a 2699.
Ela filtra origem, destino, protocolos de camada 4(TCP e UDP) e demais protocolos de rede como IP, ICMP, número de porta