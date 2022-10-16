## Conectar
- Configurando eu ambiente DEV
- Lógica de programação
- Dado e manipulação de dados
- Significado de palavras que usamos no dia a dia: URL, HTTP, TCP, IP, etc
- Cliente/Servidor
- Partes de um computador e qual o papel de cada uma
- Tipos de software
- Como a internet é possível
- Como computadores se comunicam na internet
- Sistemas operacionais
- Tipos de aplicações WEB
- Linguagens de programação

---

### Programar
1. O que é programar?
- Algoritmos
Passos para resolver um problema
Sequência lógica
<br>
- Lógica de Programação
Aplicação dos passos
Construção de Algoritmos
<br>
2. Como o computador pensa/entende?
Não pensa, processa, calcula
Só recebe ordens, como a Linguagem de Programação
Você precisa entender o problema e dar as ordens

---

### Computador, Software, Hardware

**Hardware** - É um termo técnico que se refere á parte física de um computador e outros sistemas micro eletrônicos

**Software** - É um conjunto de instruções que permite controlar um aparelho eletrônico

**Firmware** - A função do Firmware é armazenar todas as informações par que o equipamento funcione corretamente. O Firmware é armazenado permanentemente num circuito intregado (chip) de memória de hardware no momento da fabricação do componente

**Drive** - A função do Driver é ser a ponte entre o sistema operacional e o firmware dos dispositivos eletrônicos. O Drive é instalado no computador quando há a necessidade de se conectar com um novo dispositivo

**Sistema Operacional** - Um sistema operacional é responsável pelo gerenciamento de todo o hardware do seu computador. É ele que vai dizer, por exemplo, para o programa em execução, quando poderá utilizar o processador e por quanto tempo, quando de memória RAM será usada, gerenciamento de SSD/HS, etc

**Programas** - Um programa é um conjunto de instruções que descrevem uma tarefa e/outrabalho especifíco no seu computadaor. São ferramentas desenhadas para o usuário realizar ações

**Memória RAM** - A memória RAM é um espaço temporário de informações do sistema operacional e de aplicativos em uso. Quando uma tarefa é concluída por algum software, os arquivos que estavam em uso são movidos da memória RAM o HD ou SDD para serem mantidos. Quando o computador é desligado a memoria é limpa automáticamente

**HD/SDD** - São dispositivos de armazenamento de dados. O HD usa pratos mecânicos e um cabeçote móvel de leitura/gravação para acessar dados. O SSH não possui partes móveis, apenas chips de memória. Independentemente se o computador está desligado ou não, as informações contidas no HD ou SDD permanecem guardadas

**Processador** - É o cérebro do computador. Transforma informações em uma linguagem que o computador entende > 0101. Tem o formato de um chip. Ele transforma dados em informações, por exemplo, carregar páginas, fazer downloads, abrir arquivos e executar programas. A velocidade que seu computador abre ou executa programas é em apartes responsabilidade do processador

---

### Internet, Roteadores e Servidores
**O que é Internet?** - A internet são redes interligadas pelo mundo todo. Uma rete tem como objetivo interligar computadores para fornecer aos usuários acesso a diversas informações. A internet é feita de cabos que conectam o mundo inteiro

**Rede de computadores e comunicação** - Rede de computadores é a conexão de dispositivos para permitir a tranmissão de dados. A comunicação na internet é feita de protocolos (conjunto de regras)

**IP e MAC Address** - Internet Protocol é um número identificador dado ao seu computador, ou roteador, pelo provedor de internet no momento que se conecta a rede. MAC Address é um número de série identificador gravado no dispositivo de rede. Através do IP que seu computador pode enviar e receber dados na internet

**Servidores** - É um computador equipado com um ou mais processadores, portas de comunicações, software, algum sistema para armazenamento de dados como HDs e/ou SSDs. Fornece serviços a uma rede de computadores, chamada de cliente. Esses serviços podem ser, por exemplo, hospedagem de site, provedor de emails, entre outros

