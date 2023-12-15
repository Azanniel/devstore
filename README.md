<h4 align="center">
  <img width="140" src=".github/favicon.png" />
  <br/>
  devstore
</h4>

---
Devstore é um projeto de e-commerce de produtos voltados para devs como camisetas, moletons, canecas.

Nesse projeto é usado o framework NextJS que é um case usado por algumas das maiores empresas do mundo, Next.js permite que você crie aplicativos Web full-stack, estendendo os recursos mais recentes do React e integrando poderosas ferramentas JavaScript baseadas em Rust para compilações mais rápidas.

## ✨ Tecnologias relevantes

- [NextJS](https://nextjs.org/): Next.js é uma estrutura React para construir aplicativos web full-stack. Você usa React Components para construir interfaces de usuário e Next.js para recursos e otimizações adicionais.
- [TailwindCSS](https://tailwindcss.com/): Uma estrutura CSS utilitária repleta de classes e que pode ser composta para construir qualquer design, diretamente em sua marcação.
- [Zod](https://zod.dev/): Validação de esquemas TypeScript-first com inferência de tipos estáticos.

## 🃏 Layout
Caso tenha interesse em visualizar o Layout temos [o link do figma](https://www.figma.com/file/oCjfMWlVgRXEFaPcUOgadt/devstore-%E2%80%A2-Projeto-React?type=design&node-id=0%3A1&mode=design&t=Xm6X68YzQfq5nyzJ-1).

## 📃 Anotações importantes

**1. Rotas, Layouts e Grupos**

O roteamento do nextJS é feita baseada em arquivos que dependendo do nome acaba gerando uma nova rota ou página dentro da aplicação.
Uma página é uma interface de usuário exclusiva para uma rota. Você pode definir páginas exportando um componente de um page.js.

Um layout é uma interface de usuário compartilhada entre várias páginas. Na navegação, os layouts preservam o estado, permanecem interativos e não são renderizados novamente. Os layouts também podem ser aninhados.

No diretório do aplicativo, as pastas aninhadas normalmente são mapeadas para caminhos de URL. No entanto, você pode marcar uma pasta como Grupo de rotas para evitar que a pasta seja incluída no caminho URL da rota usando parenteses.

**2. Geração estática da build**

A geração estática permite criar uma versão em cache das páginas da aplicação antes de serem publicadas. Isso significa que quando um usuário acessar uma página, ela será exibida de forma instantânea, sem a necessidade de fazer requisições adicionais.

Para utilizar a geração estática, podemos exportar uma função chamada generateStaticParams dentro de uma página que recebe parâmetros dinâmicos.

**3. Cache e Memoização**

A Memoização é uma funcionalidade do React que evita requisições duplicadas durante o carregamento de uma página. Quando usamos Server Components, o React automaticamente impede que uma requisição seja feita mais de uma vez. No entanto, a Memoização não se aplica a requisições feitas em páginas diferentes. Para evitar requisições duplicadas em páginas diferentes, é necessário utilizar o Cache. O Next.js possui propriedades para controle de Cache, como a opção force-cache, que permite cachear uma requisição, e a opção no-store, que impede o cache. Além disso, há a opção revalidate, que define um tempo em segundos para atualizar o cache da requisição.

## ☕ Contatos

Você vai me encontrar em qualquer uma das redes sociais abaixo:

<a href = "mailto: leo.azannielttt@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23EA4335?style=for-the-badge&logo=gmail&logoColor=white" target="_blank" margin-right="10px"></a>
<a href="https://www.linkedin.com/in/leandroazanniel/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
<a href="https://api.whatsapp.com/send?phone=5592985406269" target="_blank"><img src="https://img.shields.io/badge/-WhatsApp-%25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>