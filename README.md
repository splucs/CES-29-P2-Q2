# CES-29-P2-Q2
Possíveis ameaças detectadas:

-Sobrescrita sobre arquivo já existente, possibilidade de deleção ou reconfiguração;

-Possibilidade de subida de pasta colocando ".." no caminho. Possibilidade de leitura de arquivos não autorizados (fora da pasta do programa);

-Possibilidade de leitura de diretórios do sistema com, paths que iniciam com C:, WINDIR ou SYSDIR;

-Não verifica existência do arquivo antes do read;

-Instanciação dupla do BufferedReader e do FileReader;

-Não fechamento do console;

-Não inicialização do BufferedReader com null;

-Loop infinito / exceção caso a entrada chegue a fim;

-Fechamento do BufferedReader e BufferedWriter.

