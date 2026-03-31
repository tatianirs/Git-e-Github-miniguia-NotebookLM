# Git-e-Github-miniguia-NotebookLM
🚀 Guia Completo de Git &amp; GitHub para Iniciantes – Do zero à publicação! Criado com NotebookLM + DIO Challenge. Resumos práticos, glossário essencial, prompts IA reutilizáveis e workflow infalível. Seu 1º repo sem erros! Clone agora e domine versionamento. ⭐ #Git #GitHub #DIO

**Descubra o poder do versionamento de código do zero!** Este repositório é o resultado prático de um desafio da DIO, onde usei **NotebookLM** e IA para criar um **mini guia temático** sobre Git e GitHub. Ideal para quem, como eu, acessa a plataforma pela **primeira vez** e precisa dominar o essencial para publicar projetos, colaborar e brilhar no portfólio.

Se você é novo no GitHub e quer **publicar seu primeiro repo sem dor de cabeça**, este guia é o seu mapa! Aprenda com resumos práticos, glossário e prompts prontos para reutilizar na IA.

## 🎯 Contexto e Objetivos
**Assunto escolhido**: Git e GitHub para iniciantes total.  
**Por quê?** Minha primeira vez na plataforma – zero conhecimento prévio! O objetivo é aprender o básico para criar, commitar e publicar este repo mesmo, fechando o ciclo do desafio DIO.  
**Ganhos esperados**: Dominar comandos essenciais, entender fluxos de trabalho e ganhar confiança para projetos reais.

## 📚 Curadoria de Fontes
Aqui vão **5 fontes abertas** selecionadas e processadas no NotebookLM (links + PDFs upados para análise):

1- https://www.youtube.com/watch?v=-l4Aa8wef8s
2- https://www.youtube.com/watch?v=BUGZZaChiYw
3- https://www.youtube.com/watch?v=EGmzAs1G0z0
4- https://docs.github.com/pt/get-started/learning-to-code/getting-started-with-git
5- https://git-scm.com/book/en/v2

**Referências**: Ao todo, foram consideradas 29 fontes dentre as fontes adicionadas manualmente e as fontes de busca pela web realizadas pelo próprio NotebookLM

## 🔧 Engenharia de Prompts e "Cicatrizes"
**Prompts testados** (e lições aprendidas):
- **Inicial**: "Haja como um especialista em git e github e explique o que é git e github, a diferença entre eles e para que são utilizados. Apresente uma instrução de como obter ou instalar considerando que esta instrução é para uma pessoa que está acessando o github pela primeira vez e também não é desenvolvedor de códigos. Seja bastante detalhista na orientação do passo a passo em como instalar o git." → Resposta boa e instrutiva, mas foi toda direcionada para a instalação em sistema Microsoft. *Cicatriz*: Adicionei "Reformular a instrução para a instalação do git em sistema Linux".

**Resposta NotebookLM**: Entender a diferença entre Git e GitHub é o primeiro passo para organizar seus projetos de forma profissional, mesmo que você não pretenda escrever uma única linha de código

O que é o Git?
O Git é um software de controle de versão gratuito que você instala diretamente no seu computador
Imagine o Git como uma "máquina do tempo" ou um "cartão de memória" para seus arquivos: ele permite que você salve o progresso do seu trabalho gradualmente e, se algo der errado no futuro, você pode retornar exatamente para uma versão anterior que estava funcionando
Ele rastreia cada pequena alteração feita, registrando quem a fez e quando

O que é o GitHub?
O GitHub é uma plataforma online que hospeda os seus projetos que utilizam o Git
Se o Git é o motor do carro que faz o trabalho pesado localmente, o GitHub é a "garagem" ou um "Google Drive especializado" onde você guarda e compartilha seus arquivos na nuvem
Ele serve para garantir a segurança dos seus dados (backup), permitir que outras pessoas colaborem no seu projeto e facilitar a publicação do seu trabalho na internet

Passo a Passo Detalhado para Instalação do Git
Para um iniciante que não utiliza o terminal no dia a dia, a instalação exige atenção a alguns detalhes de configuração:
Acesse o site oficial: Vá até git-scm.com

Baixe a versão correta: Clique no botão de download correspondente ao seu sistema operacional (Windows, macOS ou Linux)
No Windows, é importante verificar se seu sistema é de 64 bits, que é o padrão mais comum atualmente

Inicie o instalador: Abra o arquivo baixado e aceite os termos da licença

Escolha do Editor (Muito Importante): Durante a instalação no Windows, você chegará a uma tela perguntando qual será o editor padrão do Git
Por padrão, ele sugere o "Vim" (que é muito complexo para iniciantes); recomenda-se alterar essa opção para o "Visual Studio Code" ou outro editor de texto simples que você já utilize

