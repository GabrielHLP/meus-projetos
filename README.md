<!DOCTYPE html>
<html>
	<head>
		<title>Unes - Contato</title>
		<meta charset="utf-8">
	</head>
	<body background="fundo2.png">

		<table border="0" width="900" align="center"> <!--aqui foi definida a tabela-->
			<tr>
				<td height="89"><img src="logo.png"></td> <!--Td significa table data, isso define a célula da tabela-->
				<td align="right">
					<a href="index.html">Home</a> |
					<a href="quem-somos.html">Quem somos</a> |
					<a href="contato.html">Contato</a>
				</td>
			</tr>

			<tr> <!--Tr significa table row e é usada para definir uma linha -->
				<td colspan="2">

					<h1>entre em contato</h1>

					<p> Lorem <strong> ipsum dolor sit</strong> <em> amet</em>, consectetur adipisicing elit, sed do eiusmod.</p>

					<hr> <!--Isso define uma linha para que se separe o textos-->
					<form> <!--O form é responsavel por criar um formulario para o usuario-->
						seu e-mail: <br>
						<input type="text" name="email"><br>

						assunto: <br>
						<input type="text" name="assunto"><br>

						Descrição:<br>
						<textarea></textarea><br>

						<input type="submit" name="enviar">

					</form>

				</td>
			</tr>
			<tr>

				<!--O th significa Table head-->
				<td colspan="2" align="center">
					<h4>todos os direitos reservado</h4>
				</td>
			</tr>

		</table>

	</body>
</html> 
