# MINI PROJETO 2

A ideia desse desafio é estimular o estudo de novas tecnologias e acabar ou pelo menos diminuir o preconceito que muitos têm com a linguagem **PHP**.

----------

Linguagem PHP
--------

**PHP** ([http://php.net/][1]) é uma das linguagens de programação mais populares do mundo. É uma linguagem multiparadigma, leve, poderosa, gratuita e muito fácil de aprender. PHP foi criada pelo dinamarquês Rasmus Lerdorf, como um amontado de programas CGI. A linguagem foi evoluindo ao longo dos anos e incorporando recursos já presentes em diversas outras linguagens.

PHP é utilizado em diversos projetos como:

- **Facebook** (Uma das maiores redes sociais do mundo);
- **Wikipédia** (A enciclopédia livre);
- **Wordpress** (O mais popular CMS do mercado);
- **Yahoo** (Um dos maiores buscadores do mundo);
- **Governo federal do Brasil** (Diversos sites do governo usam o PHP por meio do Zend Framework, Drupal, Wordpress e Joomla)

Confira também o [Manual da linguagem][2]

----------

Desafio
--------

Crie um aplicativo web, que gere aleatoriamente apostas para os principais jogos de loteria do Brasil (Mega-Sena, Quina, Lotomania e Lotofácil). 

O aplicativo deverá:

- Solicitar do usuário para qual jogo (Mega-Sena, Quina, Lotomania e Lotofácil) ele quer gerar as apostas;
- Solicitar do usuário quantas dezenas ele quer apostar (Respeitando o mínimo e o máximo de cada jogo):
- Solicitar do usuário quantas apostas ele quer gerar
- Não gerar apostas duplicadas
- Exibir as dezenas de cada apostas em ordem crescente
- Armazenar em um arquivo de texto em formato **JSON** 
	- Todas as apostas geradas naquela e na demais rodadas (Mantendo assim um histórico)
	- Para qual jogo foram as dezenas geradas
	- A data/hora que aquela rodada foi gerada
	- O valor total da aposta
- Permitir que uma ou mais apostas sejam excluídas do arquivo de texto
- Após a gravação da rodada de apostas, listar as dezenas geradas e informar o valor total naquela rodada
- Permitir que o usuário consulte o histórico de apostas geradas

Confira o número mínimo e máximo de dezenas, bem como os respectivos valores das apostas em:
http://loterias.caixa.gov.br/wps/portal/loterias/landing/megasena
http://loterias.caixa.gov.br/wps/portal/loterias/landing/quina
http://loterias.caixa.gov.br/wps/portal/loterias/landing/lotomania
http://loterias.caixa.gov.br/wps/portal/loterias/landing/lotofacil 

> **Observações:**

> - Lembre-se de validar os dados para evitar que o usuário informe mais dezenas do que o jogo suporta.
> - Não existe prazo limite para conclusão, a ideia é que você tenha uma experiência diferente.
> - Você poderá tirar suas dúvidas no [Slack do Desafio][3]
> - Ao finalizar o seu projeto, publique-o no Github e envie o link para bugginhodeveloper@gmail.com

----------

Quem já enviou?
--------

Confira abaixo uma lista com todos os amiguinhos que já concluíram o desafio:

- Hugo Peres (https://github.com/hugueds/loteca-bugginho/)
- Vinícius Carvalho (https://bitbucket.org/marcuscarvalho6/gerador-de-apostas)

  [1]: http://php.net/
  [2]: http://php.net/manual/pt_BR/
  [3]: https://bugginhominiprojetos.slack.com/
