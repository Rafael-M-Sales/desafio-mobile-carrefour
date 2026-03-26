# 📱 Desafio de Automação Mobile — Carrefour Banco

Projeto de automação de testes mobile utilizando **WebDriverIO** e **Appium**, desenvolvido para o desafio técnico do **Carrefour Banco**.

---

## 🏗️ Arquitetura do Projeto
O projeto utiliza o padrão **Page Object Model (POM)** para garantir a manutenibilidade e escalabilidade dos testes.

---

## 📂 Estrutura do Projeto
```
desafio-mobile-carrefour/
├── app/                  # Pasta para o arquivo APK
├── test/
│   ├── pageobjects/      # Page Objects (Screens)
│   └── specs/            # Arquivos de teste (10 cenários)
├── wdio.conf.js          # Configuração do WebdriverIO + Appium
└── package.json          # Gerenciamento de dependências
```

---

## 🛠 Tecnologias Utilizadas
- **Node.js** (v18+)
- **WebDriverIO** (v8+)
- **Appium** (v2+)
- **Allure Report** (Relatórios detalhados)

---

## ✅ Pré-requisitos
1. **Appium Server**: Instalado e rodando (`v2.0+`).
2. **Android SDK & Emulator**: Configurados e ativos.
3. **Java JDK**: 11 ou superior.
4. **APK do App**: [Download WebdriverIO Native Demo App](https://github.com/webdriverio/native-demo-app/releases) (Coloque em `mobile/app/wdio-demo.apk`).

---

## 🚀 Como Executar
1. **Instale as dependências:**
   ```bash
   npm install
   ```
2. **Execute os testes:**
   ```bash
   npm test
   ```
3. **Gere o relatório:**
   ```bash
   npm run report:generate
   npm run report:open
   ```

---

## 👤 Autor
**Rafael M. Sales**
