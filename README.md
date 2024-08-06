Nessa prática aprendi a utilizar o docker e colocar em pratica os comandos tanto por meio de CLI como diretamente pelo VS Code.

Pelo VS Code configurei um arquivo no formato .yaml e realizei o up do container utilizando o comando:
---> docker compose up -d 
Também foi utilizado o comando
---> docker stop nome do container
Além do comando de stop de serviço geral
---> docker compose down 
Utilizando o comando para listar todos os containers
---> docker ps -a 
O comando que exclui uma imagem de é o
---> docker rm  nome do container


 assunto explorado nesta aula é Docker e Docker Compose, ferramentas extremamente valiosas para qualquer desenvolvedor moderno. O Docker é uma ferramenta de virtualização a nível de sistema operacional que permite empacotar aplicações de maneira isolada em 'containers'. Cada container funciona independentemente, com suas próprias configurações, bibliotecas, softwares, o que potencializa a eficiência e a produtividade no desenvolvimento de aplicativos.

Para aprofundar ainda mais o conteúdo, a aula discute Docker Compose, uma ferramenta crucial para definir e gerenciar múltiplos contêineres como um único serviço, agindo como um orquestrador de aplicativos. A importância das imagens Docker e volumes Docker também é explorada, destacando suas funções e aplicabilidades em diversos cenários. Esta aula é essencial para entender a relevância dessas ferramentas no mercado atual, possibilitando a criação de ambientes de trabalho compartilháveis e evitando problemas de compatibilidade entre sistemas operacionais. Com o Docker e Docker Compose, o gerenciamento de várias aplicações se torna mais simplificado, elevando o nível de habilidades do desenvolvedor.

 - Redes Docker

Possibilita a comunicação entre contêineres.
Pode ser configurada para isolar ambientes, garantindo segurança no tráfego de informações.
Dockerfile

Arquivo de texto que contém um conjunto de instruções que permite a criação de uma imagem Docker personalizada.
Docker Swarm

Tecnologia de clusterização e orquestração de contêineres.
Maneira de gerenciar vários contêineres docker em múltiplos hosts.
Iniciação prática

Exemplos práticos de como criar, configurar e usar contêineres para aplicações simples.
Demonstração de como montar um serviço usando Docker Compose.
