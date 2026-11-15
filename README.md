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

