# Safari ChatGPT Chat Saver (Outubro 2026) 💾

Script definitivo para exportar conversas completas do ChatGPT no navegador **Safari** usando o console do inspetor de elementos.

## 🎯 Por que usar este script?
Atualmente, o site do ChatGPT utiliza **virtualização de lista agressiva**, o que significa que mensagens antigas que saem da tela são completamente deletadas do código HTML da página. Este script ignora o HTML visual e faz uma requisição direta na **API interna de backend da OpenAI**, garantindo **100% das mensagens** em ordem cronológica perfeita.

## 🚀 Como usar:

1. Acesse a conversa do ChatGPT que você deseja salvar (garanta que a URL seja no formato `://chatgpt.com`).
2. Abra o menu de desenvolvedor do Safari e abra o console pressionando:
   * **`Option + Command + C`**
3. Copie todo o conteúdo do arquivo `chatgpt_saver.js` deste repositório.
4. Cole no console do Safari e aperte **Enter**.
5. O download do arquivo `.md` (Markdown) começará automaticamente com todo o histórico estruturado!

---
Criado por [@rafaelosouza2002-hash](https://github.com/rafaelosouza2002-hash)
