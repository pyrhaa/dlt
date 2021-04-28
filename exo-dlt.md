# Exercices Distributed Ledger Technology

- Un arbre de merkle nécessite une paire de hashes pour produire un nouveau hash parent. Il faut donc a absolument que le nombre de transactions qui produiront le `Merkle root` soit pair.  
  Comment est géré le cas ou le nombre de transactions dans le Block à valider est impair pour générer un `Merlke root` ?

> Si le bloc a un nombre impair de transactions, le hachage de la dernière est dupliqué et ajouté à lui-même.

---

- Dans le réseau bitcoin, Comment un nouveau noeud arrive t'il à retrouver ses pairs et ainsi rejoindre le réseau ?
  Expliquer le processus avec vos propres mots.

> Les nouveaux noeuds doivent trouver un noeud déjà existant avant d'être connectés au réseau.

---

- Pouvez vous nommer au moins une personne qui a ou aurait pu influencer directement ou indirectement la création de Bitcoin par ses travaux (une personne qui n'a pas été nommée dans le cours)?

> Gilles Brassard (né le 20 avril 1955 à Montréal (Québec, Canada)) est un cryptologue canadien.
> Il a notamment aidé à jeter les bases de la cryptographie quantique.

---

- Avec vos propres recherches et grâce aux compétences acquises en cours pouvez vous expliquer comment une Blockchain crée un lien entre ses différents Blocks?

> Lorsqu’un utilisateur effectue une transaction à travers le réseau blockchain, cette dernière est regroupée avec d'autres transactions au sein d'un bloc. Ensuite, intervient la vérification et la validation par les autres membres du réseau.

---

- Quelle structure de données informatique peut représenter le mieux cette chaine de Block: https://en.wikipedia.org/wiki/List_of_data_structures ?

---

- Si je souhaite modifier une transaction de 10 bitcoin que j'ai effectué il y a 6 mois en une transaction de 1 Bitcoin, que dois je modifier dans la Blockchain et que dois je mettre en oeuvre pour que cette modification persiste ?  
  Est ce possible selon vous ?

> Cela est peu probable, le registre du bitcoin est public et ne peut être modifié une fois vérifié et validé. On peut faire seulement une nouvelle transaction en BTC.
> Par contre, il y a toujours la possibilité d'une attaque des 51 % où on doit disposer de la puissance de minage suffisante (donc impossible tellement cela serait gargantuesque).
