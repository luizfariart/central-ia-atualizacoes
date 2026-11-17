# Central IA — atualizações

Este repositório guarda **só as versões compiladas** da Central IA, o app interno da Faria Group que mantém as ferramentas de IA dos Macs da equipe. O código-fonte é privado.

Cada release traz:
- `CentralIA-<versão>.zip` — o app universal (Apple Silicon + Intel, macOS 13+);
- `atualizacao.json` — versão, SHA-256 e assinatura Ed25519.

O app só instala uma versão se a assinatura conferir com a chave pública embutida nele. Não há nada para baixar à mão: a Central IA se atualiza sozinha.
