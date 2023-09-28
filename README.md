# script_netcat_chat

Neste trabalho foi utilizado três comando do Nmap/netcat para a criação de um chat lan.
O chat em uma rede lan é um éco entre a porta de uma mesma rede, ou seja, utilizando uma porta qual quer, exemplo 8080, pode-se mandar mensagens entre terminais presentes dentro de uma mesma rede lan.

# scripts:
Foram utilizados os scripts:
<ncat -v> para identificar a versão do Nmap instalada no PC.
<ncat -l <any_port>> para selecionar uma porta na rede.
<ncat -C localhost <choosen_port>> Para identificar a porta selecionada em um outro terminar na mesma rede lan.
