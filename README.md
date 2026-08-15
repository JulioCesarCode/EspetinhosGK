# Espetinhos GK — publicação no GitHub Pages

Esta pasta contém uma versão **100% estática** e pronta para publicação do sistema Espetinhos GK. Não é necessário instalar Node.js, configurar banco de dados ou criar backend para usar este pacote.

## Como publicar no GitHub

Crie um repositório novo no GitHub, por exemplo `espetinhos-gk`. Em seguida, abra a pasta deste pacote, envie **todos os arquivos e pastas que estão aqui dentro** para a raiz do repositório e confirme o envio.

No repositório, acesse **Settings → Pages**. Em “Build and deployment”, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/(root)`, depois clique em **Save**. O GitHub mostrará o endereço público assim que terminar a publicação.

## Como usar sem internet

Abra o site ao menos uma vez enquanto houver conexão. A partir disso, o navegador guarda a aplicação e os dados locais do aparelho. Para preservar pedidos e histórico ao trocar de celular ou navegador, entre em **Ajustes → Baixar backup** e guarde o arquivo JSON.

## Observação importante

Os pedidos ficam salvos apenas no navegador que os criou. Dois celulares diferentes não compartilham os pedidos automaticamente, pois esta versão foi feita para ser totalmente offline e sem servidor.
