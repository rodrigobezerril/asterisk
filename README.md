1 - ASTERISK -RX
asterisk -rx "comando"
asterisk: executa o programa Asterisk.
-r: conecta ao console (CLI) de uma instância do Asterisk que já está em execução.
-x: executa o comando informado e retorna ao terminal Linux.
"comando": comando que será executado dentro do Asterisk.


2 - Listar os endpoints PJSIP
asterisk -rx "pjsip show endpoints"

3 - Listar os contatos registrados
asterisk -rx "pjsip show contacts"

4 - Consultar um endpoint específico
asterisk -rx "pjsip show endpoint 1001"
