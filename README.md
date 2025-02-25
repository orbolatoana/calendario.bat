# Desafio de automação 

#### Introdução

O objetivo desta tarefa foi criar um arquivo README.md no GitHub, onde tem explicação do aprendizado ao desenvolver o meu próprio script em batch. O script aborda um processo automatizado utilizando a linguagem batch no ambiente Windows, como organização de arquivos, criação de pastas, ou outro processo que tenha sido relevante para o aprendizado. Além disso, o README contém a explicação detalhada de como o meu script funciona e o que eu aprendi ao implementá-lo.

#### Explicação dos códigos:

- Crie uma pasta (se ele não existir) com o primeiro parâmetro escrito e entra nesse diretório:

![image](https://github.com/user-attachments/assets/d60314c0-421a-4d30-a642-b78bc293fa7c)

- Dentro do primeiro diretório, cria uma pasta (se ele não existir) com o segundo parâmetro escrito e entre nesse diretório:

![image](https://github.com/user-attachments/assets/1f6e7498-3278-4a58-b293-531ec96d7854)

- Crie duas váriaveis, uma chamada "ano" que recebe o primeiro parâmetro, e outra chamada "mes" que recebe o segundo parametro:

![image](https://github.com/user-attachments/assets/82248c3c-2cd4-419a-82a0-afd4ec4da65b)

- Crie três váriaveis: "resto1", "resto2" e "resto3":
  -   Cada uma recebe o resto de uma divisão diferente;
  -   A primeira recebe o resto da divisão "ano / 4";
  -  A segunda recebe o resto da divisão "ano / 100";
  - A terceira recebe o resto da divisão "ano / 400". Como mostrado abaixo:

![image](https://github.com/user-attachments/assets/aae6059c-b0f4-4eb6-95c1-1534b92643f6)

- Seguidamente, é feito um cálculo que decide se bissexto é igual a "0" (não é um ano bissexto) ou "1" (é um ano bissexto):

![image](https://github.com/user-attachments/assets/bc978dc2-5bef-48fe-9877-226757250fc7)

- Em seguida, é onde a váriavel "dias" é definida de acordo com seu mês:

![image](https://github.com/user-attachments/assets/f42de7a5-739d-41f1-a6a7-132eac563e45)

#### Conclusão

Desenvolver o script calendario.bat foi uma boa oportunidade para aprender sobre automação no Windows usando batch. O script mostra um calendário simples no terminal, utilizando comandos como echo, set, e for. Enfrentei desafios na organização das datas e também por ter faltado no dia da aula. Como melhorias, poderia adicionar funcionalidades como visualização de meses futuros e integração com eventos. Esse projeto me ajudou a entender melhor como scripts batch podem ser úteis em tarefas automatizadas no Windows.


