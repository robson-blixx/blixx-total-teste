# BLIXX — Painel de teste da operação Total

Painel com acesso da equipe pelo Supabase Auth, planilhas em armazenamento privado e tratativas de tickets compartilhadas. O administrador libera os e-mails autorizados no menu Equipe. As atualizações são consultadas automaticamente a cada 10 segundos enquanto a página está aberta.

A chave publicável presente no HTML é pública por definição. As regras de acesso são aplicadas no banco e no armazenamento. Nenhuma planilha do cliente ou chave administrativa está incluída neste repositório.

Para novos usuários, liberar o e-mail na Equipe e criar a conta em Authentication > Users no projeto Supabase. A entrega de e-mails de confirmação e recuperação depende da configuração de envio do projeto.

GitHub Pages: branch main, pasta raiz. Publicar somente index.html, README.md e .nojekyll.
