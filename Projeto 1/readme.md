O projeto 1 consistia em desenvolver uma planilha que permitesse o cadastro de entradas e saídas de caixa, gerar relatórios relacionados aos dados e dois dashboard interativos, um por ano e outro por data.
### Menu:


![Imagem Menu](ImagensPlanilha/Menu.png)
Menu criado para facilitar a navegação na planilha.


### Cadastro de Entradas Nível 1:
![Imagem da planilha de Entrada nível 1](ImagensPlanilha/PCEntradaN1.png)
Planilha para realizar o cadastro de entrada nível 1, este cadastro será utilizado para validar registros de entrada.


### Cadastro de Entradas Nível 2
![Imagem da planilha de Entrada nível 2](ImagensPlanilha/PCEntradaN2.png)
Planilha para realizar o cadastro de entrada nível 2, este cadastro será utilizado para validar registros de entrada, verificando a existência do cadastro e se ele está devidamente associado ao Nível 1.


### Cadastro de Saídas Nível 1:
 ![Imagem da planilha de Saídas nível 1](ImagensPlanilha/PcSaidasN1.png)
Planilha para realizar o cadastro de saídas nível 1, este cadastro será utilizado para validar registros de saída.


### Cadastro de Saídas Nível 2:
![Imagem da planilha de Saídas nível 2](ImagensPlanilha/PCSaidasN2.png)
Planilha para realizar o cadastro de saídas nível 2, este cadastro será utilizado para validar registros de saídas, verificando a existência do cadastro e se ele está devidamente associado ao Nível 1.

 
 ### Registro de Entradas
 ![Imagem do Registro de Entradas](ImagensPlanilha/RegistroEntradas.png)
 Planiha Utilizada para o usuário realizar entradas. Nesta planilha foram realizadas as seguintes ações:
 1) Validação de dados 
 
 1.1) Para validar os dados, a coluna conta Nível 1 possui um critério de validação de listas "=PCEntradasN1_Nível_1". Permitindo apenas que dados previmente cadastrados sejam aceitos.

1.2) A coluna conta Nível 2 também possui um critério de validação de listas. "=DESLOC(PCEntradasN2_Nível_2; CORRESP(E4; PCEntradasN2_Nível_1; 0)-1; 0; CONT.SE(PCEntradasN2_Nível_1; E4))" Esta fórmula garante que possa ser cadastrado apenas itens registrados anteriormente no nível correspondente.

 2)Construção de colunas auxiliares
 