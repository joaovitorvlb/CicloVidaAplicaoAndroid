Seŕá apresentado uma aplicação no Android Studio que apresenta o entendendo o ciclo de vida de uma aplicação Android.
E os 5 metodos descritos abaixo mostra os ciclos de vida mudando ao manusear a tela do aplicativo que serão 5 mensagens.

onCreate(): É a primeira função a ser executada em uma Activity. Geralmente é a responsável por carregar os layouts XML e outras operações de inicialização. É executada apenas uma vez.

onStart(): É chamada imediatamente após a onCreate() – e também quando uma Activity que estava em background volta a ter foco.

onResume(): Assim como a onStart(), é chamada na inicialização da Activity e também quando uma Activity volta a ter foco. Qual a diferença entre as duas? A onStart() só é chamada quando a Activity não estava mais visível e volta a ter o foco, a onResume() é chamada nas “retomadas de foco”.

onPause(): É a primeira função a ser invocada quando a Activity perde o foco (isso ocorre quando uma nova Activity é iniciada).

onStop(): Só é chamada quando a Activity fica completamente encoberta por outra Activity.

onDestroy(): A última função a ser executada. Depois dela, a Activity é considerada “morta” – ou seja, nao pode mais ser relançada. Se o usuário voltar a requisitar essa Activity, um novo objeto será contruído.

onRestart(): Chamada imediatamente antes da onStart(), quando uma Activity volta a ter o foco depois de estar em background. 
