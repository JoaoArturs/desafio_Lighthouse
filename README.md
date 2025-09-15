# Manual de instalação

Este guia explica **rapidamente** como abrir e rodar o notebook do projeto no Google Colab.  
Arquivo principal: `LH_CD_JOAOARTURSALESROCHA.ipynb`

## Passo a passo

### 1) Abrir o Colab
- Acesse: https://colab.research.google.com
- Faça login com sua conta Google, caso necessário.

### 2) Enviar o notebook
- No Colab, vá em **Arquivo → Carregar notebook** e selecione `LH_CD_JOAOARTURSALESROCHA.ipynb` no seu computador.
- Alternativamente, na tela inicial do Colab, use o botão **Upload**.

> Dica: o upload vai para o ambiente temporário do Colab. Sempre que o runtime for reiniciado, você pode precisar **enviar novamente** o arquivo.

### 3) Conectar o runtime
- Clique em **Conectar** (canto superior direito). Aguarde aparecer **Conectado**.

### 4) Executar tudo
- Vá em **Executar → Executar tudo** (ou pressione `Ctrl+F9` / `Cmd+F9`).
- Acompanhe a execução das células até concluir.

---

## Células comentadas (evitam re-treino)
Para acelerar a reprodução, algumas células estão **comentadas** para **pular o re-treino** do modelo.  
Se você **não** quiser treinar novamente, **deixe-as comentadas** e siga apenas com as células de inferência/avaliação.

Se você **quiser treinar** de novo:
1. **Selecione o conteúdo da célula** (`Ctrl+A` dentro da célula).
2. **Descomente** as linhas:
   - Atalho padrão no Colab: `Ctrl+/` (Windows/Linux) ou `Cmd+/` (macOS).  
   - Em certos layouts PT-BR, `Ctrl+;` também pode funcionar como alternativo.
3. **Execute** a célula como de costume (Shift+Enter).
