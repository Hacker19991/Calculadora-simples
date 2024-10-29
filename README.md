# **AppCalculadora (Calculadora Simples)**

> Um aplicativo simples de 4 botãos de (Somar, Subtrair, Multiplicar e Dividir).

## Descrição
O **AppCalculadora** permite que o usuario possa fazer uma conta basica para obter um resultado direto a somatoria, subtração, multiplicação e divisão basicas.

## Funcionalidades
- [x] Entrada de dados de consumo
- [x] Cálculo e exibição de estatísticas de consumo
- [x] Gráficos interativos para visualização dos dados
- [x] Interface intuitiva e amigável
- [ ] Suporte para diferentes tipos de recursos (planejado para futuras versões)

## Tecnologias Utilizadas
- [x] **Android Studio** (versão recomendada: Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **EditText** para entrada e exibição de dados

## Como Rodar o Projeto
Siga os passos abaixo para rodar o projeto localmente:

1. Clone este repositório:
   ```bash
   [https://github.com/Hacker19991/Calculadora-de-consumo-de-combust-vel-Android-Studio](https://github.com/Hacker19991/Calculadora-simples)
   
2. Abra o projeto no Android Studio.
   
3. Compile e execute o projeto em um emulador ou dispositivo físico.

## Estrutura do Projeto

```
── app
   ├── src
   │   ├── main
   │   │   ├── java/com/example/appconsumo
   │   │   │   ├── MainActivity.java # Atividade principal para monitoramento de consumo
   │   │   ├── res
   │   │   │   ├── layout
   │   │   │   │   ├── activity_main.xml # Layout da tela principal
   │   │   │   └── values
   │   │   │       ├── strings.xml # Strings usadas no app
   │   │   │       ├── colors.xml # Cores definidas no projeto
   └── build.gradle # Configuração do Gradle
```

## Design e Prototipage
A interface do app foi criada usando ConstraintLayout no modelo Design para ser mais simples e facil de se usar e para ser mais compacto ao android e mais simples e pratico assim podendo se acostumar com o tempo.

## Telas do Aplicativo 

> Tela Principal

![image](https://github.com/user-attachments/assets/35f3f158-8578-4b45-aaea-1b086506f068)

Uma tela simples, as imagens são opicionais "Elas são colocadas por imagemView e selecione a pasta com as imagens pré-selecionadas", 2 EditText para, o primeiro que sofrera a alteração número e o segundo que vai alterar número, 4 buttons para, somar, subtrair, multiplicar, dividir os números inseridos em cada EditText, e no meio (Ou no final, a escolha é sua onde vai ser a amostra de resultado) o TextView para mostrar o resultado final do calculo com as informações insiridas de maneira certa de acordo com o que o usuário queira.

## Desenvolvedores
**Gabriel Henrique** - Desenvolvedor - [GitHub](https://github.com/Hacker19991).

## Licença
Este projeto está licenciado sob os termos da licença MIT. Para mais detalhes, veja o arquivo
[LICENSE](LICENSE).