Mantenha os padrões: Nas telas seguintes, o instalador oferecerá diversas opções técnicas. Para quem está começando, a recomendação de especialistas é manter as opções de fábrica ("Next") até o final, pois as configurações padrão atendem perfeitamente à maioria dos usuários

Finalização: Clique em "Install" e aguarde a conclusão

Configuração Inicial de Identidade
Após instalar, o Git precisa saber quem você é para "assinar" as versões que você salvar.
Abra o terminal: No Windows, procure por "Git Bash" no menu iniciar
No Linux ou Mac, abra o aplicativo "Terminal"

Verifique a instalação: Digite o comando git --version e aperte Enter
Se aparecer um número de versão, a instalação foi um sucesso

Configure seu Nome: Digite o seguinte comando (substituindo pelo seu nome entre aspas): git config --global user.name "Seu Nome"

Configure seu E-mail: Digite o comando abaixo usando exatamente o mesmo e-mail que você usará para criar sua conta no GitHub: git config --global user.email "seuemail@exemplo.com"

Criando sua conta no GitHub
Agora que o Git está pronto no seu PC, acesse github.com e clique em "Sign up"
Escolha um nome de usuário profissional, pois ele servirá como seu portfólio para o mercado de trabalho
Após criar a conta, não esqueça de ativar a autenticação de dois fatores (2FA) nas configurações de segurança para proteger seus arquivos contra acessos não autorizados
  
- **Próximo passo**: "Como um especialista em github, relate mais sobre o readme. O que é, para que serve e como utilizar pela primeira vez." → A resposta atendeu aos objetivos e me permitiu essa elaboração atual. 

**Resposta NotebookLM**: O README (geralmente nomeado como README.md) é considerado a "porta de entrada" ou a capa do seu projeto no GitHub
O nome vem do inglês e significa literalmente "leia-me", funcionando como o manual de instruções ou guia de introdução essencial para qualquer pessoa que visite seu repositório

O que é e para que serve?
Apresentação Visual: O conteúdo do arquivo README é exibido automaticamente na página principal do repositório, sendo a primeira coisa que os visitantes e recrutadores veem

Documentação Central: Ele serve para armazenar informações que não pertencem ao código em si, como o propósito do projeto, por que ele é útil, como instalá-lo, como executá-lo e detalhes sobre quem contribuiu

Linguagem Markdown: O arquivo utiliza a extensão .md, que se refere ao Markdown, uma linguagem de marcação simples e fácil de ler que permite formatar texto (negrito, links, listas) sem complexidade

Destaque Profissional: Para quem não é desenvolvedor, um README bem estruturado demonstra zelo, organização e cuidado com o trabalho, elevando o nível do seu portfólio aos olhos de recrutadores

Como utilizar pela primeira vez
Existem duas maneiras principais de começar a usar um README:
Criação Automática (Recomendado): Ao criar um novo repositório no site do GitHub ou no GitHub Desktop, basta marcar a caixa de seleção "Add a README file" (Adicionar um arquivo LEIAME)
Isso inicializa o projeto com um arquivo pronto para ser editado

Criação Manual: Você pode criar um novo arquivo de texto dentro da sua pasta de projeto local e nomeá-lo exatamente como README.md

Dicas para seu primeiro conteúdo
Para um bom README inicial, você deve incluir:
Título e Descrição: Um nome memorável e um resumo do que o projeto faz

Instruções Simples: Explique o passo a passo necessário para que outra pessoa consiga entender e usar o que você postou

Edição Direta: Você pode editar o arquivo diretamente no GitHub clicando no ícone de lápis ou em seu editor de texto favorito (como o VS Code) e depois realizar o commit para salvar as alterações

Dica Extra para Portfólio: Você pode criar um "README de Perfil" especial, que aparece na sua página inicial de usuário. Para isso, crie um novo repositório com o mesmo nome do seu nome de usuário (ex: seu-usuario/seu-usuario). Esse repositório especial permite que você personalize sua biografia com emojis, links sociais e status dinâmicos

- **Estratégico**: "Crie um glossário com os principais conceitos aprendidos" → Perfeito!

**Resposta NotebookLM**: Com base nos materiais fornecidos, aqui está um glossário com os principais conceitos essenciais para entender o ecossistema Git e GitHub:
A - C
Área de Preparação (Staging Area/Index): É uma zona intermediária onde você seleciona e organiza as alterações que deseja incluir no seu próximo salvamento

