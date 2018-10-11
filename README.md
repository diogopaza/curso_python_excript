<h1>Curso Básico Python</h1>
<p>Foi escrito em C e C++, é uma linguagem interpretada e é uma linguagem que utiliza varáveis de forma dinâmica, 
não é preciso informar o tipo de cada varável, como no JAVA por exemplo que é fortemente tipado.  </p>
<h4>Comandos Python</h4>
<ul>
	<li>dir( nome_comando ) uma espécie de help Exe: dir(print) </li>
	<li>type( variavel ) retorna o tipo da variavel</li>
</ul>
<p>O Python utiliza a indentação como padrão, exemplo:</p>
<p>O ";" ponto e vírgula é utlizado no Python como um delimitador. Exemplo:
<p>print("oi");print("tchau");</p>
<p>Irá imprimir na tela oi e tchau.</p>
</p>
<p>Caso seja executa o comando 1+1 no editor do Python o interpretdor irá somar e mostrar na tela o resultado 2, porém se antes da soma 1+1 tiver um espaço o interpretador do Python irá retornar um erro.</p>
<h2>Concatenando Dados:</h2>
<strong><p>Exemplo:</p></strong>

num_int = 5<br>
num_dec = 7.3<br>
val_str = "texto"

print("o valor é: ", num_int) == utilizando vírgula ","<br>
print("o valor é: %i" %num_int) == utilizando marcador<br>
print("o valor é: " + str( num_int )) == concatenando strings <br>
print("o valor é: %f" %num_dec) == imprimindo na tela valores com casa decimais<br>
print("o valor é: %.1f" %num_dec) == imprimindo na tela valor float com apenas 1 casa decimal<br>

<h2>Entrada de dados</h2>

login = input("Login: ")<br> 
senha = input("Senha")<br>
print("O usuario informado foi %s, e a senha informada foi: %s" %( login, senha))