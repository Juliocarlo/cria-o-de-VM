# cria-o-de-VM
Etapas de criação de uma VM básica no Azure

Processo de criação de uma VM no Azure

Depois de criado a conta de acesso no Azure, é necessário realizar login na conta para ser possível configurar uma VM no Azure.
Para configurar uma VM básica, é necessário determinar quais são os recursos para o funcionamento eficiente da VM, 
como sistema operacional, processador, memória, qual é a forma de acesso para gerenciar a VM.

Em máquinas que necessitam de uma maior confiabilidade, é necessário determinar se esta VM possuirá instancias em outros locais, 
se seus dados serão duplicados, triplicados ou mais, em diversas regiões e estancias para garante uma maior confiabilidade do serviço.

Se faz necessário também determinar qual é o nível desta confiabilidade, qual o tempo de indisponibilidade poderá ocorrer nesta máquina, 
e estes dados definirão também em quantas estancias e regiões esta VM será duplicada. 

Outro fator importante é determinar a escalabilidade e a flexibilidade da VM. 
Deve-se definir se esta VM terá capacidade de aumento de recursos e também se ela será flexível para o gerenciamento de uso.

Para iniciar a criação da VM básica seguiremos os seguintes passos:

1-	Na plataforma do Azure, na primeira página, selecionar o ícone de máquina virtual

https://github.com/Juliocarlo/cria-o-de-VM/blob/main/INICIO%20DA%20CRIA%C3%87%C3%83O%20DA%20VM%20FIGURA%201.png

2-	Na próxima etapa, acessar o botão de acesso CRIAR.

https://github.com/Juliocarlo/cria-o-de-VM/blob/main/BOT%C3%83O%20DE%20ACESSO%20CRIAR%20%20FIGURA%202.png

3-	Definir no menu de contexto que será aberto ao lado do botão CRIAR, qual é o de VM que será criado.

https://github.com/Juliocarlo/cria-o-de-VM/blob/main/DEFINIR%20QUAL%20O%20FORMATO%20DA%20VM%20QUE%20SER%C3%81%20CRIADO%20FIGURA%203.png

4-	Na próxima etapa deve-se escolher qual é a assinatura do Azure, grupo de recursos; nos detalhes da instancia é necessário colocar nome da máquina virtual, 
escolher a região, opções de disponibilidade, opções de zona e zona de disponibilidade.

https://github.com/Juliocarlo/cria-o-de-VM/blob/main/CONFIGURANDO%20REGI%C3%83O%20DA%20VM%20FIGURA%204.png
https://github.com/Juliocarlo/cria-o-de-VM/blob/main/CONFIGURANDO%20REGI%C3%83O%20DA%20VM%20FIGURA%204-A.png

5-	A próxima etapa será a configuração dos discos. É necessário definir qual o tamanho e tipo do disco de SO, escolher o gerenciamento de chaves, habilitar compatibilidade do disco, escolher se deseja criptografia de disco.
6-	A seguir, será configurada a rede. Nesta etapa se determina qual é a interface de rede, qual é o endereço da rede, IP Público, portas de entrada públicas
7-	Seguindo a criação da VM, escolher o gerenciamento que será utilizado.
8-	Determinar qual é a forma de gerenciar a VM
9-	Determinar quais aplicativos da VM serão instalados, recursos de desempenho dos NVMe, host, reservas de capacidade, grupo de posicionamento 
10-	Determinar quais marcas serão utilizadas
11-	Na última etapa será realizada a revisão da criação da VM

OBSERVAÇÕES:
Durante a criação da VM, verificar as informações do direito os custos mensais estimados que a VM poderá possuir mensalmente. 
Caso o valor ultrapasse ao orçamento realizado, será necessário reconfigurar toda a máquina até ela esteja dentro do orçamento disponível para utilização. 
