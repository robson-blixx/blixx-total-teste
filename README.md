# BLIXX — Painel de teste da operação Total

Painel com acesso da equipe pelo Supabase Auth, planilhas em armazenamento privado e tratativas de tickets compartilhadas. O administrador cria usuários e senhas no menu Equipe e define os níveis Administrador, Analista ou Consulta. As contas existentes também podem entrar pelo e-mail e pela senha atual. As atualizações são consultadas automaticamente a cada 10 segundos enquanto a página está aberta.

A chave publicável presente no HTML é pública por definição. As regras de acesso são aplicadas no banco e no armazenamento. Nenhuma planilha do cliente ou chave administrativa está incluída neste repositório.

Para novos acessos: Equipe > Usuários e níveis de acesso. Informe nome, usuário, senha inicial (mínimo de 10 caracteres) e nível. O funcionário entra diretamente com usuário e senha, sem e-mail de confirmação. Apenas o administrador redefine senhas, bloqueia, desbloqueia ou exclui acessos. A exclusão retira o acesso da lista e impede a entrada, preservando os registros históricos de trabalho.

No Início e em Acareações, anexe a original pelo botão do topo. Cada aba processa automaticamente sua própria planilha e mantém suas regras de cálculo separadas.

Produção: https://spklog.com.br/ na VPS. Atualizar este repositório não publica automaticamente na VPS.

Antes de registrar uma tratativa, o operador assume o ticket, que começa como Pendente. Os estados Em tratativa, Tratado e Resolvido preservam o responsável e o histórico. Apenas o responsável ou um administrador pode alterar a tratativa. Atualizar a exportação não apaga o trabalho da equipe; tickets tratados e registros ausentes da exportação continuam consultáveis no histórico. Cálculos e filtros operacionais permanecem preservados.

GitHub Pages: branch main, pasta raiz. Publicar somente index.html, README.md e .nojekyll.
