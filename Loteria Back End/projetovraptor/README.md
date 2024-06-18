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
# Tela de Cadastro
![image](https://github.com/DevanaSena/Trevo/assets/45314696/1b42f55a-51a2-42af-86d2-d8b6942ba5d1)

# Tela de Login
![image](https://github.com/DevanaSena/Trevo/assets/45314696/c2ee5a8c-c674-4e08-8bb6-a25d618ced19)

# Dashboard
![image](https://github.com/DevanaSena/Trevo/assets/45314696/c4a5be89-22ee-412e-9712-57df8df90135)

# Apostas
![image](https://github.com/DevanaSena/Trevo/assets/45314696/7c3e8163-1064-463d-af7a-cee1e2bf05c7)

# Nova Aposta
![image](https://github.com/DevanaSena/Trevo/assets/45314696/64ca7f0e-e936-45cc-943c-819e434c0a0b)






