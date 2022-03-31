# Spring Boot - Eventos App - Michelli Brito

### Aula 01 - Iniciando uma aplicação

- Criado controller
~~~
@Controller
public class IndexController {
	
	@RequestMapping("/")
	public String index() {
		return "index";
	}

}
~~~

- Criado index.html em resources/templates/
```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Index</title>
</head>
<body>
    <h1>Olá mundo com Spring Boot!</h1>
</body>
</html>
```

Rodado projeto no localhost:8080