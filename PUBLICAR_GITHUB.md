# 🚀 Guia Rápido - Como Publicar no GitHub

## Passo 1: Criar Repositório no GitHub

1. Acesse [GitHub](https://github.com) e faça login
2. Clique no botão **"+"** no canto superior direito
3. Selecione **"New repository"**
4. Preencha:
   - **Repository name**: `sistema-orcamento-mecanica` (ou outro nome)
   - **Description**: "Sistema web para geração de orçamentos de oficina mecânica"
   - Deixe como **Public** (ou Private se preferir)
   - ❌ **NÃO** marque "Add a README file" (já temos um)
5. Clique em **"Create repository"**

## Passo 2: Subir os Arquivos

### Opção A: Usando GitHub Web (Mais Fácil)

1. Na página do repositório recém-criado, clique em **"uploading an existing file"**
2. Arraste os arquivos:
   - `orcamento_mecanico.html`
   - `README.md`
   - `LICENSE`
   - `.gitignore`
3. Adicione uma mensagem: "Primeira versão do sistema"
4. Clique em **"Commit changes"**

### Opção B: Usando Git (Via Terminal)

```bash
# 1. Navegue até a pasta onde estão os arquivos
cd /caminho/para/seus/arquivos

# 2. Inicialize o repositório Git
git init

# 3. Adicione todos os arquivos
git add .

# 4. Faça o primeiro commit
git commit -m "Primeira versão do sistema de orçamentos"

# 5. Adicione o repositório remoto (substitua SEU-USUARIO)
git remote add origin https://github.com/SEU-USUARIO/sistema-orcamento-mecanica.git

# 6. Envie os arquivos
git branch -M main
git push -u origin main
```

## Passo 3: Ativar GitHub Pages (Hospedar Online Grátis)

1. No repositório, vá em **"Settings"**
2. No menu lateral, clique em **"Pages"**
3. Em **"Source"**, selecione **"main"** branch
4. Clique em **"Save"**
5. Aguarde alguns minutos
6. Seu site estará disponível em: `https://SEU-USUARIO.github.io/sistema-orcamento-mecanica/orcamento_mecanico.html`

## Passo 4: Personalizar (Opcional)

### Adicionar Descrição e Tags

1. Na página principal do repositório
2. Clique em ⚙️ ao lado de "About"
3. Adicione:
   - **Description**: "Sistema web para orçamentos de oficina mecânica"
   - **Website**: Cole a URL do GitHub Pages
   - **Topics**: `html`, `css`, `javascript`, `oficina`, `orcamento`, `mecanica`

### Adicionar Capturas de Tela

1. Tire screenshots do sistema
2. Crie uma pasta `screenshots` no repositório
3. Faça upload das imagens
4. Edite o `README.md` e atualize os links das imagens

## 📝 Comandos Git Úteis

```bash
# Ver status dos arquivos
git status

# Adicionar alterações
git add .

# Fazer commit
git commit -m "Descrição da mudança"

# Enviar para o GitHub
git push

# Puxar atualizações
git pull

# Ver histórico
git log
```

## 🆘 Problemas Comuns

### "Permission denied"
- Verifique se você tem permissão no repositório
- Configure suas credenciais Git

### "Failed to push"
- Execute: `git pull` antes de `git push`
- Resolva conflitos se houver

### GitHub Pages não funciona
- Aguarde até 10 minutos
- Verifique se o arquivo se chama `orcamento_mecanico.html`
- Certifique-se de que o repositório é público

## 🎉 Pronto!

Agora seu projeto está no GitHub e pode ser:
- ✅ Compartilhado com outros
- ✅ Acessado de qualquer lugar
- ✅ Usado online via GitHub Pages
- ✅ Melhorado pela comunidade

---

**Precisa de ajuda?** Abra uma issue no repositório!
