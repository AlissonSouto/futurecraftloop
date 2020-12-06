<html>
<head>
	<meta charset="UTF-8"/>
	<title>Formulário</title>
	<link rel="stylesheet" type="text/css" href="_css/estilo-formulario.css"/>
	<link rel="shortcut icon" href="imagens/compras.png">
</head>
<body background = "imagens/background.jpg">
	<script type="text/javascript" src="_javascript/funcoes.js">
	</script>
	<form method="post" id="fContato" name="tContato">
		<fieldset id="ident"><legend>Identificação do Usuário</legend>
		<p><label for="cNome">Nome:</label> <input type="text" name="tNome" id="cNome" size="30" maxlength="40" placeholder="Nome Completo"/></p>
		<p><label for="cMail">E-mail:</label> <input type="email" name="tMail" id="cMail" size="30" maxlength="50" placeholder="E-mail"/></p>
		<p>Sexo:
			<input type="radio" name="tSexo" id="cMasc" checked><label for="cMasc">Masculino</label><br/>
			<input type="radio" name="tSexo" id="cFem"><label for="cFem">Feminino</label>
			</p>
		<p>Data de Nascimento: <input type="date" name="tNasc" id="cNasc"/></p>
		</fieldset>
		
		<fieldset id="endereco"><legend>Endereço do Usuário</legend>
			<p><label for="cRua">Logradouro:</label> <input type="text" name="tRua" id="cRua" size="30" maxlength="80" placeholder="Rua, Av, Trav"/></p>
			<p><label for="cNum">Número: </label><input type="number" name="tNum" id="cNum" min="0" max="99999"/></p>
			<p><label for="cEst">Estado:</label>
			<select name="tEst" id="cEst">
				<option value="AL">Alagoas</option>
				<option value="RJ">Rio de Janeiro</option>
				<option value="SP">São Paulo</option>
			</select></p>
			<p><label for="cCid">Cidade:</label>
			<input type="text" name="tCid" id="cCid" size="30" maxlength="40" placeholder="Sua Cidade" list="cidades"/></p>
			<datalist id="cidades">
				<option value="Maceió"></option>
				<option value="Campo Alegre"></option>
				<option value="Atalaia"></option>
				<option value="Rio de Janeiro"></option>
				<option value="São Gonçalo"></option>
				<option value="Duque de Caxias"></option>
				<option value="São Paulo"></option>
				<option value="Guarulhos"></option>
				<option value="Campinas"></option>
			</datalist>
		</fieldset>
			
		<fieldset id="pedido"><legend>Tênis <a href="modelos.html" target="_blank">(Clique aqui para ver as imagens)</a></legend>
			<p>Modelo:
				<input type="radio" name="tMod" id="cStrung" checked><label for="cStrung">4D Strung</label><br/>
				<input type="radio" name="tMod" id="cX9000" ><label for="cX9000">X9000</label><br/>
				<input type="radio" name="tMod" id="cUltra4D" ><label for="cUltra4D">Ultra4D</label><br/>
				<input type="radio" name="tMod" id="cY3" ><label for="cY3">Y3</label><br/>
				<input type="radio" name="tMod" id="c4DRun" ><label for="c4DRun">4D Run</label><br/>
				<input type="radio" name="tMod" id="cConsortium" ><label for="cConsortium">Consortium4D</label><br/>
				<input type="radio" name="tMod" id="cAlphaEdge" ><label for="cAlphaEdge">AlphaEdge4D</label><br/>
			</p>
			<p>Tamanhos:
				<input type="radio" name="tTam" id="cTam36" checked><label for="cTam36">36</label><br/>
				<input type="radio" name="tTam" id="cTam37" ><label for="cTam37">37</label><br/>
				<input type="radio" name="tTam" id="cTam38" ><label for="cTam38">38</label><br/>
				<input type="radio" name="tTam" id="cTam39" ><label for="cTam39">39</label><br/>
				<input type="radio" name="tTam" id="cTam40" ><label for="cTam40">40</label><br/>	
			</p>
		</fieldset>
		<input type="submit" value="Enviar" onclick="validar()">
	</form>
	
</body>
</html>
