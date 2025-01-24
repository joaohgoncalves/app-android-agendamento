🔨 Funcionalidades
A primeira e principal funcinalidade: Marcar um agendamento em uma lista de horários, afim de organizar o dia a dia do profissional
Funcionalidade 2: Adicionar, remover e alterar agendamentos, clientes, serviços e despesas.
Funcionalidade 3: Atalho rápido para acessar os dias da semana atual.
Funcionalidade 4: Facilidade, objetividade e rapidez no agendamento.
Funcionalidade 5: Importar contatos do smartphone para o aplicativo.
Funcionalidade 6: Possibilitar a seleção de mais de um tipo de serviço quando for agendar um horario.
Funcionalidade 7: Relatório financeiro -> diario, mensal e por período
Funcionalidade 8: Salvar dados em um banco local, no caso, no próprio smatphone.
Funcionalidade 9: Salvar dados em um banco Remoto(cloud heroku) atravéz de uma aplicação Spring Boot.
Funcionalidade 10: Autenticar Usuário através de uma tela de login(via token para servidor remoto).
185512784-cd349ac6-a7d0-496f-b4fe-74326933823f.gif

📜 Características
1: Após autenticar o usuário pela primeira vez faze-lo de forma automática sempre que abrir o aplicativo.
2: Não permitir sobrepor um agendamento, ou seja, não é possível marcar mais de um agendamento no mesmo horário.
3: Não permitir excluir um horário caso o mesmo esteja vazio, ou seja, disponível.
4: Permitir alterar o tempo de duração de um agendamento de forma automática caso o mesmo exceda o limite disponivel na agenda.
5: Os agendamentos possuem cores distintas, são elas: branco(para agendamentos que já aconteceram), amarelo(para agendamentos qua ainda não aconteceram e que foram feitos pelo PROFISSIONAL), rosa(agendamentos que ainda não aconteceram e que foram feitos pelo CLIENTE).
cores agenda

SERVIDOR CLOUD ☁️
1: Backup de dados.
2: Cliente pode marcar horário de forma autônoma
3: inserir, editar e excluir dados só é possivel com acesso a rede
4: caso a rede esteja indisponível é possível visualizar os dados já que os mesmos estão salvos também localmente.
5: autenticação no servidor via token (expira em 24hrs), renova sempre que o app é inicializado.
SERVIDOR LOCAL
1: Os dados são salvos no próprio smartphone, ou seja, só poderão ser acessados através do mesmo.
2: inserir, editar, excluir e visualizar sem necessidade de uma rede de dados.
3: é preciso cadastrar o usuario e a empresa no servidor para ter acesso ao aplicativo. Após o cadastro e login, a rede de dados não é mais necessária.
4: sempre que abrir o app logar de maneira automática caso os dados do usuario ainda estejam salvos localmente.
📁 Acesso ao projeto
Você pode baixar o apk e instalar no seu emulador ou no próprio smartphone, é apenas para fins de estudo.

link para download do apk: https://www.mediafire.com/file/35n000ur213bh7h/beauty_style.apk/file

Pré-requisitos

Android 8.0(Oreo) Min. SDK 26
✔️ Técnicas e tecnologias utilizadas
Java 8
Android Framework
Project Struture MVVM
Clean Architecture
Clean Code
Android Studio (InteliJ IDEA)
Paradigma de orientação a objetos
RxJava3
Room SqlLite
Dagger
Retrofit
