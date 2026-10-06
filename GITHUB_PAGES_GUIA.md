# 📚 GUIA: PUBLICAR BIBLIOTECA DIGITAL NO GITHUB PAGES

## ✅ CHECKLIST (5 PASSOS)

### PASSO 1: Crie uma conta GitHub (se não tiver)
- Acesse: https://github.com
- Clique em "Sign up"
- Confirme seu email

---

### PASSO 2: Crie um repositório PÚBLICO
1. Após logado, clique no **+** (canto superior direito) → **New repository**
2. **Preencha:**
   - **Repository name:** `biblioteca-unifecaf` (pode ser qualquer nome)
   - **Description:** Biblioteca Digital UniFECAF - Projeto Design Web
   - **Marque:** ✅ **Public**
   - **Initialize with:** ✅ **Add a README file**
3. Clique em **Create repository**

---

### PASSO 3: Upload dos arquivos (2 opções)

#### OPÇÃO A: Via GitHub Web (mais fácil)
1. Entre no repositório que acabou de criar
2. Clique em **Add file** → **Upload files**
3. Selecione TODOS os arquivos:
   ```
   - index.html
   - css/style.css
   - (pode incluir assets/ com imagens depois)
   ```
4. Clique em **Commit changes**

#### OPÇÃO B: Via Git (linha de comando)
```bash
# Clone o repositório na sua máquina
git clone https://github.com/SEU_USUARIO/biblioteca-unifecaf.git

# Entre na pasta
cd biblioteca-unifecaf

# Copie os arquivos (index.html, css/style.css) para a pasta clonada

# Execute:
git add .
git commit -m "Adiciona Biblioteca Digital UniFECAF"
git push origin main
```

---

### PASSO 4: Ative GitHub Pages
1. No repositório, vá em **⚙️ Settings** (abas superiores)
2. No menu esquerdo, clique em **Pages**
3. Sob "Build and deployment":
   - **Source:** Selecione **Deploy from a branch**
   - **Branch:** Selecione **main** (ou **master**) e pasta **/(root)**
4. Clique em **Save**
5. **Aguarde 1-2 minutos** enquanto o GitHub publica o site

---

### PASSO 5: Copie e compartilhe o link
✅ Seu site estará disponível em:
```
https://SEU_USUARIO.github.io/biblioteca-unifecaf
```

**Exemplo:**
Se seu usuário GitHub é "victorBR116", o link será:
```
https://victorBR116.github.io/biblioteca-unifecaf
```

---

## 📝 ESTRUTURA ESPERADA NO GITHUB

```
biblioteca-unifecaf/
├── index.html           (arquivo principal)
├── css/
│   └── style.css       (estilos)
├── README.md           (criado automaticamente)
└── assets/             (opcional - para imagens depois)
    └── imagens/
```

---

## 🔗 LINKS IMPORTANTES

| Ação | Link |
|------|------|
| **Seu Repositório** | `https://github.com/SEU_USUARIO/biblioteca-unifecaf` |
| **Site Publicado** | `https://SEU_USUARIO.github.io/biblioteca-unifecaf` |
| **Configurações** | `https://github.com/SEU_USUARIO/biblioteca-unifecaf/settings/pages` |

---

## ⚠️ TROUBLESHOOTING

### "A página não apareceu após 2 minutos"
1. Aguarde mais 5-10 minutos
2. Vá em Settings → Pages e verifique se está com status "✅ Your site is live"
3. Limpe o cache do navegador (Ctrl+Shift+Del)

### "404 - Página não encontrada"
1. Verifique se o arquivo é chamado **exatamente** `index.html`
2. Verifique se está na raiz (não dentro de pasta)
3. Verifique se o repositório é **PUBLIC** (não privado)

### "CSS não carrega / página fica sem estilo"
1. Verifique se o arquivo é `css/style.css` (caminho correto)
2. No `index.html`, confirme que tem:
   ```html
   <link rel="stylesheet" href="css/style.css">
   ```
3. Limpe o cache (Ctrl+Shift+Del)

### "Posso usar domínio customizado?"
Sim! Em Settings → Pages → Custom domain, adicione seu domínio próprio (requer configuração DNS).

---

## 💡 DICAS

✅ **Mantenha seu repositório público** para o GitHub Pages funcionar (exceto em planos pagos)
✅ **Qualquer alteração** que você fizer em `index.html` ou `style.css` será **refletida em tempo real** no site
✅ **Você pode adicionar imagens** criando pasta `assets/imagens/` e referenciando no HTML
✅ **Para vídeo do YouTube**, use embed: `<iframe>` no HTML (GitHub Pages permite)

---

## 📧 ENTREGA PARA PROFESSOR

Forneça os 3 links:

1. **Site publicado:** `https://SEU_USUARIO.github.io/biblioteca-unifecaf`
2. **Repositório GitHub:** `https://github.com/SEU_USUARIO/biblioteca-unifecaf`
3. **Vídeo YouTube:** `https://youtube.com/watch?v=XXXXX`

---

**Pronto!** 🎉 Seu site está online e acessível de qualquer lugar do mundo.
