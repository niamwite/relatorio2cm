# 🚀 Deploy no GitHub Pages

## Passo a Passo para Publicar seu Dashboard

### 1️⃣ Criar Repositório GitHub

```bash
# Se já não tiver um repositório git
cd /home/will/relatorio
git init
git add .
git commit -m "Initial commit - Portfolio Dashboard"
```

### 2️⃣ Criar Repositório no GitHub

1. Acesse https://github.com/new
2. Crie um repositório chamado `portfolio` ou `will-developer`
3. **NÃO** inicialize com README
4. Copie a URL do repositório

### 3️⃣ Conectar e Push

```bash
# Adicionar remote
git remote add origin https://github.com/SEU-USUARIO/portfolio.git

# Fazer push
git branch -M main
git push -u origin main
```

### 4️⃣ Ativar GitHub Pages

1. Acesse o repositório no GitHub
2. Clique em **Settings** (⚙️)
3. No menu lateral, clique em **Pages**
4. Em **Source**, selecione:
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Clique em **Save**

### 5️⃣ Aguardar Deploy

- Aguarde alguns minutos
- Seu dashboard estará disponível em: `https://SEU-USUARIO.github.io/portfolio/`

---

## 📁 Estrutura de Arquivos

```
relatorio/
├── index.html                           # Dashboard principal
├── relatorio-fin.html                   # FINAN
├── relatorio-leadspro.html              # Leads Pro
├── relatorio-monju.html                 # Monju Dashboard
├── relatorio-monju-gs1.html             # Monju GS1
├── relatorio-nexusrh.html               # NexusRH
├── relatorio-skugenxi.html              # SKUgenXI (ABANDONADO)
├── relatorio-nexus-stock.html           # Nexus Stock (70%)
├── relatorio-linkedin.html              # LinkedIn Strategy
├── relatorio-whatsapp.html              # WhatsApp Automation
├── README.md                            # Este arquivo
└── DEPLOY-GITHUB-PAGES.md              # Guia de deploy
```

---

## ✅ Checklist Antes do Deploy

- [x] Todos os arquivos renomeados (sem acentos/espacos)
- [x] Links funcionando entre páginas
- [x] SKUgenXI marcado como ABANDONADO
- [x] Nexus Stock marcado como 70% desenvolvimento
- [x] LinkedIn e WhatsApp como planejamento
- [x] README atualizado
- [x] Design responsivo

---

## 🎨 Customização

### Alterar URL Base

Se quiser mudar o nome do repositório:

```bash
# Renomear repositório local
git remote set-url origin https://github.com/SEU-USUARIO/NOVO-NOME.git

# Push para novo repositório
git push -u origin main
```

### Adicionar Domínio Próprio

1. Compre um domínio (ex: willdeveloper.com)
2. No GitHub Pages > Settings > Pages > Custom Domain
3. Adicione seu domínio
4. Configure DNS conforme instruções do GitHub

---

## 📊 Atualizar Conteúdo

Para fazer mudanças:

```bash
# Falter alterações
git add .
git commit -m "Descrição das mudanças"
git push
```

O GitHub Pages fará deploy automático! ⚡

---

## 🐛 Troubleshooting

### Página não carrega
- Aguarde 5-10 minutos para o GitHub Pages processar
- Verifique se a branch está correta (main)
- Limpe cache do navegador

### Links quebrados
- Verifique se os nomes dos arquivos estão em minúsculas
- Confira que não há espaços nos nomes
- Teste localmente primeiro

### Imagens não carregam
- Use caminhos relativos (ex: `images/logo.png`)
- Não use caminhos absolutos do sistema local

---

## 🚀 Próximos Passos

1. ✅ Deploy inicial no GitHub Pages
2. ✅ Testar todos os links
3. ✅ Compartilhar link do portfólio
4. ✅ Adicionar ao perfil do LinkedIn
5. ✅ Usar em candidaturas de emprego

---

**URL do seu portfólio após deploy:**
```
https://SEU-USUARIO.github.io/REPOSITORIO/
```

Exemplo: `https://willdeveloper.github.io/portfolio/`

---

**Desenvolvido com ❤️ para GitHub Pages**
