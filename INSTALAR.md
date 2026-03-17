# 📱 CuidaCare — Guia de Instalação como App

## O que é o PWA?
O CuidaCare pode ser instalado no celular como um aplicativo de verdade,
sem precisar de App Store ou Play Store. Funciona offline depois de carregado.

---

## OPÇÃO 1 — Hospedar no Netlify (Grátis, Recomendado)

### Passo a passo:

1. Acesse https://netlify.com e crie uma conta gratuita (pode usar Google)

2. No painel do Netlify, clique em **"Add new site"** → **"Deploy manually"**

3. Arraste a pasta **cuidacare-pwa** inteira para a área indicada

4. O Netlify vai gerar um link tipo: https://cuidacare-abc123.netlify.app

5. Pronto! Compartilhe esse link com as cuidadoras

### Para instalar no celular depois de hospedar:

**Android (Chrome):**
- Abra o link no Chrome
- Toque no menu (⋮) no canto superior direito
- Toque em "Adicionar à tela inicial"
- Confirme — aparece o ícone do CuidaCare na tela

**iPhone (Safari):**
- Abra o link no Safari (não Chrome!)
- Toque no botão compartilhar (quadrado com seta ↑)
- Role para baixo e toque "Adicionar à Tela de Início"
- Confirme — aparece o ícone na tela

---

## OPÇÃO 2 — Hospedar no GitHub Pages (Grátis)

1. Crie conta em https://github.com

2. Clique em "New repository", nomeie "cuidacare", marque como Public

3. Faça upload de todos os arquivos da pasta cuidacare-pwa

4. Vá em Settings → Pages → Source: "main" branch → Save

5. Link será: https://SEU-USUARIO.github.io/cuidacare

---

## OPÇÃO 3 — Usar só o arquivo HTML (sem instalar)

Se quiser usar sem hospedar, basta abrir o arquivo **cuidacare-v2.html**
no navegador do celular. Os dados ficam salvos no celular.

Não terá ícone na tela inicial, mas funciona normalmente.

---

## ⚠️ Importante sobre os dados

- Os dados ficam salvos **no próprio celular** (localStorage)
- Cada celular tem seus próprios dados — não sincroniza automaticamente
- Para compartilhar entre celulares, use os relatórios via WhatsApp
- Faça backups periódicos exportando os relatórios

---

## 📋 Arquivos da pasta cuidacare-pwa

```
cuidacare-pwa/
├── index.html          ← App principal
├── manifest.json       ← Configuração do PWA
├── sw.js               ← Service Worker (funciona offline)
└── icons/
    ├── icon-192.png    ← Ícone Android
    ├── icon-512.png    ← Ícone Android grande
    └── apple-touch-icon.png  ← Ícone iPhone
```

---

Dúvidas? Peça ajuda ao Claude em claude.ai
