# cartorioebac
projeto curso de TI ebac
	printf("\t1 - registrar os nomes\n");
		printf("\t2 - consultar nomes\n");
		printf("\t3 - deletar nomes\n");
		printf("\t4 - Sair do sistema\n\n");
		printf("\nopção: ");//Fim do menu

    	scanf("%d" , &opcao);//Armazenando a escolha do usuário
@@ -149,10 +150,16 @@
			deletar();
			break;

			case 4:
			printf("Obrigado por ultilizar o sistema!!\n");
			return 0;
			break;
			
			default:
			printf("Essa opção não existe!\n");
			system("pause");
			break;
			
		}//Fim da seleção
