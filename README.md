# Blueprints pour les défis Hilo  
Blueprint pour Home Assistant permettant d'utiliser l'intégration Hilo facilement. Vous pourrez automatiser la température cible de vos thermostats pour maximiser vos récompenses Hilo. Vous avez également la possibilité de participer aux défis du matin et/ou du soir.  

De plus, vous pourrez contrôler votre chauffe-eau et d'autres équipements de type "switch", comme une laveuse, une sécheuse ou un chargeur de véhicule électrique.  

Ce Blueprint est basé sur ceux de @Eradash.  

---

## Configuration  

### L'application Hilo  
Pour un fonctionnement optimal, désactivez la prise en charge des thermostats pendant les défis dans l'application Hilo. Vous continuerez à participer aux défis et à recevoir les récompenses. Il est également recommandé de ne pas avoir de scènes programmées. Cela s'applique également à tous les autres thermostats non-Hilo qui pourraient être gérés par ces automatisations.  

### Intégration Hilo  
Vous aurez besoin de l'intégration [Hilo](https://github.com/dvd-dev/hilo) pour que ces Blueprints fonctionnent.  

- **La période d'appréciation doit être de 3 heures, si désiré. Vous pouvez la configurer dans l'intégration Hilo.**  
- **La période de refroidissement avant la période d'appréciation doit être de 1 heure, si désiré. Vous pouvez également la configurer dans l'intégration Hilo.**  

---

### Installation des "Blueprints"  
Installez les Blueprints avec ces liens :  

- Défis automatiques :  
  [![Importer le Blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fraw.githubusercontent.com%2Farim215%2Fha-hilo-blueprints%2Fmain%2Fdefis_hilo_automatiques.yaml)  

---

## Contribution  

Si vous souhaitez contribuer, n'hésitez pas ! Actuellement, j'aimerais ajouter une meilleure méthode pour contrôler une thermopompe afin de réduire les coûts liés au préchauffage. Cela devrait être configurable avec une limite de température extérieure.  

**Contributeurs :**  
- @Eradash  
- @arim215  
- @jrobichaud  
- @jpbaril  

---

## À faire :  

Si vous avez des idées, partagez-les !  

- Ajouter des notifications lorsqu'un défi est planifié, commence ou se termine.  
