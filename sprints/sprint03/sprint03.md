<h1 style="text-align: center;">📌DoR (Definition of Ready): Sprint 03</h1>

<table>
  <tbody>
    <tr>
      <td><strong>Capacidade estimada da Equipe por</strong></td>
      <td>79 Story Points</td>
    </tr>
    <tr>
      <td><strong>Meta da Sprint</strong></td>
      <td>User Stories de rank 24 e rank 37 (total de 79 Story
Points)</td>
    </tr>
    <tr>
      <td><strong>Previsão da Sprint (extras, sem compromisso de entrega)</strong></td>
      <td>Tudo previsto na entrega</td>
    </tr>
  </tbody>
</table>

<h2>Backlog da Sprint</h2>

 <table>
  <thead>
    <tr>
      <th>Rank</th>
      <th>User Story</th>
      <th>Critério de Aceitação</th>
      <th>Estimativa</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>24</td>
      <td>Como administrador, quero prever o saldo (valor em aberto) a partir da data dos empenhos, para prever o saldo futuro.</td>
      <td>O sistema deve exibir uma estimativa do saldo futuro com base nas variações históricas de valores ao longo do tempo.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>25</td>
      <td>Como administrador, quando cadastrar uma nota de empenho, quero que o sistema web extraia automaticamente os dados principais a partir do PDF enviado, para evitar preenchimento manual e reduzir erros de digitação.</td>
      <td>Campos a serem extraídos da nota: Valor, Número da nota de empenho, Data da nota de empenho, UG, Razão social, CNPJ, Nome do responsável. Campos que deverão ser preenchidos manualmente: Nome do responsável, Cargo do responsável, Frequência de cobrança padrão (15 dias), Urgência do pedido e Data prevista de entrega.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>26</td>
      <td>Como administrador, quero listar e consultar os detalhes das NEs com filtros por fornecedor, urgência, período e status (ativa/finalizada), para acompanhar o andamento e os disparos.</td>
      <td>Listagem com filtros e colunas essenciais (Fornecedor, NE, Data, UG, Urgência, Frequência, Data prevista, Status) e exportar listagem (CSV/PDF).</td>
      <td>3</td>
    </tr>
    <tr>
      <td>27</td>
      <td>Como administrador, quero poder editar campos do cadastro da nota de empenho.</td>
      <td>Ao clicar no botão “Finalizar Nota de Empenho”, o sistema deve alterar o status da nota para “Finalizada”, registrando a data e o usuário responsável pela ação. Além disso, os campos extraídos automaticamente da nota de empenho, utilizados para compor o e-mail de envio, devem ser exibidos apenas para visualização, sem permitir qualquer tipo de edição manual por parte do usuário.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>28</td>
      <td>Como administrador, quero editar os modelos de e-mail e usar variáveis para montar as mensagens e para personalizar comunicações com dados da NE e do fornecedor.</td>
      <td>Suporte a variáveis: {NUMERO_NE}, {DATA_NE}, {UG}, {RAZAO_SOCIAL}, {CNPJ}, {NOME_RESPONSAVEL}, {CARGO_RESPONSAVEL}, {DATA_PREVISTA}, {FREQUENCIA}, {URGENCIA}.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>29</td>
      <td>Como administrador, quero configurar e executar o envio automático de e-mails nos três fluxos: entrada do pedido, cobrança por atraso e finalização da nota de empenho, para garantir uma comunicação eficiente com o fornecedor durante todo o ciclo da NE.</td>
      <td>O sistema deve permitir configurar e personalizar os 3 tipos de disparo de e-mail:<br>
      • <b>Entrada do pedido:</b> Envia automaticamente o e-mail ao registrar a NE no sistema, com o PDF da nota anexado.<br>
      • <b>Cobrança por atraso:</b> Envia e-mails de cobrança conforme a frequência definida na NE (padrão 15 dias), até que seja finalizada.<br>
      • <b>Finalização da NE:</b> Envia o e-mail informando o encerramento do processo ao fornecedor.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>30</td>
      <td>Como usuário, quero poder redefinir minha senha quando esquecê-la, para recuperar o acesso à minha conta com segurança.</td>
      <td>Um e-mail com link de redefinição deve ser enviado ao usuário. O usuário deve conseguir criar uma nova senha e confirmar a alteração com sucesso.</td>
      <td>2</td>
    </tr>
    <tr>
      <td>31</td>
      <td>Como administrador, quero poder cadastrar, visualizar, editar e excluir os pacientes no sistema.</td>
      <td>O sistema deve permitir cadastro completo e gerenciamento de pacientes.</td>
      <td>8</td>
    </tr>
    <tr>
      <td>32</td>
      <td>Como administrador, quero poder cadastrar, visualizar, editar e excluir os tipos de exames no sistema.</td>
      <td>O sistema deve permitir cadastro e gerenciamento dos tipos de exames.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>33</td>
      <td>Como administrador, quero poder agendar exames para os pacientes.</td>
      <td>O sistema deve permitir cadastro de agendamentos vinculados a pacientes.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>34</td>
      <td>Como administrador, quero poder atualizar o status do exame dos pacientes para agendado, realizado e cancelado.</td>
      <td>O sistema deve atualizar o status dos exames conforme o fluxo do paciente.</td>
      <td>5</td>
    </tr>
    <tr>
      <td>35</td>
      <td>Como paciente, quero poder visualizar os meus agendamentos e datas de retiradas dos exames.</td>
      <td>O sistema deve exibir lista de agendamentos e datas de retirada.</td>
      <td>3</td>
    </tr>
    <tr>
      <td>36</td>
      <td>Como paciente, quero poder visualizar informações de como se preparar para o procedimento selecionado.</td>
      <td>O sistema deve exibir em tempo real os agendamentos e retiradas de exames para os pacientes.</td>
      <td>3</td>
    </tr>
      <tr>
      <td>37</td>
      <td>Como paciente, quero receber e-mails sempre que o status do meu agendamento for atualizado, para acompanhar em tempo real o andamento do meu procedimento.</td>
      <td>O sistema deve enviar automaticamente um e-mail para o paciente quando ocorrer qualquer alteração no status do seu agendamento.</td>
      <td>8</td>
    </tr>
  </tbody>
</table>

<h2>Modelo de dados</h2>
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/blob/main/sprints/sprint02/modelo-de-dados.png">
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/blob/main/sprints/sprint02/modelo-de-dados-agendamento.png">

<h2>DoD (Definition of Done)</h2>

<h2>Mockups</h2>
<h3>Mobile - Administrador do estoque</h3>
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/assets/3ede8d2a-73e1-4283-9847-7c27a54e58a2" alt="MVP">
<h3>Mobile - Administrador dos agendamentos</h3>
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/assets/548dcfb9-a890-4c7d-b853-24e63eb141cc" alt="MVP">
<h3>Mobile - Paciente</h3>
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/assets/0a14c722-ad68-47a1-accc-55dc79f9dd0d" alt="MVP">
<h3>WEB - Administrador do estoque</h3>
<img src="https://github.com/Sync-FATEC/API-2025.2-5SEM/assets/8e3d8c4a-4423-4002-802d-1dc9a8a12c78" alt="MVP">


