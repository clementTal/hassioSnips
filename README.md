# hassioSnips
Intents pour [hassio snips](https://console.snips.ai/store/fr/skill_2vNxwwenykz)

## Installation
1. Ajouter les scripts python dans le répertoir /config/python-scripts/ de votre hassio
2. Ajouter le fichier intent.yaml dans le répertoir /config/
3. Ajouter la conf suivante dans votre fichier configuration.yaml
```
python_script:

snips:

intent_script: !include _external-conf/intents.yaml
```
4. installer l'addon [snips](https://www.home-assistant.io/addons/snips/) et la configurer
5. Dans la [console snips](https://console.snips.ai/)
  - Créer un assistant
  - Ajouter l'application [hassio snips](https://console.snips.ai/store/fr/skill_2vNxwwenykz) a votre assistant
  - Télécharger votre assistant
6. Mettre votre assistant (que vous venez de télécharger) dans le dossier /share de votre hassio
7. Renomer votre assistant en **assistant.zip**
8. Démarer l'addon snips

## MAJ
Pour que vous soyez toujours a jour, il n'est pas possible de faire un fork de l'assistant.
Vous pouvez participer a la mise a jour de l'assistant en ajoutant des issues a ce dépo.
