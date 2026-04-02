# una-ihcux-lista04
Atividade UNA (Lista 04) - Interação Humano Computador UX

# 🚀 PROGRAMA SISTEMA ROBUSTO

## 🛠️ Comandos de Construção Utilizados
- `dotnet new console`: Para criar a estrutura base do C#.
- `dotnet build`: Para transformar meu código em algo que o PC entende.
- `dotnet run`: Para ver a mágica acontecer.

## 📦 Estrutura Gerada
Arquivos que o .NET criou para mim:
1. `Program.cs`: Onde fica o código.
2. `SistemaRobusto.csproj`: As configurações do meu projeto.

## 🛡️ Uso do Try-Catch

## Try-Catch e a 5ª Heurística de Nielsen: Prevenção de Erros
Este projeto demonstra como o tratamento de exceções em C# (try-catch) não é apenas uma ferramenta de segurança de código, mas um pilar fundamental da Experiência do Usuário (UX). 

## O que é o Try-Catch?
- No C#, o bloco try-catch é utilizado para lidar com exceções (erros que ocorrem durante a execução do programa). 
- try: Define um bloco de código onde "tentamos" executar algo que pode dar errado (ex: converter texto em número).
- catch: É o "plano de contingência". Se algo falhar no try, o programa pula para cá em vez de travar ("crashar").
- finally: Um bloco que sempre será executado, independentemente de ter ocorrido erro ou não, ideal para limpar recursos ou encerrar processos. 

## Conexão com IHC: Prevenção de Erros
A 5ª Heurística de Nielsen afirma que um bom design deve, primeiro, tentar evitar que o erro ocorra. Mas, se ele ocorrer, o sistema deve oferecer mensagens de erro compreensíveis e uma saída amigável. 

## Como este código aplica isso:
- Evita a Frustração: Sem o try-catch, se o usuário digitasse "vinte" em vez de "20", o programa fecharia abruptamente com uma mensagem técnica incompreensível (Exception).
- Feedback Amigável: No bloco catch, substituímos o erro técnico (System.FormatException) por uma linguagem que o ser humano entende: "Você digitou letras em um campo que só aceita números!".
- Sugestão de Recuperação: Não basta dizer que errou; o código oferece uma DICA de como fazer o certo na próxima vez ("Ex: 25").
- Estado Final Consistente: O uso do finally garante que o sistema dê um fechamento digno à operação, limpando as cores do console e informando que a tentativa foi encerrada. 

## 📸 Evidência de Execução

## - Execução bem sucedida
<img width="711" height="343" alt="evidencia-sucesso" src="https://github.com/user-attachments/assets/f75d52e0-4113-445e-b826-2ffac85b74f1" />

## - Execução mal sucedida
<img width="711" height="343" alt="evidencia-erro" src="https://github.com/user-attachments/assets/d71554c0-0524-46e7-89b5-bb070ee252db" />
