# HTTP

> ## Sucesso
1. Request com verbo http válido (post) ok
2. Passar nos headers o content type JSON ok
3. Chamar request com bodky correto ok
4. Ok - 200 e resposta com dados ok
5. No content - 204 e resposta sem dados ok

> ## Erros
1. Bad request - 400 ok
2. Unauthoridez - 401 ok
3. Forbidden - 403 ok
4. Not found - 404 ok
5. Internal server error - 500 ok

> ## Exceção - Status code diferente dos citados acima
1. Internal server error - 500 ok

> ## Exceção - Http request deu alguma Exceção
1. Internal server error - 500 ok

> ## Exceção - Verbo hhtp inválido
1. Internal server error - 500 ok

