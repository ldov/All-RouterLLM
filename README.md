# ⚡ AI-RouterLLM

> **Um servidor proxy inteligente que roda silenciosamente em segundo plano, centralizando o gerenciamento de suas chaves de API e permitindo que você crie endpoints personalizados para integrar qualquer ferramenta de IA com segurança e eficiência.**

---

## 📝 Descrição do Projeto

O **AI-RouterLLM** é um gerenciador local de credenciais e um servidor proxy unificado para modelos de linguagem (LLMs). Ele foi projetado para resolver a complexidade de lidar com múltiplos provedores diretos e hubs externos (como OpenRouter, Groq e Ofox). 

Através de uma interface nativa leve que se minimiza para a barra de tarefas do Windows (System Tray), o sistema permite cadastrar chaves em um arquivo JSON local por meio de um CRUD completo. Ele expõe um endpoint local padronizado no protocolo da OpenAI, traduzindo as requisições em tempo real e permitindo ativar ou desativar rotas sob demanda para que outras ferramentas consumam suas IAs sem expor suas chaves originais.

---

## 🛠️ Tecnologias Utilizadas

A arquitetura do projeto foi desenhada para garantir consumo mínimo de memória e execução em segundo plano no Windows:

* **Gerenciamento:** Configurado e estruturado de ponta a ponta utilizando **uv** para máxima performance no ambiente virtual.
* **Interface Gráfica (GUI):** Construída em **PyQt6**, utilizando o componente nativo `QSystemTrayIcon` para controle completo a partir do relógio do Windows.
* **Servidor Proxy:** Desenvolvido em Python com **FastAPI** e **LiteLLM**, responsável por escutar as requisições de forma assíncrona e injetar as credenciais corretas automaticamente.

---

## 🚀 Como Executar o App Localmente

Por ser uma aplicação focada na experiência local, ela pode ser instalada diretamente no seu computador para uso imediato. Baixe a versão correspondente ao seu sistema operacional através dos links oficiais abaixo:

Windows: 📥 Baixar executável para Windows (x64)

Linux: 📥 Baixar binário para Linux (x64)

Após o download, basta executar o arquivo para iniciar o aplicativo.

---
<p align="center">Developed by <b>Ldov - AI & IT Solutions</b> </p>
