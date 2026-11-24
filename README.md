# Reinstalacao limpa do OneDrive

## Motivo

Este procedimento serve para remover a instalacao atual do Microsoft OneDrive e instalar uma versao nova. Pode ajudar quando o aplicativo apresenta bugs persistentes, nao inicia, falha ao sincronizar ou parece estar com a instalacao corrompida.

## Quando usar

Use como ultima tentativa, depois de reiniciar o computador e testar as solucoes mais simples. A reinstalacao limpa pode apagar configuracoes locais do aplicativo.

## Antes de comecar

- Confirme que os arquivos importantes estao sincronizados ou que voce tem uma copia de seguranca.
- Feche os arquivos que estiverem sendo sincronizados.
- Tenha acesso a sua conta Microsoft para entrar novamente depois da instalacao.
- O script de limpeza exige o Windows PowerShell 5.1 aberto como administrador.

## Procedimento

1. Abra `APAGAR REGISTROS DE VERSÕES ANTIGAS - ONE DRIVE.txt` e execute somente a secao de remocao no Windows PowerShell como administrador. Nao execute o arquivo inteiro de uma vez.
2. Reinicie o computador quando a limpeza terminar.
3. Depois de reiniciar, execute as secoes de download e validacao. O script cancela a instalacao se a assinatura nao estiver valida ou o certificado nao pertencer a Microsoft.
4. Execute a secao de instalacao e entre novamente na sua conta Microsoft.
5. Confira se a sincronizacao voltou a funcionar e se as pastas esperadas estao configuradas.

## Observacao

O script remove componentes e configuracoes locais do OneDrive. Ele nao foi feito para apagar os arquivos da pasta de sincronizacao, mas mantenha uma copia de seguranca e confira os arquivos antes de prosseguir.
