# ContaMagica
Trabalho de verificação e validação de software



        Legenda dos casos de teste
            A1=Silver       Saldos Valorizados (R$ <50.000,00 => 0%)                            
            A2=Gold         Upgrade e Saldos Valorizados (R$ 50.000,00  => 1%)          Retrocesso   (R$ <25.000,00 )
            A3=Platinum     Upgrade e Saldos Valorizados (R$ 200.000,00 => 2.5%)        Retrocesso   (R$ <100.000,00 )  

            //*NUNCA PODE OCORRER ALTERAÇÃO DE DUAS CASAS EM UMA ÚNICA OPERAÇÃO//

            Nome do cliente com no minimo de 3 letras 
            B1=Nome com menos de 3 digitos
            B2=Com mais de 3 letras
            
            Numero da conta corrente tem q ser N-S N=>numero da conta com até 6 digitos  S=>Soma dos 6 digitos
            C1=Conta com menos de 6 digitos 
            C2=Conta com mais de 6 digitos 
            C3=conta com 6 digitos e soma correta
            C4=Conta com 6 digitos e soma errada


            Depositos nas contas
            D A1=Deposito*0+Deposito
            D A2=Deposito*0.1+Deposito
            D A3=Deposito*0.025+Deposito
            Caso teste valido ou 
            E1=Caso valido  
            E2=Caso invalido


            Casos de teste cadastro
            
            B1C1=>E2        |"Fe" 1234-10
            B1C2=>E2        |"Fe" 1234567-28                                               
            B1C3=>E2        |"Fe" 1234-10                                        
            B1C4=>E2        |"Fe" 1234-10                                
            B2C1=>E2         |"Fe" 1234-10                            
            B2C2=>E2        |"Fe" 1234-10                        
            B2C3=>E1        |"Fe" 1234-10                            
            B2C4=>E2        |"Fe" 1234-10                                
            




