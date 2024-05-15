Por que precisamos de uma estratégia UX em primeiro lugar?



Quem são nossos usuários? Que necessidades/desejos eles têm?



Quem são nossos concorrentes? Quais são seus pontos fortes/fracos?



Quais são os nossos objetivos de negócios? Quais ações trarão o maior valor comercial?



Quem precisa estar envolvido no design da estratégia UX?



Como saberemos quando tivermos sucesso? Como mediremos o sucesso?


<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulário Estratégia UX</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }
        .form-container {
            background-color: #fff;
            max-width: 600px;
            margin: 20px auto;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        h2 {
            color: #333;
        }
        .form-group {
            margin-bottom: 20px;
        }
        .form-group label {
            display: block;
            margin-bottom: 10px;
            color: #666;
        }
        .form-group input[type="text"],
        .form-group input[type="email"],
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 4px;
            box-sizing: border-box; /* Adiciona padding dentro da caixa */
        }
        .form-group textarea {
            height: 100px;
        }
        .form-group button {
            background-color: #0056b3;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        .form-group button:hover {
            background-color: #004494;
        }
    </style>
</head>
<body>

<div class="form-container">
    <h2>Formulário de Estratégia UX</h2>
    <form>
        <div class="form-group">
            <label for="nome">Nome:</label>
            <input type="text" id="nome" name="nome">
        </div>
        <div class="form-group">
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email">
        </div>
        <div class="form-group">
            <label for="questao1">Por que precisamos de uma estratégia UX em primeiro lugar?</label>
            <textarea id="questao1" name="questao1"></textarea>
        </div>
        <div class="form-group">
            <label for="questao2">Quem são nossos usuários? Que necessidades/desejos eles têm?</label>
            <textarea id="questao2" name="questao2"></textarea>
        </div>
        <div class="form-group">
            <label for="questao3">Quem são nossos concorrentes? Quais são seus pontos fortes/fracos?</label>
            <textarea id="questao3" name="questao3"></textarea>
        </div>
        <div class="form-group">
            <label for="questao4">Quais são os nossos objetivos de negócios? Quais ações trarão o maior valor comercial?</label>
            <textarea id="questao4" name="questao4"></textarea>
        </div>
        <div class="form-group">
            <label for="questao5">Quem precisa estar envolvido no design da estratégia UX?</label>
            <textarea id="questao5" name="questao5"></textarea>
        </div>
        <div class="form-group">
            <label for="questao6">Como saberemos quando tivermos sucesso? Como mediremos o sucesso?</label>
            <textarea id="questao6" name="questao6"></textarea>
        </div>
        <div class="form-group">
            <button type="submit">Enviar</button>
        </div>
    </form>
</div>

</body>
</html>