**DNS** - Os servidores DNS (Domain Name System ou sistema de nomes de domínios) são os responsáveis por localizar e traduzir para números IP os endereços dos sites que digitamos nos navegadores. O DNS permite que você acesse um site digitando nominal em lugar de números e pontos

**HTTP** - Hypertext Transfer Protocol é um protocolo de transferência de dados. No momento que o usuário digita uma URL em algum navegador, o navegador cria um requisição HTTP e manda para o servidor correspondente ao IP da URL e então o servidor responde através do HTTP enviando todos os dados necessários para exibir ao usuário no navegador. O HTTPS (Hypertext Transfer Protocol Secure) adiciona uma criptografia as informações enviadas ou recebidas de um site

---

### Sistemas Operacionais
**O que é o Sistema Operacional?** - Interface entre usuário e a máquina. Programa que irá controlar seu aparelho (computador, celular), gerenciamento de dispositivos (hardware), gerenciamento de aplicativos e programas (software), gerenciamento de tarefas. Conversar com o computador em linguagem de máquina.

**Características e Objetivo de um Sistema Operacional**
1. Fácil entendimento para o Usuário
- Experiência do usuário
2. Controle de Hardware
- Uso dos periféricos
- Memória
- HD/SDD
3. Gerenciamento dos Software
- Programas
<br>

**Grupos de Sistemas Operacionais**
- Unix: Linux, OS X, Android, iOS
- Windows: Windows 7, Windows 10, Windows Server

**Tipos de Interface do Usuário**
1. GUI (Graphical User Interface)
- Interface gráfica, elementos gráficos: Cursor do mouse ou touch, Área de trabalho, Criar arquivos e pastas...
2. CLI (Command-Line Interface)
- Linha de comando, Emitir comandos em texto para o computador, por exemplo, Criar arquivos e pastas

**Módulos**
1. Kermel
- Componente central, o cerne do S.O
- Primeiro módulo a ser iniciado
- Permanece executando enquanto o S.O estiver ligado
- Responsabilidades: Gerenciamento de memória, processos, armazenamento e dispositivos

2. Gerenciamendo de processos
- Processo é um programa em execução
- Agendamento de processos (scheduling): Qual processo está executando agora
- Thread: A divisão de um processo para melhor performance, um pedacinho do processo, poderá executar em paralelo
- Multitarefa (Multitasking): Várias tarefas podem ser executadas simultaneamente (troca muita rápida entre elas), tarefas em segundo plano

3. Gerenciamento de Arquivos
- File System
- Organização e armazenamento dos arquivos (vídeos, imagens, documentos)
- Diretórios (pastas)
- Tipos de sistemas de arquivos: FAT, NTFS, ext3, ext4, HFS+, APFS (São criados quando formatamos o nosso disco, por exemplo)

**Ferramentas de Gerenciamento**
- Tarefas (task manager, activity)
- Pacotes (chocolatey, brew, apt, snap)

---

### Linguagem de Programação
**O que é Codar?** - Escrever para o computador, seguir regras, linguagem humana x máquina

*Imagine que você precisa desbloquear seu celular...*
```
  if (input === password) {              (Se a entrada for igual a senha)
    unlockPhone()                        (Destravar o telefone)
  } else {                               (Se não)
      tryAgain()                         (Tentar novamente)
  }
```

>Curiosidades sobre codar...
>- A pessoa que cria códigos: Programadores, Desenvolvedores, Dev, Developer
>- Código vs Programa
>- Código são comandos, ordens, instruções ao computador
>- O computador provavelmente irá traduzir  o seu código
>- Existem códigos em muitos eletrônicos: Microondas, semáforos, roteadores, avião...

**O que é linguagem de programação?** - Usada para dar instruções ao computador

**Low-level vs High-level**
1. Low-level: Significa baixo nivel
- Mais próxima da máquina, do binário: É mais difícil de escrever e de ler, É mais rápida
- Existe pouca interferência de tradução
- A programação começou pelo baixo nível
- Exemplo: Assembly

