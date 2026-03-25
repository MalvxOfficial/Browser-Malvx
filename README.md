# 🚀 Chimas Browser

**Chimas Browser** é um navegador Android leve, focado em personalização e controle de privacidade, desenvolvido inteiramente no ambiente **AIDE Pro**. Ele oferece uma experiência de navegação em **Pure Black (AMOLED)** e ferramentas avançadas para desenvolvedores e entusiastas de modificação de sistema.

---

## ✨ Funcionalidades Principais

* 🌑 **Interface Ultra-Dark:** Design focado em economia de bateria e conforto visual com o tema `HOLO_DARK`.
* 🕵️ **User Agent Switcher:** Alterne instantaneamente entre perfis de **PC (Windows/Linux/macOS)**, **Mobile (iOS/Android)** e **Consoles (Xbox/PS5/Switch)**.
* 🔍 **Omnibox Inteligente:** Barra de busca que identifica automaticamente se você digitou uma URL ou um termo de pesquisa para o Google.
* 🛠️ **Controle de WebView:**
    * **Botão Pause/Play:** Interrompa a execução de JavaScript e timers da página para economizar recursos.
    * **Ajuste de Fonte (f+/f-):** Aumente ou diminua o tamanho do texto do site em tempo real.
* 📥 **Interceptação de Download:** Identifica tentativas de download e fornece a URL direta para cópia, evitando downloads automáticos indesejados.
* 🔄 **Navegação Fluida:** Botões dedicados de Voltar, Avançar e Recarregar integrados na barra de ferramentas.

---

## 📸 Demonstração da Interface

A interface foi projetada para ser acessível, com botões de tamanho ampliado (**48dp**) para facilitar o toque em qualquer dispositivo.

> **Status do Projeto:** Finalizado e estável para uso em dispositivos com Android 5.0+.

---

## 🛠️ Detalhes Técnicos

O projeto utiliza as seguintes tecnologias e permissões:

* **Linguagem:** Java / Android SDK.
* **Engine:** `android.webkit.WebView`.
* **Permissões:** * `android.permission.INTERNET`: Necessária para carregar páginas web.
* **Layout:** XML com `LinearLayout` dinâmico e otimização para teclado (adjustPan).

---

## 🚀 Como Compilar

Se você deseja clonar e testar este projeto:

1.  Abra o **AIDE Pro** no seu Android.
2.  Crie um novo projeto Android ou importe esta pasta.
3.  Certifique-se de que o `package` no `AndroidManifest.xml` corresponde à sua estrutura de pastas (`com.browsermalvx`).
4.  Clique em **Run** e instale o APK.

---

## 🤝 Créditos

Desenvolvido por **(ChimasAlice)**.
Baseado em Gemini e humanos.

---

**English summary:**
I created a comprehensive README.md for your GitHub repository. It highlights key features like the UA Switcher, Ultra-Dark UI, Font controls, and the Download Intercept logic, along with technical details for anyone who wants to compile the project.

**Legenda:**
Criei um README.md completo para o seu repositório no GitHub. Ele destaca recursos principais como o Troca de UA, Interface Ultra-Dark, controles de fonte e a lógica de interceptação de download, além de detalhes técnicos para quem quiser compilar o projeto.


***Todo o projeto foi desenvolvido por brasileiros, mas aceitamos voluntários de outros países para traduzir e modificar nosso app!***

***The entire project was developed by Brazilians, but we welcome international volunteers to help translate and modify our app!***
