Páginas de autenticação para o projeto Ciclos

Arquivos:
- login.html
- criar-conta.html
- esqueci-senha.html
- redefinir-senha.html

URLs do GitHub Pages:
- https://ellysson1.github.io/ciclos/login.html
- https://ellysson1.github.io/ciclos/criar-conta.html
- https://ellysson1.github.io/ciclos/esqueci-senha.html
- https://ellysson1.github.io/ciclos/redefinir-senha.html

No Supabase, configure:
1. Authentication > Sign In / Providers
   - deixe Email habilitado
   - ative Confirm email

2. Authentication > URL Configuration
   - Site URL: https://ellysson1.github.io/ciclos/
   - Redirect URLs:
     * https://ellysson1.github.io/ciclos/
     * https://ellysson1.github.io/ciclos/login.html
     * https://ellysson1.github.io/ciclos/criar-conta.html
     * https://ellysson1.github.io/ciclos/esqueci-senha.html
     * https://ellysson1.github.io/ciclos/redefinir-senha.html

3. Authentication > SMTP
   - configure SMTP próprio se quiser e-mails confiáveis em produção

Observação:
O app principal pode manter o botão "login" apontando para login.html.
