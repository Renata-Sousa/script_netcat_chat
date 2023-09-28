# script_netcat_chat

Neste trabalho foi utilizado três comando do Nmap/netcat para a criação de um chat lan.
O chat em uma rede lan é um éco entre a porta de uma mesma rede, ou seja, utilizando uma porta qualquer, exemplo 8080, pode-se mandar mensagens entre terminais presentes dentro de uma mesma rede lan.

# scripts:
Foram utilizados os scripts:
<ncat -v> para identificar a versão do Nmap instalada no PC.
<ncat -l 3000> para selecionar uma porta na rede, nesse caso a porta 3000.
<ncat -C localhost 3000> Para identificar a porta selecionada em um outro terminar na mesma rede lan.
