# CorrigeAí 📋

App para correção de gabaritos de prova usando IA (Claude da Anthropic).

## Como usar

### 1. Publicar no GitHub Pages

1. Crie um repositório no GitHub (pode ser público)
2. Faça upload dos arquivos `index.html` e `manifest.json`
3. Vá em **Settings → Pages → Branch: main → Save**
4. Acesse o link `https://SEU_USUARIO.github.io/NOME_DO_REPO`

### 2. Configurar a API

O app usa a API da Anthropic para analisar as imagens. Você precisará de uma chave de API:

1. Acesse [console.anthropic.com](https://console.anthropic.com)
2. Crie uma conta gratuita
3. Vá em **API Keys** e crie uma chave
4. Na primeira vez que abrir o app, cole a chave no campo indicado

> A chave fica salva apenas no seu celular (localStorage). Nunca é enviada para nenhum servidor além da Anthropic.

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
- API Claude da Anthropic para análise de imagem
- PWA (pode instalar no celular como app)
