# ada-redes
Projeto redes - GNS3

![image](https://github.com/user-attachments/assets/a8dca077-b7c2-4f6b-bbc8-74bc9d6b8fe5)


### 1. Divisão da Rede Principal (Subnetting):

- **Rede principal fornecida:** `10.100.0.0/20` (4096 endereços)
- **Sub-redes a serem criadas para cada departamento:**
    - **TI:** 100 hosts *(com possibilidade de expansão futura sem mudar IPs já atribuídos)*
    - **Helpdesk:** 120 hosts
    - **Recursos Humanos (RH):** 40 hosts
    - **Inovação:** 50 hosts *(expansão futura para 129 no próximo ano)*
    - **Vendas:** 300 hosts
    - **Gerência:** 50 hosts
 

  ## Divisão e Justificativa:

  - Vendas: 10.100.0.0/22   (1022 endereços possíveis no total)
  - Inovação: 10.100.4.0/23 (510 endereços)
  - Recursos Humanos: 10.100.6.0/25 (126 endereços)
  - Gerência: 10.100.6.128/25 (126 endereços)
  - Helpdesk: 10.100.7.0/24 (254 endereços)
  - TI: 10.100.8.0/22 (1022 endereços)
 
  Justificativa: Foram priorizadas as sub-redes de Vendas e TI. No caso de Vendas, esta é a área que já demanda um maior número hosts (talvez, em um cenário de expansão futura, esta área demande mais IP's que as outras). No caso de TI, já há apontamento de possibilidade de expansão futura com destaque para a requisição de não se mudar IPs já atribuídos).



Abaixo, prints de testes de conectividade:


![IMG-1734](https://github.com/user-attachments/assets/79d32619-1eb0-4afe-850d-b6a649142f80)


![image](https://github.com/user-attachments/assets/250f2186-07a5-46bf-ac8e-9e0ca4c7ca1e)

![image](https://github.com/user-attachments/assets/9dcdb528-1758-42cd-bba5-5500ba609a41)

![image](https://github.com/user-attachments/assets/a8fb1c49-2c1e-48f5-aff4-bb26f3fecc88)



![image](https://github.com/user-attachments/assets/687225e3-8068-4fb4-bf5b-ffdc99fecca8)

![image](https://github.com/user-attachments/assets/ab3fc7e2-14c6-439e-b84c-13230ad45045)


![image](https://github.com/user-attachments/assets/4886e5dd-b732-4d2d-8bd6-ce2659f1534e)