2. High-level: Significa alto nível
- Mais próxima da comunicação humana: If, Else, Function, Object, Class...
- Leva mais tempo para a máquina traduzir e entender: Compila ou interpreta, Nada mais que milissegundos
- Exemplo: JavaScript, Python, Rust...

**Sintaxe**
- Conjunto de regras de escrita
- Cada linguagem tem as suas regras
- Símbolos: {} () ; = ++ --
- Palavras reservadas: If, Else, While, For, Var, Let, Const

---

### Tipos de Aplicações WEB
**O que é uma webpage?** - Página WEB
- Acessado pelo navegador
- Encontrado pelo endereço universal URL
- Resposta dada pelo servidor é uma cópia da página: HTML (Hyper Text Markup Language), CSS (Cascading Style Sheet), JavaScript

**O que é website estático e dinânico?**
1. Website - Agrupamento, estruturado (arquitetado) de várias páginas WEB, pode ser: Estático ou Dinâmico
- Um usuário comum não sabe diferenciar entre estático e dinâmico
2. Website estático - A página é sempre a mesma, alteração direto no código e por quem a criou. Não interage com o banco de dados.
3. Website dinâmico - Conteúdo da página é dinâmico, interage com banco de dados: Dados + modelo da pagina = página dinâmica. Modificação sem precisar mexer no código. Com o mesmo modelo de página, é gerada uma página em tempo real

**O que é uma Aplicação WEB?**
- Um programa, um software que vive no servidor: Linguagem de programação, Banco de Dados
- Utilizado através de páginas WEB e pelo navegador
- É mais complexo e possui mais requisitos
- Exemplos: Facebook, Gmail, Youtube, Figma
- Desafios - Adaptação nos diversos dispositivos (Responsividades), Performance, Acessibilidade (Visual, Auditiva, SEO)

**Front-end vs Back-end**
1. Front-end - Cliente (Client-side)
- Browser: Digita a URL e faz um pedido (request) para o servidor
- Tecnologias: HTML, CSS, Javascript, Imagens, Frameworks e Bibliotecas

2. Back-end - Servidor (Server-side)
- Recebe o pedido do front-end: Entende e processa o pedido e devolve para o front-end, Regras de negócio da aplicação
- Tecnologias: PHP, Java, Python, Javascript, Banco de Dados

**Aplicação WEB Tradicional vs SPA**
1. Aplicação WEB Tradicional
- Recarregar a página para ter conteúdo atualizado
- Front-end e o Back-end numa só aplicação
- Servidor processa e devolve toda a página de uma só vez

2. SPA (Single Page Application)
- Sensação é de ter uma única página
- Não precisa recarregar a página para ter o conteúdo atualizado
- Front-end e Back-end são aplicações diferentes
- Servidor responde a aplicação front-end
- Front-end feito com uso de Frameworks
- Back-end é no formato de API

---
##### Siglas

*Web* - Rede (Tenha de aranha como exemplo) <br>
*String* - Sequência de caracteres <br>
*Boleano* - Falso ou Verdadeiro <br>
*URL* - Uniform Resource Locator (Localizador e identificador de um recurso) <br>
*HTTP* - Hypertext Transfer Protocol (Função: Trocar mensagens entre computadores) <br>
*TCP* - Transmission Control Protocol (Função: Garantir que os pacotes cheguem corretamente ao destino) <br>
*Cliente* - O computador, dispositivo ou aplicativo que fez o pedido; Browser <br>
*Servidor* - Computador configurado para receber os pedidos e enviar respostas aos pedidos <br>
*IP* - Internet Protocol (Função: Endereçamento dos computadores) <br>
*DNS* - Domain Name Servers (Função: Converter um Dominio em um endereço de IP) <br>
*Proxy* - Qualquer dispositivo no meio do caminho; Modem, Roteador, outros computadores (Função: Encaminhamento dos pacotes) <br>
*Software* - Programa de computador <br>
*Program* - Programa de computador ou aplicativo <br>
