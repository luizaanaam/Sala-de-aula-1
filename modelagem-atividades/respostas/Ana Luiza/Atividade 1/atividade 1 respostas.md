## Atividade 1  Engenharia de Requisitos (Ana Luiza A.)

### Estudo de Caso 1  Conecta Campus

### 1. Concepção
- Problema: O sistema atual é lento, difícil de usar e as informações acadêmicas ficam espalhadas.

- Objetivo: Unificar notas, horários, avisos e eventos em um único sistema rápido e fácil de acessar.

### 2. Elicitação

- Stakeholders: alunos, professores, coordenação, universidade e equipe de desenvolvimento.

Técnicas:
1. Entrevistas: Conversar diretamente com alunos e professores para entender as principais dificuldades.
2. Análise de documentos: Olhar o sistema atual e relatórios de reclamações para ver o que precisa ser consertado.

### 3. Análise e modelagem de requisitos
Requisitos Funcionais (RF):

- RF01: Permitir login de usuários por perfil (aluno, professor, coordenação).

- RF02: Permitir que o aluno consulte suas notas.

- RF03: Exibir a grade de horários das aulas.

- RF04: Permitir que professores publiquem materiais de estudo.

- RF05: Permitir o envio de avisos e comunicados.

Requisitos Não Funcionais (RNF):

- RNF01: O sistema deve abrir notas e horários em até 2 segundos.

- RNF02: O acesso a dados acadêmicos exige login e senha seguros.

- RNF03: Os alunos devem conseguir usar o sistema sem precisar de treinamento.

### 4. Negociação MoSCoW

- Must Have: Login, consulta de notas, horários e postagem de materiais (o essencial para funcionar)

- Should Have: Avisos e comunicados (importantes mas secundários)

- Could Have: Notificações no celular (se der tempo)

- Won't Have: Chat entre alunos e professores (para não atrasar o desenvolvimento)

### 5. Especificação de requisitos não funcionais

- RNF01 Desempenho: Carregar telas em até 2 segundos. 
Teste: Simular acessos de vários alunos ao mesmo tempo e medir o tempo.

- RNF02Segurança: Bloquear acesso sem login. 
Teste: Tentar entrar no sistema sem senha.

- RNF03 Usabilidade: Alunos novos acharem notas em até 2 minutos. Teste: Observar pessoas usando o sistema pela primeira vez.
 

### 6. Validação

1. Revisão: Mostrar o documento pronto para professores e alunos conferirem se está tudo certo
2. Protótipo: Testar telas de mentirinha (no papel ou computador) para ver se o visual ficou bom antes de programar

## Estudo de Caso 2 PetCare

### 1. Elicitação e stakeholders

- Stakeholders: Tutores, Veterinários, Recepção, Gerência e Proprietário.

Técnicas:

1. Observação: Acompanhar o trabalho na recepção e ver onde perdem tempo com papéis.

2. Entrevistas: Perguntar aos funcionários o que mais dificulta o atendimento.

### 2. Análise e especificação de requisitos

Requisitos Funcionais (RF):

- RF01: Cadastrar pets e tutores.

- : Agendar consultas pelo celular.

- RF03: Controlar horários na recepção.

- RF04: Consultar histórico médico do animal.

- RF05: Registrar diagnósticos e tratamentos.

Requisitos Não Funcionais (RNF):

- RNF01: A agenda deve abrir em até 2 segundos.

- RNF02: Proteção de dados contra vazamentos.

- RNF03: Funcionar nos principais navegadores e celulares

### 3. Negociação MoSCoW

- Must have: Cadastro, agendamento, controle de agenda e histórico do pet (o básico para a clínica funcionar sem papel).
  
- Should have: Lembretes de vacina e relatórios para o chefe.
  
- Could have: Pagamento pelo app e chat com o veterinário.
  
- Won't have: Venda online de produtos(tirando o foco do atendimento médico)

### 4. Especificação de requisitos não funcionais

- RNF01 Desempenho: Abrir a agenda em até 2 segundos. 
  Teste: Cronometrar o tempo de resposta do sistema
  
- RNF02 Segurança: Proteger prontuários. 
  Teste: Tentar entrar com uma conta sem permissão.
  
- RNF03 Prevenção de erros: Impedir dois agendamentos no mesmo horário. 
 Teste: Tentar marcar dois pets na mesma vaga simultaneamente.
  

### 5. Validação dos requisitos

1. Revisão: Apresentar a lista de funções para a recepção e veterinários aprovarem.

2. Protótipos: Testar telas simuladas do app antes de começar a codificar.
   
### 6. Desafio 

1. Cadastro de pets e tutores: Essencial para guardar os dados (beneficia recepção e veterinários).

2. Agendamento pelo celular: Acaba com a demora no WhatsApp (beneficia os tutores).

3. Controle de agenda: Evita choque de horários (beneficia a recepção).

4. Histórico médico: Substitui as fichas de papel (beneficia os veterinários).

5. Controle de senhas: Garante a segurança dos dados (beneficia a todos)

Riscos de adiar o resto: Deixar o chat ou pagamentos para depois evita atrasar o projeto e garante que o sistema principal comece funcionando bem.