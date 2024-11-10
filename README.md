# Janela de Cadastro - Interface Gráfica com Java Swing

Este projeto implementa uma janela de cadastro utilizando Java Swing, com um padrão de projeto **Singleton** para garantir que apenas uma instância da janela esteja aberta ao mesmo tempo. 

## 📋 Funcionalidades

- **Janela Interna (JInternalFrame)**: O projeto usa uma `JInternalFrame` para representar uma janela interna, ideal para sistemas que precisam de múltiplas janelas subordinadas a uma principal.
- **Padrão Singleton**: A implementação garante que apenas uma instância da janela de cadastro seja criada durante a execução do programa.
- **Botão de Fechar**: Um botão de fácil acesso para fechar a janela, liberando a instância para reabertura.
