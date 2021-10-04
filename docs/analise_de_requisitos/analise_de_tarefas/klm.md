# KLM

## Introdução

<p style="text-indent: 20px; text-align: justify">
KLM ou Keystroke-level Model é um método que permite prever o tempos de execução de uma tarefa para execução sem erros por um usuário experiente. Esse método não pressupõem um esforço cognitivo do usuário já que trabalha com a ideia de um usuário experiente realizar a tarefas sem erros e, por isso, possui limitações. É um método que pode ser usado como complemento ao GOMS. [1]
</p>

<p style="text-indent: 20px; text-align: justify">
O método é estruturado em um conjunto de operadores primitivos:
</p>

<p style="text-indent: 20px; text-align: justify">
  <ul>
    <li><b>K</b> para pressionar tecla ou botão.</li>
    <li><b>P</b> para apontar com o mouse um alvo num dispositivo.</li>
    <li><b>H</b> para mover as mãos para o teclado ou outro dispositivo.</li>
    <li><b>D</b> para desenhar um segmento de reta em um grid.</li>
    <li><b>M</b> para se preparar mentalmente para realizar uma ação ou série de ações primitivas fortemente relacionadas entre si.</li>
    <li><b>R</b> para o tempo de resposta do sistema, durante qual o usuário precisa esperar</li>
    <li><b>T</b> indica o tempo para se digitar uma tecla.</li>
    <li><b>B</b> indica o pressionar e soltar o botão do mouse.</li>
  </ul>
</p>

## Resultados

<table style="width:100%">
  <tr>
    <th>Método</th>
    <th>Operador</th>
    <th>Descrição</th>
    <th>Tempo (em segundos)</th>
  </tr>
  <tr>
    <td rowspan=9 >Página inicial -> Portal da transparência -> COVID 19</td>
    <td>M</td>
    <td>Preparação</td>
    <td>1.35</td>
  </tr>
  <tr>
    <td>H</td>
    <td>Levar as mãos do teclado ao mouse</td>
    <td>0.40</td>
  </tr>
  <tr>
    <td>P</td>
    <td>Levar o cursor até o item "Portal da transparência" na barra de navegação</td>
    <td>1.05</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Pressionar e soltar o botão do mouse</td>
    <td>0.20</td>
  </tr>
  <tr>
    <td>R</td>
    <td>Esperar a página ser carregada</td>
    <td>1.20</td>
  </tr>
  <tr>
    <td>R</td>
    <td>Esperar a página ser carregada</td>
    <td>1.20</td>
  </tr>
  <tr>
    <td>P</td>
    <td>Levar o cursor até o item "COVID 19"</td>
    <td>1.40</td>
  </tr>
  <tr>
    <td>B</td>
    <td>Pressionar e soltar o botão do mouse</td>
    <td>0.20</td>
  </tr>
  <tr>
    <td>R</td>
    <td>Esperar a página ser carregada</td>
    <td>1.20</td>
  </tr>
  <tr>
    <td style="text-align: center;" colspan=3><b>Tempo total</b></td>
    <td>8.20</td>
  </tr>
</table>

## Referências

 > https://tassioauad.com/2017/04/10/analise-de-tarefas-com-goms-klm-e-cmn-goms/ último acesso em: 25/08/2021 às 9:20

  > Livro: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. 1ª edição, Rio de Janeiro: Elsevier, 2010.

## Versionamento

|    Versão    | Data |                     Modificação                   |    Autor    |
| :----------: | :--: | :-----------------------------------------------: | :---------: |
| 0.1 |  25/08/2021   |             Estruturação do documento             | Rafael Leão |
| 0.2 |  25/08/2021   |          Escrita do tópico de Introdução          | Rafael Leão |
| 1.0 |  26/08/2021   | Elaboração da análise de tarefas com o método KLM | Rafael Leão |
| 1.1 |  26/08/2021   |               Revisando documento                 | Abner Filipe|
