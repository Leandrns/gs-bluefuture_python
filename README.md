<h1 align="center"> Sistema da plataforma em Python do projeto para a Global Solution</h1>
<h2 align="center">Grupo SeaConnect | 1°ESA</h2>

#### Integrantes:
<p>Caio Alexandre dos Santos - RM:558460</p>
<p>Leandro do Nascimento Souza - RM:558893</p>
<p>Rafael de Mônaco Maniezo - RM:556079</p>

## Sobre o projeto
<p>A falta de conscientização da população sobre os oceanos é uma questão crucial que contribui para a falta de engajamento na preservação e proteção dos ecossistemas marinhos. Para abordar esse desafio, surge o SeaConnect, uma plataforma na qual a população e as empresas que estão situadas em regiões próximas ao mar possam se conectar. A plataforma apresenta um recurso comum a todos os usuários: uma visualização de dados coletados de diferentes pontos do oceano através de boias oceânicas e esses dados são tratados e publicados na plataforma em formas de visualizações interativas e intuitivas.</p>

## Funcionalidades
- Sistema de ocorrências de pontos de poluição em regiões beira-mar com a seguinte estrutura: título da ocorrência; descrição; local; e anexos (fotos/vídeos). 

- As empresas cadastradas na plataforma têm a possibilidade de ir ao local de uma ocorrência e resolvê-la, criando um portfólio de contribuições ao cuidado dos oceanos

- Tanto o desempenho das empresas quanto o dos usuários da comunidade são medidos em forma de pontos e expostos em rankings dentro da plataforma, visíveis para qualquer usuário.

- Os usuários da comunidade podem gerar uma ocorrência ou contribuir resolvendo aquele problema, como a retirada de resíduos plásticos da areia de uma praia, criando um portfólio pessoal e ganhando maior pontuação no ranking.
 

## Plataforma
#### O sistema da plataforma do projeto foi desenvolvida em Python, sendo executado diretamente no terminal.
### Criando uma conta de usuário
<p>O usuário deve informar se vai fazer uma conta pessoa física ou empresa;</p>

#### Caso o usuário que está se cadastrando for pessoa física, ele deve fornecer os seguintes dados:

- Nome completo do usuário; 
- Email com o formato padrão de nome@dominio.com e não deve estar associado a outro usuário cadastrado; 
- Telefone válido;
- Nome de usuário, devendo ser único entre todos os usuários com pelo menos 5 caracteres; 
- Criar senha de acesso com pelo menos oito caracteres e depois confirmar-la;

 
#### Caso o usuário que está se cadastrando for uma empresa, ele deve fornecer os seguintes dados:

- Nome da empresa;
- CNPJ válido com 14 caracteres;
- Email da empresa deve seguir o formato padrão de nome@dominio.com e não deve estar associado a outro usuário cadastrado;
- Criar senha de acesso com pelo menos oito caracteres e depois confirmar-la;

### Página inicial 
- Na página inicial de pessoa física, estão disponíveis as opções: 1 - Criar Report, 2 - Solucionar Report, 3 - Acessar dados sobre os oceanos;
- Na página inicial de empresa, estão disponíveis as opções: 1 - Solucionar Report 2 - Acessar dados sobre os oceanos.

### Página criar report
- Ao acessar a página de criar reports, você deve informar o título, local, descrição e imagem/vídeo para o report;
- A inserção de imagem/vídeo é simbólica nessa aplicação;
- Após preencher, o usuário poderá visualizar a prévia do report, podendo edidar algum dado antes de enviar;
<p> O usuário pode voltar para página inicial ou sair do sistema.</p>

### Página de solucionar reports
- Ao acessar a página de Solucionar reports, serão mostrados os títulos, local e descrição do report feitos na plataforma;
- A pessoa/empresa pode escolher qual report ela irá resolver, estabelecendo uma data e a quantidade de colaboradores.
- Após isso, será mostrado no terminal o report, a data e a quantidade de colaboradores escolhido pelo usuário.
<p> O usuário pode voltar para página inicial ou sair do sistema.</p>

### Página de dados
#### O usuário escolhe uma cidade (1 - Santos | 2 - Vitória | 3 - Balneário Camboriú | 4 - Salvador) e poderá conferir os seguintes dados:

- Nome da cidade escolhida;
- Nível de oxigênio dissolvido: caso esteja entre 5mg/L e 6mg/L, o estado está OK;
- pH:  caso esteja entre  8 e 8.3, o pH está OK;
- Temperatura:  caso esteja entre 25°C e 27°C, a temperatura está OK;
- Turbidez: caso esteja menor que 50NTU o estado está OK;
- Salinidade: caso esteja entre 33% e 37%, o estado está OK;
- Quantidade de microplástios na água:  caso esteja menor de 300g o estado está OK.
<p>Caso algum dado fique fora da normalidade, aparecerá o estado RUIM.</p>
<p> O usuário pode visualizar outros dados de outras cidades ou não.</p>
<p> Caso usuário não queira ver outros dados, ele pode voltar para página inicial ou sair do sistema.</p>