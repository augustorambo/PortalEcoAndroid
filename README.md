# Portal ECO — projeto Android

Este projeto cria um aplicativo Android simples que abre o portal ECOpel, SAAEco e ECOcar publicado no Google Apps Script.

## O que já está configurado
- Endereço `/exec` informado pelo usuário
- WebView em tela cheia
- JavaScript e armazenamento local habilitados (necessários ao HTML Service)
- Cookies habilitados para o fluxo de autenticação Google
- Navegação de retorno pelo botão Voltar
- Ícone simples do Portal ECO

## Gerar o APK no Android Studio
1. Instale o Android Studio atualizado.
2. Abra a pasta `PortalEcoAndroid` no Android Studio.
3. Aguarde a sincronização do Gradle e instale o Android SDK 35 quando solicitado.
4. Selecione **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
5. O APK de depuração ficará em `app/build/outputs/apk/debug/app-debug.apk`.

Para distribuir fora do teste, use **Build > Generate Signed Bundle / APK** e crie uma chave de assinatura.

## Atenção sobre o acesso ao Apps Script
O endereço de implantação precisa estar publicado para acesso dos usuários pretendidos. Se o Google exigir login, o usuário deverá autenticar-se; o acesso também depende das opções de implantação e das permissões da planilha. O link fornecido redirecionou para a página de login quando foi verificado nesta sessão, então confirme no navegador do celular se o app abre sem bloqueio.

## Identificação
- Nome: Portal ECO
- Application ID: `br.com.portaleco.app`
- Versão: 1.0.0
