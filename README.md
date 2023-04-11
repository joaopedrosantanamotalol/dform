# formulario
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=1, initial-scale=1.0">
    <title>formulario</title>
</head>
<body>
    <div class="caixa">
    <form action="action"></form>
<fieldset>
    <legend> <b>formulario do cliente</b></legend>
    <div class="inputcaixa">
        <input type="text" name="nome" id="nome" class="inputUser" required>
        <label for="nome">nome completo</label>
    </div>
    <div class="inputcaixa">
        <input type="text" name="email" id="email" class="inputUser" required>
        <label for="nome">gmail</label>
    </div>
    <div class="inputcaixa">
        <input type="tel" name="telefone" id="telefone" class="inputUser" required>
        <label for="nome">telefone</label>
    </div>
    <p><b>sexo:</b></p>
    <input type="radio" id="femenino" name="genero" value="femenino" required>
    <label for="femenino">femenino</label>
    <input type="radio" id="masculino" name="genero" value="masculino" required>
    <label for="masculino">masculino</label>
    <input type="radio" id="outro" name="genero" value="outro" required>
    <label for="outro">outro</label>
    <br>
    <label for="dataNascimento"><b>data de nascimento:</b></label>
    <input type="date" id="dataNascimento" name="dataNascimento" class="inputUser" required>
    <div class="inputcaixa">
        <input type="text" name="cidade" id="cidade" class="inputUser" required>
        <label for="cidade">cidade</label>
    </div>
    <div class="inputcaixa">
        <input type="text" name="estado" id="estado" class="inputUser" required>
        <label for="estado">estado</label>
    </div>
    <div class="inputcaixa">
        <input type="text" name="endereco" id="endereco" class="inputUser" required>
        <label for="endereco">endereço</label>
    </div>
    <input type="submit" name="submit">
</fieldset>
<style>
body{
    background-color: lightblue;
}
</style>
</div>
</body>
</html>
