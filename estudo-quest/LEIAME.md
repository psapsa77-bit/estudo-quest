# 📚 Codex do Estudante — PWA

App de gamificação de estudos com notificações, conquistas e progressão de nível.

---

## 🚀 Como instalar no celular (GitHub Pages — gratuito)

### Passo 1 — Criar conta no GitHub
Acesse https://github.com e crie uma conta gratuita se ainda não tiver.

### Passo 2 — Criar repositório
1. Clique em **"New repository"**
2. Nome: `estudo-quest` (ou qualquer nome)
3. Marque **"Public"**
4. Clique em **"Create repository"**

### Passo 3 — Subir os arquivos
1. Na página do repositório, clique em **"uploading an existing file"**
2. Arraste todos os arquivos desta pasta:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - pasta `icons/` com `icon-192.png` e `icon-512.png`
3. Clique em **"Commit changes"**

### Passo 4 — Ativar GitHub Pages
1. Vá em **Settings** (no seu repositório)
2. Menu lateral: **Pages**
3. Em "Branch": selecione `main` e pasta `/root`
4. Clique em **Save**
5. Aguarde ~1 minuto. Seu app estará em:
   `https://SEU-USUARIO.github.io/estudo-quest/`

### Passo 5 — Instalar no Android
1. Abra o link acima no **Chrome do Android**
2. Aguarde carregar completamente
3. Chrome mostrará um banner: **"Adicionar à tela inicial"**
   - Se não aparecer: menu (⋮) → "Adicionar à tela inicial"
4. Confirme. O app aparece como ícone na tela inicial!

---

## 🔔 Notificações
- Dentro do app, vá até a aba de qualquer pilar
- Role até **"Lembretes Diários"**
- Ative o toggle e defina o horário
- Clique em "Testar Notificação" para confirmar

---

## 🔄 Como atualizar o app no futuro
Basta editar o `index.html` no GitHub (pelo navegador mesmo) e fazer commit.
O app atualiza automaticamente na próxima abertura.

Para versionar: altere `CACHE_NAME = 'estudo-quest-v2'` no `sw.js` a cada atualização.

---

## 📁 Estrutura dos arquivos
```
estudo-quest/
├── index.html      ← App completo
├── manifest.json   ← Configuração PWA
├── sw.js           ← Service Worker (offline + notificações)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```
