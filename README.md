# SOLID-x-Development-Threads
Projeto para entender onde o SOLID está influênciando nas tendências de desenvolvimento de software.

Vou separar em 11 tópicos sobre tecnologias novas que o SOLID tem influência

### 1 - Businesses Adopt Low-Code And No-Code Development
- Para conseguir criar um padrão de desenvolvimento onde você não utiliza código, é necessário que o código utilizado para criar aplicativos "No-code" utilize os principios do SOLID.
- Se não for utilizado, a manutenção desse tipo de software se torna cada dia mais complexa.

### 2 - Remote Work Drives An Increase In Cloud Computing
- Todos os projetos criados utilizando Cloud Computing como SaaS, Iaas e Paas utilizam o conceito de SOLID.
- Um bom exemplo seria a utilização de Terraform.
  - No Terraform, é definido qual infraestrutura será utilizada mas o arquivo em si pode ser utilizado para criar a infraestrutura em vários provedores de Cloud como AWS, Azure entre outros.
  - Não temos definições de arquivos separadas para cada provedor.
  - Estamos centralizando a linguagem que é utilizada para criação de infraestrutura.
 
### 3. Malicious Software Development Ramps Up
- Como tudo está sendo migrado para a Cloud, os ataques estão aumentando cada dia mais.
- Isso faz com que as empresas invistam na mesma proporção para manter suas aplicações seguras.
- A AWS tem um serviço de cloud que garante que seu sistema não será invadido.
  - A parte em que temos uma ligação com o SOLID é que para a AWS garantir a integridade da sua aplicação, você deve seguir vários padrões de desenvolvimento que incluem recuperação de senhas, tipos de arquitetura, tipos de acesso e tipos de comunicação entre sistemas.
  - A maioria das regras exigidas pela AWS para manter sua aplicação segura parecem ter sido criadas levando em consideração os principios do SOLID.
 
### 4. AI Adoption Accelerates
- A AI utiliza dados para conseguir aprender sobre determinada área e já é utilizada em várias áreas.
- Se os projetos que a AI vai utilizar para aprender foram criados utilizando os principios do SOLID, o aprendizado será mais rápido e com uma melhor qualidade.

### 5. Rust Gains Momentum
- Nunca trabalhei com o Rust então não posso dizer se podemos utilizar os conceitos do SOLID em projetos utilizando Rust

### 6. Continued Expansion Of The IoT
- IoT é o futuro da programação porque pode ser utilizada em vários lugares não somente em um computador ou celular.
- Minha preocupação nas áreas de IoT, Automação e Robótica é que me parece que quem trabalha nessas áreas está interessada somente em fazer a ideia funcionar sem levar em consideração conceitos de programação.
- Uma boa solução para se ter um projeto perfeito seria os engenheiros e programadores se comunicarem para seguir padrões de projeto que facilitam a manutenção do software no futuro.
- A aplicação do conceito de SOLID cai como uma luva nesse caso.

### 7. Progressive Web Apps (PWAs) Aim To Provide A Better User Experience
- Seriam páginas web no lugar de aplicativos de celular
- Da mesma forma que os aplicativos de celular podem seguir os conceitos de SOLID, as páginas web também podem seguir os conceitos de SOLID

### 8. Microservices Architecture Simplifies Deployment And Scaling
- A arquitetura de microserviços é o conceito inicial do SOLID (S - Single Responsibility Principle (Princípio da Responsabilidade Única))
- Cada parte do sistema tem sua responsabilidade única e se comunica com as outras partes do sistema para entregar o resultado final

### 9. Use Of Blockchain In Software Development Expands
- A Blockchain pode ser considerada uma interface no mundo das transações
- Vários jogos digitais utilizam criptomoedas para realizar suas transações e manter seu ecosistema funcionando
- A parte em que esse exemplo se conecta com o SOLID seria no I (Interface Segregation Principle (Princípio da Segregação de Interface))
- Temos um conceito generico de blockchain mas cada jogo utiliza sua criptomoeda que tem seu sistema especifico de manutenção e valorização da moeda

### 10. Companies Turn To Outsourcing In The Face Of IT Skills Shortage
- Existem várias vagas na área de TI que não estão sendo preenchidas por falta de conhecimento dos candidatos
- Podemos dizer que isso está acontecendo porque os candidatos preferem focar seus esforços em aprender novas linguagens e fazer cursos do que aprender principios de programação.
- As empresas adoram ter seu código único, ter seu jeito único de trabalhar e entregar projetos
- Mas quando precisam de profissionais experientes para entregar esses projetos não consegue encontrar porque os candidatos estão mais focados em aprender linguagens novas e fazer cursos do que aprender principios de programação.
- É uma culpa tanto da empresa quanto do candidato porque as vagas estão pedindo cada vez mais tecnologias.
- O candidato tem que dividir seu tempo entre aprender conceitos que irão melhorar seu código como o SOLID e aprender tecnologias novas.

### 11. DevSecOps Approach Integrates Security Into The Development Process
- Esse é outro ponto que está dificultando a aprovação do candidato.
- Aproveitando o ponto vamos ver o que um desenvolvedor Pleno/Sênior precisa saber para entregar um projeto e ser considerado como uma boa opção para uma vaga em uma empresa:
  - Saber criar a estrutura do projeto inicial (Spring Boot e outras tecnologias)
  - Saber guardar os dados em algum tipo de banco de dados utilizando a aplicação (MySQL, Postgres e outros bancos)
  - Saber tratar as regras de negócio do projeto em forma de código (Finalmente programação)
  - Saber testes cada componente da aplicação (Testes unitários)
  - Saber testar a aplicação como um todo (Testes integrados)
  - Saber realizar testes automatizados
  - Manter logs da aplicação para saber se a aplicação está funcionando corretamente e em casos de erros realizar a analise do problema
  - Criar um gráfico com esses logs para saber a saúde da aplicação
  - Criar um pacote onde todas as tecnologias utilizadas vão funcionar corretamente e tem que ser simples de utilizar em qualquer lugar
  - Criar uma rotina de CI/CD para que todas as atualizações sejam entregues ao cliente em questão de minutos

- Isso estou pegando somente uma parte do que um programador precisa saber para conseguir uma vaga no mercado de trabalho
- Além desses pontos, ainda temos que levar em consideração a parte de segurança que é um outro mundo de requisitos que precisam ser atendidos para entregar um software com qualidade
- Logicamente que o SOLID ajuda em várias questões de segurança mas a cada dia está ficando mais especifico de acordo com a tecnologia que você está utilizando.

## Conclusão
- O SOLID pode ser aplicado em várias Development-Threads porque ele é um conceito primário para o desenvolvimento de software.
- Agora se as empresas vão utilizar ele ou não vai definir o futuro da área de TI.
- Se utilizarem vamos ter cada dia um ambiente mais simples de se programar e desenvolver novos projetos.
- Isso irá facilitar a entrada de cada vez mais pessoas na área de TI.
- Caso contrário vamos ter um ambiente onde os salários são cada vez mais altos e onde cada vez menos pessoas vão conseguir atender os requisitos das vagas.

#### Links Utilizados
- 11 Key Software Development Trends (2024-2026)
  - https://explodingtopics.com/blog/software-development-trends
