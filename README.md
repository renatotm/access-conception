# Briefing
Uma empresa necessita fazer o controle de entradas e saídas de funcionários, prestadores e visitantes, bem como controlar as permissões de acessos a determinados setores

# Informações Basicas
- Verificar se o visitante já encontra-se cadastrado (CPF).
- Verificar se os dados obrigatórios foram preenchidos no cadastro.
- Verificar se o veículo já encontra-se cadastrado (Placa).
- Verificar se os dados obrigatórios do veículo foram preenchidos.
- Não permitir uma segunda entrada de pessoa ou veículo sem que a primeira tenha saído.
- Não permitir uma saída sem que haja uma entrada.

# Fazendo uma entrada
- Verificar se existe o cadastro da pessoa(CPF).
- Se houver, verificar se há foto no perfil e caso não haja, gravar a foto para reconhecimento facial no cadastro.
- Informar as permissões de acesso (portões).
- Se for entrada com veículo, verificar se há cadastro do veículo, do contrário, efetuar o cadastro e associar ao acesso da pessoa.

# Restrições de cadastro
- Apenas um cadastro por CPF.
- Apenas um cadastro por placa de veículo.
