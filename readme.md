# 📂 Leitura de Arquivos com Node.js

## 📌 Descrição

Este código demonstra como **ler o conteúdo de um arquivo de texto** utilizando o **Node.js**, recebendo o caminho do arquivo diretamente pela **linha de comando**.

Ele é um ótimo exemplo para aprender como o Node.js interage com o **sistema de arquivos** e com os **argumentos do terminal**.

---

## 💻 Código Analisado

```js
const fs = require("fs");

const caminhoArquivo = process.argv;
const link = caminhoArquivo[2];

fs.readFile(link, "utf-8", (erro, texto) => {
  console.log(texto);
});
```
