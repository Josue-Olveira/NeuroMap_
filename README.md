# NeuroMap 🧩📍

> **Conectando pessoas a lugares acessíveis.**
> *Tecnologia social para inclusão e previsibilidade sensorial.*

![Badge Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?style=flat&logo=flutter)
![Badge Dart](https://img.shields.io/badge/Dart-3.0-0175C2?style=flat&logo=dart)
![Badge Firebase](https://img.shields.io/badge/Firebase-Serverless-FFCA28?style=flat&logo=firebase)
![Badge License](https://img.shields.io/badge/License-MIT-green)

## 📖 Sobre o Projeto

O **NeuroMap** é uma aplicação móvel multiplataforma desenvolvida como Trabalho de Conclusão de Curso (TCC) em Ciência da Computação no Centro Universitário do Distrito Federal (UDF).

O objetivo principal é mitigar as barreiras invisíveis enfrentadas por pessoas com **Transtorno do Espectro Autista (TEA)**. Através de um sistema colaborativo (*crowdsourcing*), o aplicativo mapeia critérios de **acessibilidade sensorial** (nível de ruído, iluminação, zonas de descompressão), oferecendo a previsibilidade necessária para que famílias atípicas possam planejar suas atividades sociais com segurança e autonomia.

---

## 📱 Funcionalidades Principais

* **Autenticação Segura:** Login social (Google) e via e-mail, com gestão de identidade via Firebase Auth.
* **Mapa Interativo:** Visualização de locais acessíveis utilizando a API do Google Maps com marcadores personalizados.
* **Filtros Sensoriais:** Busca refinada por critérios como "Baixo Ruído", "Luz Adaptada" e "Atendimento Inclusivo".
* **Antecipação Visual:** Galeria de fotos focada em mostrar o ambiente para redução de ansiedade.
* **Avaliação Assistida por IA:** Integração com Inteligência Artificial Generativa para auxiliar usuários na redação de feedbacks sobre os locais.
* **Neuro Chat:** Assistente virtual integrado para suporte e recomendação de locais via linguagem natural.
* **Privacidade (LGPD):** Controle total dos dados pelo usuário, incluindo funcionalidade de "Excluir Conta".

---

## 📸 Screenshots

| Login & Acesso | Mapa & Descoberta | Detalhes do Local | Avaliação com IA |
|:---:|:---:|:---:|:---:|
| <img src="assets/screenshots/login.png" width="200"> | <img src="assets/screenshots/mapa.png" width="200"> | <img src="assets/screenshots/detalhes.png" width="200"> | <img src="assets/screenshots/avaliacao.png" width="200"> |

---

## 🛠️ Tecnologias Utilizadas

A arquitetura do projeto segue o padrão **Serverless**, priorizando escalabilidade e performance.

* **Front-end:** [Flutter](https://flutter.dev/) (Framework UI) & [Dart](https://dart.dev/) (Linguagem).
* **Back-end:** [Google Firebase](https://firebase.google.com/).
    * **Firestore:** Banco de dados NoSQL para sincronização em tempo real.
    * **Authentication:** Gestão de usuários.
    * **Storage:** Armazenamento de imagens dos locais.
    * **Cloud Messaging:** Notificações Push.
* **APIs Externas:**
    * **Google Maps Platform:** Geolocalização e Rotas.
    * **OpenAI API / Gemini:** Processamento de linguagem natural para o Chatbot e avaliações.
* **Gerenciamento de Estado:** Provider / Riverpod.

---

## 🚀 Como Executar o Projeto

Para rodar o projeto localmente, você precisará do [Flutter SDK](https://docs.flutter.dev/get-started/install) instalado.

### Pré-requisitos
* Flutter SDK (v3.0 ou superior)
* Dart SDK
* Android Studio ou VS Code (com extensões Flutter/Dart)

### Passos para Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/neuromap.git](https://github.com/seu-usuario/neuromap.git)
    cd neuromap
    ```

2.  **Instale as dependências:**
    ```bash
    flutter pub get
    ```

3.  **Configuração do Firebase:**
    * Este projeto utiliza o `flutterfire_cli`. Certifique-se de ter o arquivo `firebase_options.dart` configurado na pasta `lib/`.
    * Devido a questões de segurança, as chaves de API (Google Maps e Firebase) não estão incluídas no repositório público. Crie um arquivo `.env` na raiz com suas credenciais.

4.  **Execute o App:**
    ```bash
    flutter run
    ```

---

## 📂 Estrutura de Pastas

A organização do código segue os princípios de *Clean Architecture* para garantir manutenibilidade:











## 📲 Download & Demonstração (APK)

Para facilitar a avaliação e testes em dispositivos físicos, disponibilizamos a versão compilada mais recente do aplicativo para Android.

> **Nota:** Como este é um aplicativo acadêmico e não está na Play Store, você pode precisar habilitar a instalação de "Fontes Desconhecidas" nas configurações do seu dispositivo.

| Versão | Build | Download Direto |
|:---:|:---:|:---:|
| **v1.2 (Estável)** | Release | [![Download APK](https://img.shields.io/badge/Download-APK_Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://drive.google.com/file/d/14Qomd5aYLd4NK3-K_sa-UGm1FJ9tl3XH/view?usp=sharing)

### 📸 Escaneie para Baixar

<img src="https://github.com/Josue-Olveira/NeuroMap_/blob/main/Untitled.png?raw=true">

<img src="assets/qrcode-apk.png" width="150">

---
