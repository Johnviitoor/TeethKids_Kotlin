# Aplicativo TeethKids Dentista

Este é um aplicativo de marcação de consultas dentárias, desenvolvido em Kotlin utilizando o Android Studio. Ele permite que os dentistas realizem o cadastro, façam login, cadastrem seus dados pessoais, receba solicitações de consultas feitas por usuario no app em flutter, compartilhem informações de localização e sejam avaliados pelos usuarios.

## Funcionalidades Principais

1. **Cadastro e Login:** Os dentistas podem se cadastrar utilizando um endereço de e-mail e senha. Se já tiverem cadastro, eles podem fazer login com suas credenciais.

2. **Informações Pessoais:** Após o cadastro, os dentistas podem completar seu perfil, incluindo nome completo, foto de perfil, currículo, três endereços e telefone de contato.

3. **Marcação de Consultas:** Os dentistas podem marcar consultas com os pacientes, selecionando uma data e horário disponíveis. Os locais de atendimento são baseados nos endereços cadastrados tanto pelo dentista quanto pelo usuário.

4. **Comunicação em Tempo Real:** O dentista deve ligar para o usuário em até 2 minutos após a marcação da consulta. O aplicativo fornece funcionalidades de chamada telefônica para facilitar a comunicação.

5. **Compartilhamento de Localização:** Após o contato inicial, tanto o usuário quanto o dentista podem compartilhar suas localizações em tempo real para facilitar o encontro no local de atendimento combinado.

6. **Avaliação de Dentistas:** Após a conclusão do procedimento, os usuários podem avaliar o dentista com base em sua experiência. Se um dentista receber uma avaliação negativa, ele pode solicitar uma reavaliação. Caso o dentista considere um comentário ofensivo ou constrangedor, ele pode denunciar o comentário para o suporte.

7. **Atualização do Perfil:** Os dentistas têm a opção de atualizar seu perfil, incluindo a foto, o número de telefone e os endereços de atendimento.

8. **Notificações:** Sempre que um usuário solicitar uma consulta, o aplicativo exibirá uma notificação para o dentista.
   
9. **Avaliações:** Sempre ao final da consulta o app solicita que o usuario avalie o dentista, o aplicativo exibirá a nota dada pelo usuario de 1-5 e o comentarios para o dentista (somente a nota sera exibida no perfil publicamente), caso o dentista não goste do comentario e da nota ele pode pedir uma reavaliação e caso se sinta ofendido com o comentario ele pode pedir ao suporte a verificação do comentario.

## Requisitos Técnicos

- O aplicativo é desenvolvido em Kotlin.
- É necessário ter o Android Studio instalado para compilar e executar o projeto.
- O aplicativo requer acesso à internet para funcionar corretamente.
- É recomendado um dispositivo Android com versão mínima XXXX para garantir a compatibilidade.

## Instalação e Configuração

1. Clone ou faça o download deste repositório em sua máquina local.

2. Abra o Android Studio e importe o projeto.

3. Execute o projeto no emulador do Android Studio ou conecte seu dispositivo Android ao computador e execute o aplicativo diretamente nele.

4. Certifique-se de que as permissões de acesso à internet estejam configuradas corretamente no dispositivo ou no emulador.

## Limitações Conhecidas

- O aplicativo depende de uma conexão estável com a internet para funcionar corretamente.
- A disponibilidade de dentistas e horários pode variar.
- O aplicativo atualmente não oferece suporte a outros métodos de autenticação além de e-mail e senha.
- Recomenda-se que os usuários estejam atentos à privacidade das informações compartilhadas e

 tomem medidas apropriadas para proteger seus dados.

## Contribuição

Contribuições são bem-vindas! Se você encontrar problemas ou tiver sugestões de melhorias, fique à vontade para abrir uma issue neste repositório. Sinta-se à vontade também para fazer um fork do projeto e enviar um pull request com suas modificações.

## Licença

Este projeto está licenciado sob a [Licença XYZ](https://exemplo.com/licenca). Leia o arquivo `LICENSE` para obter mais informações.

*Observação: Este arquivo README é apenas um exemplo e pode ser adaptado de acordo com as necessidades e requisitos específicos do seu projeto.*
