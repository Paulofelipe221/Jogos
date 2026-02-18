# 🚀 Comandos Prontos - Cole no Terminal!

## Para Mac/Linux:

```bash
# 1. Baixe e extraia todos os arquivos em uma pasta
# 2. Abra o Terminal nessa pasta
# 3. Cole estes comandos (um de cada vez):

# Inicializar Git
git init

# Adicionar todos os arquivos
git add .

# Fazer commit
git commit -m "🎮 Deploy inicial do e-Soccer AI Predictor"

# AGORA: Crie o repositório no GitHub
# Vá para: https://github.com/new
# Nome: esoccer-predictor
# Clique em "Create repository"

# DEPOIS: Cole a URL que o GitHub mostrar
# Exemplo: https://github.com/SEU-USUARIO/esoccer-predictor.git
git remote add origin https://github.com/SEU-USUARIO/esoccer-predictor.git

# Renomear branch para main
git branch -M main

# Upload!
git push -u origin main
```

---

## Para Windows (Git Bash):

```bash
# 1. Baixe e extraia todos os arquivos em uma pasta
# 2. Clique com botão direito na pasta → "Git Bash Here"
# 3. Cole estes comandos:

git init && git add . && git commit -m "🎮 Deploy inicial"

# Crie repo no GitHub: https://github.com/new
# Cole a URL:
git remote add origin https://github.com/SEU-USUARIO/esoccer-predictor.git
git branch -M main
git push -u origin main
```

---

## Ativar GitHub Pages (ÚLTIMO PASSO):

1. Vá para o seu repositório no GitHub
2. Clique em **Settings** (⚙️)
3. No menu lateral, clique em **Pages**
4. Em **Source**, selecione:
   - Branch: `main`
   - Folder: `/ (root)`
5. Clique em **Save**
6. Aguarde 2-3 minutos
7. Acesse: `https://SEU-USUARIO.github.io/esoccer-predictor/`

---

## 🎉 Pronto!

Seu site está no ar! Compartilhe:
```
🎮 Confira minhas previsões de e-Soccer!
https://SEU-USUARIO.github.io/esoccer-predictor/
```

---

## 🔑 (Opcional) Adicionar API Key do Gemini

Para análises com IA:

1. No GitHub, vá em: **Settings → Secrets → Actions**
2. Clique em **New repository secret**
3. Name: `GEMINI_API_KEY`
4. Value: Sua chave da API (pegue em: https://makersuite.google.com/app/apikey)
5. **Add secret**

Pronto! Os dados atualizarão automaticamente a cada 6 horas!

---

## ⚠️ Problemas?

Se der erro de autenticação:
```bash
# Use token em vez de senha
# Crie um token em: https://github.com/settings/tokens
# Use o token como senha quando pedir
```

Se já tiver um repositório:
```bash
git remote remove origin
git remote add origin https://github.com/SEU-USUARIO/esoccer-predictor.git
git push -u origin main
```
