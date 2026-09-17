# CONTRAT DE CONNEXION DES FARMS Ω

Chaque FARM doit connaître l’URL canonique du registre central :
`https://raw.githubusercontent.com/dmaillot95-ui/cerebron-omega-encyclopedia/main/registry/manifest.json`

Règles :
1. Charger le manifeste central au démarrage lorsque le réseau est disponible.
2. Ne récupérer que les objets utiles à la mission courante.
3. Ne jamais traiter l’encyclopédie comme preuve indépendante : elle est une mémoire/registre, pas une source externe.
4. Respecter les statuts CANDIDATE / TESTING / VERIFIED_LOCAL / TRANSFERRED / CANONICAL / NARROWED / DORMANT / KILLED.
5. Conserver provenance, version, domaine de validité et conditions de réouverture.
6. Un objet central peut guider un agent mais ne remplace ni test, ni preuve, ni audit.
7. Toute contribution d’une FARM vers l’encyclopédie doit arriver comme DELTA candidat avant promotion.
8. UNKNOWN REMAINS UNKNOWN ; contradiction non résolue conservée.

Objet local minimal attendu dans chaque FARM : `CEREBRON_REGISTRY.json`.