Branch (Ramo/Ramificação): Uma linha do tempo paralela no seu projeto
Permite desenvolver novas funcionalidades ou corrigir erros sem afetar a versão principal (main)

Clone: O ato de criar uma cópia local (no seu computador) de um repositório que está hospedado na nuvem

Commit: Um "instantâneo" ou foto do estado dos seus arquivos em um determinado momento
Cada commit possui uma mensagem descritiva e um código único de identificação (Hashcode)

F - G
Fetch: Comando que busca atualizações no servidor remoto para ver o que mudou, mas sem aplicar essas alterações automaticamente nos seus arquivos locais

Fork: Uma cópia de um repositório de outra pessoa para a sua própria conta do GitHub, permitindo que você faça alterações de forma independente

Git: Um software de controle de versão que rastreia o histórico de alterações nos arquivos localmente no computador

GitHub: Uma plataforma online baseada na nuvem que hospeda repositórios Git, facilitando a colaboração e o backup

gitignore: Um arquivo de texto onde você lista arquivos ou pastas que o Git deve ignorar (como senhas ou arquivos temporários), evitando que sejam enviados para a nuvem

M - P
Markdown (.md): Uma linguagem de marcação simples usada para formatar textos (como negritos e listas), muito utilizada na criação de arquivos README

Merge (Fusão): O processo de unir as alterações de um branch secundário de volta para o branch principal

Pull: O ato de "puxar" ou baixar as alterações do GitHub para o seu computador, sincronizando sua versão local com a da nuvem

Pull Request (PR): Uma proposta formal para que suas alterações sejam revisadas e integradas ao projeto original. É a base da colaboração no GitHub

Push: O ato de "empurrar" ou enviar seus commits locais para o servidor remoto no GitHub

R - S
README.md: O arquivo que serve como a "capa" ou manual de instruções do seu projeto. Ele aparece automaticamente na página principal do repositório

Repositório (Repo): Uma pasta virtual que armazena todos os arquivos de um projeto e todo o seu histórico de versões
Pode ser local (no PC) ou remoto (na nuvem)

SSH (Secure Shell): Um protocolo que permite uma conexão segura e criptografada entre seu computador e o GitHub, eliminando a necessidade de digitar usuário e senha repetidamente


- **Seguindo com o modo introdutivo**: "Explique detalhadamente, com passo a passo, como um projeto criado em meu computador é publicado no github" → Dificuldade: IA não foi clara quanto ao uso do github desktop e principalmente como instalar no Linux. *Solução*: Foi necessário aumentar as fontes de dados inscluindo artigos de como instalar github desktop em linux Lux2 Bellatrix e Prompt refinado com "e inclua a instrução de como instalar o github desktop para linux".

**Resposta NotebookLM**: Para publicar um projeto que você já iniciou no seu computador no GitHub, você precisa transformar a sua pasta local em um repositório Git e conectá-la a um repositório remoto na nuvem

Existem dois caminhos principais: utilizar a Linha de Comando (Terminal) ou o GitHub Desktop. Abaixo está o detalhamento de ambos:
Método 1: Utilizando a Linha de Comando (Terminal)
Este método é o padrão utilizado por desenvolvedores e envolve os seguintes passos:
Prepare seu ambiente: Certifique-se de que o Git está instalado e sua identidade (nome e e-mail) configurada no terminal

Inicie o repositório local: Abra o terminal na pasta raiz do seu projeto e digite o comando git init
Isso criará uma pasta oculta .git que rastreará todas as alterações nos seus arquivos

Crie o repositório no GitHub:
Acesse sua conta em github.com e clique no botão "New" ou "+" no canto superior direito

Dê um nome ao repositório (preferencialmente o mesmo da sua pasta local) e escolha a visibilidade (Público ou Privado)

Importante: No caso de um projeto já existente no PC, não selecione a opção de inicializar com README, .gitignore ou licença para evitar conflitos

Clique em "Create repository" e copie a URL HTTPS que aparecerá na tela

Conecte o seu PC ao GitHub: No terminal, informe ao Git para onde ele deve enviar os arquivos com o comando:
git remote add origin URL_DO_REPOSITORIO
(O termo "origin" é um apelido padrão para o seu repositório na nuvem)

Prepare e salve seus arquivos (Commit):
Adicione todos os arquivos para a área de preparação: git add .

Grave a primeira versão do projeto: git commit -m "Meu primeiro commit"

Envie para a nuvem (Push):
Defina a ramificação principal como main: git branch -M main

Envie os arquivos: git push -u origin main

Nesta etapa, o sistema poderá solicitar que você faça login pelo navegador para autenticar a conexão


