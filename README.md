# Analise-IA
![Iniciando Projeto][assests/inicio.png]
Para começar o projeto foi necessário criar um novo recuso, portanto iniciamos acessando o portal da Azure e clicando na opção "Criar um recurso";

![Selecinando Serviços](assets\opcoesSelecionadas.png)
Após a abertura da tela, selecionar a categoria de "IA + Machine Learning" e criar o recurso para "Serviço de Linguagem";

![Language Studio](assets\languageStudio.png)
Ao acessar o Langua Studio, para utilizar a fução do nosso projeto, devemos selecionar a opção de "Classify text" e optar pela "Analyze sentiment and mine opninions";

![Primeio Teste](assets\primeiraSentenca.png)
Para a realização do teste, foi elaborado a primeira sentença com fim de analisar um texto onde descrevesse um dia majoritariamente bom. Ficou claro que a Ia soube dividir os processos e situações, dando uma resposta certeira sobre os sentimentos passados nas situações descritas;

![Segundo Teste](assets\segundaSentenca.png)
Para a realização do teste, dessa vez foi elaborado um texto onde o relator estivesse informando uma situação ruim que passou. A Ia novamente soube separar as sentencas no texto e classificar o sentimento nas frases, mas houve dificuldade no processo de Mine Opninions onde explicaria onde estaria o "assessment";

Conclusão do projeto:
Comparando os dois textos notacesse a importância de um Alvo de opinião claro e um sentimento claro, para que possa ser associado corretamente.
Podemos identificar que na frase “Today I spent the whole afternoon at the park with my friends, it was a lot of fun…”
Ela captou que: O alvo da opinião é o “park” e o sentimento associado é “fun”, com 100% positivo.
Já na frase negativa, houve a dificuldade da análise por completa pois a frase mesmo tendo experiências negativas, acaba não associando esses sentimentos a um objeto ou entidade específica.
Se quisermos que o Language Studio capte melhor os "targets" e os assessments, podemos estruturar a frases assim:
“The headache was terrible and made my day awful.”
Fazendo com que  o “headache” vire um alvo claro, e “terrible”/“awful” como avaliações explícitas.

[def]: \assets\inicio.png