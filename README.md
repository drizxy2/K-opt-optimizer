K-OPT
Aplicativo portátil para Windows x64 que reúne informações do computador,
processos e ferramentas de apoio para jogos em uma interface.

Recursos
Consulta informações de hardware e processos do Windows.
Exibe métricas de CPU e, quando há uma fonte compatível, tempos de quadro.
Permite cadastrar jogos e acompanhar uma sessão iniciada pelo usuário.
Oferece controles compatíveis para o Windows, com confirmação antes das
alterações e tentativa de restauração do estado anterior.
Guarda preferências e o registro de aceite dos termos localmente no perfil
Windows do usuário.
Os dados variam conforme o computador, o Windows, as permissões e as fontes
disponíveis. Métricas que não podem ser medidas são indicadas como indisponíveis,
em vez de serem apresentadas como resultados reais. Algumas ações podem exigir
confirmação do Windows e reinicialização. Consulte os avisos mostrados no
aplicativo antes de aplicá-las.

O K-OPT não promete aumento específico de FPS ou desempenho. A seção de ponto
de restauração explica como abrir as ferramentas do Windows; o aplicativo não
cria nem verifica pontos de restauração. Ele não instala um driver de kernel.

Requisitos
Windows 10/11 de 64 bits (x64).
Microsoft Edge WebView2 Evergreen Runtime.
O runtime .NET necessário já está incluído no pacote.
Baixar e executar
Baixe k-opt github.zip na seção Releases deste repositório.
Extraia o ZIP inteiro em uma pasta. Não mova o executável para fora dela.
Execute KOpt.Desktop.exe.
Leia e aceite os termos na primeira execução para continuar.
Mantenha todos os arquivos e pastas extraídos juntos. O K-OPT é portátil: este
pacote não é um instalador e não configura atualizações automáticas.

Aviso do Windows
O aplicativo não tem assinatura digital. O Microsoft Defender SmartScreen pode
mostrar um aviso dizendo que o publicador é desconhecido. Baixe somente do
repositório/release oficial e confira o SHA-256 publicado junto ao ZIP antes de
executá-lo. Algumas ações de configuração podem solicitar confirmação do UAC;
autorize somente uma ação que você iniciou e compreendeu.

Privacidade
O aplicativo usa um serviço local no próprio computador; não é necessário criar
uma conta K-OPT. Informações de hardware e processos são consultadas localmente
para exibir os recursos escolhidos. Preferências, consentimento dos termos e
informações necessárias para tentar restaurar alterações ficam no computador,
no perfil Windows do usuário.

Licença
O K-OPT é proprietário. A licença incluída permite baixar, instalar e usar
gratuitamente, para fins pessoais ou comerciais, uma cópia obtida de um canal
autorizado pelo titular. Ela não permite modificar, redistribuir, vender ou
sublicenciar o próprio K-OPT. Os componentes de terceiros seguem suas próprias
licenças; consulte LICENSE.txt e THIRD-PARTY-NOTICES.txt.

Suporte
Se encontrar um problema, informe a versão do Windows e os passos para
reproduzi-lo. Não publique nomes de usuário, caminhos pessoais, nomes/PIDs de
processos ou logs que possam identificar você ou seu computador.
