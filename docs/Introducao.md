# Introdução

Camada de registro, composta de:

* Método para processar mensagem síncrona: SyncMessage

## SyncMessage

Método de mensagem síncrona:

* A transação é síncrona, ou seja: requisição recebida do sistema origem é encaminhada ao sistema destino imediatamente e a resposta é aguardada para imediata devolução a origem.
* As transações são gravadas em tabelas e detalhes das transações serão gravadas em log.
* Possibilita monitoramento, telemetria e auditoria.
* Possibilita diagnóstico e troubleshooting.