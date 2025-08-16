# Challenge-Forum-Hub

🧩 Objetivo do Desafio Fórum Hub:

Criar uma aplicação que simula o funcionamento do Fórum da Alura.
Permitir que pessoas usuárias cadastradas criem, atualizem, visualizem e excluam tópicos.
Praticar autenticação, regras de negócio e segurança de dados.

🧑‍💻 Regras de Negócio
Cada tópico deve conter:

Título;
Mensagem;
Nome do curso;
Data de criação (gerada automaticamente);
Cada tópico pertence a uma pessoa usuária cadastrada;
Apenas a autora ou autor pode editar ou excluir seu próprio tópico;
Tópicos estão vinculados a cursos específicos.

🔐 Segurança e Autenticação:

A aplicação exige login e autenticação via token Bearer.
Sem autenticação, ações como criar, editar ou deletar tópicos são proibidas (erro 403).
A autenticação protege o banco de dados contra ações indevidas de usuários não autorizados.

🧪 Testes com Insomnia
Testes realizados para:

Listar todos os tópicos;
Listar tópico por ID;
Criar novo tópico (com token);
Atualizar tópico (com token);
Deletar tópico (com token);
Exemplo de criação: título “Me ajuda nessa dúvida”, curso “Java”, mensagem “Estou com dúvida”.
