## Revisão - Prova 2

| GRR | NOME |
| ------ | ------ |
| 2017208552 | Bruno Leandro Diniz |

1 de Marcar X
2 de verdadeiro e falso
1 de justificar o pq de estar correto
2 de Comentários descritivos

## Quadro da sala
    - Triângulo
        - tempo - custo - escopo
            - qualidade
    
    - Premissa -> Risco
    - Restrição -> Resposta a um risco

### Elicitação de Requisitos (funcionais/não-funcionais)
    - Revista/Brainstorm/técnicas de levantamento de requisitos (Aplicamos os Forms do Google)
    - Levantamento dos requisitos
        * Não ambíguos
            - Sem acrônimos (Descrever siglas / Frase com dupla interpretação)
            - Utilizar ferramentas apropriadas/modelagens para descrever/reler
        * Verificável (é verificável se ele pode ser testado completamente)
            - Assegurar que o Sistema funciona corretamente / Exceções são tratadas de forma correta
            - “o sistema deverá ser amigável." ????
        * Determinístico
            - “o sistema deve enviar novos registros ao sistema X a cada cinco minutos.”
            - O que fazer se nenhum registro for recebido em cinco minutos?
        * Rastreável
            - Rastrear determinado requisito até o seu requisitante
            - Rastrear determinado requisito até sua implementação 
        * Correto
            - Assegurar que o requisito descrito é o requisito correto
            - Assegurar que está requisitando o que foi pedido
    
    - Análise dos requisitos
        - Requisitos Funcionais
        - Regras de Negócio
        - Requisitos Não Funcionais

    - Gerenciamento dos requisitos (caso precise fazer uma alteração)
        - Reunião de negociação:
            - Fase de informação -> Explicar os problemas associados com os requisitos a negociar
            - Fase de discussão -> Stakeholders devem ter oportunidades de comentar os requisitos que lhes dizem respeito
            - Fase de resolução -> Eliminar, alterar ou refinar o requisito
        - Caso aja alteração
            - Garantia de que o escopo do projeto está sob controle
            - Garantia de que o conjunto de requisitos continua válido e aderente às necessidades dos stakeholders
            - Manutenção da rastreabilidade dos requisitos
        
        - Passos para elicitação de requisitos:
            - Selecionar a fonte
                - Quem são os stakeholders do projeto? (disponibilidade, restrições de contato, fisicamente acessíveis?)
                - Existe um sistema anterior?
                - Existe um repositório de requisitos que podem ser reutilizado?
            - Escolher a técnica
                - Braimstorm / Questionário / Entrevista / Reunião / Documentos
            - Descrever os requisitos
       
    - Verificação e validação
        - Avaliação cuidadosa dos requisitos, com ênfase em sua consistência e completude (completo/perfeito).
        - Verificação: O padrão para documentar requisitos foi seguido?
        - Validação: Os requisitos estão adequados sob a ótica do cliente?
        - Nessa atividade deve-se identificar possíveis problemas nos requisitos antes que o documento produzido sirva de base para o desenvolvimento do sistema.

    - Escopo de Projeto	é todo o trabalho necessário para entregar um produto, serviço ou resultado (define o trabalho e o "não-trabalho" durante o projeto)
    - Escopo de Produto é o conjunto de características que descrevem o resultado final do projeto (o produto acabado)
    - Scope creep
        - Crescimento desordenado do escopo
    - Gold plating
        - Adicionar uma série de coisas ao projeto sem a devida necessidade, famoso "xícara de ouro"

    - Stakeholder é qualquer pessoa ou organização que tenha interesse, ou seja afetado pelo projeto
    - Cliente irá se beneficiar da aplicação
    - Usuário irá utilizar a aplicação

    - Requisitos estáveis X requisitos voláteis
        - Alguns requisitos estão mais sujeitos a mudanças (voláteis) do que outros (estáveis)
        - Os requisitos estáveis estão associados à essência do sistema e ao seu domínio de aplicação
            - Atividade principal que está sendo informatizada
        - Os requisitos voláteis são específicos de uma instância do sistema para um cliente e para o contexto particular
            - Política governamental que rege a atividade.
    - Recebe a solicitação de mudança > Analisa o impacto > Implementa ou Rejeita
        - Analisar que outros requisitos podem ser afetados pela mudança
        - Qual o custo da mudança?
        - Qual o risco da  mudança?
    - Risco em relação ao sistema
        - Influência nas atividades existentes do sistema:
            - Baixo
            - Médio
            - Alto 
    - Impactos na arquitetura do software
            - Baixo
            - Médio
            - Alto 

