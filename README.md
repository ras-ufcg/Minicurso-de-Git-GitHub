# Minicurso de Git e GitHub
</a> <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>
</a> <img alt="GitHub" src="https://img.icons8.com/fluency/48/000000/github.png"/>
## Sumário

1. [Introdução](#introdução)
2. [Sobre](#sobre)
3. [Aula 01](#aula-01)
4. [Aula 02](#aula-02)
6. [Ministrantes](#ministrantes)

## Introdução
     
![image](https://user-images.githubusercontent.com/50165797/155042504-0fd61ba8-bd10-4409-8077-c588b6d7f608.png)

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Este minicurso apresentará o site e as possibilidades com o GitHub, como adicionar arquivos, fazer commits etc. Além disso, apresentará o GitHub Desktop, exemplos com linha de comando e com VS Code.

## Sobre
O minicurso foi organizado pelo Capítulo Estudantil IEEE RAS UFCG e ministrados por voluntários e membros do capítulo. Essa atividade tem como objetivo de  aprimorar habilidades técnicas e sociais dos voluntários, sejam eles ministrantes ou alunos, contribuindo com o capítulo e sua comunidade. Essa atividade foi idealizada para introduzir e apresentar uma ferramenta de gerenciamento de versão, o Git e GitHub. 

## Aula 01

### Apresentação
- [Aula 01 - Minicurso de Git e GitHub.pdf](https://drive.google.com/file/d/1_wUGKrmNKKR21x4GmCNw99KTktxTTLUh/view?usp=sharing)
- [Aula 01 - Minicurso de Git e GitHub.mp4](https://drive.google.com/file/d/1DcIxT5yg6IbuYxX6SDd6kQENSSX-3BSM/view?usp=sharing)

### Repositórios Remotos
Alguns sites de gerenciamento de repositórios online, existem outros
- [PyPI](https://pypi.org)
- [GitLab](https://about.gitlab.com)
- [Bitbucket](https://bitbucket.org)


### Repositórios Citados
Alguns dos repositórios citados durante a aula, caso alguém queira acessar para conhecer mais sobre.
  -  [OpenDevUFCG](https://github.com/OpenDevUFCG)
  -  [torvalds/linux](https://github.com/torvalds/linux)
  -  [danilo-bc/edge-detect](https://github.com/danilo-bc/edge-detect)
  -  [numba/numba](https://github.com/numba/numba)
  -  [abntex/abntex2](https://github.com/abntex/abntex2)
  -  [danilo-bc/exercism-julia](https://github.com/danilo-bc/exercism-julia) 
  -  [danilo-bc/calculus-visualized](https://github.com/danilo-bc/calculus-visualized)
  -  [opencv/opencv](https://github.com/opencv/opencv)
  -  [The-OpenROAD-Project/OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD)
  -  [godotengine/godot](https://github.com/godotengine/godot)
  -  [McNopper/OpenGL](https://github.com/McNopper/OpenGL)

### GitHub Desktop
Concentre-se no que importa em vez de lutar com o Git. Seja você novo no Git ou um usuário experiente, o GitHub Desktop simplifica seu fluxo de trabalho de desenvolvimento.
- [Download - GitHub Desktop for Windows](https://desktop.github.com/)

### Git
O Git é um sistema de controle de versão distribuído gratuito e de código aberto projetado para lidar com tudo, desde projetos pequenos a muito grandes com velocidade e eficiência. Além disso, é fácil de aprender e tem uma pegada pequena com desempenho extremamente rápido . Ele supera ferramentas SCM como Subversion, CVS, Perforce e ClearCase com recursos como ramificação local barata , áreas de teste convenientes e vários fluxos de trabalho .
- [Sobre](https://git-scm.com/about/free-and-open-source)
- [Documentação](https://git-scm.com/doc)
- [Download - Git for Windows](https://gitforwindows.org/)

## Aula 02

### Apresentação

- [Aula 02 - Minicurso de Git e GitHub.mp4](https://drive.google.com/file/d/1nZuUPANTNJBDJgqEF3wN9vYv3UsAgidf/view?usp=sharing)

### GitHub Folha de Dicas de Git - Comandos

- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
- [GitHub Folha de Dicas de Git](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf)

### O que é Markdown?

Markdown Syntax é uma sintaxe usada para padronizar e facilitar formatação de texto na web, utilizada em aplicativos como Slack e GitHub. Textos estilizados com Markdown são, na maioria dos casos, apenas texto com caracteres não-alfabéticos, como #, \* e , usados para a configuração de títulos, listas, itálico, negrito e inserção de imagens.

- [Markdown Cheat Sheet | Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
- [Guia básico de Markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)

### Como personalizar o seu perfil no GitHub?

Existem inúmeras formas de você personalizar o seu perfil no GitHub, primeiro você terá que criar um repositório publico exatamente com seu *username*, o GitHub interpretará como um repositório especial, com um README.md de forma que ele será exibido ao abrir seu perfil.

É possível personalizar utilizando HTML e Markdown, segue alguns exemplos.

Para transformar um texto em citação ou comentário em Markdown utilize o sinal  >  no inicio da linha que será formatada:

```jsx
> olá, meu nome é guilherme
```

Como aparecerá no HTML:

> olá, meu nome é guilherme

Legal, mas eu gostaria de adicionar aquelas coisas prontas bonitas. O mais comum é adicionar estatísticas  do GitHub geradas dinamicamente. Inicialmente parece algo extremamente complexo, felizmente temos o repositório ****GitHub Readme Stats****, com ele é necessário apenas adicionar o código HTML abaixo alterando para o link do seu perfil no github e o seu *username.*

```jsx
<div align="center">
  <a href="https://github.com/drawnator">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=drawnator&show_icons=true&theme=dracula&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=drawnator&layout=compact&langs_count=7&theme=dracula&hide_border=true"/>
</div>
```

Como aparecerá no HTML:

<div align="center">
  <a href="https://github.com/drawnator">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=drawnator&show_icons=true&theme=dracula&include_all_commits=true&count_private=true&hide_border=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=drawnator&layout=compact&langs_count=7&theme=dracula&hide_border=true"/>
</div>

- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
     
Outros modelos, temas e entre outras coisas conseguimos encontrar no repositório acima.
     
Essas são apenas algumas formas, existem muitas outras personalizações e ferramentas que auxiliam nisso, abaixo temos um exemplo e um tutorial em vídeo retirado do YouTube.

- [YouTube - Rafaella Ballerini](https://www.youtube.com/watch?v=TsaLQAetPLU&t=319s)
- [GitHub - Rafaella Ballerini](https://github.com/rafaballerini/PerfilGithub)
<img align="center" height="180em" src="https://user-images.githubusercontent.com/50165797/155046903-43a749cd-6cd2-4874-a4ed-27190fb6af79.png"/>

## Ministrantes
- [Danilo Barreto Cavalcanti](https://github.com/danilo-bc)

[![my email](https://img.shields.io/static/v1?style=flat&logo=gmail&labelColor=fafafa&label=Email&message=danilo.cavalcanti@ee.ufcg.edu.br&color=red)](mailto:danilo.cavalcanti@ee.ufcg.edu.br)
[![my linkedin](https://img.shields.io/static/v1?style=flat&logo=linkedin&logoColor=0072b1&labelColor=fafafa&label=LinkedIn&message=Danilo%20Barreto%20Cavalcanti&color=0072b1)](https://www.linkedin.com/in/danilo-barreto-cavalcanti-956ba91b4/) 

- [Guilherme Silva Toledo](https://github.com/drawnator)

[![my email](https://img.shields.io/static/v1?style=flat&logo=gmail&labelColor=fafafa&label=Email&message=guilherme.toledo@ccc.ufcg.edu.br&color=red)](mailto:guilherme.toledo@ccc.ufcg.edu.br)
