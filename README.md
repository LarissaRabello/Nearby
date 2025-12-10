# 🍔 Projeto Nearby

![Status](https://img.shields.io/badge/Status-Desafio%20Concluído-blue)
![Linguagem](https://img.shields.io/badge/Linguagem-Kotlin-7f52ff?style=flat-square&logo=kotlin)
![Framework UI](https://img.shields.io/badge/UI-Jetpack%20Compose-4285F4?style=flat-square&logo=android)
![Licença MIT](https://img.shields.io/badge/License-MIT-blue.svg)

## 💡 Sobre o Projeto

O **Nearby** é um aplicativo Android desenvolvido em Kotlin, focado em utilizar recursos modernos da plataforma para fornecer informações de localização e estabelecimentos próximos.

Este projeto foi criado como um **desafio de 3 dias** com o objetivo de praticar e aprofundar o uso do **Jetpack Compose** na criação de componentes de tela avançados.

### Principais Funcionalidades

* **Geolocalização:** Carregamento e interação com o **Google Maps** (via API) para exibir o mapa e pontos de interesse.
* **Integração de Dados:** Consumo de uma **base de dados externa** (API) para carregar informações detalhadas sobre os estabelecimentos.
* **Interação:** Implementação de leitura de **QR Codes** para comunicação estruturada com serviços de backend.

## 🚀 Tecnologias utilizadas e Arquitetura
<div style="display: inline_block"><br>
  <img align="center" alt="Kotlin" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kotlin/kotlin-plain.svg">
  <img align="center" alt="Android" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-plain.svg">
</div>

<br>

Este projeto utiliza o *stack* moderno do Android, com forte foco no desenvolvimento declarativo:


| Categoria | Tecnologia / Componente | Foco de Estudo |
| :--- | :--- | :--- |
| **Linguagem** | **Kotlin** | Linguagem oficial para desenvolvimento Android. |
| **Framework UI** | **Jetpack Compose** | Criação de interface de usuário declarativa. |
| **UI Avançada** | `Bottom Sheet` | Componente para exibição de conteúdo adicional de forma semi-modal. |
| **Arquitetura** | `ViewModel` | Gerenciamento de dados sensíveis ao ciclo de vida da UI. |
| **Navegação** | `Navigation in Compose` | Implementação de navegação entre diferentes telas (Composables). |
| **Recursos Externos** | Google Maps API | Carregamento de Mapas e funcionalidades de geolocalização. |
| **Comunicação** | Consumo de API's e Leitura de QR Codes | Integração eficiente e estruturada com serviços externos. |
| **Design** | Tematização e Design System | Aplicação de estilos globais e componentes reutilizáveis. |

## 📸 Screenshots
Os screenshots abaixo demonstram a interface do aplicativo, a integração com mapas e a exibição de componentes avançados do Compose:

<img src="https://github.com/user-attachments/assets/d42c465e-b658-4dbe-8576-f22527d3fd5a" width="130">
<img src="https://github.com/user-attachments/assets/3b7c61af-2a60-4ef9-9c8f-05823613b89b" width="130">
<img src="https://github.com/user-attachments/assets/c472408e-d925-4d2e-bb0c-a2566e22d694" width="130">
<img src="https://github.com/user-attachments/assets/0e5d4282-0917-484c-ae2e-011dbbbefe88" width="130">
<img src="https://github.com/user-attachments/assets/8082446e-c1be-470d-8955-ed9ff10de003" width="130">
<img src="https://github.com/user-attachments/assets/32c93548-ca6d-4a34-af1f-94dc74b031e5" width="130">

## 🏗️ Rodando o Projeto

Para executar o **Nearby** em seu ambiente local, você precisará ter o **Android Studio** instalado.

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/LarissaRabello/Nearby.git](https://github.com/LarissaRabello/Nearby.git)
    ```
2.  **Configuração da Chave API (Maps)**
   Para que o mapa funcione, você deve obter uma chave da **Google Maps API** e adicioná-la ao seu projeto no arquivo `AndroidManifest.xml`

    > **[Em breve, instruções específicas sobre onde colocar a chave API do Google Maps.]**

3.  **Abrir e Sincronizar:**
    Abra o projeto no Android Studio e aguarde a sincronização do Gradle.
4.  **Execute:**
    Rode a aplicação em um emulador ou dispositivo físico.

## 👩‍💻 Autor
Desenvolvido por **Larissa Rabello da Silva**.

* [LinkedIn](https://www.linkedin.com/in/larissa-rabello/)

## ⚖️ Licença
```
The MIT License (MIT)

Copyright (c) 2024 Larissa Rabello da Silva

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
