# Devops challenge júnior

Objetivo é demonstrar inteligência, capacidade e organização para realizar tarefas básicas para o cargo.

### Critérios de avaliação:

✔ Organização <br>
✔ Esforço <br>
✔ Entrega em si dos 2 Challenges <br>
✔ Documentação da entrega <br>


### → Challenge Ops:
> Iniciar e configurar uma instância do WordPress no Amazon Lightsail <br>
https://lightsail.aws.amazon.com/ls/docs/pt_br/articles/amazon-lightsail-tutorial-launching-and-configuring-wordpress <br>
Fazer da etapa 1 até a 5 somente.

### → Challenge Dev:
> Resolva os 3 erros no plugin<br>
[Plugin DevOps Challenge](devops_challenge.php)



### Entrega
1. Efetue o fork deste repositório e crie um branch com o seu nome e sobrenome. (exemplo: fulano-dasilva)
2. Após finalizar o desafio, crie um Pull Request.
3. Aguarde algum contribuidor realizar o review.
4. Dados de acesso do WordPress e Lightsail com tudo configurado e funcionando
5. Prints e url "http://PublicIpAddress/wp-login.php"
6. Documentação (Opcional)
7. Arquitetura (Opcional)
8. Plugin informado arrumado e versionado
9. Suba o plugin para a sua instalação WordPress Lightsail e ative o mesmo.



### Para atualizar a funcionalidade do plugin, foi realizada a seguinte alteração no código:

Inclusão da tag do php na primeira linha, para indicar ao interpretador do php para ler o código
```
<?php 

```
inclusão do ; para indicar a interpretação da linha de código 

```
$lyrics = explode( "\n", $lyrics );

```
inclusão da função nativa do wordpress para escrever textos no header da página inicial

```
add_action( 'admin_notices','devops_challenge' );

```


### Arquitetura 

- Lightsail
![Word](https://github.com/mpletti/devops-challenge-junior/assets/134749110/2a7535fc-56a3-4dae-8dff-f04cfb3d0f59)
- wordpress
![Wordpress_painel](https://github.com/mpletti/devops-challenge-junior/assets/134749110/d347c45c-9485-42a3-b3e4-452125c8866e)






