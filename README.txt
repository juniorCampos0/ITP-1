-- 1 -- Das funcionalidades{
	# Solicitadas{
		- 1 - Criação de tabelas;
		- 2 - Listar tabelas;
		- 3 - Criar nova linha;
		- 4 - Listar todos os dados de uma tabela;
		- 5 - Procurar valores{
			- a - Valores maiores ou iguais;
			- b - Valores maiores;
			- c - Valores menores ou iguais;
			- d - Valores menores;
			- e - Valores iguais;
			- f - Valores proximos (para string apenas);
		}
		- 6 - Apagar valor de uma tabela;
		- 7 - Apagar tabela;	
	}
	# extras{
		- 1 - Criar Coluna;	
	}
}

-- 2 -- Todas as funções solicitadas foram implementadas;

-- 3 -- O que poderíamos fazer diferente{
	# Das Funções solicitas{
		- 1 - Criação de tabelas{
			# Inicialmente, o tratamento para a criação da tabela, ao invés array de uma struct, seria recebendo todos os dados como string e depois, tratá-los de modo diferente nas leituras da tabela.
		}

		- 2 - Listar tabelas{
			# Utilização de um comando universal para Windows e Linux, pois utilizamos apenas para Linux na distribuição Ubunto;
		}

		- 3 - Criar nova linha{
			# permitir a inserção de multiplas linhas simultaneamente;
		}
	
		- 4 - Listar todos os dados de uma tabela{
			# Tratar tudo como strings na hora da impressão;		
		}
		- 5 - Procurar valores{
			# Em valores proximos, poder reconhecer letras maiusculas e minusculas como "iguais" na hora da  busca para assim encontrar palavras com diferenças de letras maiusculas e minusculas, como "atuAlmEente" e "atualmente";
		}
		- 6 - Apagar valor de uma tabela{
			# colocar valores "NULL" nos tipos Double e float.
		}
		- 7 - Apagar tabela{
			# Utilização de um comando universal para Windows e Linux, pois utilizamos apenas para Linux na distribuição Ubunto;
		}
	}
	# Das funções extras{
		- 1 - Criar Coluna{
			# Apenas escrever ao final de cada linha ao invés de ler todos os dados da tabela e reescrever toda ela agora com uma nova coluna;
			# permitir a inserção de multiplas colunas simultaneamente;
		}
	}
}

-- 4 -- Da compilação{
	# O programa vem com um pequeno arquivo para facilitar sua compilação, o ExecutarTudo.c,  caso deseje utilizar-se dele digite no terminal{
		gcc ExecutarTudo.c -o ex
		./ex
		./ex
	}
	# caso deseje compilar através das linhas de comando deve ir até a pasta que contém o Arquivo Interface.c e execultar o comando{
		gcc Interface.c Headers/CriaTabela.c Headers/CriaLinha.c Headers/ListaDados.c Headers/ProcuraString.c Headers/ApagaValor.c Headers/ApagaTabela.c Headers/CriaColuna.c -o ex -g -w
	}
		Para compilar todo o programa, não há necessidade de bibliotecas especiais, Headers/ é o caminho dos arquivos onde se encontram as funcionalidades, caso não os coloque os arquivos não serão encontrados e um erro será retornado. 
}
	#Versao do gcc{
		Eu nao sei professora.
}


-- 5 -- Autores:
	FRANCISCO DE ASSIS CAMPOS JÚNIOR/ E-mail: campos.junior.ifrn@gmail.com ;
		# Contribuições: 
			*	Apagar Tabela;
			*	Criar coluna (função extra);
			*	O arquivo para a compilação rápida;
			*	Procurar valor;

	KAIO HENRIQUE DE SOUSA/ E-mail: kaioh95@gmail.com ;
		# Contribuições: 
			*	Apagar valor de uma tabela;
			*	Criar Linha;
			*	Criar Tabela;
			* 	Listar dados;
			*	Listar tabelas;
			*	Interface;

-- 6 -- Das Funções extras{
	# Criar coluna{
		- 1 - Pois a necessidade de se incluir novas colunas em uma tabela acaba sendo constante, adicionar novas colunas para notas em uma tabela que contenha trabalhos ou provas por exemplo ou mesmo adicionar novas colunas para contas e uma tabela de despesas;
	}
}


			
		
	

