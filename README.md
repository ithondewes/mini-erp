Mini Sistema ERP
Um sistema ERP simples para gerenciamento de produtos, pedidos, cupons e estoque, desenvolvido com PHP puro, MySQL e Bootstrap (via CDN).

Funcionalidades
Gerenciamento de Produtos: Criação e atualização de produtos com nome, preço, variações e quantidades em estoque.

Carrinho de Compras: Adição de produtos a um carrinho baseado em sessão, com cálculo de frete (R$15 para subtotais entre R$52,00 e R$166,59, frete grátis para valores acima de R$200,00, e R$20 nos demais casos).

Validação de CEP: Validação de códigos postais brasileiros utilizando a API do ViaCEP.

Gerenciamento de Cupons: Criação e aplicação de cupons com regras de validade e valor mínimo.

Notificações por E-mail: Envio de e-mails de confirmação de pedidos com os detalhes do endereço informado.

Webhook: Atualização do status do pedido (ex.: cancelamento de pedidos) via requisição POST.

Instruções de Configuração
Instalação Local
Instale as Dependências:

Instale o XAMPP ou equivalente (PHP 7.4+ e MySQL).

O Bootstrap 4.5.2 e o jQuery 3.5.1 estão incluídos via CDN nos arquivos de visualização (product_view.php, cart_view.php, coupon_view.php). Não é necessário utilizar arquivos locais de estilo ou script. As CDNs utilizadas são:

html
Copy
Edit
<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
