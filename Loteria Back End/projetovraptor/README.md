# Loteria

Instalado o tomcat9 e rodando o login e cadastar

- Pagina login 
   http://localhost:8080/projetovraptor/login
- Pagina cadastrar
   http://localhost:8080/projetovraptor/cadastrar

Na pasta controler criado uma nova classe LoginController e CadastrarController


Login
```java
package br.com.caelum.vraptor.controller;

import br.com.caelum.vraptor.Controller;
import br.com.caelum.vraptor.Get;
import br.com.caelum.vraptor.Path;

@Path("cadastrar")
@Controller
public class CadastrarController {
	
	@Get("")
	public void cadastrar() {
		
	}	
}

```

Cadastrar

```java

package br.com.caelum.vraptor.controller;

import br.com.caelum.vraptor.Controller;
import br.com.caelum.vraptor.Get;
import br.com.caelum.vraptor.Path;

@Path("cadastrar")
@Controller
public class CadastrarController {
	
	@Get("")
	public void cadastrar() {
		
	}	
}


```