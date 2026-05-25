SGM App Android

Este projeto transforma https://sgm-app.lovable.app/ em app Android WebView.

O app já inclui:
- Permissão de internet
- Permissão de localização precisa e aproximada
- Pedido de localização ao abrir o app
- WebView com JavaScript, DOM Storage e geolocation ativados

Como gerar o APK:
1. Instale o Android Studio.
2. Abra a pasta SGMAppAndroid no Android Studio.
3. Aguarde o Gradle sincronizar.
4. Vá em Build > Build Bundle(s) / APK(s) > Build APK(s).
5. O APK será gerado em app/build/outputs/apk/debug/app-debug.apk.

Para publicar na Play Store, gere uma versão assinada em:
Build > Generate Signed Bundle / APK.
