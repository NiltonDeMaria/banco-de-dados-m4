# banco-de-dados-m4
Projeto individual do módulo 4 sobre Banco de Dados.

# Sistema Resilia

A Resilia está pensando em lançar um novo sistema de
acompanhamento e para isso precisa de ajuda para modelar um
banco de dados que vai armazenar seus cursos, turmas e alunos.

⇨ Existem outras entidades além dessas três?

    Sim, funcionários.

⇨ Quais são os principais campos e tipos?

    Cursos: curso_id(int), nome(varchar), categoria(varchar) e turma_id(int).
    Turmas: turma_id(int), nome(varchar), turno(varchar) e curso_id(int).
    Alunos: aluno_id(int), nome(varchar), cpf(varchar) e turma_id(int).
    Funcionários: funcionario_id(int), nome(varchar), cpf(varchar), cargo(varchar) e turma_id(int).

⇨ Como essas entidades estão relacionadas?

    Curso contém turma que possui aluno e funcionário.