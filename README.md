
<!DOCTYPE html>
<html>
 
<head>
    <title>Verificar Número é Par ou Ímpar </title>
</head>
<body>
    <script type="text/javascript">
        function verificarParImpar() {
            var numero = parseInt(prompt("Insira um número inteiro:"));
            if (isNaN(numero)) {
                alert("Por favor, insira um número válido.");
                return;
            }
            if (numero % 2 === 0) {
                alert("O número " + numero + " é par.");
            } else {
                alert("O número " + numero + " é ímpar.");
            }
            verificarParImpar();
        }
    </script>
    <button onclick="verificarParImpar()"> Verificar Par ou Ímpar </button>
</body>
 
</html>
