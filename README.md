Aqui então  códigos e testes do ROS 1 e ROS 2,  quais servirão de base para simulação de drone e  de logística   
Cabe ressaltar que essa pagina foi feita baseado no estudo da documentação do ROS  (Robot Operating System)  link da pagina http://wiki.ros.org/pt_BR 
# ROS-1_and_ROS-2 


O ROS (Robot Operating System) é um framework de software de código aberto usado para desenvolver e controlar sistemas robóticos. Ele fornece uma coleção de ferramentas, bibliotecas e convenções que facilitam o desenvolvimento de software para robôs. O ROS permite que os desenvolvedores criem módulos independentes de software chamados de nós, que se comunicam entre si por meio de mensagens, serviços e tópicos. Com sua natureza modular, o ROS promove o desenvolvimento colaborativo, reutilização de código e acelera o progresso na área da robótica.
 O ROS 2 é a versão mais recente e atualizada do ROS, com várias diferenças significativas em relação ao ROS 1. Aqui estão algumas das principais diferenças entre o ROS 1 e o ROS 2:

Sistema de comunicação: O ROS 1 usa um sistema de comunicação baseado em tópicos e serviços usando o middleware ROS 1, conhecido como "roscpp" ou "rospy". O ROS 2 introduz um novo sistema de comunicação chamado ROS 2 Middleware, que é baseado em um padrão industrial chamado Data Distribution Service (DDS). O ROS 2 Middleware oferece maior flexibilidade, escalabilidade e suporte para comunicação em tempo real, além de permitir a interoperabilidade com outros sistemas que também usam o DDS.

Modularidade aprimorada: O ROS 2 é projetado com uma arquitetura modular mais clara e flexível. Ele permite a execução de nós em diferentes máquinas ou em contêineres separados, facilitando a distribuição e o gerenciamento de sistemas robóticos complexos.

Ferramentas adicionais: O ROS 2 vem com uma nova coleção de ferramentas que abrangem desde a compilação e depuração até a visualização e análise de dados. Ferramentas como o "ros2cli" e o "rqt" fornecem recursos aprimorados para ajudar os desenvolvedores no desenvolvimento e depuração de aplicativos robóticos.

 # ROS 1
Nesse campo vamos discultir porque ainda usamos o ROS 1, razões pelas quais alguém pode optar por usar o ROS 1 em vez do ROS 2.

Maturidade e estabilidade: Ele tem uma comunidade de desenvolvedores ativa e estabelecida, bem como uma vasta quantidade de pacotes e bibliotecas disponíveis. Isso significa que o ROS 1 é uma plataforma madura, estável e amplamente testada em muitos projetos robóticos ao redor do mundo. Resaltando,  grande quantidade de recursos disponíveis, como tutoriais, exemplos, documentação e fóruns de discussão. Isso facilita a obtenção de suporte e a resolução de problemas durante o desenvolvimento de projetos com o ROS 1.

Suporte a hardware: O ROS 1 tem um suporte bem estabelecido para uma ampla variedade de hardware robótico. Existem pacotes e drivers disponíveis para trabalhar com sensores, atuadores e plataformas de robôs populares.

Integração com pacotes existentes/ Sistemas legado: Se você já possui pacotes, bibliotecas ou código legado desenvolvido para o ROS 1, pode ser mais conveniente continuar usando o ROS 1 para aproveitar e reutilizar esses recursos. A migração para o ROS 2 pode exigir esforços adicionais de portabilidade e adaptação.

# Ros 2
Nesse topico cabe ressaltar que o ROS 2 se diferencia ja no que foi citado mas o grande coisa que ele sai na frente é a facilidade de comunicação e velocidade o que per mite criar mais facilmente, robos com processamentos em diferentes lugaraes, o que gera tipos de robos como enxame. A titulo de exemplo:  ROS 2 Multimaster é um projeto que aborda o desafio de comunicação entre múltiplos mestres do ROS 2. Em um enxame de robôs, cada robô pode ter seu próprio mestre ROS 2 para gerenciar sua rede de comunicação interna. O ROS 2 Multimaster permite que os mestres se comuniquem entre si, permitindo a colaboração e a troca de informações em um enxame distribuído. 

# Primeiros passos em ROS 1
Em primeiro ligar você precisa de um sistema linux, pode se wsl, uma virtulização ou ate mesmo  um dualboot. Eu indico uma virtualização ou dualboot pela interfaca grafica, pois para algumas aplicações você pode quer simular. Dito isso o primeiro passo com isso é baixar o sistema na sua maquina siga os a trilha https://github.com/danielgenio/ROS-1_and_ROS-2/blob/main/instala%C3%A7%C3%A3o.md
Indico testar o ROS 1 com a sequente trilha 

