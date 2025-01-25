Beauty Style - Aplicativo de Agendamento e Gestão

🔨 Funcionalidades

 Agendamento de Horários: Marque agendamentos em uma lista de horários para organizar o dia a dia do profissional.
 
 Gestão de Agendamentos: Adicione, remova e altere agendamentos, clientes, serviços e despesas.
 
 Atalho Rápido: Acesso rápido aos dias da semana atual.
 
 Facilidade e Objetividade: Agendamentos rápidos e diretos.
 
 Importação de Contatos: Importe contatos do smartphone para o aplicativo.
 
 Seleção de Vários Serviços: Permita a seleção de múltiplos serviços ao agendar um horário.
 
 Relatório Financeiro: Gere relatórios financeiros diários, mensais e por período.
 
 Armazenamento Local: Dados salvos no banco de dados local do smartphone.
 
 Armazenamento Remoto: Dados também salvos na nuvem através de um servidor Heroku utilizando Spring Boot.
 
 Autenticação de Usuário: Login via token para acessar o servidor remoto.
 
📜 Características

 Autenticação Automática: Após o primeiro login, o usuário será autenticado automaticamente ao abrir o aplicativo.
 
 Prevenção de Conflitos de Agendamento: Impede que dois agendamentos sejam marcados no mesmo horário.
 
 Agendamentos Válidos: Não é possível excluir um horário que esteja disponível.
 
 Ajuste Automático de Tempo de Agendamento: O tempo de duração dos agendamentos será ajustado automaticamente se exceder o tempo disponível na agenda.
 
 Cores para Agendamentos: Cada tipo de agendamento é representado por uma cor distinta:
 
 Branco: Agendamentos já realizados.
 
 Amarelo: Agendamentos futuros feitos pelo profissional.
 
 Rosa: Agendamentos futuros feitos pelo cliente.
 
☁️ Servidor Cloud

 Backup de Dados: Backup contínuo dos dados na nuvem.
 
 Agendamentos Autônomos: O cliente pode marcar seus próprios horários.
 
 Acesso à Rede: Inserir, editar ou excluir dados só é possível com conexão à internet.
 
 Funcionamento Offline: Caso a rede esteja indisponível, os dados ficam disponíveis localmente.
 
 Autenticação por Token: Autenticação via token com validade de 24 horas, renovado sempre que o app é iniciado.
 
🏠 Servidor Local

 Armazenamento Local: Todos os dados são salvos no smartphone, podendo ser acessados apenas por ele.
 
 Sem Conexão Necessária: Permite a inserção, edição, exclusão e visualização de dados sem rede de dados.
 
 Cadastro Inicial: O cadastro do usuário e da empresa deve ser feito no servidor antes do uso do aplicativo.
 
 Login Automático: O login será feito automaticamente se os dados estiverem salvos localmente.
 
📁 Acesso ao Projeto

 Você pode baixar o APK e instalar no seu emulador ou dispositivo físico para fins de estudo.
 
Link para download do APK: https://www.mediafire.com/file/35n000ur213bh7h/beauty_style.apk/file

Pré-requisitos
Android 8.0 (Oreo) ou superior
SDK mínimo 26
✔️ Técnicas e Tecnologias Utilizadas
Java 8
Android Framework
Estrutura de Projeto MVVM
Clean Architecture
Clean Code
Android Studio (IntelliJ IDEA)
Paradigma de Orientação a Objetos
RxJava3
Room SQLite
Dagger
Retrofit
