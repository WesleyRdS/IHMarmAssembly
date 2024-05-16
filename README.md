# Interface Homem/Maquina para ultilização de sensores em sistemas embarcados.

Program em linguagem de montagem que gerencia a interação entre o sistema embarcado e o usuário, exibindo informações relevantes no LCD e respondendo às entradas dos botões para fornecer funcionalidade e controle adequados.

## Funcionamento do Código

### 1. Configuração Inicial:
- Configura os pinos para o LCD, UART (comunicação serial) e botões.
- Inicializa o display LCD.

### 2. Loop Principal (`_start`):
- Mostra informações sobre sensores no LCD, permitindo que o usuário navegue entre diferentes telas e selecione opções.
- As opções incluem escolher entre diferentes sensores, categorias (como temperatura, umidade) e modos de operação.
- Exibe resultados de medições de temperatura e umidade nos modos normal e contínuo.
- Verifica o status do sistema e exibe no LCD.

### 3. Detecção de Botões:
- Monitora se os botões foram pressionados para realizar ações correspondentes, como navegar entre telas ou selecionar opções.

### 4. Saída:
- Finaliza o programa quando necessário.