--------------------------------------------------------------------------------
Método 2: Utilizando o GitHub Desktop (Interface Visual)
Para quem não é desenvolvedor, esta é a forma mais intuitiva, pois substitui os comandos de texto por botões

Adicione o projeto ao App:
Abra o GitHub Desktop e vá em File > Add Local Repository

Selecione a pasta do seu projeto no seu computador

O aplicativo avisará que a pasta não é um repositório Git. Clique em "Create a repository" para inicializá-la

Configurações Iniciais:
Preencha o nome e a descrição do projeto

Clique em "Create Repository"

Publique na Nuvem:
Na barra superior, aparecerá o botão "Publish repository"

Confirme o nome, escolha se o código será privado e clique em "Publish Repository" novamente

O aplicativo criará automaticamente o repositório no site do GitHub e enviará seus arquivos

Dicas de Boas Práticas
README.md: Sempre inclua este arquivo para que as pessoas (e recrutadores) entendam do que se trata o seu projeto logo na página inicial

gitignore: Crie este arquivo para listar pastas que o Git não deve enviar, como arquivos temporários de sistema ou senhas

Commits Pequenos: Em vez de enviar o projeto inteiro de uma vez no futuro, faça pequenos salvamentos à medida que termina cada tarefa

--------------------------------------------------------------------------------
Instalação do GitHub Desktop para Linux

A distribuição Lux 2 (Bellatrix), comumente encontrada em notebooks da Lenovo, é baseada no sistema Debian
Como o GitHub Desktop não possui uma versão oficial para Linux, você deve utilizar uma versão adaptada pela comunidade, sendo a mais conhecida a do desenvolvedor Shiftkey

Abaixo estão os três métodos principais para realizar essa instalação:
Método 1: Via Repositório APT (Recomendado para atualizações)
Este método integra o aplicativo ao seu sistema, permitindo que ele receba atualizações automáticas junto com outros programas

Prepare o sistema: Abra o seu terminal e instale o curl, ferramenta necessária para baixar as chaves de segurança

Comando: sudo apt update && sudo apt install curl -y

Adicione a chave GPG: Isso garante que o software que você está baixando é autêntico e não foi alterado

Comando: curl -fsSL https://mirror.mwt.me/shiftkey-desktop/gpgkey | sudo gpg --dearmor -o /usr/share/keyrings/mwt-desktop.gpg

Adicione o repositório: Informe ao sistema onde encontrar os arquivos do GitHub Desktop

Comando: echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/mwt-desktop.gpg] https://mirror.mwt.me/shiftkey-desktop/deb/ any main" | sudo tee /etc/apt/sources.list.d/mwt-desktop.list

Instale o aplicativo: Atualize sua lista e finalize a instalação

Comando: sudo apt update && sudo apt install github-desktop -y

Método 2: Via AppImage (Mais simples, sem instalação)
O formato AppImage funciona como um "arquivo único" que você baixa e executa, sem precisar instalar nada no sistema

Acesse a página de lançamentos do projeto shiftkey/desktop no GitHub

Na seção "Assets", baixe o arquivo que termina com a extensão .AppImage

Após o download, clique com o botão direito no arquivo, vá em Propriedades > Permissões e marque a opção "Permitir executar arquivo como programa" (ou use o terminal: chmod +x nome-do-arquivo.AppImage)

Dê um clique duplo no arquivo para abrir o programa

Método 3: Via Flatpak
Se o seu sistema Lux Bellatrix já tiver suporte ao Flatpak, você pode instalá-lo de forma isolada (sandbox), o que aumenta a segurança

Habilite o Flathub:
Comando: flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

Instale o GitHub Desktop:
Comando: flatpak install flathub io.github.shiftey.Desktop

Configuração Inicial e Autenticação
Após abrir o GitHub Desktop pela primeira vez, siga estas etapas para sincronizar sua conta:
Login no Navegador: Clique em "Sign in to GitHub.com". O aplicativo abrirá seu navegador padrão (como Firefox ou Chrome) para que você insira sua senha do GitHub e autorize o acesso

Identidade Git: O aplicativo perguntará qual nome e e-mail você deseja usar para "assinar" seus trabalhos. Recomenda-se selecionar a opção "Use my GitHub account name and email address" para evitar inconsistências

Atenção ao Lux Bellatrix: Como essa distribuição é baseada em uma versão mais antiga do Debian, caso o login pelo navegador falhe com o erro "user interaction failed", você poderá precisar configurar uma Chave SSH manualmente para autenticar seus envios (Push) e recebimentos (Pull)



- **Final**: "Resuma em miniguia: resumos, glossário e 5 prompts reutilizáveis." → Sucesso total!
