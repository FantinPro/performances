## Lucy mobility

### Préambule

- Site vitrine de trotinettes éléctriques B2B.
- Donnez des informations sur le business de l'entreprise.
- Des futurs propspects (maximum quelques secondes sur le site puis partir).

### Architecture app

- techno: react (gatsby), host AWS sur S3 cloudfront.``

### Exigence

- Est ce que le site supporte une montée en charge progressive d'utilisateur (au moins 100 ?)
- Les métrics qui seront analysé vont être le temps de réponse.

### Environement de test

- Mon PC (local) Apple M1, 16GO


### Planification des tests

- Stress test: 50 utilisateurs minimum puis augmentation progressive de 10 utilisateurs par secondes.
- La réussite du stress test se fera sur le temps de réponse de l'application.

### Etapes du test

- Aller sur la page
- Scroll sur la page
- Quitter la page

