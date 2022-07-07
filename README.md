<div align="center">
  <img src="https://revobeautytech.com.br/assinaturas/logo-jfy.png">
</div>

---

<div align="center">
  <h1>⚗️ JustForYou Data Science Challenge</h1>
</div>


Primeiramente, obrigado pelo seu interesse em trabalhar na JustForYou! Abaixo você encontrará todas as informações necessárias para iniciar o seu teste.

## 💡 Avisos antes de começar

* Crie um repositório na sua conta do GitHub sem citar nada relacionado a JustForYou;
* Faça seus commits no seu repositório;
* Compartilhe com a justfor-br (username do Github do avaliador rftemer), assim você poderá dar permissão de leitura no código; 
* Fique tranquilo, respire, assim como você, também já passamos por essa etapa. Boa sorte! :)

## ❓ Desafio

### Contextualização
Você trabalha em uma empresa do tipo e-commerce que vende produtos para cabelo personalizados.
A empresa para personalizar o produto, precisa que o cliente preencha um formulario onde
vai contar sobre a rotina e sobre o cabelo. Apos finalizar o preenchimento o cliente pode 
comprar ou nao (é automaticamente direcionando para o checkout).
</br>
A experiência de venda online é baseada em três etapas:
</br>
<ul>
    <li> Preenchimento de um formulário </li>
    <li> Seleção dos produtos </li>
    <li> Fechamento da compra </li>
</ul>

### Problema e desafio
A empresa esta gastando muito dinheiro com os disparos via whatsapp para pessoas que preenchem o formulario (leads), 
desta forma seria interessante qualificar quem sao os leads que possuiem maior probabilidade de efetuar uma compra.
</br>
</br>
Você então é convocado para solucionar tal desafio, e <b>deve achar a correlação entre compradores e leads.</b>
<br>
Para isso, acesse o banco para coletar os dados, e use os recursos ao seu alcance para
solucionar o problema e apresentar as suas conclusões.

### Recursos
Sua empresa contém um banco de dados relacional (Postgres) hospedado remotamente, com as credenciais de acesso listadas [aqui](db_access.txt). O banco contém a seguinte estrutura de tabelas e relações:

<div align="center">
  
</div>


</br>
Seria interessante utilizar jupyter notebook e bibliotecas do python para normalização de dados, algoritmos e plotagem. 
</br>

### Entregas
A entraga deve conter um arquivo .ipynb contendo toda evolução da solução, com alguns pontos em especifico:
<ol>
    <li>Leitura dos dados e normalização </li>
    <li>Separação de bases para treinar e efetuar o crossvalidation </li>
    <li>Definição teorica e pratica sobre as escolhas dos algoritmos (podendo ser mais de um)</li>
    <li>Como foi escolhido as features</li>
    <li>Salvar o arquivo de treinamento para uma API consumir e gerar o score</li>
    <li>Resultado final contendo o quanto de acertividade o algoritmo ira gerar</li>
</ol>
</br>

Devem constar em seu repositório git:
<ul>
    <li>Arquivo .ipynb contendo toda evolução</li>
    <li>Arquivo .sql contendo as <i>queries</i> utilizadas para obtenção dos dados</li>
    <li>Scripts utilizados para análises, caso tenha utilizado algum (exemplo: arquivos .py)</li>
</ul>
