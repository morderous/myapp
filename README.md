Apps utilizados: ATOM & Git

$ touch index.html														// cria arquivo na pasta
$ git init																		// torna a pasta um repositor
$ git --global user.name 'Lucas Hubes'				//Nome
$ git --global user.email 'lucas@bla.com'			//e-mail
$ git add index.html													//adiciona um arquivo a stage area
$ git rm --cached index.html									//remove o arquivo da stage area
$ git status 																	//arquivos modificados que estao na stage
$ git add *.html															//adiciona todos os arquivos .html
$ git add .																		//adiciona tudo na pasta
$ git commit 																	//commit nos arquivos sem mensagem
																							//porem abre um menu. 'i' para editar
																							//esc para sair e ':wq' para commitar
$ git commit -m 'mensagem'										//commit com um breve resumo das mod
$ git branch login														//cria uma branch chamada 'login'
$ git checkout login													//muda para a branch 'login'
$ git checkout -b login												//cria E muda para a branch 'login'
