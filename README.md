# Tp1_socle_fastapi_karim_traore

Partie 1:

1) A quoi servent ces dépendances (fastAPI, uvicorn, pydantic) ?
-  fastAPI sert à créer des APIs web rapidement et proprement en Python, avec de bonnes performances.
-  uvicorn est le serveur ASGI qui exécute l’application FastAPI et gère les requêtes HTTP.
-  pydantic permet de valider, convertir et documenter automatiquement les données échangées par l’API (entrées/sorties).

Partie 4:

Cas 1 : **GET /users/1**
1) La requête est-elle exécutée ? Quelle est la valeur retournée ?
-  Oui, elle est exécutée avec la valeur : **id: 1**

Cas 2 : **GET /users/toto**
2) La requête est-elle exécutée ? Quel est le code HTTP retournée ? Le paramètre concerné. Le type attendu.
-  Non, elle n'est pas exécutée, le code http retournée est 422 "Unprocessable Entity", le paramètre concerné est l'user_id avec pour type attendu "int_parsing", un entier.
