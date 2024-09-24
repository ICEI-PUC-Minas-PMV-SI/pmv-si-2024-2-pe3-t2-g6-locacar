# 3. DOCUMENTO DE ESPECIFICAÇÃO DE REQUISITOS DE SOFTWARE

Nesta parte do trabalho você deve detalhar a documentação dos requisitos do sistema proposto de acordo com as seções a seguir. Ressalta-se que aqui é utilizado como exemplo um sistema de gestão de cursos de aperfeiçoamento.

## 3.1 Objetivos deste documento
O objetivo do LocaCar é simplificar e agilizar a interação entre clientes e locadoras, permitindo a busca, seleção e locação de veículos de forma intuitiva, segura e rápida, oferecendo opções de personalização, pagamento online e suporte integrado.

## 3.2 Escopo do produto

### 3.2.1 Nome do produto e seus componentes principais
O produto será denominado LocaCar. Será um sistema web voltado para o mercado de locação de veículos. 

### 3.2.2 Missão do produto
Integrar tecnologias inovadoras de desenvolvimento WEB e modelagem de processos, o LocaCar otimiza cada etapa do processo de locação, desde a reserva até a devolução do veículo, garantindo uma experiência fluida e sem complicações. 

### 3.2.3 Limites do produto
Cobertura Geográfica: O sistema pode ter restrições geográficas, funcionando apenas em certas regiões ou países devido a requisitos legais ou de infraestrutura de internet.
Suporte a Moedas e Idiomas: Pode haver limites na quantidade de moedas e idiomas que o software suporta, especialmente em operações multinacionais.
Gestão de Frota: Pode haver um limite máximo de veículos cadastrados ou simultaneamente gerenciados pelo sistema.
Reserva de Veículos: O sistema pode ter uma capacidade máxima de reservas simultâneas ou no período de tempo definido.
Tipos de Veículos: Algumas soluções podem ser limitadas em relação à variedade de categorias e especificações de veículos que podem ser gerenciadas.
Capacidade de Customização: O software pode ter limites na personalização de recursos, como fluxos de aprovação, taxas de aluguel ou requisitos específicos do cliente.

### 3.2.4 Benefícios do produto

| # | Benefício | Valor para o Cliente |
|--------------------|------------------------------------|----------------------------------------|
|1	| Facilidade no cadastro de dados |	Essencial |
|2 | Facilidade no processo de locação  | Essencial | 
|3 | Segurança nos dados dos clientes | Essencial | 
|4	| Interfaces amigáveis 	| Recomendável | 

## 3.3 Descrição geral do produto

### 3.3.1 Requisitos Funcionais

| Código | Requisito Funcional (Funcionalidade) | Descrição |
|--------------------|------------------------------------|----------------------------------------|
| RF1 | Gerenciar Reserva |	Processamento de efetuar, editar ou excluir uma reserva.| 
| RF2 |	Gerenciar Pagamento | Processamento da forma de pagamento, validação e aprovação.| 
| RF3 | Gerenciar Frota | Processamento de gerenciamento completo da frota, incluir e excluir veículos, quilometragem, modelo. | 
| RF4 | Validar Senha | Processamento de validação de senha no login. | 
| RF5 | Sair do Sistema | Processamento de Logoff do usuário do sistema | 
| RF6 | Gerenciar Clientes | Processamento de cadastro de clientes contendo nome, telefone, CPF/CNPJ e as demais informações pessoais. | 
| RF7 | Gerenciar Cadastro | Processamento de editar e excluir cadastros. | 
| RF8 | Gerenciar Seguros | Processamento de inclusão, exclusão e edição do seguro na locação do veículo. | 
| RF9 | Gerenciar Checklist | Processamento de inclusão, exclusão e edição do checklist do veículo. | 
| RF10 | Gerenciar Receitas | Processamento ao administrador a inclusão, exclusão e quitação de contas a receber. Além disso, deve ser permitido editar essas parcelas. | 
| RF11 | Gerenciar Funcionários | Processamento de inclusão, exclusão e edição de novos e atuais funcionários. | 
| RF12 | Gerenciar Usuários | Processamento de inclusão, alteração, consulta e bloqueio de usuário. | 
| RF13 | Gerenciar Relatórios | Processamento de gerar, editar, adicionar informações a relatórios. | 
| RF14 | Entrada no Sistema | Processamento de Login do usuário cadastrado. | 
| RF15 | Gerenciar Manutenção | Processamento de incluir, editar, excluir e programar manutenção nos veículos. | 
| RF16 | Gerenciar Fornecedores | Processamento de inclusão, alteração, consulta e exclusão de fornecedores. | 
| RF17 | Gerenciar Despesas | Processamento ao administrador a inclusão, exclusão e quitação de contas a pagar. | 

