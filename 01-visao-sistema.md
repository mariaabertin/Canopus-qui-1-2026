👁️ **DOCUMENTO VISÃO**


Grupo: Canopus


**1 - Introdução:**

&nbsp;O sistema Cash Alert é uma plataforma web que tem o propósito de garantir o controle e planejamento do financeiro para observar a movimentação e evitar atrasos de contas, por meio de alertas e lembretes inteligentes via e-mail que são baseados em datas e em prazos de valores de entrada e saída. O sistema apresenta os dados de receitas e despesas, inseridos pelo usuário, de forma analítica, transformando registros brutos em informações úteis para o planejamento de curto e longo prazo. A aplicação é estruturada no padrão Model-View Controller (MVC), garantindo escalabilidade e separação de responsabilidades. Para assegurar a integridade e a confiança do usuário, o sistema adota políticas de governança de dados em conformidade com a LGPD e mecanismos de segurança via OpenID. Com alta disponibilidade e suporte a operações offline, o Cash Alert atua não apenas como um relatório de dados, mas como uma ferramenta de apoio à saúde financeira, reduzindo a ansiedade causada pelos esquecimentos de prazos e pela falta de organização.



**2 - Objetivos do sistema:**

&nbsp;Pessoas sofrem com a falta de controle de suas finanças por não terem uma visão concreta e completa de suas movimentações, gerando uma série de problemas, como: atrasos em pagamentos, débitos de multas com altos juros, acúmulo de contas ignoradas, gastos excessivos e invisíveis e falta de planejamento adequado, que podem levar o indivíduo à deficiência de retenção de dinheiro, prejuízos com dívidas e estresse/ansiedade frequente com suas finanças. Para resolver essas questões, Cash Alert atua na disponibilidade de inserção de gastos fixos e variáveis, que irão proporcionar uma visão completa das movimentações realizadas pelo usuário. Além disso, possui um sistema de alertas via e-mail que irá notificar o usuário do vencimento de suas contas e lembrá-lo de especificações financeiras a partir de alertas personalizados. O sistema também possibilita o cadastro de receitas e reservas mensais, que integram o dashboard completo para visão das movimentações e a manutenção dos históricos mensais, gerando, assim, um controle completo das finanças do usuário, para que encontre a sensação de prosperidade financeira a partir do seu gerenciamento adequado.



**3 - Stakeholders usuários e clientes:**

&nbsp;Usuário: utilizador do sistema, é o único impactado com este sistema, capaz de realizar todas as funcionalidades.


**4 - Escopo:**

Cadastrar perfil do usuário (Cadastrar conta do usuário no sistema por meio do fornecimento de CPF, nome completo, e-mail e senha de acesso para autenticação na plataforma).


Acessar o sistema (Usuário acessa sua conta por meio do CPF e senha previamente cadastrados no sistema).


Registrar saldo inicial (Permitir ao usuário definir o saldo financeiro total disponível no momento do primeiro acesso).


Visualizar relatorio mensal (Dashboard completo contendo os cadastros de receitas, despesas variáveis, despesas fixas e reservas financeiras, com seus parâmetros, cadastrados para o mês vigente).


Cadastrar receitas (Registrar entradas financeiras informando categoria, data e valor, permitindo o acompanhamento mensal).


Cadastrar despesas (Registrar saídas financeiras classificando como fixa ou variável e informando categoria da despesa, data e valor).


Editar e excluir registros financeiros (Permitir ao usuário modificar ou remover registros cadastrados de entrada, saída ou alertas, garantindo melhor gerenciamento).


Configurar alertas para vencimento de despesas (Permitir ao usuário definir notificações automáticas -eviadas para o email cadastrado- para vencimentos de contas).


Configurar alertas personalizados (Permitir a criação de lembretes financeiros personalizados baseados em data e horário definidos pelo usuário, que aparecerão no calendário do sistema e notificadas no email cadastrado).


Notificar saldo negativo ou risco financeiro (Enviar notificações ao usuário -via email- quando o sistema identificar risco de saldo negativo ou quando as despesas registradas ultrapassarem as entradas do período).


Visualizar registros em formato de calendário (Visualizar registros criados pelo usuário baseados em mês e dia por meio do calendário do sistema).


Vincular registros em calendário externo (Vincular registros no calendário do Teams e/ou Google Calendar).


Realizar buscas por filtros (Permitir a pesquisa de registros financeiros utilizando filtros como valor, tipo de movimentação, categoria e intervalo de tempo).


Gerar relatório financeiro mensal (Gerar automaticamente um relatório ao final de cada mês, apresentando o resumo das entradas, saídas e movimentações financeiras registradas).


Criar histórico de relatórios mensais (Armazenar e disponibilizar relatórios financeiros gerados, permitindo consultas futuras e geração de relatórios com base em períodos definidos pelo usuário).


Baixar relatórios mensais (Permite que o usuário faça o download do relatório em formato PDF).


Realizar Backup e recuperação de dados (Permitir a realização de cópias de segurança das informações financeiras registradas e possibilitar a recuperação dos dados em caso de perda ou falha do sistema).



**5 - Restrições:**

Funcionalidade apenas web, precisa de conexão; <br>
O sistema não consegue descobrir saldos e despesas além do que for registrado pelo usuário.



**6 - Critérios de sucesso:**

Teste de software para validação da performance requisitada e esperada do sistema; <br>
Sistemas de controle de satisfação do usuário com o sistema; <br>
Tempo de utilização da plataforma; <br>
Indicadores de taxa de abandono. <br>
