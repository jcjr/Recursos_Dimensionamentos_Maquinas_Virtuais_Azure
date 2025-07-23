# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## OBJETIVO
O objetivo principal é descrever de forma simples como criar uma máquina virtual na plataforma Microsoft Azure. Serão abordados conceitos
de configuração básica como nome nome, poder de processamento e memória RAM, tamanho de armazenamento, rede, gerenciamento de acesso,
monitoramento e diagnótico da máquina virtual, aplicativos da VM e host de acesso.

## Criando a rede virtual
1o. Na pesquisa da tela inicial, procure por "Máquina virtuais", e clique no item com o nome descrito.

2o. Na tela apresentada clique no menu "+ Criar" e selecione "Máquina virtual". Existem outras opções mais avançadas que possem
configurações já pré estabelecidas que são adotados por profissionais com mais conhecimento nessa área.

3o. Na aba básico apresentada, deve-se escolher o grupo de recursos na qual sua máquina virtual irá trabalhar. Mais abaixo você
cria um nome para a máquina virtual a ser criada e escolhe a zona que será criado a VM (OBS: Alguns recursos são limitados em
algumas zonas). Em seguida, escolhe entre os diversos sistemas operacionais disponíveis e escolhe o sistema de arquivo x64 ou
Arm64 caso o seu sistema tenha suporte. Também é possível escolher o nível de processamento e memória a ser utilizado no servidor.
Criar uma conta de usuário com senha logo mais abaixo e por último escolhe a porta de comunicação com a máquina virtual.

4o. Seleciona a aba "Discos". Nesse ponto é selecionado o tamanho de armazenamento do disco da máquina virtual. Também é possível 
seleciona um disco já existente.

5o. Na aba "Rede" é possível criar uma rede virtual dentro da sua VM. Caso não apareça nome de alguma rede já criada deve-se 
clicar no link "Criar novo" e daí colocar um nome para a rede. Mais abaixo seleciona o tipo de portas de entrada públicas.

6o. Na aba "Gerenciamento" é possível realizar configurações relacionada ao backup e atualização do sistema operacional da VM.

7o. Na aba "Revisar + criar" após a conclusão das configurações básicas, deve-se clicar no botão "Criar" que fica mais abaixo para
criar sua máquina virtual.

Outras configurações encontradas são mais avançadas e depende de conhecimento específico para cada item, como este é um caso
de aprendizagem inicial não foram comentados.
