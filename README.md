# Business Intelligence - Parte 1

Visualizações realizadas no Tableau.
Visualizações podem ser vistas no <a href="https://public.tableau.com/app/profile/rafael.oliveira5857/vizzes"> Tableau Public</a>.

## Databases:
### 1. Métodos de Pagamento Brasileiro:
Data: Jan/2017 até Jun/2024

#### Métodos de Pagamento:
<ul>
    <li>
        <b>TED:</b> Transferência Eletrônica Disponível. Não há limite de valor de transferência.
    </li>
    <li>
        <b>DOC:</b> Documento de Ordem de Crédito. Há um limite de R$ 4.999,99 por operação ou por dia. Descontinuado em Fev/2024.
    </li>
    <li>
        <b>TEC:</b> Transferência Especial de Crédito. Usado somente por empresas para conceder vantagens aos seus colaboradores. Descontinuada em Fev/2024.
    </li>
    <li>
        <b>Boleto:</b> Título de cobrança que funciona como um compromisso de pagamento entre o cliente e o fornecedor. Emitido pela instituição financeira e contém um código de barras (atualmente QR Code foi incluido) que permite o pagamento.
    </li>
    <li>
        <b>Cheque:</b> Funciona como uma ordem de pagamento à vista ao banco, para que este pague um valor ao beneficiário.
    </li>
    <li>
        <b>Pix:</b> Teve ínicio no meio de Nov/2020. Permite a tranferência de valores entre contas de modo instantâneo, em poucos segundos. Para receber ou fazer transferência é necessário o prévio cadastro de uma chave de acesso, que pode ser o CPF, CNPJ, e-mail, número de telefone ou uma chave aleatória. Não há limitação de horário e é gratuito para pessoas físicas, mas pode ser pago para pessoas jurídicas, com custos que variam de acordo com a instituição financeira.<br>
        Teve uma grande adesão devido a sua flexibilidade de uso. Uma cobrança pode ser emitida pelo próprio usuário sem necessidade de autorização do banco, podendo substituir outros métodos de pagamento e até mesmo o pagamento em dinheiro.
    </li>
</ul>

#### Análises:
<ul>
    <li>
        Análise Temporal
    </li>
    <li>
        Box Plot
    </li>
    <li>
        Correlação Valores x Quantidade
    </li>
</ul>

<hr>

### 2. Pix:

Data: Nov/2020 até Jun/2024.<br>
Nov/2020 considerado como outlier.

#### Dados:
<ul>
    <li>
        <b>Pix:</b> Teve ínicio em Nov/2020. Permite a tranferência de valores entre contas de modo instantâneo, em poucos segundos. Para receber ou fazer transferência é necessário o prévio cadastro de uma chave de acesso, que pode ser o CPF, CNPJ, e-mail, número de telefone ou uma chave aleatória. Não há limitação de horário e é gratuito para pessoas físicas, mas pode ser pago para pessoas jurídicas, com custos que variam de acordo com a instituição financeira.<br>
        Teve uma grande adesão devido a sua flexibilidade de uso. Uma cobrança pode ser emitida pelo próprio usuário sem necessidade de autorização do banco, podendo substituir outros métodos de pagamento e até mesmo o pagamento em dinheiro.
    </li>
    <li>
        PIB: Produto Interno Bruto dos estados.
    </li>
    <li>
        PIB per Capita: Produto Interno Bruto dos estados per Capita.
    </li>
    <li>
        População: Número de habitantes de cada estado, valores de 2022 fornecidos pelo IBGE.
    </li>
    <li>
        Estabelecimentos: Número de pessoas jurídicas de cada estado.
    </li>
</ul>

#### Análises:
<ul>
    <li>
        Análise Temporal
    </li>
    <li>
        Análise por Região, Estado e Município
    </li>
    <li>
        Correlação Valores x Quantidade
    </li>
    <li>
        Correlação Pix com os outros dados
    </li>
</ul>
