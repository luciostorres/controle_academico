Durante o semestre, deverá ser construído um site que faça um controle do histórico acadêmico  dos alunos dos cursos de graduação da Faculdade Senac Goiás.

Esse site deverá ser capaz de: 

  Manter o cadastro atualizado dos alunos e ex-alunos  (para que seus históricos não se  percam). Esse cadastro será composto dos dados básicos dos alunos, a saber: nome,  endereço completo, CPF, data de nascimento, sexo e telefones,  e-mail,  além de uma  foto  do  aluno.  Cada  aluno  será  identificado  pelo  seu  CPF.  Esses  dados  poderão  ser  atualizados sempre que necessários. 

  Manter um cadastro  dos cursos oferecidos,  devendo conter um código do curso (com  no  máximo  cinco  caracteres),  o  nome  do  curso,  nome  e  telefone  de  contato  do  coordenador. 

  Matricular  um  aluno  e  um  determinado  curso.  Ao  ser  matriculado,  o  aluno  será identificado por um número de matrícula único no sistema, associado ao curso. Caso o  aluno faça mais de um curso, ele terá dois ou mais números de matrículas, de acordo  com o número de cursos que ele faz (ou fez).  Os dados  do aluno deverão ser cadastrados  somente  uma  vez  no  sistema,  independentemente  se  ele  faz  mais  de  um  curso.  O  sistema também deverá controlar a situação da matrícula  do aluno, que poderá ser:  ativa  (aluno  está  frequentando  o  curso),  trancada  (aluno  está  matriculado,  porém  trancou a matrícula), evadido (aluno desistiu do curso e sua matrícula não é mais válida)  ou  concluído  (aluno  já  concluiu  o  curso,  ou  seja,  colou  grau).  Se  um  aluno  tiver  se  matriculado em um curso, seus dados não poderão ser excluídos (ou seja, um aluno não  poderá ser apagado do sistema), independentemente da situação dessa matrícula. 

  Manter  cadastro  das  disciplinas  de  cada  curso  (grade  curricular),  contendo:  código  alfanumérico  que  identifica  a  disciplina,  nome  da  disciplina  e  curso  no  qual  essa  disciplina faz parte.  Se uma disciplina fizer parte de mais de um curso, ela deverá ser  cadastrada mais de uma vez, com códigos diferentes (um para cada curso). 

  Matricular  um  aluno  em  uma  ou  mais  disciplinas.  Para  cada  disciplina,  deverá  ser  mantido os seguintes dados: ano e semestre (1º ou 2º) que o aluno cursou a disciplina,  conceito do aluno (Insuficiente, Suficiente, Bom ou Ótimo, lembrando que esse conceito  somente  será  conhecido  no  final  do  semestre,  ou  seja,  quando  o  aluno  concluir  a  disciplina), situação da disciplina (em andamento ou já concluída). 

  Ao  matricular  o  aluno  em  uma  determinada  disciplina,  deverão  ser  validadas  as  seguintes regras: o  A disciplina deverá fazer parte da grade curricular do curso no qual o aluno está  matriculado e cursando (a matrícula no curso deverá estar ativa). o  Não pode matricular em uma disciplina que ele já tenha sido aprovado. CONTROLE DE ACESSO Somente  poderão  ter  acesso  ao  site  usuários  cadastrados.  Existirão  os  seguintes  tipos  de  usuários: 

  Administradores: terão acesso a todas as funcionalidades do site, e acesso aos dados de  todos os cursos e alunos. 

  Coordenadores:  terão  acesso  às  funcionalidades  e  acesso  aos  dados  dos  alunos associados aos cursos que ele for coordenador. 

  Funcionários:  terão acessos às funcionalidades relacionadas às matriculas dos alunos  em cursos e disciplinas (todos os cursos e disciplinas). 

  Alunos:  somente  poderão  consultar  seus  próprios  dados  (cadastro  e  histórico  acadêmico). Para acessar o site, os alunos deverão usar seu número de matrícula e uma senha que será  gerada pelo sistema quando o aluno matricular em um curso. Os demais usuários irão acessar o  site  via  login  e  senha,  definidos  pelo  administrador  do  sistema  (o  site  deverá  permitir  a  manutenção  do  cadastro  de  usuários).  O  site  deverá  permitir  que  os  usuários  alterem  suas  senhas de acesso ou que a senha seja redefinida via e-mail. RELATÓRIOS Além das funcionalidades descritas  anteriormente (cadastros), o site deverá disponibilizar  os  seguintes  relatórios  (ou  pesquisas),  obedecidas  às  restrições  de  acesso  por  tipo  de  usuário  conforme descrito anteriormente: 

  Histórico escolar do aluno

  Lista de alunos matriculados em uma determinada disciplina 

  Lista de alunos que poderão colar grau (formar) no final do semestre  (vai depender se  eles forem aprovados nas disciplinas que estão matriculados) 

  Lista de alunos que  já irão colar grau (já foram aprovados em todas as disciplinas do  curso, mas ainda não colaram grau) 

  Relatórios gerenciais
