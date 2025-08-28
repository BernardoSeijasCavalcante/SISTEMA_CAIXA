# SISTEMA_CAIXA
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/LICENSE) 

<div>
  Este repositório exibe duas versões de um sistema de CAIXA inicialmente planejado para um <a href="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/CAIXA_QUIOSQUE.xlsm">QUIOSQUE</a>, mas posteriormente adaptado para um <a href="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/tree/main/CAIXA_RESTAURANTE">RESTAURANTE</a>. O sistema do restaurante é a versão mais atualizada dos dois, incluindo várias funções não só dedicadas ao sistema de gestão de produtos, estoque e pedidos padrões de um caixa, como também adaptadas às regras de negócio do cenário específico de um restaurante. <strong>Tudo isso feito em VBA no Excel</strong>.
</div>

<h2>SISTEMA DE CAIXA</h2>
<img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/TELA_DE_CAIXA_COM_CLIENTES_E_PRODUTOS.png">

<h2>SISTEMA DE CADASTROS</h2>
<img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/TELA_CADASTRO_COM_PRODUTO.png">

<h2>ESTRUTURA DO BANCO DE DADOS NO ACCESS</h2>
<img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/BANCO_DE_DADOS.png">

<hr>

<h2>Funcionalidades</h2>
<p>Observe que as tabelas abaixo demonstram os códigos necessários para a utilização do sistema para cada respectiva funcionalidade implementada nele.</p>
<h4>SISTEMA DE CAIXA</h4>
<table>
  <tr>
    <td>Registro de Produto no Pedido por Código Principal</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/C%C3%93DIGO_PRINCIPAL.png"></td>
  </tr>
  <tr>
    <td>Registro de Produto no Pedido por Nome</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/REGISTRO_NOME_PRODUTO.png"></td>
  </tr>
  <tr>
    <td>Registro de Produto no Pedido por Código Auxiliar</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/C%C3%93DIGO_AUXILIAR.png"></td>
  </tr>
  <tr>
    <td>Reiniciar Pedido</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/REIN.png"></td>
  </tr>
  <tr>
    <td>Registro de Produto no Pedido com Quantidade</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/REGISTRO_COM_QUANTIDADE.png"><p>O número à esquerda do "*" é a quantidade.</p></td>
  </tr>
  <tr>
    <td><strong>Registro de Produto no Pedido Descontando Quantidade</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/DESCONTA_QUANT.png"><p>Se houver o registro do produto no pedido, sua quantidade será descontada</p></td>
  </tr>
  <tr>
    <td>Registro de Produto sem Cadastro no Pedido</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/DIV.png"></td>
  </tr>
  <tr>
    <td>Apagar Último Registro de Produto no Pedido</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/APAGARU.png"></td>
  </tr>
  <tr>
    <td><strong>Apagar um Registro de Produto Selecionado no Pedido</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/APAGAR.png"></td>
  </tr>
  <tr>
    <td>Efetuar Pagamento</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/DINouDEBouCREDouPIX.png"><p>DIN para pagar em dinheiro; DEB para pagar no débito; CRED para pagar no crédito; PIX para pagar no PIX.</p></td>
  </tr>
  <tr>
    <td><strong>Pagar com Mais de uma Forma de Pagamento</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/PAGAR.png"><p>Digite o valor a ser pago na forma de pagamento X e preencha o campo forma de pagamento. Vá fazendo isso até que a dívida seja quitada.</p></td>
  </tr>
  <tr>
    <td><strong>Deletar o Registro do Último Pedido</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/DELETU.png"></td>
  </tr>
  <tr>
    <td><strong>Salvar o Pedido em Andamento de um Cliente</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/CLIENTE.png"></td>
  </tr>
  <tr>
    <td><strong>Seleciona o Pedido em Andamento de um Cliente</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/SELECIONA_CLIENTE.png"></td>
  </tr>
  <tr>
    <td><strong>Apagar o Pedido em Andamento de um Cliente</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/CLIENTEDEL.png"></td>
  </tr>
  <tr>
    <td><strong>Encaminha Usuário para a Tela de Cadastro</strong></td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/C%C3%93DIGOS/CAD.png"></td>
  </tr>
</table>
<h4>SISTEMA DE CADASTRO DE PRODUTOS</h4>
<table>
  <tr>
    <td>Buscar Cadastro de Produto</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/BUSCAR_CADASTRO_DE_PRODUTO.png"><p>O sistema busca automaticamente o cadastro do produto no banco de dados assim que o usuário digita um identificador qualquer.</p></td>
  </tr>
  <tr>
    <td>Botão para Registrar Produto</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/REGISTRAR.png"></td>
  </tr>
  <tr>
    <td>Botão para Reiniciar Processo de Registro</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/REINICIAR.png"></td>
  </tr>
  <tr>
    <td>Botão para Resgatar Último Produto Registrado</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/EDITAR_ULTIMO.png"></td>
  </tr>
  <tr>
    <td>Botão para Deletar o Registro do Produto Selecionado</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/DELETAR.png"></td>
  </tr>
  <tr>
    <td>Botão para Retornar ao Caixa</td>
    <td><img src="https://github.com/BernardoSeijasCavalcante/SISTEMA_CAIXA/blob/main/IMAGENS/CAIXA_RESTAURANTE/SISTEMA%20DE%20CADASTRO/CAIXA.png"></td>
  </tr>
</table>

<hr>

<h3>Tecnologias Utilizadas</h3>
<ul>
  <li>Excel;</li>
  <li>VBA-Excel;</li>
  <li>Macro-Excel;</li>
  <li>Access;</li>
  <li>SQL.</li>
</ul>

# Autor

Bernardo Seijas Cavalcante - 2024

www.linkedin.com/in/bernardoseijascavalcante
