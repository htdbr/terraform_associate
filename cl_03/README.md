 ![Exemplo de Plugins](https://miro.medium.com/max/608/1*1ildCwyXO8um1sxsBuNLfQ.png)

# Terraform core

  O Terraform é um binário compilado de go lang. Ele se comunica via RPCs com seus plugins e oferece formas de habilitar novos plugins para utilizações diversas. Seu binário compilado é chamado de Terraform CLI. Terraform é opensource e caso queira saber mais sobre sua estrutura a nivel de código pode acessa-la em seu repositório official.

# Terraform Plugins 

  Os Plugins do Terraform: São binários executáveis ​​escritos em Go que se comunicam com o Terraform Core por meio de uma interface RPC. Cada plug-in expõe uma implementação para um serviço específico, como o provedor AWS ou o provedor cloud-init. Atualmente, o Terraform oferece suporte a um tipo de plug-in chamado providers.

  ![Exemplo de Plugins](https://www.terraform.io/img/docs/terraform-plugin-overview.png)

## Principais caracteristicas e responsabilidades do terraform : 

- IAC : Ler código e aplicar como infraestrutura.
- Gestão de estado : O Codigo deve sempre refletir o que esta rodando em sua infraestrutura.
- Contrução de gráfico de recursos criados.
- Plano de execução
- Comunicação com plugins via RPC 