### 3.3.2 Requisitos Não Funcionais

| Código | Requisito Não Funcional (Restrição) |
|--------------------|------------------------------------|
| RNF1 | Usabilidades: O sistema deve apresentar uma interface intuitiva e responsiva, adaptada para dispositivos móveis.  | 
| RNF2 | Manutenibilidade: O sistema deve ser modular e de fácil manutenção, permitindo atualização e correções de bugs sem grandes interrupções. | 
| RNF3 | Confiabilidade: O sistema deve funcionar na maior parte do tempo, com poucas interrupções ou falhas. | 
| RNF4 | Desempenho: Respostas em tempo real para consultas e reservas, com tempo de resposta inferior a 2 segundos. | 
| RNF5 | Permissões: Quem permissões de acesso a cada área do sistema. | 
| RNF6 | O sistema não deve permitir a exclusão de tipos de cobranças e recebimentos com vínculos. | 
| RNF7 | O sistema deve ter capacidade para recuperar os dados perdidos da última operação que realizou em caso de falha | 
| RNF8 | Autorização: O sistema deve garantir que usuários só acessem funcionalidades de acordo com seu nível de permissão. | 
| RNF9 | Segurança: Todos os dados pessoais e transações financeiras devem ser criptografados, com acesso restrito por autenticação. | 
| RNF10 | Disponibilidade: O sistema deve estar disponível 24/7, com uma janela de manutenção não superior a 2 horas por semana. | 
| RNF11 | Conformidade legal: O sistema deve estar em conformidade com as leis de proteção de dados, como a LGPD (Lei Geral de Proteção de Dados). | 
| RNF12 | Deve ser possível rastrear todas as alterações nos dados de reserva e cliente, incluindo histórico de transações. | 
| RNF13 | Disponibilidade: O sistema deve estar disponível 24/7, com uma janela de manutenção não superior a 2 horas por semana. | 
| RNF14 | Suporte técnico: Deve garantir que os problemas reportados sejam resolvidos em até 48 horas após o chamado. | 
| RNF15 | Portabilidade: O sistema deve ser facilmente transferido para ambientes de nuvem como AWS, Azure ou Google Cloud. 
### 3.3.3 Usuários 

| Ator | Descrição |
|--------------------|------------------------------------|
| Clientes |	São os principais usuários do sistema de locação de veículos, realizando reservas, retiradas e devoluções de automóveis. |
| Funcionários  |	Incluem atendentes, agentes de locação, mecânicos e outros profissionais envolvidos na operação da locadora. Eles desempenham papéis cruciais na prestação de serviços de alta qualidade e no atendimento às necessidades dos clientes. |
| Gerentes e Supervisores |	Responsáveis pela supervisão e coordenação das atividades da locadora, garantindo o cumprimento de metas e a eficiência operacional. |

## 3.4 Modelagem do Sistema

### 3.4.1 Diagrama de Casos de Uso
Como observado no diagrama de casos de uso da Figura 1, a secretária poderá gerenciar as matrículas e professores no sistema, enquanto o coordenador, além dessas funções, poderá gerenciar os cursos de aperfeiçoamento.

#### Figura 1: Diagrama de Casos de Uso do Sistema.

