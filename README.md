repo pubblico usato solo per contenere i file letti dal config server di spring cloud contenuto nei repo di coding skills


application.properties viene caricato nell'env di tutti i client del config server
nomemicroservizio.properties viene caricato solo dal client che ha quel nome nell'application name, indipendentemente dal profilo (e va in aggiunta al suo specifico application.properties)
nomemicroservizio-profilo.properties viene caricato solo dal client che ha quel nome nell'application name, se sta usando il profilo SPRING CLOUD (concetto distaccato tecnicamente dal profilo spring) -profilo