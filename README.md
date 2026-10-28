# 🗺️ Roadmap Definitivo: HTML Descomplicado (Do Zero ao Site Seguro)

> 💡 **Para quem é este guia?**  
> Este guia foi feito para **qualquer pessoa, mesmo quem NUNCA escreveu uma linha de código na vida**. Aqui você vai aprender o que é HTML, como criar seu primeiro site em 2 minutos e como deixá-lo protegido contra invasões de forma simples.

---

## 📌 Sumário do Roadmap

- [📖 Dicionário do Iniciante (Traduzindo o "Techês")](#-dicionário-do-iniciante-traduzindo-o-techês)
- [⚡ Passo a Passo: Seu Primeiro Site em 2 Minutos](#-passo-a-passo-seu-primeiro-site-em-2-minutos)
- [🟢 Nível 1: Os Primeiros Passos no HTML](#-nível-1-os-primeiros-passos-no-html)
- [🟡 Nível 2: Montando o Visual e os Textos da Página](#-nível-2-montando-o-visual-e-os-textos-da-página)
- [🟠 Nível 3: Organizando a Casa (Estrutura do Site)](#-nível-3-organizando-a-casa-estrutura-do-site)
- [🔴 Nível 4: Protegendo Seu Site (Segurança Descomplicada)](#-nível-4-protegendo-seu-site-segurança-descomplicada)
- [📊 Checklist Final do Seu Site](#-checklist-final-do-seu-site)

---

## 📖 Dicionário do Iniciante (Traduzindo o "Techês")

Antes de começar, vamos entender os termos que você vai ouvir muito:

- 🌐 **Navegador (Browser)**: O programa que você usa para entrar na internet (Google Chrome, Edge, Firefox, Safari).
- 💻 **Código HTML**: As instruções que você escreve para o navegador desenhar a página.
- 🏷️ **Tag**: Os "tijolos" do HTML. São palavras entre sinais de menor e maior (ex: `<p>` para parágrafo).
- 🔗 **URL / Link**: O endereço de um site na web (ex: `https://google.com`).
- 🛡️ **Segurança Web**: As regras que você segue para garantir que hackers não invadam seu site nem roubem dados dos seus visitantes.

---

## ⚡ Passo a Passo: Seu Primeiro Site em 2 Minutos

Você não precisa pagar nada nem instalar programas complicados para começar. Siga estes 4 passos:

1. **Abra o Bloco de Notas** (no Windows) ou **TextEdit** (no Mac).
2. **Cole o código abaixo** dentro dele:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Meu Primeiro Site</title>
</head>
<body>
    <h1>Olá, Mundo!</h1>
    <p>Eu acabei de criar o meu primeiro site na internet!</p>
</body>
</html>
```

3. **Salve o arquivo**:
   - Vá em *Arquivo > Salvar Como*.
   - Escolha o nome `meusite.html` (⚠️ **Atenção**: certifique-se de colocar `.html` no final e não `.txt`!).
4. **Abra o site**:
   - Vá até a pasta onde salvou o arquivo e dê **dois cliques** nele. Ele vai abrir direto no seu navegador! 🎉

---

# 🟢 Nível 1: Os Primeiros Passos no HTML

## 🏠 A Analogia da Casa
Pense em um site como se fosse a construção de uma casa:
- 🧱 **HTML** = **A Estrutura e as Paredes** (sustenta tudo).
- 🎨 **CSS** = **A Pintura e a Decoração** (deixa bonito).
- ⚡ **JavaScript** = **A Automação da Casa** (o portão elétrico, o alarme).

---

## 🧱 Como funcionam as Tags?

As tags no HTML quase sempre funcionam em **duplas** (uma tag de abertura e uma de fechamento com `/`):

```html
<p>Este é o conteúdo dentro do parágrafo.</p>
 ↑                                    ↑
Abertura                           Fechamento
```

Algumas tags raras não precisam de fechamento porque só inserem algo na tela (ex: `<img>` para imagem ou `<br>` para pular linha).

🌐 **Links para Aprofundar:**
- 📘 [MDN: O que é HTML? (Guia para Iniciantes)](https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- 💻 [W3Schools: Teste e Pratique HTML no Navegador](https://www.w3schools.com/html/)

---

# 🟡 Nível 2: Montando o Visual e os Textos da Página

Aqui estão as tags mais comuns que você vai usar todos os dias:

### 1. Títulos (`<h1>` até `<h6>`)
Servem para destacar o título principal e os subtítulos da sua página.

```html
<h1>Título Principal (O mais importante da página)</h1>
<h2>Subtítulo da Seção</h2>
<h3>Título de um assunto menor</h3>
```

### 2. Textos e Parágrafos (`<p>`, `<strong>`, `<em>`)
- `<p>`: Cria um parágrafo normal.
- `<strong>`: Deixa o texto em **negrito** (indica que a palavra é importante).
- `<em>`: Deixa o texto em *itálico* (dá ênfase à leitura).

```html
<p>Aprender a programar é <strong>muito divertido</strong> e <em>fácil</em> quando começamos do jeito certo.</p>
```

### 3. Criando Listas (`<ul>` e `<li>`)
Para fazer listas de compras, tarefas ou tópicos:

```html
<ul>
    <li>Aprender HTML</li>
    <li>Aprender CSS</li>
    <li>Criar meu primeiro projeto</li>
</ul>
```

### 4. Links e Imagens (`<a>` e `<img>`)
- `<a>`: Cria um link clicável. Usa o parâmetro `href="endereço"`.
- `<img>`: Coloca uma imagem na tela. Usa `src="foto.jpg"` e `alt="descrição da foto"`.

```html
<!-- Link para outro site -->
<a href="https://google.com" target="_blank" rel="noopener noreferrer">Ir para o Google</a>

<!-- Imagem -->
<img src="foto-gato.jpg" alt="Um gatinho branco brincando com um novelo de lã">
```

> 💡 **Dica de Acessibilidade**: O parâmetro `alt` nas imagens serve para leitores de tela explicarem a imagem para pessoas com deficiência visual.

---

# 🟠 Nível 3: Organizando a Casa (Estrutura do Site)

Em vez de jogar tudo solto na página, organizamos o site em "cômodos" usando tags semânticas (tags com nome legível):

```html
<body>
    <!-- 🚪 Entrada / Cabeçalho -->
    <header>
        <h1>Meu Site Pessoal</h1>
        <nav>
            <a href="#inicio">Início</a> | 
            <a href="#sobre">Sobre Mim</a>
        </nav>
    </header>

    <!-- 🛋️ Sala / Conteúdo Principal -->
    <main>
        <section>
            <h2>Sobre Mim</h2>
            <p>Olá! Estou aprendendo HTML para criar meus próprios projetos.</p>
        </section>
    </main>

    <!-- 📦 Rodapé do Site -->
    <footer>
        <p>© 2024 - Feito por mim com HTML</p>
    </footer>
</body>
```

---

# 🔴 Nível 4: Protegendo Seu Site (Segurança Descomplicada)

Agora vem a parte mais importante: **como garantir que seu site seja seguro contra ataques**, explicado de forma simples com exemplos do dia a dia!

---

### 🛡️ 1. Protegendo contra Injeção de Scripts (O Ataque "XSS")

- 🗣️ **O que é isso?** Pense nisso como evitar que um estranho coloque uma armadilha dentro da sua caixa de correio. Se um usuário puder digitar um código malicioso num campo de texto e o seu site executar esse código, ele pode roubar dados.
- 💡 **Como resolver?** Nunca confie no que o usuário digita. Converta caracteres especiais (como `<` e `>`) em texto puro.

---

### 🛡️ 2. Colocando iFrames na "Quarentena" (`sandbox`)

- 🗣️ **O que é um iFrame?** É quando você coloca uma janela de outro site dentro do seu (ex: um vídeo do YouTube ou um mapa).
- 🕵️ **O risco**: Se o site dentro dessa janela for invadido, ele pode tentar controlar o seu site.
- 💡 **A solução (Analogia da Sala de Vidro)**: Use o atributo `sandbox`. É como colocar o convidado em uma sala de vidro com luvas de proteção para ele não poder quebrar nada na sua casa.

```html
<!-- iFrame protegido e em quarentena -->
<iframe src="https://site-terceiro.com" sandbox title="Janela Protegida"></iframe>
```

---

### 🛡️ 3. Protegendo Links que Abrem em Nova Aba (`target="_blank"`)

- 🗣️ **O risco (Ataque "Tabnabbing")**: Quando você coloca um link para abrir em nova aba (`target="_blank"`), o novo site ganha uma "chave temporária" para redirecionar a sua página anterior sem o usuário perceber.
- 💡 **A solução (Mudar a Fechadura)**: Coloque sempre `rel="noopener noreferrer"` em todos os links que abrem em nova aba!

❌ **Inseguro:**
```html
<a href="https://site-externo.com" target="_blank">Clique aqui</a>
```

✅ **Seguro:**
```html
<a href="https://site-externo.com" target="_blank" rel="noopener noreferrer">Clique aqui</a>
```

---

### 🛡️ 4. Formulários Seguros (`<form>`)

- 🗣️ **O risco**: Se você enviar senhas ou dados pessoais pela URL do navegador (usando o método `GET`), a senha fica salva no histórico de navegação de qualquer pessoa.
- 💡 **A solução**: Para formulários com dados sensíveis, use sempre `method="POST"`.

```html
<!-- Formulário de Login Seguro -->
<form action="/login" method="POST">
    <label for="email">E-mail:</label>
    <input type="email" id="email" name="email" required>

    <label for="senha">Senha:</label>
    <input type="password" id="senha" name="senha" required minlength="8">

    <button type="submit">Entrar</button>
</form>
```

---

# 📊 Checklist Final do Seu Site

Antes de colocar seu site no ar, faça este teste simples:

- [ ] Seu código começa com `<!DOCTYPE html>` e `<html lang="pt-BR">`?
- [ ] Todas as suas imagens possuem descrição no atributo `alt`?
- [ ] Todos os links que abrem em nova aba (`target="_blank"`) têm `rel="noopener noreferrer"`?
- [ ] Formulários com senhas usam `method="POST"`?
- [ ] Seus iFrames possuem o atributo `sandbox`?
- [ ] Você testou abrir o arquivo `.html` no navegador e tudo funcionou?

---

## 🌐 Ferramentas Gratuitas para Testar Seu Site

1. 🛠️ [W3C HTML Validator](https://validator.w3.org/): Cole o seu código para ver se cometeu algum erro de digitação de tags.
2. 🛡️ [Mozilla Observatory](https://observatory.mozilla.org/): Testa se o seu site segue as boas práticas de segurança.
