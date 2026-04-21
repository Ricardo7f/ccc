# 📱 Quiz App - Android WebView

App Android que abre o sistema Quiz do servidor local.

**URL configurada:** `http://192.168.1.17:8766/`  
*(pode ser alterada dentro do próprio app na tela de erro → "Alterar URL")*

---

## 🚀 Como gerar o APK

### Opção 1 — GitHub Actions (sem instalar nada no PC)

1. Crie uma conta em [github.com](https://github.com) se não tiver
2. Crie um repositório novo (pode ser privado)
3. Faça upload de todos esses arquivos para o repositório
4. Vá em **Actions** → o build roda automaticamente
5. Quando terminar, clique no build → **Artifacts** → baixe `quiz-app-debug`
6. Extraia o `.apk` e instale no Android

### Opção 2 — Android Studio (PC)

1. Baixe o [Android Studio](https://developer.android.com/studio)
2. Abra a pasta `QuizApp` como projeto
3. Menu **Build** → **Build Bundle(s) / APK(s)** → **Build APK(s)**
4. O APK estará em `app/build/outputs/apk/debug/app-debug.apk`

---

## 📲 Como instalar o APK no celular

1. No Android, vá em **Configurações → Segurança → Instalar apps desconhecidos** e habilite para o seu gerenciador de arquivos
2. Transfira o `.apk` para o celular (WhatsApp, cabo USB, Google Drive, etc.)
3. Abra o arquivo e instale

---

## ⚙️ Alterar o IP do servidor

Se o IP do servidor mudar, dentro do app na tela de erro há um botão **"⚙️ Alterar URL"** para digitar o novo endereço. A URL fica salva automaticamente.

---

## 📋 Recursos do app

- ✅ Abre o Quiz em tela cheia
- ✅ Barra de progresso de carregamento
- ✅ Tela de erro amigável se o servidor não for encontrado
- ✅ Botão de tentar novamente
- ✅ Configuração de URL salva no app
- ✅ Botão Voltar navega pelo histórico do WebView
- ✅ Tema escuro combinando com o Quiz
