# Lista de User Stories

## Descrição

Este documento descreve os User Stories criados a partir da Lista de Requisitos no [Documento de Visão](doc-visao.md). 

## Histórico de revisões

| Data       | Versão |                           Descrição                       | Autor                          |
| :--------- | :----: | :-------------------------------------------------------: | :----------------------------- |
| 21/04/2023 | 1.0.0  |                Detalhamento do User Story US02            | Raquel Lima Fernandes          |
| 10/05/2023 | 1.0.0  |               Inserção dos testes de aceitação            | Raquel Lima Fernandes          |


<table>
  <thead>
    <tr>
      <th colspan="4" scope="row">User Story US02 - Manter Produto</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td scope="row"><b>Descrição</b></td>
      <td colspan="3">Como gerente de uma loja de materiais de construção,
        quero ser capaz de manter uma lista atualizada de produtos,
        para que eu possa gerenciar meu estoque de maneira eficiente e atender às necessidades dos clientes.
</td>
    </tr>
    <tr>
      <td scope="row"><b>Requisistos Envolvidos<b/></td>
      <td colspan="3">RF001, RF002, RF003, RF004, RF005 e RF006</td>
    </tr>
    <tr>
      <td scope="row"><b>Prioridade</b></td>
      <td colspan="3">Essencial</td>
    </tr>
    <tr>
      <td scope="row"><b>Estimativa<b/></td>
      <td>5h</td>
      <td><b>Tempo Gasto (real):<b/></td>
      <td>5h</td>
    </tr>
    <tr>
      <td scope="row"><b>Analista<b/></td>
      <td colspan="3">Raquel (responsável por especificar/detalhar o US).</td>
    </tr>
    <tr>
      <td scope="row"><b>Desenvolvedor<b/></td>
      <td colspan="3">Raquel (responsável por implementar e realizar testes de unidade e testes de integração).</td>
    </tr>
    <tr>
      <td scope="row"><b>Revisor<b/></td>
      <td colspan="3">Annielly (responsável por avaliar a implementação e executar os testes de unidade e testes de integração).</td>
    </tr>
    <tr>
      <td scope="row"><b>Testador<b/></td>
      <td colspan="3">Renata (responsável por executar os Testes de Aceitação e fazer o relatório de testes).</td>
    </tr>
    <tr>
      <th colspan="4" scope="row">Testes de Aceitação (TA)</th>
    </tr>
    <tr>
      <td scope="row"><b>Código</b></td>
      <th colspan="3">Descrição</th>
    </tr>
    <tr>
      <td scope="row"><b>TA01.01<b/></td>
      <td colspan="3">Como gerente da loja, quando eu acessar a página para adicionar um novo produto, devo ser capaz de preencher todos os campos obrigatórios, incluindo nome, descrição, categoria, preço, estoque, imagem e outras informações relevantes. Ao clicar em "Salvar", devo ser notificado com uma mensagem de sucesso: "Produto adicionado com sucesso". O produto deve ser exibido na lista de produtos disponíveis na loja.</td>
    </tr>
    <tr>
      <td scope="row"><b>TA01.02</b></td>
      <td colspan="3">Como gerente da loja, ao acessar a página para editar as informações de um produto, devo ser capaz de editar todos os campos do produto, incluindo nome, descrição, categoria, preço, estoque, imagem e outras informações relevantes. Ao clicar em "Salvar", as alterações devem ser salvas com sucesso e as informações do produto devem ser atualizadas na lista de produtos disponíveis na loja.</td>
    </tr>
    <tr>
      <td scope="row"><b>TA01.03</b></td>
      <td colspan="3">Como gerente da loja, quando eu acessar a página de listagem de produtos, devo ser capaz de selecionar um produto para exclusão. Quando eu clicar em "Excluir", o produto deve ser excluído com sucesso e uma mensagem "Produto excluído com sucesso" deve ser exibida na tela. Após a exclusão, o produto não deve mais ser exibido na lista de produtos disponíveis na loja.</td>
    </tr>
    <tr>
      <td scope="row"><b>TA01.04</b></td>
      <td colspan="3">Como gerente da loja, quando eu acessar a página de listagem de produtos, devo ser capaz de visualizar todos os produtos existentes na loja. Ao clicar em um produto, devo ser direcionado para a página de detalhes do produto, e as informações do produto devem ser exibidas corretamente, incluindo nome, descrição, categoria, preço, estoque, imagem e outras informações relevantes.</td>
    </tr>
    <tr>
      <td scope="row"><b>TA01.05</b></td>
      <td colspan="3">Como gerente da loja, quando tento adicionar ou editar informações de um produto, todos os campos obrigatórios devem ser validados. Se inserir dados inválidos em algum campo, exibirá uma mensagem de erro (Mensagem: Campos incorretos) e o produto não será adicionado ou editado até que todos os campos sejam preenchidos corretamente. Se o estoque de um produto for menor que zero, exibirá uma mensagem de erro informando que o produto está fora de estoque. Mensagem: Produto fora de estoque.
      </td>
    </tr>
  </tbody>
</table>
