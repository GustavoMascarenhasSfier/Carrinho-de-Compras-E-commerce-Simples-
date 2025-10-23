# 🛒 Carrinho de Compras (E-commerce Simples)

Este projeto é uma aplicação web de vitrine de produtos e um carrinho de compras funcional, desenvolvida com as tecnologias essenciais do Front-end: HTML, CSS e **JavaScript puro**.

O projeto simula um e-commerce básico onde o usuário pode visualizar uma lista de produtos, adicionar itens ao carrinho, visualizar o resumo (incluindo descontos), e manter o estado do carrinho salvo ao recarregar a página através do **LocalStorage**.



## 🎯 Objetivo de Estudo (Foco em JavaScript Puro)

Este projeto foi concebido como uma prática essencial para consolidar o conhecimento em lógica de negócios e manipulação do DOM utilizando **JavaScript puro** (sem bibliotecas), com foco nos seguintes tópicos:

* **Manipulação do DOM:** Uso de funções nativas como `document.createElement`, `innerHTML`, `appendChild`, e `classList` para a renderização dinâmica de produtos e itens no carrinho.
* **Gerenciamento de Estado:** Implementação de um array (`carrinho`) que gerencia o estado global e persistência dos dados via **LocalStorage**.
* **Array Methods Avançados:** Prática com `Array.prototype.find` (para procurar produtos e itens no carrinho) e `Array.prototype.reduce` (para calcular totais e descontos).
* **Event Delegation:** Uso de `addEventListener` nos containers principais para gerenciar cliques em botões "Adicionar" e "Remover", otimizando a performance.
* **Sincronização de Estado:** Implementação do evento `window.addEventListener('storage', ...)` para manter o carrinho atualizado em múltiplas abas do navegador.

## ✨ Funcionalidades

* **Listagem de Produtos:** Exibe uma grade de produtos com imagem, nome e preço.
* **Preços e Descontos:** Mostra o preço final e o preço original riscado (`<s>`) quando há descontos aplicados.
* **Adicionar ao Carrinho:** Inclui o produto ou incrementa a quantidade se o item já existir.
* **Contador de Itens:** Um *badge* vermelho no ícone do carrinho exibe a quantidade total de produtos.
* **Remoção de Itens:** Permite remover itens individuais do carrinho.
* **Resumo:** Exibe o total de descontos e o valor total final da compra.
* **Persistência de Dados:** O carrinho é salvo e recarregado automaticamente via LocalStorage.

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso | Função Principal |
| :--- | :--- | :--- |
| **HTML5** | `index.html` | Estrutura da página (vitrine e carrinho). |
| **CSS3** | `css.css` | Estilização, layout Flexbox/Grid e design do *badge* de quantidade. |
| **JavaScript (Puro)** | `script.js` | Lógica de estado, manipulação do DOM e cálculos de totais. |
| **LocalStorage** | API Web | Persistência do estado do carrinho. |

## ⚙️ Como Executar o Projeto

1.  Baixe ou clone os arquivos.
2.  Abra o arquivo **`index.html`** diretamente em seu navegador.
3.  O JavaScript carregará os produtos e o carrinho salvo, se houver.

## 📁 Estrutura de Pastas <a id="estrutura-de-pastas"></a>

```

📦 Carrinho de Compras

├── 📄 index.html 
├── 📄 css.css 
├── 📄 script.js 
├── 📂 img/
│   └── cart_15407002      
└── 📜 README.md

```


## 👨‍💻 Autor <a id="autor"></a>

**Gustavo Mascarenhas**  

📍 Curitiba - PR  

💻 Estudante de Engenharia de Software | Desenvolvedor Front-End  

📧 [gugab1249@gmail.com].  

🌐 [LinkedIn](https://www.linkedin.com/in/gustavo-mascarenhas-a3b570297/) 



---


## 📝 Licença


Este projeto é de código aberto e pode ser utilizado para fins educacionais e pessoais.  

Sinta-se à vontade para modificar e melhorar! 🚀
