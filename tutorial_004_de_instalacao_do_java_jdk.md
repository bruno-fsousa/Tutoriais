# Tutorial de instalação do java jdk

## Windows

### Download

Para instalar o Java SDK (Software Development Kit), também conhecido como JDK (Java Development Kit), siga os passos abaixo, adequados ao seu sistema operacional:

- Baixar o JDK:
  - Acesse o site oficial da Oracle: [Oracle JDK Downloads](https://www.oracle.com/java/technologies/downloads) (você pode escolher a versão desejada).
  - Selecione a versão do JDK apropriada para o seu sistema (Windows x64 Installer) e faça o download.

- Instalar o JDK:
  - Execute o arquivo ``.exe`` que você baixou.
  - Siga as instruções do assistente de instalação. O instalador guiará você através das etapas necessárias.
  - O local de instalação padrão geralmente é ``C:\Program Files\Java\jdk-<versão>``.

- Configurar a variável de ambiente ``JAVA_HOME``:
  - Abra o Painel de Controle e vá para Sistema e Segurança > Sistema > Configurações avançadas do sistema.
  - Clique no botão Variáveis de Ambiente.
  - Em Variáveis do sistema, clique em Novo.
  - Defina o Nome da variável como JAVA_HOME.
  - Defina o Valor da variável como o caminho onde o JDK foi instalado (por exemplo, ``C:\Program Files\Java\jdk-<versão>``).
  - Clique em OK.

- Adicionar o JDK ao ``PATH``:
  - Ainda na janela de Variáveis de Ambiente, encontre a variável ``Path`` na lista de Variáveis do sistema e selecione-a.
  - Clique em Editar e adicione um novo caminho: ``%JAVA_HOME%``.
  - Clique em OK para fechar todas as janelas.

- Verificar a instalação:
  - Abra um prompt de comando (``cmd``) e digite ``java -version`` e ``javac -version`` para verificar se o JDK foi instalado corretamente e está configurado no ``PATH``.

<!-- macOS

    Baixar o JDK:
        Acesse o site oficial da Oracle ou da AdoptOpenJDK e baixe o instalador do JDK para macOS.

    Instalar o JDK:
        Abra o arquivo .dmg baixado e siga as instruções do instalador.

    Configurar a variável de ambiente JAVA_HOME:
        Abra o Terminal.
        Adicione a seguinte linha ao seu arquivo ~/.bash_profile ou ~/.zshrc (dependendo do shell que você está usando):

        sh

        export JAVA_HOME=$(/usr/libexec/java_home)
        export PATH=$JAVA_HOME/bin:$PATH

        Salve o arquivo e reinicie o Terminal ou execute source ~/.bash_profile ou source ~/.zshrc.

    Verificar a instalação:
        No Terminal, digite java -version e javac -version para verificar se o JDK foi instalado corretamente.

Linux

    Baixar e instalar o JDK:
        Para distribuições baseadas em Debian (como Ubuntu), você pode usar o seguinte comando:

        sh

sudo apt update
sudo apt install openjdk-11-jdk

Para distribuições baseadas em RPM (como Fedora), use:

sh

    sudo dnf install java-11-openjdk-devel

Configurar a variável de ambiente JAVA_HOME:

    Adicione as seguintes linhas ao seu arquivo ~/.bashrc ou ~/.zshrc:

    sh

        export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
        export PATH=$JAVA_HOME/bin:$PATH

        Substitua o caminho conforme necessário, verificando o local exato do JDK instalado.
        Salve o arquivo e execute source ~/.bashrc ou source ~/.zshrc.

    Verificar a instalação:
        No Terminal, digite java -version e javac -version para verificar se o JDK foi instalado corretamente.

Seguindo esses passos, você terá o JDK instalado e configurado no seu sistema, pronto para o desenvolvimento em Java. -->