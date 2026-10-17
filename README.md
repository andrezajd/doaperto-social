DoaPerto Social

> Uma plataforma para aproximar doadores, instituições e campanhas sociais do município.

## Sobre o projeto

O **DoaPerto Social** é uma proposta de plataforma web que centraliza informações sobre campanhas de doação. A ideia é facilitar o caminho de quem quer ajudar, mostrando de forma clara **o que doar**, **onde entregar** e **quando a instituição está recebendo**.

O projeto será construído gradualmente durante o curso de Análise e Desenvolvimento de Sistemas (ADS). A primeira versão será um protótipo acadêmico com dados fictícios. Integrações reais com CRAS, prefeitura e instituições só poderão ser consideradas posteriormente, mediante autorização dos envolvidos e definição de medidas de proteção de dados.

## Problema

Campanhas solidárias costumam ser divulgadas em vários canais, como redes sociais, mensagens e cartazes. Isso pode dificultar que a população encontre informações atualizadas sobre:

- campanhas ativas;
- itens que realmente são prioridade;
- locais e horários de recebimento;
- possibilidade de agendar uma entrega ou retirada.

Também pode ocorrer o recebimento de itens que não são necessários naquele momento, enquanto outros produtos importantes estão em falta.

## Solução proposta

O DoaPerto Social reunirá as campanhas em um único ambiente digital. Cada campanha poderá informar sua finalidade, os itens necessários, período de arrecadação, ponto de coleta e horários disponíveis.

O doador poderá consultar as campanhas e agendar uma entrega. Instituições poderão atualizar suas necessidades e acompanhar os recebimentos. Em etapas futuras, um perfil de gestão municipal poderá acompanhar indicadores consolidados das campanhas.

## Objetivos

### Objetivo geral

Planejar e desenvolver uma plataforma digital que facilite a divulgação e a organização de campanhas de doação no município.

### Objetivos específicos

- Centralizar campanhas e necessidades de instituições sociais.
- Orientar doadores sobre itens prioritários, locais, datas e horários.
- Permitir o agendamento de entregas.
- Reduzir desencontros entre o que é doado e o que as campanhas necessitam.
- Produzir indicadores que auxiliem instituições e gestores a acompanhar as campanhas.

## Público-alvo

- Pessoas interessadas em realizar doações;
- instituições sociais, ONGs e projetos comunitários;
- gestores de campanhas;
- órgãos municipais de assistência social, em uma possível evolução do projeto.

## Perfis de acesso

| Perfil | Responsabilidades principais |
| --- | --- |
| Doador | Consultar campanhas, verificar itens necessários e agendar uma entrega. |
| Instituição | Criar e atualizar campanhas, informar necessidades, horários e confirmar recebimentos. |
| Administrador | Validar instituições, acompanhar campanhas e administrar o sistema. |
| Beneficiário | Consultar doações ou campanhas disponíveis para seu perfil, acompanhar solicitações e agendar a retirada quando autorizado. |
| Gestor social (futuro) | Visualizar indicadores consolidados e demandas, sem expor dados pessoais de beneficiários. |

## Acesso do beneficiário

O beneficiário também terá acesso ao DoaPerto Social. Após ser validado pela instituição responsável ou pelo CRAS, ele poderá entrar em uma área pessoal para:

- informar ou atualizar suas necessidades, quando autorizado;
- acompanhar o andamento de uma solicitação;
- visualizar doações liberadas para retirada;
- consultar local, data e horário da retirada;
- confirmar o recebimento da doação.

O objetivo é dar mais autonomia à pessoa atendida, sem expor suas informações aos doadores. A validação da necessidade continua sendo responsabilidade de profissionais e instituições autorizadas.

## Funcionalidades previstas

### Versão inicial

- Cadastro e login de usuários;
- visualização de campanhas ativas;
- detalhes da campanha: itens necessários, local, datas e horários;
- cadastro e atualização de campanhas por instituições;
- agendamento de entrega de uma doação;
- confirmação de recebimento;
- consulta e acompanhamento de solicitações pelo beneficiário;
- painel administrativo básico.

