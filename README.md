# Atividade de Projeto Estruturado
### Informações do Aluno
Nome: João Pedro Scardelai Benevide  
RA: 09023410  
Curso: Sistemas de Informação  
Polo: Cascavel - PR  


## 1. O que é Git?
O Git é um sistema de controle de versão (Version Control System) de código muito utilizado em Desenvolvimento de Software, e com o Git podemos criar e visualizar todo o histórico das alterações no código e sempre que necessário validar o código ou o projeto em uma data específica. O Git foi criado em 2005 por Linus Torvalds para o kernel (núcleo principal) do Linux e foi utilizado por diversos programadores e projetos desde sua criação, Linus criou o Git porque o sistema de controle de versão que ele utilizava (BitKeeper) teve a revogação da sua licença por conta de um desentendimento, isso girou uma chave para Linus onde ele desenvolveu o Git com o objetivo de ser uma ferramenta rápida, eficiente e que funcionasse muito bem com um projeto e código grande, o kernel do Linux.  

## 2. O que é versionamento de software?
Versionamento de Software (Version Control System) é o processo de controle de versão de código e arquivos, facilitando desenvolvedores a rastrear, gerenciar e documentar o histórico das alterações no código de um projeto. É uma prática de Clean Code e essencial para o desenvolvimento de um software, pois é um chave facilitadora na equipe de desenvolvimento, para manutenção do código e garantir a qualidade do projeto e código.  
O versionamento é importante pois conseguimos:  
1. Acompanhar as alterações do código como as correções de bugs, melhorias implementadas, grandes adições no software;  
2. A colaboração de outras pessoas com a funcionalidade que está sendo desenvolvida em diversas partes do código ao mesmo tempo, mesclando as alterações de forma eficiente;  
3. Recuperar Versões do código que causou algum problema ou restaurar funcionalidades;  
4. Uso de Branches para testes das funcionalidades sem afetar a versão principal do software.  

## 3. Por que utilizar o Git como controle de versionamento?
O Git é excelente para se utilizar no controle de versionamento por sua facilidade, eficiência e agilidade em instalar, configurar, utilizar, considerada pelos desenvolvedores uma ferramenta essencial para se trabalhar e se ter conhecimento. Por ser um software Open-Source, possui compatibilidade e integração com diversos outros softwares como o Jira - GitHub - GitLab, onde podemos realizar configurações para uma melhor visualização do cliente e outras pessoas envolvidas no desenvolvimento do software, auxiliando na apresentação do histórico de versões. O preço de se utilizar o Git é um diferencial dele, pois é gratuito e acessível a qualquer pessoa, equipes e empresas sem ter um custo para licenças.  

## 4. Quais as vantagens do Git?
As razões por muitos desenvolvedores e equipes de desenvolvimento preferem o Git é:
1. Distribuição: cada desenvolvedor ao utilizar o Git possui uma cópia completa do seu repositório na local machine. Podendo trabalhar offline e tornando o controle de versão mais forte a falhas de rede mostrando a sua eficácia;  
2. Desempenho: o Git é conhecido por sua velocidade e eficiência durante o gerenciamento de grandes repositórios, operando com commits, branches e merges executadas rapidamente, sendo adequado a qualquer projeto;  
3. Branching: com o Git é possível utilizar branches (ramificações) permitindo ao desenvolvimento trabalhar em várias funcionalidades, correções de bugs e realizar melhorias simultaneamente sem atrapalhar o trabalho da outra pessoa. A merge de branches é de fácil acesso e confiança;  
4. Histórico Completo: no Git é mantido um histórico completo de todas as alterações do código, permitindo realizar auditorias bem detalhadas e ser possível retornar as versões anteriores do código. Sempre mantendo a integridade e segurança dos dados por um hash criptografado;
5. Suporte: o Git possui uma comunidade de desenvolvimento e suporte muito ativa, sempre auxiliando e reforçando com novos recursos e ajuda a comunidade.  

## 5. Qual a importância da utilização do controle de versionamento no desenvolvimento de software?
Quando utilizamos o controle de versionamento temos a possibilidade de:
1. Rastrear as alterações do código, facilitando as futuras manutenções no código e a qualidade do software;  
2. Colaboração com outros desenvolvedores;  
3. Gerenciar todos os conflitos da funcionalidade;  
4. Reverter e Excluir alterações de formas eficientes;  
5. Integração com automação de tarefas, testes e implementação de códigos;  
6. Facilidade na correção de bugs, sem gerar muitos riscos e conflitos no software;
7. Facilidade na alteração da Arquitetura do Software, onde a longo prazo pode trazer grandes alterações e impactar toda a arquitetura construída. Com o versionamento é possível ver a evolução do software com mais facilidade.  

## 6. Três ferramentas de controle de versão e seus detalhes
1. **Subversion (SVN)**: o **SVN** é um software de controle de versão que foi o mais utilizado antes do Git ser popular, onde possui um repositório central (pai) com todas as versões do código e os desenvolvedores utilizam cópias locais sincronizadas ao repositório pai, onde diariamente realizam o carregamento da versão mais atual do repositório (head version) - é chamada de _checkout_ essa operação. O desenvolvedor utilizada essa cópia da última versão durante sua jornada de trabalho e ao final do dia deve subir o commit das suas alterações realizadas.  
2. **Mercurial**: o **Mercurial** é um software de controle de versão de software baseado em Python, e assim como o Git pormite que várias pessoas trabalhem em um mesmo projeto ao mesmo tempo, mantendo o histórico completo de alterações e gerenciamento do código. Tendo uma alta perfomance e escalabilidade, controle de arquivos de textos e códigos de forma robusta, utilização de branches e merges. Possui também um sistema de visualização dos repositórios web.  
3. **Perforce (Helix Core)**: o **Perforce** é um software de controle de versão focado em grandes dados digitais e códigos de ambientes corporativos com grandes massa de informações. É muito usado por empresas que produzem jogos e produzem mídias, pois se tratam de empresas que precisam de uma grande escalabilidade, segurança e desempenho eficiente em seus projetos gigantes. O Perforce possui diversas integrações com ferramentas de desenvolvimentos como **IDEs** e softwares de rastreamento de problemas (**SONAR**).  
4. **Bazaar**: o **Bazaar** foi um software de controle de versão que permitia rastrear, gerenciar e controlar as alterações do código durante o desenvolvimento. Assim como o Git ele permitia que o desenvolvedor utilizasse um cópia completa do respositório na sua máquina local, facilitando a colaboração. Era de fácil usabilidade e possui um ótimo suporte multiplataforma, além de possuir integrações com outras ferramentas e IDEs.