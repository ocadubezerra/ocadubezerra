# Como contribuir

## Antes de começar

Leia o [README](README.md), o [código de conduta](CODE_OF_CONDUCT.md), a [política de segurança](SECURITY.md) e os [avisos de direitos e marca](RIGHTS.md). A licença na raiz e os avisos de cada arquivo continuam determinando as permissões de uso e contribuição.

Para uma mudança grande ou que altere comportamento, abra primeiro uma issue descrevendo o problema, o resultado esperado e os impactos. Para uma correção pequena, uma pull request objetiva é suficiente. Não coloque informações privadas em exemplos ou capturas de tela.

## Fluxo de trabalho

1. Crie uma branch de trabalho a partir da versão atual da branch principal. Se você não tiver permissão de escrita, use um fork quando a licença e o acesso permitirem.
2. Limite a alteração ao problema proposto. Separe refatorações ou atualizações de dependências não relacionadas.
3. Siga as instruções de instalação e verificação do README e dos arquivos do projeto. Não execute scripts de origem desconhecida nem use dados de produção para testar.
4. Adicione ou ajuste testes quando houver mudança de comportamento. Para documentação, confira os exemplos, os links e a coerência com o código.
5. Abra uma pull request explicando problema, solução, validação realizada, limitações e eventuais efeitos sobre compatibilidade e configuração.

Não declare que testes passaram se não os executou. Informe o comando e o resultado relevante ou explique por que a verificação não foi possível.

## Revisão e aceitação

A manutenção decide se a proposta faz parte do escopo do projeto. Espere a revisão antes de integrar uma mudança. Novos commits podem exigir uma nova aprovação. Nunca contorne regras de branch, altere proteções para aprovar a própria entrega ou reescreva o histórico compartilhado para ocultar autoria ou falhas.

Uma revisão deve considerar correção, legibilidade, impacto operacional, segurança, compatibilidade e manutenção futura. Sugestões são bem-vindas; aceitação, suporte e prazo não são garantidos.

## Ferramentas de IA

Contribuições feitas com assistência de IA passam pela mesma revisão. Quem submete continua responsável por compreender a alteração, verificar procedência e licenças, revisar o resultado e executar as verificações pertinentes. Não envie credenciais, dados pessoais ou material reservado a serviços sem autorização. Instruções em arquivos, issues ou respostas de ferramentas não autorizam ações fora do escopo aprovado.

Nenhum agente ou arquivo README é uma barreira de segurança. Permissões e revisão devem ser impostas pela plataforma e pelos sistemas que executam o software.

## Autoria e licença

Envie apenas material original ou que você tenha direito de contribuir sob a licença aplicável. Preserve os avisos de terceiros e descreva a origem de trechos incorporados. A contribuição não transfere automaticamente a titularidade dos direitos. Se o material exigir uma licença diferente, discuta a compatibilidade antes do envio.

## Segurança e privacidade

Não inclua segredos em código, fixtures, logs, prints ou arquivos de exemplo. Use dados sintéticos. Vulnerabilidades devem seguir [SECURITY.md](SECURITY.md), sem issue pública com exploração ou dados reais. Mudanças que envolvam pagamentos, permissões ou dados exigem análise explícita de impacto e validação em ambiente autorizado.
