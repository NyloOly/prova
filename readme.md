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



Questão 06: Você realizou uma alteração no arquivo InimigoIA.cs mas
percebeu que cometeu um erro e deseja descartar essas alterações locais
antes de realizar o commit (reverter o arquivo para o estado do último commit).
Qual comando do Git você utilizaria para descartar as modificações locais
especificamente neste arquivo?

RESPOSTA: b git restore InimigoIA.cs



Questão 07: Após finalizar a implementação da IA do inimigo, você precisa
marcar esse ponto no histórico do projeto como uma versão estável chamada
"v1.0". Quais comandos Git você usaria para criar uma tag leve (lightweight) e
uma tag anotada para essa versão?

RESPSOTA: utilizaria "git tag v1.0", "git tag -a v1.0 -m 'Versão estável v1.0'", "git tag", "git push origin v1.0" e caso for enviar todas "tags git push origin --tags"



Questão 08: Você terminou seu código localmente e agora precisa conectá-lo
a um repositório no GitHub. Qual comando você utiliza para adicionar um
servidor remoto chamado 'origin' apontando para a URL do seu repositório no
GitHub?

RESPOSTA: o comando seria algo como "git remote add origin https://github.com/seu-usuario/seu-repositorio.git"


Questão 09: Após conectar seu repositório local ao remoto, você precisa
enviar a branch 'feature-ia-inimigo' para o GitHub. Qual comando você utiliza
para realizar o push dessa branch e, ao mesmo tempo, configurar o
rastreamento ('upstream') para essa branch no repositório remoto?

RESPOSTAS: podemos utilizar "git push -u origin feature-ia-inimigo" ou "git push" para poder puxar tudo
