# Resolução da Tela em Java

Este projeto é um programa simples desenvolvido como parte do aprendizado em **Java** no **NetBeans IDE**. O objetivo é exibir a resolução da tela do usuário no console.

## Sobre o projeto

- Linguagem: Java  
- IDE utilizada: NetBeans  
- Tipo de projeto: Console application  
- Autor: Luan Fernandes  

## Funcionalidade

O programa utiliza a classe `Toolkit` para capturar a dimensão da tela do sistema e exibe a largura e altura no console.

```java
import java.awt.Dimension;
import java.awt.Toolkit;

public class ResolucaoTela {
    public static void main(String[] args) {
        Toolkit tk = Toolkit.getDefaultToolkit();
        Dimension d = tk.getScreenSize();
        System.out.println("A resolução da sua tela é: " + d.width + " x " + d.height);
    }
}
```
Exemplo de saída
```
A resolu��o da sua tela �: 1920 x 1080
