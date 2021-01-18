# Minhas Ferramentas no Visual Studio Code.
![Version](https://img.shields.io/badge/Version-1.0.0-F21B3F) ![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-Markdown-blue)

![image](https://user-images.githubusercontent.com/71250901/104920020-ed2b0f80-5975-11eb-8bd2-10d874dbc0e9.png)

# Primeiro o que é o Visual Studio code?
O **Visual Studio Code é um editor de código-fonte** desenvolvido pela Microsoft para Windows, Linux e macOS. Ele inclui suporte para depuração, controle Git incorporado, realce de sintaxe, complementação inteligente de código, snippets e refatoração de código. Ele também é **customizável**, fazendo com que os usuários possam mudar o tema do editor, teclas de atalho e preferências. Ele é um software livre e de código aberto, apesar do download oficial estar sob uma licença proprietária.

## Conteúdos

  - [o que é o Vscode](#primeiro-o-que-é-o-visual-studio-code)
  - [Conteúdos](#conteúdos)
  - [Ferramentas que uso](#ferramentas-que-eu-utlizo-no-vscode)
  - [o que cada ferramenta faz](#o-que-cada-ferramenta-faz)
  - [Como contribuir](#como-contribuir)

 
## ferramentas que eu utilizo:

 - [Code Runner:](#code-runner)
 - [Dracula Official.](#dracula-official)
 - [GitLens.](#gitlens)
 - [Live Server.](#live-server)
 - [Markdown all in one.](#markdown-all-in-one)
 - [Portuguese(Brazil) languange pack.](#portuguesebrazil-languange-pack)


 

### O que cada ferramenta faz?

#### Code Runner:
   
![image](https://user-images.githubusercontent.com/71250901/104915848-fd3ff080-596f-11eb-96b9-c49c8bf6e5a5.png)

Execute snippet de código ou arquivo de código para várias linguagens: C, C ++, Java, JavaScript, PHP, Python, Perl, Perl 6, Ruby, Go, Lua, Groovy, PowerShell, BAT / CMD, BASH / SH, F # Script, F # ( .NET Core), C # Script, C # (.NET Core), VBScript, TypeScript, CoffeeScript, Scala, Swift, Julia, Crystal, OCaml Script, R, AppleScript, Elixir, Visual Basic .NET, Clojure, Haxe, Objective-C , Rust, Racket, Scheme, AutoHotkey, AutoIt, Kotlin, Dart, Free Pascal, Haskell, Nim, D, Lisp, Kit, V, SCSS, Sass, CUDA, Less, Fortran e comando personalizado.

Características
- **Execute** o arquivo de código do Editor de Texto ativo atual.
- **Execute** o arquivo de código através do menu de contexto do explorador de arquivos.
- **Execute** o trecho de código selecionado no Editor de Texto.
- **Execute** o código por Shebang.
- **Execute** o código por nome de arquivo glob.
- **Executar** comando personalizado.
- **Pare** a execução do código.
- **Ver** saída na janela de saída.
- **Defina** o idioma padrão para executar.
- **Selecione** o idioma para executar.
- **Suporte** REPL executando código no Terminal Integrado.

**Usos**
- **Para executar o código:**
    - usar atalho Ctrl+Alt+N
    - ou pressione F1e selecione / digite Run Code,
    - ou clique com o botão direito do mouse no Editor de Texto e clique Run Codeno menu de contexto do editor
    - ou clique Run Codeno botão no menu do título do editor
    - ou clique Run Codeno botão no menu de contexto do explorador de arquivos
- **Para interromper a execução do código:**
    - usar atalho Ctrl+Alt+M
    - ou pressione F1e selecione / digiteStop Code Run
   - ou clique com o botão direito no canal de saída e clique Stop Code Runno menu de contexto
  

<img src="https://github.com/formulahendry/vscode-code-runner/raw/master/images/usage.gif">

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)

#### Dracula Official.

![image](https://user-images.githubusercontent.com/71250901/104915721-d386c980-596f-11eb-9f40-7e53780240eb.png)

**Tema** é algo que todo mundo gosta de alterar na IDE e colocar de acordo a sua cara. E um dos temas mais baixados para quem usa o VsCode é o **Dracula**.
Ele vem com várias cores e temas que você pode alterar de acordo com o seu gosto. Eu muito o tema Dracula Dark (como da imagem abaixo)😊.

![image](https://user-images.githubusercontent.com/71250901/104916066-53149880-5970-11eb-95f1-87bb4c0b3e7f.png)

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)

#### GitLens.

![image](https://user-images.githubusercontent.com/71250901/104916470-e1891a00-5970-11eb-9878-e1073604becb.png)

**GitLens** é uma extensão de código aberto para Visual Studio Code criado, desenvolvido e mantido por Eric Amodio.

**GitLens** simplesmente ajuda você a entender melhor o código . Vislumbre rapidamente quem, por que e quando uma linha ou bloco de código foi alterado. Volte na história para obter mais insights sobre como e por que o código evoluiu. Explore sem esforço a história e a evolução de uma base de código.

**GitLens** é poderoso , rico em recursos e altamente personalizável para atender às suas necessidades. Você acha que a lente do código é intrusiva ou a anotação de culpa da linha atual é perturbadora - sem problemas, desligue-as rapidamente ou mude como elas se comportam por meio do editor interativo de configurações GitLens . Para personalizações avançadas, consulte os documentos GitLens e edite suas configurações de usuário .

Aqui estão apenas alguns dos **recursos** que o GitLens oferece,

- Navegação de revisão sem esforço (para trás e para frente) através do histórico de um arquivo
- uma anotação de culpa de linha atual discreta no final da linha mostrando o commit e o autor que modificou a linha pela última vez, com informações de culpa mais detalhadas acessíveis ao passar o mouse
- Lente do código de autoria mostrando o commit mais recente e o número de autores no topo dos arquivos e / ou em blocos de código
- Uma anotação de culpa na barra de status mostrando o commit e o autor que modificou a linha atual pela última vez
- Anotações de arquivo sob demanda na calha do editor, incluindo
    - Culpa - mostra o commit e o autor que modificou cada linha de um arquivo pela última vez
    - Alterações - destaca quaisquer alterações locais (não publicadas) ou linhas alteradas pelo commit mais recente
    - Mapa de calor - mostra como as linhas foram alteradas recentemente, em relação a todas as outras alterações no arquivo e até agora (quente x frio)
- Muitas vistas ricas da barra lateral
    - Uma visão de commits para visualizar, explorar e gerenciar commits Git
    - Uma visualização Repositórios para visualizar, explorar e gerenciar repositórios Git
    - Uma visão de histórico de arquivo para visualizar, navegar e explorar o histórico de revisão do arquivo atual ou apenas as linhas selecionadas do arquivo atual
    - Uma visualização de Histórico de linha para visualizar, navegar e explorar o histórico de revisão das linhas selecionadas do arquivo atual
    - Uma visualização de ramos para visualizar, explorar e gerenciar ramos Git
    - Um Remotes visualizar para visualizar, explorar e gerenciar controles remotos Git e filiais remotas
    - Uma visualização Stashes para visualizar, explorar e gerenciar stashes Git
    - Uma visualização de tags para visualizar, explorar e gerenciar tags Git
    - Uma visualização de colaboradores para visualizar, navegar e explorar colaboradores
    - Uma visualização de Pesquisa e Comparação para pesquisar e explorar históricos de commits por mensagem, autor, arquivos, id, etc, ou visualizar comparações entre branches, tags, commits e mais
- Uma Paleta de comandos Git para fornecer acesso guiado (passo a passo) a muitos comandos Git comuns, bem como acesso rápido a
    - Commits - histórico e pesquisa.
    - Esconderijos
    - Status - branch atual e status da árvore de trabalho
- Um editor de rebase interativo amigável para configurar facilmente uma sessão de rebase interativa
- Links de terminal -ctrl+clickem autolinks no terminal integrado para ir rapidamente para mais detalhes para commits, branches, tags e muito mais
- Ricas integrações de provedor remoto - GitHub, GitLab, Bitbucket, Azure DevOps
    - Emitir e obter link automático de solicitação
    - Informações valiosas de foco fornecidas para problemas vinculados e solicitações pull (apenas GitHub)
    - Associa solicitações de pull a branches e commits (somente GitHub)
- Muitos comandos poderosos para navegar e comparar revisões e muito mais
- Modos definidos pelo usuário para alternar rapidamente entre conjuntos de configurações
- e muito mais 😁

<img src="https://raw.githubusercontent.com/eamodio/vscode-gitlens/main/images/docs/revision-navigation.gif">

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)

#### Live Server.
   
![image](https://user-images.githubusercontent.com/71250901/104916539-fb2a6180-5970-11eb-89e4-6e846ff10f8f.png)

Ajuda na visualização, pois conforme você digita no VsCode, atualiza automaticamente na página WEB.


<img src="https://github.com/ritwickdey/vscode-live-server/raw/master/images/Screenshot/vscode-live-server-animated-demo.gif">

**Características**
- Um Quick Development Live Server com recarga de navegador ao vivo.
- Inicie ou pare o servidor com um único clique na barra de status.
- Abra um arquivo HTML para o navegador a partir do menu do Explorer. [ Quick Gif Demo ].
- Suporte para exclusão de arquivos para detecção de alterações.
- Controle de tecla de atalho.
- Número da porta personalizável, raiz do servidor, navegador padrão.
- Suporte para qualquer navegador (Ex: Firefox Nightly) usando linha de comando avançada.
- Suporte para anexo de depuração do Chrome ( mais informações ). [ Demonstração rápida do Gif ].
- Conexão remota através de WLAN (por exemplo: conectar com celular) [Precisa de ajuda? Consulte a seção FAQ]
- Use o nome de host preferível (localhost ou 127.0.0.1) .
- Tag de suporte personalizável para o recurso Live Reload. (O padrão é Bodyou head)
- Suporte SVG
- https Apoio, suporte.
- Suporte para proxy.
- CORS ativado
- Espaço de trabalho multi-root suportado.
- Suporte para qualquer arquivo, até mesmo páginas dinâmicas, por meio do Live Server Web Extension .

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)

#### Markdown all in one.

![image](https://user-images.githubusercontent.com/71250901/104916630-18f7c680-5971-11eb-81ee-654bbbe64605.png)

Markdown como uma linguagem de marcação leve tem sido usada extensivamente por escritores e desenvolvedores da web em sites muito populares por algum tempo, o mais popular é, possivelmente, o GitHub. Imagine se a Microsoft nos anos 90 criasse o Microsoft Word, mas para a Internet? Isso seria Markdown. Markdown é um formato de texto simples, convertido em HTML estruturalmente válido.

 <img src="https://github.com/yzhang-gh/vscode-markdown/raw/master/images/gifs/section-numbers.gif">

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)

#### Portuguese(brazil) languange pack.
   
![image](https://user-images.githubusercontent.com/71250901/104916719-34fb6800-5971-11eb-9581-888d088ea4d6.png)

**Pacote de idioma português (Brasil) para o código VS**
O pacote de idiomas em português (Brasil) fornece experiência de interface do usuário localizada para o VS Code.

**Uso**
Uma vez instalado, configurado "locale": "pt-br"em locale.jsoncarregar Português (Brasil) Language Pack. Para modificar, locale.jsonpressione Ctrl+Shift+Ppara abrir a Paleta de comandos , comece a digitar “config” para filtrar a lista de comandos disponíveis e selecione o comando Configurar idioma . Consulte o Docs para obter mais informações.

[Voltar às ferramentas](#ferramentas-que-eu-utilizo)
## Como contribuir

Contribuições são sempre bem-vindas. Existem várias maneiras de contribuir com este projeto, como:

💪 Se juntando ao time de desenvolvimento.

🌟 Dando uma estrela no projeto.

🐛 Reportando um Bug.

😅 Indicando um vacilo que eu possa ter cometido.

📄 Ajudando a melhorar a documentação.

🚀 Compartilhando este projeto com seus amigos.

[Voltar ao topo](#conteúdos)