### Evoluções futuras

- Notificações sobre novas campanhas e alterações de horário;
- mapa de pontos de coleta;
- relatórios de campanhas, itens recebidos e necessidades em aberto;
- painel de indicadores para instituições e gestores;
- área interna para registrar demandas validadas por profissionais da assistência social;
- implantação piloto com instituições interessadas.

## Privacidade e uso responsável dos dados

O sistema não deverá expor publicamente informações de famílias atendidas, como nomes, documentos, endereços ou situação social. Para o protótipo acadêmico serão utilizados apenas dados fictícios.

O beneficiário poderá ter acesso a uma área pessoal do aplicativo para acompanhar solicitações e verificar doações liberadas para retirada. No entanto, ele não será aprovado automaticamente pelo sistema. Caso exista uma etapa futura com participação do CRAS ou de outros órgãos públicos, a validação deverá ocorrer somente em uma área restrita, por profissionais autorizados. O papel do sistema será apoiar campanhas e necessidades, e não substituir a avaliação social realizada pelos órgãos responsáveis.

## Escopo por semestre

| Semestre | Entregas planejadas |
| --- | --- |
| 1º | Pesquisa do problema, levantamento de requisitos, protótipo das telas e modelagem inicial do banco de dados. |
| 2º | Cadastro, login e perfis de doador, instituição e administrador. |
| 3º | Criação de campanhas, itens necessários, datas, locais e horários. |
| 4º | Agendamento, confirmação de recebimento e notificações. |
| 5º | Perfil do beneficiário, controle de solicitações, demandas e área interna para gestão social, com foco em proteção de dados. |
| 6º | Dashboard, relatórios, mapa de coleta, testes com usuários e possível piloto. |

## Escopo do 1º semestre

Neste semestre, o foco é entender o problema e planejar a solução. As entregas previstas são:

1. Pesquisa com possíveis doadores e, se possível, instituições locais;
2. levantamento de requisitos funcionais e não funcionais;
3. definição dos perfis de usuário;
4. protótipo navegável das telas principais;
5. modelagem inicial do banco de dados;
6. documentação da proposta e do planejamento do projeto.

Não faz parte do escopo inicial criar uma integração real com prefeitura, CRAS ou bancos de dados públicos.

## Telas planejadas para o protótipo

1. Página inicial com campanhas em destaque;
2. lista e filtros de campanhas;
3. detalhes de uma campanha;
4. agendamento de doação;
5. login e cadastro;
6. área do beneficiário para acompanhar solicitações e retiradas;
7. painel da instituição para criar ou editar campanhas;
8. painel administrativo básico.

## Tecnologias previstas

As tecnologias serão definidas conforme o conteúdo de cada semestre. Como ponto de partida, o projeto pode utilizar:

- **Protótipos:** Figma;
- **Front-end:** HTML, CSS e JavaScript;
- **Back-end:** Node.js, Java/Spring ou outra tecnologia trabalhada no curso;
- **Banco de dados:** MySQL ou PostgreSQL;
- **Versionamento:** Git e GitHub.

## Pesquisa inicial

Antes de definir as funcionalidades finais, o grupo realizará uma pesquisa com a comunidade. O objetivo é compreender hábitos de doação e identificar as informações que mais dificultam esse processo.

O roteiro completo está em [docs/pesquisa-inicial.md](pesquisa-inicial.md).

## Decisão de escopo: por que não monitoramento de energia?

A ideia inicial de monitoramento de picos de energia residencial foi descartada porque a medição real exigiria integração com equipamento elétrico ou sensor. Isso aumentaria a complexidade técnica, os custos e os riscos do projeto. Sem uma fonte de dados real, a solução se limitaria a dados simulados e teria pouca diferença em relação às informações já apresentadas na conta de luz.

O DoaPerto Social foi escolhido por ser viável como sistema web, ter impacto social local e permitir evolução contínua ao longo dos semestres.

## Status

O projeto encontra-se na etapa de **planejamento e pesquisa do 1º semestre**.
