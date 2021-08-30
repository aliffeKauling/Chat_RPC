==========================
DESCRIÇÃO DA ATIVIDADE
==========================

Desenvolver um Chat RPC com transferência de arquivos. O Cliente Chat lê (aloca em memória) um arquivo do disco local e envia (via RPC) para o servidor. O servidor, por sua vez, recebe o arquivo (via RPC), grava no disco local no padrão <nome-usuario>-<contador-msg>.serv.
Para receber as mensagens, os clientes devem consultar o servidor de tempos em tempos (polling).



==========================
DESCRIÇÃO DE SAÍDA DE CONSTRUÇÃO
==========================

Para executar o projeto a partir da linha de comando, vá para a pasta dist e
digite o seguinte:

java -jar "Chat.jar"

Para distribuir este projeto, compacte a pasta dist (incluindo a pasta lib)
e distribuir o arquivo ZIP.

Notas:

* Se dois arquivos JAR no caminho de classe do projeto tiverem o mesmo nome, apenas o primeiro
O arquivo JAR é copiado para a pasta lib.
* Apenas os arquivos JAR são copiados para a pasta lib.
Se o caminho de classe contiver outros tipos de arquivos ou pastas, esses arquivos (pastas)
não são copiados.
* Se uma biblioteca no classpath do projeto também tiver um elemento Class-Path
especificado no manifesto, o conteúdo do elemento Class-Path deve estar
o caminho do tempo de execução dos projetos.
* Para definir uma classe principal em um projeto Java padrão, clique com o botão direito do mouse no nó do projeto
na janela Projetos e escolha Propriedades. Em seguida, clique em Executar e insira o
nome da classe no campo Classe principal. Como alternativa, você pode digitar manualmente o
nome da classe no elemento Main-Class do manifesto.
