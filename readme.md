Questão 03: Com o commit já realizado, você precisa garantir que a alteração
foi registrada corretamente no histórico do projeto. Qual comando você
utilizaria para listar os commits realizados no branch atual, permitindo visualizar
o autor, a data e a mensagem da alteração que você acabou de fazer?

RESPOSTA: apenas utilizaria "git log"


Questão 04: Você terminou o desenvolvimento da IA no branch
feature-ia-inimigo. Agora, você deve voltar ao branch main e realizar o merge
das suas alterações. Caso ocorra um conflito ao tentar realizar esse merge,
quais comandos você utilizaria para identificar o arquivo conflitante e finalizar o
processo de merge após a correção?

RESPOSTA: podemos fazer as seguintes usabilidades "git checkout main", "git merge feature-ia-inimigo", "git status" e em seguida "git add InimigoIA.cs" e "git commit -m "resolver conflito da merge da IA do inimigo"

