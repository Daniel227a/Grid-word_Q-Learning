# Grid-word_Q-Learning

**Uso:** gridworld.py [opções]

**Opções:**
- `-h, --help`: Mostra esta mensagem de ajuda e sai.
- `-d DISCOUNT, --discount=DISCOUNT`: Desconto no futuro (padrão 0.9).
- `-r R, --livingReward=R`: Recompensa por estar vivo por um passo de tempo (padrão 0.0).
- `-n P, --noise=P`: Com que frequência a ação resulta em uma direção não intencional (padrão 0.2).
- `-e E, --epsilon=E`: Probabilidade de tomar uma ação aleatória no q-learning (padrão 0.3).
- `-l P, --learningRate=P`: Taxa de aprendizado TD (padrão 0.5).
- `-i K, --iterations=K`: Número de rodadas de iteração de valor (padrão 10).
- `-k K, --episodes=K`: Número de episódios do MDP para executar (padrão 1).
- `-g G, --grid=G`: Grade a ser usada (sensível a maiúsculas e minúsculas; opções são BookGrid, BridgeGrid, CliffGrid, MazeGrid, padrão BookGrid).
- `-w X, --windowSize=X`: Solicita uma largura de janela de X pixels * por célula da grade * (padrão 150).
- `-a A, --agent=A`: Tipo de agente (opções são 'random', 'value' e 'q', padrão random).
- `-t, --text`: Usar exibição somente de texto ASCII.
- `-p, --pause`: Pausar a GUI após cada etapa de tempo ao executar o MDP.
- `-q, --quiet`: Pular a exibição de quaisquer episódios de aprendizado.
- `-s S, --speed=S`: Velocidade da animação, S > 1.0 é mais rápida, 0.0 < S < 1.0 é mais lenta (padrão 1.0).
- `-m, --manual`: Controlar manualmente o agente.
- `-v, --valueSteps`: Exibir cada etapa da iteração de valor.
**example:**
- `python,gridworld.py -a q -k 120 -r 0.01
