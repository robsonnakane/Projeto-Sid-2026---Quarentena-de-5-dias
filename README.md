# Debian Family
Este repositório é para compartilhar os arquivos de atualização dos sistemas da Família Debian de ser.
O Fedora ainda continua como meu "porto seguro" mas todas as distros tem uma nova chance né.
Hoje 2 de novembro de 2026 (fase alpha do projeto), elaborei o shell script "quarentena_debiansid.sh" o qual funciona para controle das novas atualizações de pacotes. O processo de hold e unhold está automático com as condições dos 5 dias de quarentena ou na presença do pacote no listbugs do Debian.
O "Validador de Inicialização Automática" foi criado com o objetivo de verificar se o sistema terá algum problema antes da reinicialização. Portanto se houver alguma inconsistência, melhor resolvê-la antes de reiniciar o sistema.
Os shell script "quarentena_debiansid.sh" e "Validador de Inicialização Automática" funcionan em conjunto com o "Atualização Debian Sid.sh" o qual também possui outros comandos validando o "quarentena_debiansid.sh", assim temos um double-check.
Portanto na utilização do "Atualização Debian Sid.sh", façam o download dos 2 arquivos .sh citados e deem permissão de execução para ambos. 
Tenham a experiência completa de minimizar pelo menos a dor de cabeça com as atualizações bugadas que podem ocorrer. 
Pode não ser perfeito, mas já é o início de um controle.
Esses 3 shell scripts do Debian Sid são os mais atuais. Os outros de distros baseadas no Debian são "menos completos" até pq eu acredito que os scripts do Debian Sid sejam por enquanto os mais completos e quiçá os mais complexos existentes neste Github.
Dia 8 de Novembro de 2028, após a validação de alguns pacotes passados pela quarentena, atualizando-os e reiniciando o sistema sem problema algum, considero os scripts do Debian Sid como fase beta.
Próximos passos, ou pelo menos idéia, elaborar uma interface gráfica para que todos possam utilizar como um atualizador de Debian Sid mas, ainda nem sei por onde começar. 
Quero talvez ter a certeza de que com esses 3 scripts fica inviável a quebra do sistema pelo menos com as novas atualizações.
E importante eu não instalei nenhum pacote adicional de uso do meu dia a dia de forma nativa, eu acredito que se for pra usar o Sid como daily driver, usarei como uma distro imutável, ou seja apenas com containeres e flatpaks.
