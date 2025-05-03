# Projeto iPhone - Modelagem e Implementação

Este projeto simula a estrutura básica de um iPhone com funcionalidades divididas em três interfaces principais:

- **Reprodutor Musical**
- **Aparelho Telefônico**
- **Navegador na Internet**

## Estrutura

### Interfaces

- `ReprodutorMusical`
  - `void tocar()`
  - `void pausar()`
  - `void selecionarMusica(String musica)`

- `AparelhoTelefonico`
  - `void ligar(String numero)`
  - `void atender()`
  - `void iniciarCorreioVoz()`

- `NavegadorInternet`
  - `void exibirPagina(String url)`
  - `void adicionarNovaAba()`
  - `void atualizarPagina()`

### Classe Principal

- `Iphone`: Implementa todas as interfaces e simula o funcionamento dos métodos.

## Como Executar

1. Coloque todos os arquivos `.java` no mesmo diretório.
2. Compile com:
   ```
   javac *.java
   ```
3. Execute com:
   ```
   java Iphone
   ```

## Exemplo de Uso

A classe `Iphone` pode tocar músicas, fazer ligações e navegar na internet via terminal.

```
Tocando música...
Ligando para: 123456789
Exibindo página: https://www.apple.com
```