### Projeto de Software
    - Projeto Lógico -> Onde vão ser usados os Diagramas UML (caso de uso, especificação de caso de uso, diagramas de sequência) para projetar o software 
    - Modelagem do Banco de Dados (Sistema Gerenciador de Banco de Dados)
    - Paradgma (Orientada Objeto, eventos,...)
    - Projeto Lógico (UML)
    - Diagrama de Classes

### Construção de Software
    - Códigos simples, bem definidos, identação, possibilitar mudanças no futuro, facilitar testes e revisões, construir para reutilização, eficiência, qualidade, segurança, custo
    - Programar a aplicação, banco de dados, construir o software
    - Boas práticas de construção (escrita de programa) -> Padrão de nome de sistema/variável, documentar, trabalhar de forma padrão e organizada
    - Ferramentas para melhorar na programação (VsCode)
    - Baseado no modelo de desenvolvimento e nas ferramentas definidas
        - Construção ocorre após o levantamento/detalhamento dos requisitos e elaboração do projeto detalhado (Modelo V, Cascata)
        - Construção pode ocorrer simultaneamente com outras atividades de desenvolvimento (Iterativo, Met Ágeis)
    - Considerando os requisitos do produto
    - Escrita do software
    - Testes básicos durante o desenvolvimento

    - Considerações práticas na construção de software
        - Projeto de construção
            - Pode ser na construção ou na fase de projeto de software
            - Limitações impostas pelo problema do mundo real que está sendo resolvido pelo software
        - Linguagem de construção
            - Podem afetar a qualidade do software
                - Desempenho
                - Confiabilidade
                - Portabilidade
            - Vulnerabilidades,  entre outros
            - Sistema Operacional – Linux, Windows, Unix, IOS
        - Codificação
            - Código-fonte compreensível, uso de nomenclaturas e layout
            - Uso adequado das classes especificadas
            - Uso de estruturas de controle (if; do-while; switch-case)
            - Manipulação de erros – entrada de dados incorreta
            - Prevenção de falhas de segurança
        - Teste de construção
        - Diminuir o intervalo entre o momento em que as falhas são inseridas no código e que são detectadas, reduzindo o custo da correção
        - Realizadas pelo desenvolvedor do código
        - Tipos:
            - Teste unitário
            - Teste de integração
        - Aplicar casos de teste.
        - Construção para reutilização
        - Construção com reutilização
        - Qualidade da construção
            - Problemas
                - Falhas dos requisitos e dos projetos
                - Falhas da construção em si
            - Vulnerabilidades
            - Falhas na funcionalidade
        - Integrações

### Teste de Software
    - v & v (VERIFICAR se está dando a resposta correta (identificar defeitos e possíveis problemas de um componente pronto) e VALIDAR se está trabalhando com os requisitos de forma correta - regra de negócio)
    - Revisões de Software
        - Técnicas estáticas que identificam a correspondência entre o programa e sua especificação ou necessidades do cliente.
        - Não demonstram se o software é operacionalmente útil ou se suas características não-funcionais atendem os requisitos desejados.

    - Testes de Software
        - Técnicas dinâmicas que podem ser aplicadas para verificação e validação, trabalhando sobre uma versão executável do produto de software.
        * Tipos de testes 
            - Funcionais: caixa branca / preta / etc
            - Não-funcionais: carga, volume, usabilidade, estresse, etc
        * Método de aplicação

### Manutenção de Software
    - Necessidades baseadas no Swebok
        - Corrigir falhas
        - Melhorias
        - Melhorar design/projeto
        - Integrações
        - Adaptar os programas
        - Migrar o software legado
        - Desativar software
    - Correção de eventuais erros, melhora em seu desempenho ou qualquer outro atributo
    - Análise de impacto e risco (com base em novas manutenções)
        - Analisar as solicitações de mudança
        - Replicar ou verificar o problema
        - Desenvolver opções para implementar a modificação
        - Elaborar documentação de soclitação de mudança
        - Obter a aprovação para a opção de modificação selecionada
    
    - Tipos de manutenção (por erro, bug, features, melhorias)
        - Correção de defeitos ou manutenção corretiva
        - Adaptação ambiental ou manutenção adaptativa
        - Adição de novas funcionalidades ou  manutenção de aperfeiçoamento
    
    - Técnicas de manutenção (preventiva, corretiva)
        - Proativa é preventiva e de aperfeiçoamento do software
        - Reativa é corretiva e adaptativa
        - Reengenharia de software
        - Gerenciamento de sistemas legados
        - Engenharia reversa
        - Refatoração

    - Gerenciamento de manutenção (histórico de manutenção, etc)
        - Esforço de análise e adaptação (código-fonte, documentação)
        - Verificação (averiguar se o software está de acordo com as especificações preestabelecidas)
        - Validação (processo de confirmação de que o sistema está apropriado e consistente com os requisitos)
        - Adaptação (impacto, nova versão)

