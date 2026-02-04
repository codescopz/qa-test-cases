# Cenários de Teste – Login (Conecte-se)

## CT-01 – Login com credenciais válidas
Dado que o usuário esteja na tela de login  
Quando informar e-mail e senha válidos  
Então o sistema deve permitir o acesso

## CT-02 – Login com senha inválida
Dado que o usuário esteja na tela de login  
Quando informar senha incorreta  
Então o sistema deve exibir mensagem de erro

## CT-03 – Campos obrigatórios não preenchidos
Dado que o usuário esteja na tela de login  
Quando tentar acessar sem preencher os campos  
Então o sistema deve alertar sobre campos obrigatórios
