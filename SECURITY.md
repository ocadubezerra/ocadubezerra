# Segurança

## Relato responsável

Não publique senhas, tokens, dados de clientes, detalhes de exploração ou provas com informações pessoais em issues, comentários ou pull requests.

Quando o repositório oferecer o botão **Report a vulnerability**, use o formulário privado na aba **Security**. Se o recurso não estiver disponível, procure https://x.com/ocadubezerra apenas para solicitar um canal privado antes de enviar detalhes.

No relato privado, informe a versão ou commit afetado, passos mínimos de reprodução, impacto e uma prova sanitizada. Use contas de teste sob seu controle. Não acesse dados de terceiros, não altere saldos ou transações e não realize testes de carga sem autorização.

## Credenciais e dados

- Configure segredos fora do Git, por variáveis de ambiente ou cofre de segredos.
- Não versione arquivos .env reais, chaves privadas, bancos, dumps ou backups com dados de produção.
- Compartilhe apenas credenciais estritamente necessárias e revogue acessos que deixaram de ser necessários.
- Se uma credencial for exposta, revogue ou rotacione na origem. Apagar o arquivo ou tornar o repositório privado não invalida cópias existentes.
- Verifique as licenças e a procedência das dependências antes de redistribuí-las.

Não há promessa de prazo de resposta, recompensa ou autorização para testes em produção neste documento.
