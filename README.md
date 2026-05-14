# 🏎️ Projeto Expositor de Carros (Básico) - VR

Este projeto consiste em uma experiência de Realidade Virtual (VR) desenvolvida no Unity, focada em um ambiente de showroom automotivo (expositor de carros de luxo). Criado com base nas aulas de **Metaverso**, o projeto utiliza o Meta SDK para fornecer interações imersivas, destacando a mecânica de agarrar objetos (*Grab Interaction*) em um espaço virtual realista.

**Autor:** Luciano Damião de Brito  
**Trilha:** 1  

---

## 🛠️ Tecnologias e Versões

* **Engine:** Unity 6000.3.13f1
* **SDK:** Meta XR All-in-One SDK
* **Plataforma Alvo:** Android (Oculus Quest 2 / 3)

---

## 🚀 Configuração do Ambiente

Para garantir que o projeto funcione corretamente na sua máquina, siga as etapas de configuração abaixo:

### 1. Alteração da Plataforma de Build
Como o foco do projeto são os dispositivos Meta Quest, é necessário alterar a plataforma de compilação:

1. Vá em `File > Build Settings`.
2. Selecione `Android` na lista de plataformas.
3. Clique em `Switch Platform`.
4. Certifique-se de que o **Texture Compression** está definido como `ASTC`.

### 2. Instalação do Meta SDK
O projeto utiliza as ferramentas oficiais da Meta para rastreio e interação. Para instalar:

1. Vá em `Window > Package Manager`.
2. Clique no ícone de `+` e selecione `Add package from git URL` ou procure por **Meta XR All-in-One SDK** na Unity Asset Store e importe para o projeto.
3. Garanta que o **Oculus XR Plugin** esteja habilitado acessando `Edit > Project Settings > XR Plug-in Management`.

---

## 🏢 Cenário e Elementos do Projeto

O ambiente virtual foi montado para simular uma concessionária de alto padrão. O cenário (cena) é composto pelos seguintes elementos:

* 🚗 **3 Expositores** contendo modelos de carros de luxo.
* 🔑 **3 Chaves** posicionadas na frente de cada carro, configuradas com **Grab Interaction** (permitindo que o jogador interaja e pegue as chaves com as mãos/controles).
* 🪴 **3 Plantas decorativas** para humanizar o ambiente.
* 🖥️ **1 Mesa de escritório** com suas respectivas cadeiras.
* 🛋️ **1 Conjunto de sofá** compondo uma área de descanso/espera.
* 🧱 **Estrutura Física:** Paredes delimitadoras, Chão (*Floor*) e Céu (*Skybox*).

---

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto foi colocar em prática a confecção de um expositor interativo utilizando a tecnologia de Realidade Virtual. O foco do aprendizado técnico se deu na implementação da interação de *Grab* (agarrar), essencial para a imersão em VR, permitindo que o usuário interaja fisicamente com as chaves dos veículos no expositor.

---

## 🚧 Desafios e Aprendizados

Durante a fase de desenvolvimento e testes, o principal desafio superado foi a **utilização do simulador do Unity (XR Device Simulator)**. Que não funcionou de maneira adequada, prejudicando a experiência de aprendizado.

---

## 📹 Demonstração em Vídeo

Confira o resultado final e o projeto em execução através do link abaixo:

🔗 **[Assistir demonstração no YouTube](https://youtu.be/G7nY4UliH18)**
