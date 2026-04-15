# trabalhocommediaqueries
!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hamburgueria Delícia</title>
<style>
/* Reset básico */
* {
margin: 0;
padding: 0;
box-sizing: border-box;
font-family: Arial, sans-serif;
}

body {
background-color: #f8f1e4;
color: #333;
}

header {
background-color: #ff6347;
color: white;
text-align: center;
padding: 2rem 1rem;
}

header h1 {
font-size: 2.5rem;
margin-bottom: 0.5rem;
}

header p {
font-size: 1.2rem;
}

.cardapio {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
gap: 1.5rem;
padding: 2rem;
max-width: 1200px;
margin: auto;
}

.item {
background-color: #fff;
border-radius: 12px;
box-shadow: 0 5px 15px rgba(0,0,0,0.1);
overflow: hidden;
transition: transform 0.3s, box-shadow 0.3s;
cursor: pointer;
}

.item:hover {
transform: translateY(-10px);
box-shadow: 0 15px 25px rgba(0,0,0,0.2);
}

.item img {
width: 100%;
height: 180px;
object-fit: cover;
}

.item-content {
padding: 1rem;
text-align: center;
}

.item-content h3 {
margin-bottom: 0.5rem;
color: #ff6347;
}

.item-content p {
font-size: 0.9rem;
margin-bottom: 0.8rem;
}

.item-content span {
font-weight: bold;
color: #333;
}

footer {
text-align: center;
padding: 1.5rem;
background-color: #ff6347;
color: white;
margin-top: 2rem;
}

@media (max-width: 600px) {
header h1 {
font-size: 2rem;
}
}
</style>
</head>
<body>
<header>
<h1>Hamburgueria Delícia</h1>
<p>Os melhores hambúrgueres da cidade!</p>
</header>

<section class="cardapio">
<div class="item">
<img src="https://via.placeholder.com/400x180.png?text=Cheeseburger&quot; alt="Cheeseburger">
<div class="item-content">
<h3>Cheeseburger</h3>
<p>Hambúrguer suculento com queijo cheddar, alface e tomate.</p>
<span>R$ 18,90</span>
</div>
</div>

<div class="item">
<img src="https://via.placeholder.com/400x180.png?text=Hambúrguer+Bacon" alt="Hambúrguer Bacon">
<div class="item-content">
<h3>Hambúrguer Bacon</h3>
<p>Delicioso hambúrguer com bacon crocante e queijo especial.</p>
<span>R$ 22,50</span>
</div>
</div>

<div class="item">
<img src="https://via.placeholder.com/400x180.png?text=Veggie+Burger&quot; alt="Veggie Burger">
<div class="item-content">
<h3>Veggie Burger</h3>
<p>Hambúrguer vegetariano com legumes frescos e molho especial.</p>
<span>R$ 20,00</span>
</div>
</div>

<div class="item">
<img src="https://via.placeholder.com/400x180.png?text=Duplo+Cheddar&quot; alt="Duplo Cheddar">
<div class="item-content">
<h3>Duplo Cheddar</h3>
<p>Dois hambúrgueres com cheddar derretido e cebola caramelizada.</p>
<span>R$ 25,90</span>
</div>
</div>
</section>

<footer>
&copy; 2026 Hamburgueria Delícia - Todos os direitos reservados
</footer>
</body>
</html>