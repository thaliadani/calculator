# 📱 Modern JS Calculator

Uma calculadora web minimalista e funcional construída com **HTML5**, **CSS3** e lógica **JavaScript** diretamente nos eventos de clique. Este projeto foca na simplicidade e no uso da função `eval()` para processamento matemático em tempo real.

---

## ✨ Demonstração das Funcionalidades

A calculadora suporta as seguintes operações e recursos:

* ➕ **Soma**: Adição de valores.
* ➖ **Subtração**: Diferença entre números.
* ✖️ **Multiplicação**: Produto de valores.
* ➕ **Divisão**: Quociente entre números.
* 🔢 **Operações de Precisão**: Suporte a números decimais (ponto flutuante).
* 🧹 **Limpeza (Clear)**: Botão `C` para reiniciar o visor instantaneamente.
* ⚡ **Cálculo Rápido**: Processamento imediato ao clicar no botão `=`.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando o "trio fundamental" do desenvolvimento web:

* **HTML5**: Estruturação semântica dos botões e do visor (`display`).
* **CSS3**: Estilização externa (via arquivo `style.css`) para layout responsivo e visual moderno.
* **JavaScript**: Lógica de inserção de caracteres e execução de fórmulas matemáticas.

---

## 🚀 Como Executar o Projeto

Como este é um projeto *frontend-only*, a execução é extremamente simples:

1.  Clone este repositório ou baixe os arquivos.
2.  Certifique-se de que o arquivo `style.css` esteja na mesma pasta que o seu `index.html`.
3.  Abra o arquivo `index.html` em qualquer navegador (Chrome, Firefox, Safari, Edge).

---

## 🔍 Destaques do Código

O diferencial deste projeto é a execução da lógica diretamente no HTML, utilizando o atributo `onclick`:

```html
<input type="button" value="+" onclick="display.value += '+' ">

<input type="button" value="=" onclick="display.value = eval(display.value)">
```

## 🎨 Personalização

Você pode facilmente alterar o visual da sua calculadora editando o arquivo `style.css`. Algumas sugestões:
* Alterar a cor dos botões de `.operator`.
* Adicionar um efeito de *hover* para melhorar a experiência do usuário.
* Ajustar o `border-radius` para um design mais arredondado ou quadrado.

---
*Feito com ❤️ por um entusiasta de código.*
