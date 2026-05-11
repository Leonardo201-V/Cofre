# Cofre

## Descrição
  Um cofre virtual, com intuito de contabilizar o valor existente em diversas fontes e tipos diferentes de moedas, podendo fazer a conversão para que visualize o valor correto e total.

  Ainda bem manual por ter de ser adicionado os valores manualmente, mas capaz de ser expandido para ter automações maiores.

## Tecnologia
- Java

## Estrutura do projeto
```
cofrinho/
├── src/
│   ├── Principal.java   # Classe principal (executa o programa)
│   ├── Moeda.java       # Classe abstrata/base para moedas
│   ├── Real.java        # Implementação da moeda Real
│   ├── Dolar.java       # Implementação da moeda Dólar
│   ├── Euro.java        # Implementação da moeda Euro
│   └── Cofrinho.java    # Gerencia as moedas (adicionar, remover, converter)
├── README.md
└── .gitignore
```

## Como executar
1. Certifique-se de ter o Java JDK instalado
2. Clone o repositório:
   ```bash
   git clone [https://github.com/seu-usuario/cofrinho.git]```
3. Entre na pasta cofrinho
4. Compile os arquivos
5. Execute o programa "Java src/Principal"

## Autor 
Leonardo Rodrigues

## Status
Concluido
