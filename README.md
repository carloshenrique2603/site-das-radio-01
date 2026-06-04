# 📻 Rádio Jovem FM — Site para GitHub Pages

## 📁 Arquivos incluídos
```
📂 jovemfm-site/
├── index.html       ← Site principal (player + programação + pedidos + sobre)
├── assets/
│   └── logo.png     ← Sua logo (já incluída!)
└── README.md        ← Este arquivo
```

---

## 🚀 PASSO A PASSO — Publicar no GitHub Pages

### 1. Crie uma conta no GitHub
👉 Acesse: **https://github.com** → clique em "Sign up" (é gratuito)

---

### 2. Crie um repositório
1. Após logar, clique no botão verde **"New"** (ou **"+"** no canto superior direito)
2. Em **"Repository name"**, digite: `radiojovemfm`
3. Deixe marcado como **Public**
4. Clique em **"Create repository"**

---

### 3. Faça upload dos arquivos
1. Na página do repositório que abriu, clique em **"uploading an existing file"**
2. **Arraste** a pasta `assets/` e o arquivo `index.html` para a área de upload
3. Em "Commit changes", escreva: `Primeiro upload do site da rádio`
4. Clique no botão verde **"Commit changes"**

---

### 4. Ative o GitHub Pages
1. No repositório, clique em **"Settings"** (engrenagem no topo)
2. No menu da esquerda, clique em **"Pages"**
3. Em **"Branch"**, selecione `main`
4. Deixe a pasta como `/ (root)`
5. Clique em **"Save"**
6. Aguarde **1 a 2 minutos** ⏳

---

### 5. Seu site está no ar! 🎉
```
https://SEU_USUARIO.github.io/radiojovemfm/
```
> Substitua SEU_USUARIO pelo seu nome de usuário do GitHub

---

## ⚙️ Personalizações Importantes

Abra o arquivo `index.html` e procure estas linhas (por volta da linha 5):

```javascript
const CONFIG = {
  streamURL:   "https://SEU_SERVIDOR:8000/stream",  // ← URL do seu stream de rádio
  whatsapp:    "5545999999999",                     // ← Seu número real
  stationName: "Rádio Jovem FM",
  cidade:      "Boa Vista da Aparecida – PR"
};
```

### O que editar:
| Campo | O que colocar |
|-------|--------------|
| `streamURL` | URL do seu servidor de stream (Icecast, Shoutcast, Zeno.fm, etc.) |
| `whatsapp` | Seu número com DDI+DDD, sem espaços ou traços. Ex: `5545999999999` |
| `stationName` | Nome da sua rádio |
| `cidade` | Sua cidade |

---

## 🎙️ Como Transmitir Sua Rádio Online

Para ter uma URL de stream, você precisa de um serviço. Opções gratuitas:

| Serviço | Site | Observação |
|---------|------|------------|
| **Zeno.fm** | zeno.fm | Mais fácil, totalmente gratuito |
| **Radio.co** | radio.co | Interface bonita |
| **AzuraCast** | azuracast.com | Open source, instala no servidor |
| **Icecast** | icecast.org | Clássico, técnico |

---

## 📱 Pedido de Música
O formulário de pedido de músicas envia automaticamente para o seu WhatsApp.  
Basta configurar o número no `CONFIG` acima.

---

## 🎨 Alterar Cores
No topo do `index.html`, dentro de `:root { }`:
```css
:root {
  --gold: #F5A623;    /* Dourado */
  --amber: #E8650A;   /* Laranja */
  --pink: #E91E8C;    /* Rosa/Pink */
  --cyan: #00D4FF;    /* Azul ciano */
}
```

---

## 📞 Precisa de ajuda?
Pergunte ao Claude em **claude.ai** — ele criou este site! 🤖✨
