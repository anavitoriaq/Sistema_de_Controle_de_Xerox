# Sistema de Controle de Xerox


<div>
<img align="right" width="110" height="170" src="https://assecom.ufersa.edu.br/wp-content/uploads/sites/24/2014/09/PNG-bras%C3%A3o-Ufersa.png">
<br>



 


## Requisitos do projeto:

- A opção Sair é a única que permite sair do programa.
- A cada execução do seu programa, os dados devem ser armazenados em um arquivo txt e deve carregar os mesmos para o programa.
- Cada nova reserva cadastrada deve ser inserida em uma ordem cronológica.
- O arquivo deve refletir o estado atual dos dados em virtude da adição ou remoção.



## Sobre o Projeto:

Este projeto tem como objetivo o desenvolvimento de um sistema de controle de xerox, capaz de gerenciar pedidos de cópias feitos por alunos, professores e funcionários permitindo registrar, consultar e controlar os pedidos e os custos envolvidos.

## Como funciona:

O sistema funciona como um gerenciador de pedidos de xerox, registrando informações como nome, tipo de solicitante (aluno, professor, funcionário), quantidade de páginas e o valor total do pedido. Cada pedido tem um status que pode ser "pendente", "concluído" ou "cancelado". O usuário interage com o sistema por meio de um menu, onde pode:

   - Adicionar novos pedidos
   - Excluir ou editar pedidos existentes
   - Listar todos os pedidos ou filtrá-los por status
   - Buscar pedidos pelo nome ou número do solicitante
   - Consultar o total de cópias realizadas e o valor arrecadado.

O sistema utiliza um arquivo texto para salvar e carregar os pedidos, garantindo que as informações sejam mantidas entre execuções do programa. A cada operação, o arquivo é atualizado automaticamente para refletir o estado atual dos pedidos.

A implementação do sistema utiliza a linguagem C, para garantir que os pedidos sejam mantidos organizados e atualizados no arquivo, garantindo a integridade dos dados.


<div>
    <h2 id="tech" style="font-weight: bold; font-size: 2rem">Tecnologia Utilizada</h2>
    <img width="50" height="26" alt="C" src="https://img.shields.io/badge/C-4169E1?style=for-the-badge&logo=c&logoColor=white"/>
  </div>


## Como rodar na minha maquina?

Primeiro Clone o repositorio na sua maquina:

```bash
git clone https://github.com/classroom-ufersa/Sistema_de_Controle_de_Xerox.git
```

Para executar você precisa navegar até o diretório onde o arquivo c se encontra, e no terminal use este comando:

```
gcc main.c -o main && ./main
```

  

<h2 id="colab" style="font-weight: bold; font-size: 2rem">Contribuidores</h2>
 
<table>
</div>
<table> <tr> <td align="center"> <a href="#"> <img src="https://avatars.githubusercontent.com/u/162624679?v=4" width="100px;" alt="Fernanda Kipper Profile Picture"/><br> <sub> <a href="https://github.com/anavitoriaq"><b>Ana Vitória</b></a> </sub> </a> </td> <td align="center"> <a href="#"> <img src="https://avatars.githubusercontent.com/u/143735022?v=4" width="100px;" alt="Laura Gonçalves"/><br> <sub> <a href="https://github.com/lauragoncalvesf"><b>Laura Gonçalves</b></a> </sub> </a> </td> </tr> </table>
</div>