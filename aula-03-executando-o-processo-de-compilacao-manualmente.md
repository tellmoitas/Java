# Aula 03: Executando o processo de compilação manualmente

Escrevendo o primeiro código, abra um editor de texto qualquer.

Eu gosto muito do Sublime e do VS Code, mas você pode usar até o bloco de notas.

```java
public class OlaMundo{
	public static void main (String[] args){
		System.out.println("Deu certo!");
	}
}
```

Salve o arquivo como OlaMundo.java

Os arquivos em java antes de serem executados, eles precisam ser compilados.

Abra o Terminal, vá até a pasta onde salvou o arquivo e digite:

```text
javac OlaMundo.java
```

Após isto, dentro desta pasta irá surgir o arquivo **OlaMundo.class**

Para executar, digite no Terminal : 

```text
java OlaMundo
```



