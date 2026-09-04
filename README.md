# Meu Treino — PWA v3

## Correção do salvamento
Nesta versão:
- a carga é salva ao digitar;
- é salva novamente ao sair do campo;
- existe botão explícito `Salvar carga`;
- aparece confirmação `Salvo no aparelho`;
- aceita vírgula ou ponto em cargas decimais;
- o histórico é registrado ao concluir uma série;
- cache atualizado para v3.

## Atualizar no GitHub
No repositório, substitua:
- index.html
- service-worker.js
- manifest.webmanifest

Faça Commit changes.

## IMPORTANTE no iPhone
Para garantir que não está abrindo a versão antiga:
1. Abra a URL do GitHub Pages no Safari.
2. Confira se aparece a faixa `Versão 3 — salvamento reforçado`.
3. Se não aparecer, recarregue a página.
4. Remova o ícone antigo `Meu Treino` da Tela de Início.
5. No Safari, abra novamente a URL e use Compartilhar > Adicionar à Tela de Início.
6. Digite uma carga e toque em `Salvar carga`.
7. Confirme que aparece `Salvo no aparelho: XX kg`.
8. Feche o app completamente e abra novamente.

Não use navegação privada do Safari para o app.
