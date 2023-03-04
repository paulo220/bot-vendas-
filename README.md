# Cyberspace bot

Esta fonte serve de base para os bots das lojas do ciberespaço.
Pretende ser o mais modular possível, permitindo adicionar novas funcionalidades com o menor esforço.

## Exemplo de arquivo de configuração

```python
# Seu token de bot do Telegram.

BOT_TOKEN = "1234567890:ABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"

# ID da API do Telegram e Hash. Este NÃO é o token do seu bot e não deve ser alterado.

API_ID = 611335
API_HASH = "d524b414d21f4d37f08684c1df41ac9c"

# Bate-papo usado para registrar erros.

LOG_CHAT = -1001567213817

#Bate-papo usado para registrar ações do usuário  (like buy, gift, etc).

ADMIN_CHAT = -1001567213817

# Quantas atualizações podem ser tratadas em paralelo.
# Não use valores altos para servidores de baixo custo.

WORKERS = 20

# Os administradores podem acessar o painel e adicionar novos materiais ao bot.

ADMINS = [1089910057]

# Os sudoers têm acesso total ao servidor e podem executar comandos.
SUDOERS = [1089910057]

# Todos os sudoers devem ser administradores também
ADMINS.extend(SUDOERS)

GIFTERS = []
```
