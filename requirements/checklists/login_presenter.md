# Login Presenter

> ## Regras
1. Chamar Validation ao alterar o email ok
2. Notificar o emailErrorStream com o mesmo erro do Validation, caso retorne erro ok
3. Notificar o emailErrorStream com null, caso o Validation retorne erro ok
4. Não notificar o emailErrorStream se o valor for igual ao último ok
5. Notificar o isFormValidStream após alterar o email ok
6. Chamar Validation ao alterar a senha ok
7. Notificar o passwordErrorStream com o mesmo erro do Validation, caso retorne erro ok
8. Notificar o passwordErrorStream com null, caso o Validation não retorne erro ok
9. Não notificar o passwordErrorStream se o valor for igual ao último ok
10. Notificar o isFormValidStream após alterar a senha ok
11. Para o formulário estar válido, todos  os Streams de erro precisam estar null e todos os campos obrigaótios não podem estar vazios ok
12. Não notificar os isFormValidStream se o valor for igual ao último ok
13. Chamar o Authentication com email e senha corretos ok
14. Notificar o isLoadingStream como true antes de chamar o Authentication ok
15. Notificar o isLoadingStream como false no fim do Authentication ok
16. Notificar o mainErrorStream caso o Authentication retorne um DomainError ok
17. Fechar todos os Streams no dispose ok
18. Gravar o Account no cache em caso de Sucesso
19. Levar o usuário pra tela de Enquetes em caso de Sucesso

