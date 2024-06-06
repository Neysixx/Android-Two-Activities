Un Activity représente un écran unique dans votre application avec lequel votre utilisateur peut
effectuer une tâche unique et ciblée, telle que prendre une photo, envoyer un e-mail ou afficher une
carte. Une activité est généralement présentée à l'utilisateur sous la forme d'une fenêtre plein écran.
Une application se compose généralement de plusieurs écrans qui sont vaguement liés les uns aux
autres. Chaque écran est une activité. En règle générale, une activité dans une application est
spécifiée comme activité "principale" ( MainActivity.java), qui est présentée à l'utilisateur lorsque
l'application est lancée. L'activité principale peut alors démarrer d'autres activités pour effectuer
différentes actions.
Chaque fois qu'une nouvelle activité démarre, l'activité précédente est arrêtée, mais le système
conserve l'activité dans une pile (la "pile arrière"). Lorsqu'une nouvelle activité démarre, cette nouvelle
activité est poussée sur la pile arrière et prend l'attention de l'utilisateur. La pile arrière suit la logique
de pile de base "dernier entré, premier sorti". Lorsque l'utilisateur a terminé l'activité en cours et
appuie sur le bouton Précédent, cette activité est extraite de la pile et détruite, et l'activité précédente
reprend.
Une activité est démarrée ou activée avec un intent . An Intent est un message asynchrone que vous
pouvez utiliser dans votre activité pour demander une action à une autre activité ou à un autre
composant de l'application. Vous utilisez une intention pour démarrer une activité à partir d'une autre
activité et pour transmettre des données entre les activités.
An Intent peut être explicite ou implicite :


Une intention explicite est une intention dans laquelle vous connaissez la cible de cette intention.
Autrement dit, vous connaissez déjà le nom de classe complet de cette activité spécifique.
Une intention implicite est une intention dans laquelle vous n'avez pas le nom du composant cible,
mais vous avez une action générale à effectuer.
Dans cet exercice pratique, vous créez des intentions explicites. Vous découvrirez comment utiliser
les intentions implicites dans un exercice pratique ultérieur.