### Qualidade de Software
    - Necessidade de desenvolver software com qualidade
        - Satisfação do cliente
        - Superar as expectativas
        - Atender plenamento aos requisitos
        - Satisfazer as necessidades explícitas e implícitas
    - Controle de qualidade X Garantia de qualidade
        - Não basta que a qualidade exista, ela deve ser reconhecida pelo cliente
        - Deve existir uma certificação oficial emitida com base em um padrão
        - Controle de qualidade
            -Evita que produtos defeituosos sejam entregues aos clientes
            - Natureza reativa
            - Objetiva monitoração de processo e detecção e correção de defeitos
            - Inspeção e testes.
        Garantia de qualidade
            - Tenta produzir software com uma baixa taxa de defeitos
            - Natureza proativa
            - Definição de procedimentos, padrões e treinamentos
            - Gerência e melhoria de processo
    - Normas e modelos de qualidade de SW (Objetivo de buscar organização e melhoria continua no processo de desenvolvimento de software)
        * ISO (normas/diretrizes para qualidade/avaliação/processos de ciclo de vida de softwares)
        * CMMI (modelo que estende o CMM para avaliação de processos de software)
        * MPS-Br (Modelo Brasileiro de qualidade de processo de software - controle de qualidade com base em níveis)
    - Itens de qualidade de produto de SW - Square
        * Niveis de qualidade que validam o produto final (confiabilidade, portabilidade, usabilidade, segurança, manutenibilidade, adequação formal, eficiência de desempenho, compatibilidade)

### Gerencia de configuração de Software
    - Motivação (Mudanças pelo usuário)
        - Necessidade do negócio
        - Ambiente
        - Legislação
        - Manutenção (correção de erros / adaptação / melhorias)
    - Benefícios
        - Ganho de produtividade e eficiência;
        - Diminuição do retrabalho e dos erros;
        - Aumento da disciplina/organização no processo de desenvolvimento;
        - Aumento da memória organizacional – gestão do conhecimento;
    - Itens de gerencia de configuração
        * Controle de modificações
            - Armazena todas as informações geradas durante o andamento das solicitações de modificação
            - Relata essas informações aos participantes interessados e autorizados - comunicação.
        * Controle de versões
            - Evita perdas ou sobreposições durante o desenvolvimento e a manutenção do artefato.
        * Controle de gerenciamento de construção
            - Automatiza o processo de transformação dos diversos artefatos do software que compõem um projeto em um sistema executável propriamente dito
            - Este processo é nomeado construção do software que, por exemplo, testa e empacota uma aplicação.
    - Ferramentas de gerenciamento de configuração de SW
        * Git, metodologias ágeis
        - Versão de software
            - Baseline – uma linha de base ou uma linha de referência de software é uma versão formalmente aprovada de um item de configuração designada e fixa em um momento específico durante o ciclo de vida do item de configuração.
        - Aquisição de itens de configuração de software
            - Biblioteca de software
        - Ferramentas de suporte individual
            - Controle de versão – código-fonte e documentação 
            - Controle de manipulação – versão executável do software
            - Controle de mudança – controle de solicitação de mudanças e status
        - Ferramentas de suporte ao projeto
            - Equipes de desenvolvimento de software
        - Ferramentas de suporte ao processo da empresa
            - Gerenciamento de fluxo de trabalho, incluindo certificação 

### Gerenciamento de Projeto de TI (PMBOK)
    - Gerenciamento de escopo
        * O que fazer no projeto, requisitos
        * Descrever as atividades para realizar os requisitos (atividades)
    - Gerenciamento de tempo
        * Pegar as atividades, colocar uma em baixo da outra e dar uma sequência, o que torna um cronograma (milestones "medições" - avalia tudo, quanto tempo levou, quanto gastou, gestão do projeto de forma geral)
    - Gerenciamento de risco
        * GUT, Impacto de planilha de calor