# Sistemas de Controle de Versão : git-scm

<!-- toc -->

* [Hospedagem de repositórios Git](#hospedagem-de-repositórios-git)
* [Git e GitHub](#git-e-github)
  * [Sobre](#sobre)
* [Aprendizado](#aprendizado)
  * [Referência](#referência)
  * [Curso online](#curso-online)
  * [Cursos online interativos](#cursos-online-interativos)
  * [Aprendizado: GitHub](#aprendizado-github)
* [Git em empresas](#git-em-empresas)
* [Dicas](#dicas)
  * [Workflow](#workflow)
  * [Merge](#merge)
    * [Squash commits](#squash-commits)
  * [SVN para GIT](#svn-para-git)
    * [Problema conhecido](#problema-conhecido)
  * [git submodule](#git-submodule)
  * [git branch](#git-branch)
  * [Fork de um repositório](#fork-de-um-repositório)
  * [Colaboração](#colaboração)
    * [pull request](#pull-request)
    * [patch](#patch)
  * [Curiosidades](#curiosidades)
  * [Dicas: GitHub](#dicas-github)
    * [gh-pages](#gh-pages)
    * [Wiki](#wiki)
    * [Livro online](#livro-online)
  * [Sistemas de Blog e Sites Estáticos](#sistemas-de-blog-e-sites-estáticos)
    * [Jekyll](#jekyll)
    * [Octopress](#octopress)
    * [Hexo](#hexo)
    * [Cabin.js](#cabinjs)
    * [Docpad](#docpad)
* [Ferramentas](#ferramentas)
  * [Gestão de servidor Git](#gestão-de-servidor-git)
  * [Mac](#mac)
  * [Windows](#windows)
  * [Windows, Linux e Mac](#windows-linux-e-mac)
  * [Eclipse IDE - Git plugin](#eclipse-ide-git-plugin)
* [Quem usa o Git/GitHub?](#quem-usa-o-gitgithub)
  * [Governos](#governos)
    * [Brasil](#brasil)
    * [Estados Unidos](#estados-unidos)
  * [Empresas](#empresas)
    * [NASA](#nasa)
    * [SAP](#sap)
    * [Microsoft](#microsoft)
    * [Globo.com](#globocom)

<!-- toc stop -->


## Hospedagem de repositórios Git

* [GitHub](https://github.com/)

* [Gitlab](https://gitlab.com/)

* [Git - Geekli.st](https://git.geekli.st)

* [BitBucket](https://bitbucket.org/)


## Git e GitHub

### Sobre

* [Git | Wikipedia PT](https://pt.wikipedia.org/wiki/Git)

* [[YouTube] Tech Talk: Linus Torvalds on git](https://www.youtube.com/watch?v=4XpnKHJAok8)

* [Uma Breve História do Git](http://git-scm.com/book/pt-br/Primeiros-passos-Uma-Breve-Hist%C3%B3ria-do-Git)

* [Sistemas de Controle de Versão Distribuídos](http://git-scm.com/book/pt-br/Primeiros-passos-Sobre-Controle-de-Vers%C3%A3o#Sistemas-de-Controle-de-Vers%C3%A3o-Distribu%C3%ADdos)

O Git é um Sistema de Controle de Versão Distribuído. (Distributed Version Control System ou DVCS). Em um DVCS, os clientes não apenas fazem cópias das últimas versões dos arquivos: eles são cópias completas do repositório. Assim, se um servidor falha, qualquer um dos repositórios dos clientes pode ser copiado de volta para o servidor para restaurá-lo. Cada checkout (resgate) é na prática um backup completo de todos os dados.

* [git-scm](http://git-scm.com/)

* [GitHub](https://github.com/)

  * [Education | GitHub](https://education.github.com/)

  * [List of guides and tutorials](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github) for learning how to use them

  * [Open source training materials](http://training.github.com/kit/) to you can use/customize for your classes

  * [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf)

  * [Projects that power GitHub](https://github.com/showcases/projects-that-power-github)

  * [How GitHub Uses GitHub to Build GitHub | Zach Holman](http://zachholman.com/talk/how-github-uses-github-to-build-github/) - 2011/09/21


## Aprendizado

* [git-scm: Pro Git book](http://git-scm.com/book/pt-br/) - livro online completo sobre git, em português

  * [Learn Git | GitBook](https://gitbookio.github.io/git/en/) - This is a GitBook version of the Scott Chacon's book: Pro Git

  * [Git for Everyone | GitBook](http://anotheruiguy.gitbooks.io/gitforeveryone/) - The Git Workshop Guide

* [Learn Git and GitHub without any code! | GitHub](https://guides.github.com/activities/hello-world/) - Using the Hello World guide, you’ll create a  repository, start a branch, write comments, and open a pull request.

* [Using Git | GitHub:Help](https://help.github.com/categories/19/articles)

* [GitHub Guides](http://guides.github.com/)

  * [[YouTube] GitHub Guides](https://www.youtube.com/githubguides)

* [[GitHub] tiimgreen/github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) - A list of cool features of Git and GitHub

* [Git Commands and Best Practices Cheat Sheet | zeroturnaround.com](http://zeroturnaround.com/rebellabs/git-commands-and-best-practices-cheat-sheet/)

* [Git Tutorials - become a git guru | Atlassian](https://www.atlassian.com/git/tutorials/)

--

* [SlideShare] Vinicius Ban

  * [Git conceitos](http://www.slideshare.net/viniciusban/git-conceitos) - 2014/09/12

  * [Git commits - como, quando e por quê?](http://www.slideshare.net/viniciusban/git-commits-39022351) - 2014/09/12

  * [Git na pratica](http://www.slideshare.net/viniciusban/git-na-pratica-39022552)  - 2014/09/12

--

* [[SlideShare] Primeiros passos - GIT](http://www.slideshare.net/horochovec/primeiros-passos-git) - by Stefan Horochovec

* [[YouTube] Git e Github para iniciantes](https://www.youtube.com/watch?v=UMhskLXJuq4)

* [Começando com Git | DPW](http://desenvolvimentoparaweb.com/indicacoes/comecando-com-git/)

* [Comandos básicos do Git | GustavoHenrique.net](http://blog.gustavohenrique.net/2011/03/comandos-basicos-do-git/)

* Tabless - Iniciando no GIT : [Parte 1](http://tableless.com.br/iniciando-no-git-parte-1/) | [Parte 2](http://tableless.com.br/iniciando-no-git-parte-2/)

* [Saíndo do Básico com Git | developerWorks IBM](http://www.ibm.com/developerworks/br/local/opensource/saindo_basico_git/) - Aprendendo a reescrever histórico e a rearranjar commits (18/06/2013) | escrito por: Fernando Granha Jeronimo, Engenheiro de Software, Linux Technology Center - IBM

* [How to GitHub: Fork, Branch, Track, Squash and Pull Request | Gun.io](http://gun.io/blog/how-to-github-fork-branch-and-pull-request/)

--

* [Controle de versão com Git | Simplificando Isto (ponto) Net](http://simplificandoisto.net/andre/blog/controle-de-versao-com-git/)

* [7 Useful Git Tips for Beginners | Six Revisions](http://sixrevisions.com/web-development/git-tips/)

* [Top 10 Git Tutorials for Beginners | Six Revisions](http://sixrevisions.com/resources/git-tutorials-beginners/)

--

* [[Speaker Deck] GitHub for Designers](https://speakerdeck.com/ashfurrow/github-for-designers)

  * [GitHub Fundamentals | Teehan+Lax](http://www.teehanlax.com/blog/github-fundamentals/)


### Referência

* [Git Reference](http://gitref.org/)

* [A Visual Git Reference](http://marklodato.github.com/visual-git-guide/index-en.html)

* [Why Git is Better than X](http://thkoch2001.github.io/whygitisbetter/)

* [[GitHub] tiimgreen / github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet) - A list of cool features of Git and GitHub

* [[GitHub] agis- / git-style-guide](https://github.com/agis-/git-style-guide) - A Git Style Guide


### Curso online

* [git - guia prático - sem complicação!](http://rogerdudler.github.com/git-guide/index.pt_BR.html)

* [Git Immersion](http://gitimmersion.com/) - is a guided tour that walks through the fundamentals of Git, inspired by the premise that to know a thing is to do it.

* [Git Tutorials and Training | Atlassian](https://www.atlassian.com/git)

* [Learn Git - Learn Version Control with Git | Git Tower](http://www.git-tower.com/learn/) - A step-by-step course for the complete beginner

* [[YouTube] Curso básico de Git](https://www.youtube.com/playlist?list=PLInBAd9OZCzzHBJjLFZzRl6DgUmOeG3H0)


### Cursos online interativos

* [Try Git - Code School](http://www.codeschool.com/courses/try-git)

* [GitHub - Try Git | created by Code School](http://try.github.com/)

* [Learn Git Branching](http://pcottle.github.io/learnGitBranching/index.html)


### Aprendizado: GitHub

* [Learn Git | GitHub Learn](http://learn.github.com/)

  * [git undoing | GitHub Learn](http://learn.github.com/p/undoing.html)

  * [How to undo (almost) anything with Git | GitHub Blog](https://github.com/blog/2019-how-to-undo-almost-anything-with-git) - 2015/06/08

* [GitHub Official Teaching Materials | GitHub Teach](http://teach.github.com/)

* [GitHub Training](http://training.github.com/)

* [GitHub Help](https://help.github.com/)

* [Team Collaboration With GitHub | Nettuts+](http://net.tutsplus.com/articles/general/team-collaboration-with-github/)


## Git em empresas

* [Git Turns 8, Sees Wide Adoption in the Enterprise | Linux.com](http://www.linux.com/news/enterprise/systems-management/715287-git-turns-8-enterprise-wide-adoption/) (20/04/2013)

* [Why the (legacy) Enterprise is Scared of Git – and what you can do about it – Laurence Sweeney | Opscode Blog](http://www.opscode.com/blog/chefconf-talks/why-the-legacy-enterprise-is-scared-of-git-and-what-you-can-do-about-it-laurence-sweeney/)

* [Thoughts on Git and 'Enterprise Open Source' | Guilherme Chapiewski](http://guilherme.pro/2012/06/12/thoughts-on-git-and-enterprise-open-source/)

* [Using Git in Enterprise environment | Programmers Stack Exchange](http://programmers.stackexchange.com/questions/96915/using-git-in-enterprise-environment)

* [Easy Configuration of Git for Windows on a Corporate Network | Programmatic Ponderings](http://programmaticponderings.wordpress.com/2013/12/25/managing-git-proxy/)

* [Setting git to work behind NTLM-authenticated proxy: cntlm to the rescue | A place for spare thoughts](http://sparethought.wordpress.com/2012/12/06/setting-git-to-work-behind-ntlm-authenticated-proxy-cntlm-to-the-rescue/)

--

* [Why DVCS, git, Atlassian Stash? | AppFusions](http://www.appfusions.com/display/StashSCMImporter/Why+DVCS,+git,+and+Atlassian+Stash)

* [Git Patterns and Anti-Patterns | DZone Refcardz](http://refcardz.dzone.com/refcardz/git-patterns-and-anti-patterns) - Scaling from Workgroup to Enterprise

* [Git Behind the Firewall with Atlassian Stash | Matthew Riley](http://matthewriley.us/git-behind-the-firewall-with-atlassian-stash/) (28/02/2013)

* [Git Branching and Forking in the Enterprise | Atlassian](http://blogs.atlassian.com/2013/05/git-branching-and-forking-in-the-enterprise-why-fork/) - Why Fork?

--

* [ALM vendors scramble to add support for Git | Ovum](http://ovum.com/2013/06/19/alm-vendors-scramble-to-add-support-for-git/)

* IBM

  * [Rational Team Concert](https://jazz.net/products/rational-team-concert/)

    * [Integrating other SCM Systems with Rational Team Concert 2.0 | Jazz Community](https://jazz.net/library/article/194/) - Git e IBM RTC

    * [Integrating Rational Team Concert and Git | Help - IBM Rational Software](http://pic.dhe.ibm.com/infocenter/clmhelp/v4r0m2/index.jsp?topic=%2Fcom.ibm.team.connector.cq.doc%2Ftopics%2Fc_integ_git.html)

  * [Collaborative Lifecycle Management](https://jazz.net/products/clm/)

    * [Connect Rational CLM to Atlassian JIRA, HP ALM, and Git or Gerrit | Jazz Community](https://jazz.net/products/clm/features/clm_integrations) - possibilidade de integrar ao Atlassian Jira e ao Git




## Dicas

* [GitLogs Search](http://www.gitlogs.com/) - A better interface for Github's search API

--

> **Commit de um diretório vazio**
>
> Dentro do respectivo diretório crie o arquivo **\*.gitkeep**

--

> **Ignorar o commit de arquivos e/ou diretórios**
>
> Para isso defina o arquivo **\*.gitignore**
>
> [Uma coleção com templates de .gitignore úteis](https://github.com/github/gitignore)
>
> [gitignore.io](http://www.gitignore.io/) - Create useful .gitignore files for your project - [github code](https://github.com/joeblau/gitignore.io)

--

> **Tag**
>
> * [2.6 Git Basics - Tagging](http://git-scm.com/book/en/Git-Basics-Tagging)
>
> * [Como trabalhar com tags no Git | iMasters](http://imasters.com.br/artigo/21127/software-livre/como-trabalhar-com-tags-no-git/)
>
> * [[StackOverflow] Rename a tag in git?](http://stackoverflow.com/questions/1028649/rename-a-tag-in-git)

--

* Error: pathspec 'branchName' did not match any file(s) known to git

  * [Git - Error: pathspec 'develop' did not match any file(s) known to git. | coderwall](https://coderwall.com/p/zcozuq/git-error-pathspec-develop-did-not-match-any-file-s-known-to-git) - by Antony D'Andrea

  * [Git: How to check out branches that exist on multiple remotes | makandropedia](http://makandracards.com/makandra/14323-git-how-to-check-out-branches-that-exist-on-multiple-remotes)

--

* [[StackOverflow] Git - how to revert uncommitted changes including files and folders?](https://stackoverflow.com/questions/5807137/git-how-to-revert-uncommitted-changes-including-files-and-folders/5812972#5812972)

```bash
# Revert changes to modified files.
git reset --hard

# Remove all untracked files and directories.
git clean -fd
```


* [How to undo (almost) anything with Git | The GitHub Blog](https://github.com/blog/2019-how-to-undo-almost-anything-with-git) - 2015/06/08

* [19 Tips For Everyday Git Use | Alex Kras](http://www.alexkras.com/19-git-tips-for-everyday-use/)

--

* [Git Large File Storage (LFS)](https://git-lfs.github.com/) replaces large files such as audio samples, videos, datasets, and graphics with text pointers inside Git, while storing the file contents on a remote server like GitHub.com or GitHub Enterprise.

--

* [[GitHub] zeke / ghwd](https://github.com/zeke/ghwd) - Open the github URL that matches your shell's current branch and working directory | mac and linux terminal utils

--

* [Everyday GIT With 20 Commands Or So](https://www.kernel.org/pub/software/scm/git/docs/everyday.html)

* [Git Basic Commands | Pankaj Kumar](http://panks.me/blog/2011/12/git-basic-commands/)

* [Git Hooks](http://githooks.com/) - Git hooks are scripts that Git executes before or after events such as: commit, push, and receive. Git hooks are a built-in feature - no need to download anything. Git hooks are run locally.

--

* [Configurando proxy no Git](http://rodrigoramalho.org/2012/03/14/configurando-proxy-no-git/)

* [Using git command with proxy network settings | Xinyustudio](http://xinyustudio.wordpress.com/2012/02/03/using-git-command-with-proxy/)

--

* [Release Your Software | GitHub Blog](https://github.com/blog/1547-release-your-software)

* [Very Easy Changelogs with Git | Tech.Pro](http://tech.pro/tutorial/1649/very-easy-changelogs-with-git)

* [Git Howto: Revert a Commit Already Pushed to a Remote Repository](http://christoph.ruegg.name/blog/2010/5/5/git-howto-revert-a-commit-already-pushed-to-a-remote-reposit.html)

* [9.7 Git Internamente - Manutenção e Recuperação de Dados | Pro Git](http://git-scm.com/book/pt-br/Git-Internamente-Manuten%C3%A7%C3%A3o-e-Recupera%C3%A7%C3%A3o-de-Dados)


### Workflow

* [GitHub Flow Like a Pro with these 13 Git Aliases | You've Been Haacked](http://haacked.com/archive/2014/07/28/github-flow-aliases/)

--

* [GitHub Flow in the Browser | GitHub Blog](https://github.com/blog/1557-github-flow-in-the-browser)

* [Understanding the Git Workflow](https://sandofsky.com/blog/git-workflow.html)

* [Simple Git workflow is simple | Atlassian Blogs](http://blogs.atlassian.com/2014/01/simple-git-workflow-simple/)

* [cheatsheet do git-flow](http://danielkummer.github.io/git-flow-cheatsheet/index.pt_BR.html) - O git-flow é um conjunto de extensões para o git que provê operações de alto-nível para repositórios usando o modelo de branches do Vincent Driessen.

* [Quatro workflows para trabalhar com Git | iMasters﻿](http://imasters.com.br/desenvolvimento/qatro-workflows-para-trabalhar-com-git/)


### Merge

* [Five advanced Git merge techniques](http://blog.ezyang.com/2010/01/advanced-git-merge/)

* [More Git and GitHub Secrets | Zach Holman](http://zachholman.com/talk/more-git-and-github-secrets/)

* [Please, use git pull --rebase](https://coderwall.com/p/7aymfa)

* [[GitHub] visionmedia / git-extras](https://github.com/visionmedia/git-extras) - GIT utilities - repo summary, repl, changelog population, author commit percentages and more (for Mac/Unix)

* [Using Sublime Text 2 as your default editor | github:help](https://help.github.com/articles/using-sublime-text-2-as-your-default-editor)

* [glog - a git log alias for a decent view of your repo : by Jed Schneider | Coder Wall](https://coderwall.com/p/syqplg)


#### Squash commits

* [Squash your commits | GitHub Blog](https://github.com/blog/2141-squash-your-commits) - 2016/04/01

* [Juntando commits com git rebase - squash commits](http://rodrigopinto.me/2013/03/05/juntando-commits-com-git-rebase-squash-commits/) - Dica para o pessoal que usa o git, basicamente o squash commit é  juntar vários commits referentes a uma mesma tarefa em um só commit.

* [git merge --squash | 365git](http://365git.tumblr.com/post/4364212086/git-merge-squash)

--

* Manual steps

```sh
git checkout target/branch

git checkout -b merge/branch

git merge --squash feature/branch

git add .

git commit -m $'squash feature/branch commits\ncloses #{pull request number}'

git checkout target/branch

git merge merge/branch

git push origin target/branch

git branch -D merge/branch

git push origin :feature/branch

git branch -D feature/branch
```


### SVN para GIT

* [Migrate your code with the GitHub Importer | GitHub Blog](https://github.com/blog/2110-migrate-your-code-with-the-github-importer) - 2016/02/11

--

* [Mudando do Subversion para o Git: antes tarde do que nunca | Pseudo-blog](http://luthiano.com/2012/11/12/mudando-do-subversion-para-o-git-antes-tarde-do-que-nunca/)

* [conversão do svn | git ready](http://pt-br.gitready.com/iniciante/2009/02/04/converting-from-svn.html)

--

* [git-svn(1) Manual Page | Kernel.org](https://www.kernel.org/pub/software/scm/git/docs/git-svn.html)

* [Como migrar um repositório de códigos Svn para Git | iMasters](http://imasters.com.br/desenvolvimento/como-migrar-um-repositorio-de-codigos-svn-para-git/)

* [8.2 Git e Outros Sistemas - Migrando para o Git | Pro Git](http://git-scm.com/book/pt-br/Git-e-Outros-Sistemas-Migrando-para-o-Git)

* [Migrating from SVN to Git, preserving branches and tags | Sailmaker Blog](http://www.sailmaker.co.uk/blog/2013/05/05/migrating-from-svn-to-git-preserving-branches-and-tags-3/)

* [Migrando um repositório SVN para GIT | leonardofaria.net](http://leonardofaria.net/2013/01/04/migrando-um-repositorio-svn-para-git/)

* [Converting subversion to git redux | linsec.ca blog ](http://linsec.ca/blog/2013/04/27/converting-subversion-to-git-redux/)

* [Converting a Subversion repository to Git | JohnAlbin](http://john.albin.net/git/convert-subversion-to-git) - 7 steps to migrate a complete mirror of svn in git


#### Problema conhecido

* [Git Svn clone certain revision, and continue cloning other revisions in the future](http://fatalweb.com/question/git-svn-clone-certain-revision-and-continue-cloning-other-revisions-in-the-future-17689582.html)

> RA layer request failed: REPORT request failed on '/svn/project/!svn/vcc/default': REPORT of '/svn/project/!svn/vcc/default': Could not read chunk size: Secure connection truncated (https://svn.myserver.com) at /usr/lib/perl5/site_perl/Git/SVN/Ra.pm line 282

* sugestão puxar parcialmente, iniciando em -r1:10000, por exemplo e depois puxar as demais partes

* **Quando ocorre?**

> Este erro ocorre em revisões do SVN, as quais possuem muitos arquivos associados, onde o servidor do SVN não consegue responder todas as informações.


### git submodule

* [git submodule Manual Page | git-scm](http://git-scm.com/docs/git-submodule)

* [6.6 Git Tools - Submodules | Pro Git | git-scm](http://git-scm.com/book/en/Git-Tools-Submodules)

* [Git Submodules Cheat Sheet | blog.jacius.info](http://blog.jacius.info/git-submodule-cheat-sheet/)

* [Git Submodules: Core Concept, Workflows And Tips | Atlassian Blogs](https://blogs.atlassian.com/2013/03/git-submodules-workflows-tips/)

* [[GitHub] NebuPookins / git-submodule-tutorial](https://github.com/NebuPookins/git-submodule-tutorial) - A tutorial on how to use git submodule to share a model across multiple applications

* [Working with submodules | GitHub Blog](https://github.com/blog/2104-working-with-submodules) - 2016/02/01

--

* [Generate GitHub pages in a submodule](http://blog.blindgaenger.net/generate_github_pages_in_a_submodule.html)


### git branch

> Encontrando branch's localmente que ainda não foram mesclados
>
> `git branch --no-merged`
>

* [git branch | git-scm docs](http://git-scm.com/docs/git-branch)

* [Learn Git Branching](http://pcottle.github.io/learnGitBranching/index.html)

* [A successful Git branching model](http://nvie.com/posts/a-successful-git-branching-model/)

* [[Gist] jbenet / simple-git-branching-model.md](https://gist.github.com/jbenet/ee6c9ac48068889b0912) - a simple git branching model

* [Desmitificando branches remotas com Git | Caelum](http://blog.caelum.com.br/desmitificando-branches-remotas-com-git/)

* [Branching and Merging | Git Reference](http://gitref.org/branching/)

* [Empurrando e puxando | Git Ready](http://pt-br.gitready.com/iniciante/2009/01/21/pushing-and-pulling.html)


### Fork de um repositório

* [Fork A Repo | GitHub:Help](https://help.github.com/articles/fork-a-repo)

* [Syncing a fork | GitHub:Help](https://help.github.com/articles/syncing-a-fork)

* [Using Pull Requests | GitHub:Help](https://help.github.com/articles/using-pull-requests)

* [Keep sync with another git repository? | StackOverflow](http://stackoverflow.com/questions/11646080/keep-sync-with-another-git-repository)

* [Syncing a Forked git Repository With a Master Repository´s Changes | Chris Case](https://chriscase.cc/2011/02/syncing-a-forked-git-repository-with-a-master-repositorys-changes/)

* [Manter repositório do Github forkado sincronizado com o original | Da2k Blog](http://blog.da2k.com.br/2014/01/19/manter-repositorio-github-forkado-sincronizado-com-o-original/)


### Colaboração

* [Gitter - Chat, for GitHub](http://gitter.im) - Free chat rooms for your public repositories. A bit like IRC only smarter.

--

* [Git (e Github) para dados | iMasters](http://imasters.com.br/desenvolvimento/git-e-github-para-dados/)

* [Clay Shirky: How the Internet will (one day) transform government | Ted Talks](http://www.ted.com/talks/clay_shirky_how_the_internet_will_one_day_transform_government.html) - The open-source world has learned to deal with a flood of new, oftentimes divergent, ideas using hosting services like GitHub -- so why can’t governments? In this rousing talk Clay Shirky shows how democracies can take a lesson from the Internet, to be not just transparent but also to draw on the knowledge of all their citizens. [Video no YouTube](https://www.youtube.com/watch?v=CEN4XNth61o)

  * [GitHub e Linux são exemplos para a política | Estadão](http://blogs.estadao.com.br/link/github-e-linux-sao-exemplos-para-a-politica/) (04/10/2012)

* [GitHub gains new prominence as the use of open source within governments grows | O'Reilly Radar](http://radar.oreilly.com/2013/03/github-government-bureaucat-open-source.html)

* [GitLaw: GitHub for Laws and Legal Documents - a Tourniquet for American Liberty | Abe Voelker](https://blog.abevoelker.com/gitlaw-github-for-laws-and-legal-documents-a-tourniquet-for-american-liberty/)

* [Writing a New Dictionary? | Fox News](http://video.foxbusiness.com/v/2667694577001/writing-new-dictionary) - Github’s CEO and co-founder Tom Preston-Werner breaks down his company’s goals and explains what it will take to continue its success.

* [Mother Forkers! Social Authoring (with Git) & The Developer Content Revolution | AirPair Blog](https://www.airpair.com/social-authoring)

--

* [GitHub and Government](http://government.github.com/) - Make government better, together

  * [Introducing government.github.com | GitHub Blog](https://github.com/blog/1657-introducing-government-github-com)

  * [GitHub lança plataforma voltada para governos | iMasters](http://imasters.com.br/noticia/github-lanca-plataforma-voltada-para-governos/)

--

* [Understanding Git: Collaborating](http://www.sbf5.com/~cduan/technical/git/git-4.shtml)

* [5.2 Git Distribuído - Contribuindo Para Um Projeto | Pro Git](http://git-scm.com/book/pt-br/Git-Distribu%C3%ADdo-Contribuindo-Para-Um-Projeto)

* [Working on other people's projects with Git | Barking Iguana](http://barkingiguana.com/2008/11/20/working-on-other-peoples-projects-with-git/)

* [git: fetch and merge, don’t pull](http://longair.net/blog/2009/04/16/git-fetch-and-merge/)


#### pull request

* [Checking out Pull Requests | GitHub Blog](https://github.com/blog/1582-checking-out-pull-requests)

* [git request-pull | Manual Page](http://git-scm.com/docs/git-request-pull)

* [[Gist] Checkout github pull requests locally](https://gist.github.com/piscisaureus/3342247)

* [Effective pull requests and other good practices for teams using GitHub](http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/)

* [Sending a "request to pull"](http://wiki.koha-community.org/wiki/Sending_a_%22request_to_pull%22)

* [How to send pull request on GIT | StackOverflow](http://stackoverflow.com/questions/6235379/how-to-send-pull-request-on-git)

* [Is it possible to create merge requests in pure Git from the **command line**? | StackOverflow](http://stackoverflow.com/questions/7273434/is-it-possible-to-create-merge-requests-in-pure-git-from-the-command-line)

* [How to use a signed tag in pull requests](https://www.kernel.org/pub/software/scm/git/docs/howto/using-signed-tag-in-pull-request.html)

* [Merging in a Pull Request](http://yuilibrary.com/yui/docs/tutorials/merge-pull-request/) - This tutorial is for developers who want to check out a Pull Request issued by another user. This is the workflow the YUI team follows to merge in Pull Requests to the YUI projects.

* [Conduct a Git pull request on Visual Studio Online | Microsoft Application Lifecycle Management - Site Home - MSDN Blogs](http://blogs.msdn.com/b/visualstudioalm/archive/2014/06/10/git-pull-request-visual-studio-online.aspx)


#### patch

* [git-format-patch(1) Manual Page | Kernel.org](https://www.kernel.org/pub/software/scm/git/docs/git-format-patch.html)

* [How to generate patches with git format-patch | OpenHatch wiki](https://openhatch.org/wiki/How_to_generate_patches_with_git_format-patch)

* [How to create and apply a patch with Git | ariejan.net](http://ariejan.net/2009/10/26/how-to-create-and-apply-a-patch-with-git/)

* [Applying patches with Git | drupal.org](https://drupal.org/node/1399218)

* [git - partially applying a patch | Python Tales and Plone Stories](http://devblog.4teamwork.ch/blog/2013/06/05/git-partially-applying-a-patch/) (utilizando: `git apply --reject file.patch` )



### Curiosidades

* [The Open Source Report Card](http://osrc.dfm.io/) - Enter a GitHub username to see a dynamically generated progress report for their open source contributions

* [StarWars + Git logs = StarLogs](http://starlogs.net/)

* [GitHub & BitBucket HTML Preview](http://htmlpreview.github.io/)

* [NodeJS + Nginx + Deploy pelo git](http://pablocantero.com/blog/2012/01/04/configurando-o-node-js-no-amazon-ec2/)

* [How to use Google Drive or Dropbox to host your private Git repositories](http://kahthong.com/2012/05/how-use-google-drive-or-dropbox-host-your-private-git-repositories)

* [Usando Dropbox para manter seu repositório Git | Igor Costa](http://www.igorcosta.com/usando-dropbox-para-manter-seu-repositorio-git/)

* [Usando Dropbox como Repositório GIT | Thiago Genez](http://blog.thiagogenez.com/2011/05/usando-dropbox-como-repositorio-git.html)

* [[GitHub] qrpike / NodeJS-Git-Server](https://github.com/qrpike/NodeJS-Git-Server) - A multi-tenant git server using NodeJS

* [Using GitHub as a personal maven repository](http://coffeecoders.de/2011/09/using-github-as-a-personal-maven-repository/)


### Dicas: GitHub

* [[GitHub] dbader / readme-template](https://github.com/dbader/readme-template) - README.md template for your open-source project

* [[GitHub] gist-run / gist-run](https://github.com/gist-run/gist-run) - Bring your Gists to life with [GistRun](https://gist.run/)

--

* [Automated Deployments with GitHub Webhooks | Toptal](http://www.toptal.com/devops/deploy-web-applications-automatically-using-github-webhooks)

* [How We Organize GitHub Issues - A Styleguide For Tagging | Robin at Work](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues/)

* [Issue and Pull Request templates | GitHub Blog](https://github.com/blog/2111-issue-and-pull-request-templates) - 2016/02/17

  * [[GitHub] devspace / awesome-github-templates](https://github.com/devspace/awesome-github-templates) - Curated list of GitHub Issues and Pull Requests templates

--

* [[Gist] How to show migration guides in GitHub Markdown](https://gist.github.com/staltz/728a18877948f059d570)

--

* [Embed Github Repos | insert.ly](http://www.insert.ly/) - New way to Embed Github Repos to your Blog & Web Sites!

* [Top Github Languages for 2013 (so far) | Adam Bard](http://adambard.com/blog/top-github-languages-for-2013-so-far/)

* [[GitHub] rgrove / rawgithub](https://github.com/rgrove/rawgithub) - rawgithub.com serves files from raw.github.com, but with the correct content types

* [Octotree | Google Chrome Extension](https://chrome.google.com/webstore/detail/octotree/bkhaagjahfmjljalopjnoealnfndnagc/) - Useful for developers who frequently read source in GitHub


#### gh-pages

* [GitHub Pages](https://pages.github.com/)

--

* [[GitHub] js-org / dns](https://github.com/js-org/dns) - free and short JS.ORG domains for GitHub Pages

--

* [Publicando páginas HTML+JS+CSS diretamente no GitHub - gist:833223](https://gist.github.com/chrisjacob/833223)

* [Criando páginas web para seus repositórios com o GitHub Pages | Tableless](http://tableless.com.br/criando-paginas-web-para-seus-repositorios-com-o-github-pages/)

* [Segredos do Github - Hospedando seu site no Github | Da2k Blog](http://blog.da2k.com.br/2015/02/05/segredos-do-github-hospedando-seu-site-no-github/)

* [Getting started with GitHub Pages](http://xlson.com/2010/11/09/getting-started-with-github-pages.html)

* [A Guide To Using Github Pages | Thinkful](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)

* [Easily keep gh-pages in sync with master | Lea Verou](http://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/)

* [Pushing to GitHub Pages gh-pages branch from only local master branch](http://blog.yjl.im/2012/02/pushing-to-github-pages-gh-pages-branch.html)

* [Easy Syncing of GitHub Pages](http://ryanfitzer.org/2011/11/easy-syncing-of-github-pages/)

* [Github as a CMS to end CMSes](http://paulhammant.com/blog/github-as-a-cms-to-end-cmses.html/)

* [Designing Custom Github Demo Pages](http://speckyboy.com/2013/03/04/designing-custom-github-demo-pages/)


#### Wiki

* [Adding a Table of Contents to your Github Wiki | BLACKBELT](http://blackbe.lt/github-wiki-sidebar-table-contents-header-footer/)


#### Livro online

* [GitBook](https://www.gitbook.io/) - Modern Publishing, Simply taking your books from ideas to finished, polished books.

  * [[GitHub] GitbookIO / gitbook](https://github.com/GitbookIO/gitbook) - Utility for generating books and exercises using GitHub/Git and Markdown

  * [Documentation | GitBook](http://help.gitbook.io/)

  * [Learn Markdown | GitBook](https://gitbookio.github.io/markdown/)


### Sistemas de Blog e Sites Estáticos

* [[GitHub] pinceladasdaweb / Static-Site-Generators](https://github.com/pinceladasdaweb/Static-Site-Generators) - A definitive list of tools for generating static websites.


#### Jekyll

* [Jekyll](http://jekyllrb.com/)

* [github pages tips for jekyll wiki](https://gist.github.com/jedschneider/2890453)

* [Servindo sites estáticos com Jekyll | Tableless](http://tableless.com.br/jekyll-servindo-sites-estaticos/) - Entenda como o Jekyll funciona e como ele pode te ajudar a fazer websites estáticos, sem banco de dados e fáceis de gerenciar.


#### Octopress

* [Site](http://octopress.org/) | [GitHub](https://github.com/imathis/octopress) | [Wiki](https://github.com/imathis/octopress/wiki)

* [Getting Started with Octopress | Webdesigntuts+](http://webdesign.tutsplus.com/tutorials/applications/getting-started-with-octopress/)

* [Deploying to Github Pages | Octopress](http://octopress.org/docs/deploying/github/)

* [Blog with Octopress and Github pages](http://kvz.io/blog/2012/09/25/blog-with-octopress/)

* [Instalando Octopress no Mountain Lion](http://gutocarvalho.net/octopress/2013/01/23/instalando-octopress-no-mountain-lion/)

* [From Wordpress to Octopress | Pankaj Kumar](http://panks.me/blog/2012/12/from-wordpress-to-octopress/)

* [Migrando o blog para o Octopress | Pedro Vanzella](http://ppvanzella.com/migrando-o-blog-para-o-octopress/)

* [Migrating from WordPress to Octopress](http://jason.pureconcepts.net/2013/01/migrating-wordpress-octopress/)


#### Hexo

* [Hexo - Node.js blog framework](http://zespia.tw/hexo/) - A fast, simple & powerful blog framework, powered by Node.js


####  Cabin.js

* [Cabin.js](http://www.cabinjs.com/) - Simple and extensible static site generator powered by Grunt.


#### Docpad

* [DocPad - Streamlined Web Development](http://docpad.org/) - build on top of node.js - Empower your website frontends with layouts, meta-data, pre-processors (markdown, jade, coffeescript, etc.), partials, skeletons, file watching, querying, and an amazing plugin system. Use it either standalone, as a build script, or even as a module in a bigger system. Either way, DocPad will streamline your web development process allowing you to craft full-featured websites quicker than ever before.

* [[GitHub] bevry / docpad](https://github.com/bevry/docpad)

* [Primeiros passos com o Docpad | Luiz Felipe Tartarotti Fialho](http://www.felipefialho.com/blog/2013/primeiros-passos-com-o-docpad/)


## Ferramentas

* [Git: ferramentas & dicas](http://www.daviferreira.com/posts/git-ferramentas-dicas)

* [Aplicações visuais para o Git | Tabless](http://tableless.com.br/git-com-interface-grafica/)

* [Git-SCM : Indicações](http://git-scm.com/downloads/guis)


### Gestão de servidor Git

* [GitLab](http://gitlab.org/) - Self hosted Git management software. Keep & manage your code on your own server. [[GitHub] gitlabhq / gitlabhq](https://github.com/gitlabhq/gitlabhq)

* [GitHub Enterprise](https://enterprise.github.com/)

* [Atlassian Stash](https://www.atlassian.com/software/stash)

* [TeamForge for Git | CollabNet](http://www.collab.net/products/teamforge/git-for-the-enterprise) - Central control for DVCS. Enterprise-grade security and compliance.


### Mac

* [GitHub:Mac](http://mac.github.com/)

* [Atlassian SourceTree](http://www.sourcetreeapp.com/) -  Git e Mercurial. Necessário registrar, porém a licensa é gratuíta.

* [GitX](http://gitx.frim.nl/)


### Windows

* [GitHub:Windows](http://windows.github.com/)

* [GitExtensions](https://code.google.com/p/gitextensions/)

* [msysgit](http://msysgit.github.io/)

* [5 Windows Git Clients To 'Git' The Job Done](http://www.makeuseof.com/tag/5-windows-git-clients-git-job/)

* [Best git clients on windows](http://gitstack.com/best-git-clients-on-windows/)

* [[GitHub Blog] GitHub for Windows Recent Improvements](https://github.com/blog/1420-github-for-windows-recent-improvements)

* [Atlassian SourceTree](http://www.sourcetreeapp.com/) - Git e Mercurial | apenas para Windows 7 ou superior. Necessário registrar, porém a licensa é gratuíta.

* [TortoiseGit](https://code.google.com/p/tortoisegit/)


### Windows, Linux e Mac

* [GitEye | CollabNet](http://www.collab.net/giteyeapp)

* [SmartGit](http://www.syntevo.com/smartgithg)

* [Git-Cola](http://git-cola.github.com/)

* ungit : [[GitHub] FredrikNoren / ungit](https://github.com/FredrikNoren/ungit) | [npm](https://npmjs.org/package/ungit) | [[Youtube] Introduction](https://www.youtube.com/watch?v=hkBVAi3oKvo) - The easiest way to use git. On any platform. Anywhere. (Node.js)

  * [Ungit real with this great web based UI - by shoogle designs | shoogle designs' blog](http://shoogledesigns.com/blog/blog/2013/10/11/ungit-real-great-web-based-ui/)


### Eclipse IDE - Git plugin

* [GitHub: Eclipse | eGit - Git in Eclipse](http://eclipse.github.com/)

* [Tutorial: Usando o EGit Eclipse Plugin com o GitHub | Loiane](http://www.loiane.com/2009/11/tutorial-usando-o-egit-eclipse-plugin-com-o-github/)

* [Tips and Tricks: Using Eclipse with GitHub](http://eclipsesource.com/blogs/2012/08/28/tips-and-tricks-using-eclipse-with-github/)

* [Git version control with Eclipse (EGit) - Tutorial](http://www.vogella.com/articles/EGit/article.html)



## Quem usa o Git/GitHub?

### Governos

#### Brasil

* [PloneGovBr](http://www.softwarelivre.gov.br/plone)

* [PloneGovBr no GitHub](https://github.com/plonegovbr)

* [DadosGovBr](http://dados.gov.br/)

* [DadosGovBr no GitHub](https://github.com/dadosgovbr)

* [Demoiselle](http://www.frameworkdemoiselle.gov.br/) | [GitHub](https://github.com/demoiselle) - é um conjunto de seis projetos, sendo cinco de software e um processo de desenvolvimento (Framework em Java criado pelo SERPRO)

#### Estados Unidos

* [Casa Branca no GitHub](https://github.com/WhiteHouse)

  * [Casa Branca lança primeiro sistema no GitHub, baseado em PHP/MySQL e MongoDB | InfoQ Br](http://www.infoq.com/br/news/2012/08/casa-branca-opensource) (29/08/2012)


### Empresas

#### NASA

* [NASA Open Source Software versioned with Git | code.NASA](http://code.nasa.gov/version-control-system/git/)

* [NASA no GitHub](https://github.com/nasa)


#### SAP

* [SAP no GitHub](http://sap.github.io/)

* [Essentials - Working with Git & Maven in Eclipse | SAP Community Network](http://scn.sap.com/community/developer-center/cloud-platform/blog/2012/11/02/essentials--working-with-git-maven-in-eclipse)


#### Microsoft

* [Windows Azure SDK team on GitHub](http://windowsazure.github.io/)

* Notícia sobre o início do suporte da Microsoft ao Git

  * [Visual Studio 2012 ganha suporte a Git | InfoQ Br](http://www.infoq.com/br/news/2013/02/vs2012-suporte-git)

  * [Git init VS | Brian Harry's blog : MSDN](https://blogs.msdn.com/b/bharry/archive/2013/01/30/git-init-vs.aspx)

  * [Microsoft Announces Git Support For Visual Studio, Team Foundation Server And Service | TechCrunch](http://techcrunch.com/2013/01/30/microsoft-announces-git-support-for-visual-studio-team-foundation-server-and-service/) (30/01/2013)

  * [TFS Now Integrated with Git | Visual Studio Magazine](http://visualstudiomagazine.com/articles/2012/08/13/tfs-now-integrated-with-git.aspx) (13/08/2012)

  * [Getting started with Git and TFS | ALM Guide - Esteban Garcia](http://www.almguide.com/2013/04/getting-started-with-git-and-tfs/)


* [Visual Studio 2012 update 3](https://www.microsoft.com/en-us/download/details.aspx?id=39305) | [Visual Studio Tools for Git](http://visualstudiogallery.msdn.microsoft.com/abafc7d6-dcaa-40f4-8a5e-d6724bdb980c) - Free

* [Getting Started with Git in Visual Studio and Team Foundation Service | MSDN](https://blogs.msdn.com/b/visualstudioalm/archive/2013/01/30/getting-started-with-git-in-visual-studio-and-team-foundation-service.aspx)

* [Create a new code project in a local Git repo using Visual Studio with Git | Team Foundation Service](http://tfs.visualstudio.com/en-us/learn/create-code-project-vs-git.aspx)

* [Git support for Visual Studio - Git, TFS, and VS put into Context | Scott Hanselman](http://www.hanselman.com/blog/GitSupportForVisualStudioGitTFSAndVSPutIntoContext.aspx)

* [Use Git and Xcode with TFS](http://tfs.visualstudio.com/en-us/learn/use-git-and-xcode-with-tfs.aspx)


#### Globo.com

* [Globo.com](http://www.globo.com/)

* [Globo.com no GitHub](https://github.com/globocom)

* [Projetos e Colaboradores do Globo.com no GitHub](http://opensource.globo.com/)

* [[GitHub] globocom / IWantToWorkAtGloboCom](https://github.com/globocom/IWantToWorkAtGloboCom) - seleção de desenvolvedores
