# CorrigeAí 📋

App para correção de gabaritos de prova usando IA (Google Gemini — **gratuito**).

## Como usar

### 1. Publicar no GitHub Pages

1. Crie um repositório no GitHub (pode ser público)
2. Faça upload dos arquivos `index.html` e `manifest.json`
3. Vá em **Settings → Pages → Branch: main → Save**
4. Acesse o link `https://SEU_USUARIO.github.io/NOME_DO_REPO`

### 2. Obter a chave do Google Gemini (gratuito)

1. Acesse [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Faça login com sua conta Google
3. Clique em **"Create API Key"**
4. Copie a chave gerada
5. Na primeira vez que abrir o app, cole a chave no campo indicado

> Plano gratuito: **1500 análises por dia** — mais que suficiente para uso escolar.
> A chave fica salva apenas no seu celular (localStorage).

### 3. Usar o app

1. **Gabarito**: Selecione as respostas corretas das questões 3 a 8
2. **Corrigir**: Digite o nome do aluno e tire uma foto do gabarito preenchido
3. O app mostra a nota e quais questões estão certas/erradas
4. **Turma**: Veja o histórico de todos os alunos corrigidos

## Formato do gabarito suportado

- Questões 1 e 2: Discursivas
- Questões 3 a 8: Múltipla escolha (A, B, C, D, E)
- Questões 9 e 10: Soma (número escrito pelo aluno)

## Tecnologias

- HTML/CSS/JS puro (sem frameworks)
- Google Gemini 2.0 Flash para análise de imagem
- PWA (pode instalar no celular como app)
