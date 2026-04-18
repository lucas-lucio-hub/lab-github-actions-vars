1) Por que a Secret aparece no log como ** e a variável aparece normalmente? 

Porque o GitHub automaticamente mascara secrets nos logs por segurança

2) O Job deploy_app consegue ler a variável BUILD_VERSION criada no Job build_app? Por quê?

Não, porque cada job roda em um ambiente separado e variáveis de job não são compartilhadas automáticamente.
