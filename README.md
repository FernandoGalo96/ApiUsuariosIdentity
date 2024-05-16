Descrição da API - Controle de Usuário e Autenticação
Esta API oferece um sistema completo para controle de usuários e autenticação, permitindo a criação, gerenciamento e autenticação de contas de usuário. Desenvolvida utilizando MySQL Workbench, Entity Framework, DTOs, AutoMapper, ela proporciona uma solução robusta e segura para a gestão de usuários em seus aplicativos.

Recursos Principais
Controle de Usuário: Crie, edite, liste e remova informações sobre usuários. Cada usuário possui detalhes como nome, e-mail, senha e permissões.

Autenticação: Implementação de um sistema de autenticação seguro, permitindo que os usuários façam login de forma segura em suas contas.

Token de Acesso: Após a autenticação bem-sucedida, é gerado um token de acesso que pode ser usado para autorizar e acessar recursos protegidos da API.

Segurança-->

Esta API implementa medidas de segurança robustas para proteger os dados dos usuários e garantir a autenticação segura:

Hash de Senha: As senhas dos usuários são armazenadas de forma segura, utilizando algoritmos de hash criptográficos, garantindo a confidencialidade das informações.

JWT (JSON Web Token): O sistema de autenticação utiliza tokens JWT para autorização e acesso aos recursos protegidos da API. Esses tokens são assinados digitalmente e possuem tempo de expiração, aumentando a segurança do sistema.

Esta API fornece uma base sólida para implementação de sistemas de autenticação e controle de usuários em seus aplicativos. Explore a documentação e comece a integrá-la aos seus projetos hoje mesmo!