![dcu](https://github.com/user-attachments/assets/41f6b731-b44e-43aa-911f-423ad6198f47)
 
### 3.4.2 Descrições de Casos de Uso

Cada caso de uso deve ter a sua descrição representada nesta seção. Exemplo:

#### Gerenciar Professor (CSU01)

Sumário: A Secretária realiza a gestão (inclusão, remoção, alteração e consulta) dos dados sobre professores.

Ator Primário: Secretária.

Ator Secundário: Coordenador.

Pré-condições: A Secretária deve ser validada pelo Sistema.

Fluxo Principal:

1) 	A Secretária requisita manutenção de professores.
2) 	O Sistema apresenta as operações que podem ser realizadas: inclusão de um novo professor, alteração de um professor, a exclusão de um professor e a consulta de dados de um professor.
3) 	A Secretária seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta, ou opta por finalizar o caso de uso.
4) 	Se a Secretária desejar continuar com a gestão de professores, o caso de uso retorna ao passo 2; caso contrário o caso de uso termina.

Fluxo Alternativo (3): Inclusão

a)	A Secretária requisita a inclusão de um professor. <br>
b)	O Sistema apresenta uma janela solicitando o CPF do professor a ser cadastrado. <br>
c)	A Secretária fornece o dado solicitado. <br>
d)	O Sistema verifica se o professor já está cadastrado. Se sim, o Sistema reporta o fato e volta ao início; caso contrário, apresenta um formulário em branco para que os detalhes do professor (Código, Nome, Endereço, CEP, Estado, Cidade, Bairro, Telefone, Identidade, Sexo, Fax, CPF, Data do Cadastro e Observação) sejam incluídos. <br>
e)	A Secretária fornece os detalhes do novo professor. <br>
f)	O Sistema verifica a validade dos dados. Se os dados forem válidos, inclui o novo professor e a grade listando os professores cadastrados é atualizada; caso contrário, o Sistema reporta o fato, solicita novos dados e repete a verificação. <br>

Fluxo Alternativo (3): Remoção

a)	A Secretária seleciona um professor e requisita ao Sistema que o remova. <br>
b)	Se o professor pode ser removido, o Sistema realiza a remoção; caso contrário, o Sistema reporta o fato. <br>

Fluxo Alternativo (3): Alteração

a)	A Secretária altera um ou mais dos detalhes do professor e requisita sua atualização. <br>
b)	O Sistema verifica a validade dos dados e, se eles forem válidos, altera os dados na lista de professores, caso contrário, o erro é reportado. <br>
 
Fluxo Alternativo (3): Consulta

a)	A Secretária opta por pesquisar pelo nome ou código e solicita a consulta sobre a lista de professores. <br>
b)	O Sistema apresenta uma lista professores. <br>
c)	A Secretária seleciona o professor. <br>
d)	O Sistema apresenta os detalhes do professor no formulário de professores. <br>

Pós-condições: Um professor foi inserido ou removido, seus dados foram alterados ou apresentados na tela.

### 3.4.3 Diagrama de Classes 

A Figura 2 mostra o diagrama de classes do sistema. A Matrícula deve conter a identificação do funcionário responsável pelo registro, bem com os dados do aluno e turmas. Para uma disciplina podemos ter diversas turmas, mas apenas um professor responsável por ela.

#### Figura 2: Diagrama de Classes do Sistema.
 
![dcu](https://github.com/user-attachments/assets/97ab1aa8-eb03-4b58-9ad5-1697d414a451)

### 3.4.4 Descrições das Classes 

| # | Nome | Descrição |
|--------------------|------------------------------------|----------------------------------------|
| 1	|	Aluno |	Cadastro de informações relativas aos alunos. |
| 2	| Curso |	Cadastro geral de cursos de aperfeiçoamento. |
| 3 |	Matrícula |	Cadastro de Matrículas de alunos nos cursos. |
| 4 |	Turma |	Cadastro de turmas.
| 5	|	Professor |	Cadastro geral de professores que ministram as disciplinas. |
| ... |	... |	... |
