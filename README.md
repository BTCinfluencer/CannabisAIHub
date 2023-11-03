# CannabisAIHub
Building AI course project "Cannabis AI Hub"
<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

Cannabis AI Hub

Final project for the Building AI course

## Summary

"CannabisAIHub.com" sera bien adapté à un projet qui rassemble des informations, des ressources et des applications d'intelligence artificielle liées au cannabis. 
"CannabisAIHub.com" aura une plateforme de recommandation de produits à base de cannabis, avec un centre d'information, des outils d'éducation et de dosage, d'analyse de données sur les variétés de cannabis & un forum communautaire.



## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?
Manque d'informations fiables: De nombreuses personnes ont du mal à trouver des informations fiables sur les variétés de cannabis, leurs effets, leurs applications médicales, et les lois qui les entourent. CannabisAIHub peut servir de source d'informations de confiance. 
Personnalisation des choix de cannabis: L'IA peut personnaliser les recommandations de produits en fonction des préférences et des besoins individuels, aidant ainsi les gens à faire des choix plus éclairés. 
Gestion des doses: Un outil d'IA peut éduquer les utilisateurs sur les doses appropriées pour éviter la surconsommation. 
Accès aux données: L'industrie du cannabis est en constante évolution, mais il peut être difficile d'accéder aux dernières données et recherches. CannabisAIHub peut centraliser les informations et les rendre accessibles à tous.
Conformité aux réglementations: Les lois et réglementations qui entourent le cannabis varient d'une région ou d'un pays à l'autre. L'IA peut aider à informer les utilisateurs sur la légalité de leur situation géographique.

La motivation personnelle derrière ce projet pourrait découler d'un intérêt pour l'éducation, la technologie et l'amélioration de la sécurité et de la responsabilité dans l'utilisation du cannabis.
Ce sujet est très important car il touche à la fois à des questions de santé publique, à la légalisation du cannabis et à la technologie. Il offre l'opportunité d'aider les individus à prendre des décisions plus éclairées en matière de cannabis, d'encourager la responsabilité et la sécurité, et de contribuer à l'évolution de l'industrie du cannabis vers des normes plus élevées en matière d'information et de transparence.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
Le projet "Cannabis AI Hub" a pour objectif de fournir des informations, des recommandations et des outils pour aider les utilisateurs à prendre des décisions éclairées concernant le cannabis
Processus d'utilisation :
Accès à la plateforme : Les utilisateurs accèdent à la plateforme "Cannabis AI Hub" en visitant le site Web.
Identification des besoins : Les utilisateurs sont invités à définir leurs besoins et préférences, que ce soit pour un usage récréatif ou médical, pour la gestion de la douleur, l'insomnie, l'anxiété, etc.
Recommandations personnalisées : L'IA analyse les données des utilisateurs et propose des recommandations de produits à base de cannabis, que ce soit des variétés de cannabis, des huiles, des produits comestibles, ou d'autres formes de consommation.
Éducation et information : Les utilisateurs peuvent accéder à des ressources éducatives sur le cannabis, y compris des guides, des articles et des informations sur la législation en vigueur dans leur région.
Simulations : Si un utilisateur souhaite comprendre les effets potentiels de différentes doses de cannabis, il peut utiliser des outils d'IA pour simuler ces effets.
Forum communautaire : Les utilisateurs peuvent participer à des discussions sur le cannabis, partager leurs expériences et poser des questions.

Types de situations et utilisateurs :
Personnes novices en matière de cannabis : Les novices qui cherchent à en savoir plus sur le cannabis et à prendre des décisions éclairées sur son utilisation.
Patients médicaux : Les patients cherchant à utiliser le cannabis à des fins médicales, par exemple, pour soulager la douleur chronique, l'anxiété, ou d'autres affections.
Utilisateurs récréatifs : Les consommateurs récréatifs souhaitant découvrir de nouvelles variétés de cannabis ou comprendre les doses appropriées pour éviter les effets indésirables.
Professionnels de la santé : Les médecins et les professionnels de la santé qui ont besoin d'informations actualisées sur le cannabis à des fins médicales.
Consommateurs expérimentés : Les consommateurs chevronnés qui souhaitent accéder à des informations avancées sur les variétés de cannabis et des ressources communautaires.


Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)

https://creator.nightcafe.studio/creation/uipnEuAZF4OOSJ476uNU 
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

# This is how you create code examples:

1. Exemple de recommandation de produit :
     # Supposons que vous ayez des données de produits et des préférences utilisateur
     # Utilisez un algorithme de recommandation, tel que des filtres collaboratifs, pour recommander des produits en fonction des préférences de l'utilisateur
def recommander_produit(utilisateur, produits):
    # Code de recommandation ici
    return produits_recommandes
    
2. Exemple de simulation d'effets du cannabis :
    # Créez une fonction pour simuler les effets du cannabis en fonction de la dose et de la variété
def simuler_effets(dose, variete):
    # Code de simulation ici
    return effets_simules
    
3. Exemple de récupération de données :
    # Utilisez des bibliothèques telles que Requests ou Beautiful Soup pour récupérer des données sur les variétés de cannabis à partir de sources en ligne
      import requests
url = "URL_de_la_source_de_données"
response = requests.get(url)
    # Analysez les données récupérées ici

```

def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Sources de données :
Bases de données publiques : Vous pouvez recueillir des données à partir de bases de données gouvernementales, de centres de recherche sur le cannabis, de rapports réglementaires, et d'autres sources publiques.
Sites Web de cannabis : De nombreux sites Web spécialisés dans le cannabis fournissent des informations sur les variétés, les produits, les effets, etc. Vous pourriez envisager de collaborer avec ces sources ou de les gratter pour collecter des données.
Laboratoires de test : Les laboratoires de test de cannabis fournissent des données sur la composition chimique des variétés. Vous pourriez obtenir ces données par le biais de partenariats ou d'accords.
Forums et communautés : Les forums de discussion et les communautés en ligne peuvent fournir des informations sur les expériences des utilisateurs. Vous pourriez envisager d'extraire des informations anonymisées à partir de ces sources.

Méthodes d'IA :
Apprentissage supervisé : Vous pourriez entraîner des modèles d'apprentissage automatique à l'aide de données étiquetées pour créer des systèmes de recommandation de produits ou d'effets.
Apprentissage non supervisé : Les méthodes d'apprentissage non supervisé peuvent être utilisées pour l'analyse de données et la catégorisation de variétés de cannabis.
Traitement du langage naturel (NLP) : Si vous envisagez d'analyser des forums ou des communautés, NLP peut vous aider à extraire des informations utiles à partir de textes non structurés.
Simulation : L'IA peut être utilisée pour simuler les effets de différentes doses et variétés de cannabis en fonction de données chimiques et d'effets connus.
Fusion de données : Vous pourriez intégrer des données de différentes sources en utilisant des méthodes de fusion de données pour fournir des informations plus complètes aux utilisateurs.

Bases de données gouvernementales : Recherchez les sites web des autorités gouvernementales responsables de la réglementation du cannabis dans votre région. Par exemple, aux États-Unis, la Drug Enforcement Administration (DEA) et la Food and Drug Administration (FDA) fournissent des informations sur les lois et réglementations liées au cannabis.
Sites Web spécialisés dans le cannabis : Explorez des sites web spécialisés dans le cannabis, tels que Leafly, High Times, ou Weedmaps, qui proposent des informations sur les variétés, les produits, les effets et les critiques.
Laboratoires de test : Contactez des laboratoires de test de cannabis, comme Steep Hill, et demandez s'ils sont disposés à partager des données sur la composition chimique des variétés de cannabis.
Forums et communautés en ligne : Explorez des forums de discussion et des communautés en ligne liés au cannabis, comme Grasscity ou Reddit's r/trees. Ces sources peuvent fournir des informations sur les préférences des utilisateurs et leurs expériences.
Ressources de recherche : Recherchez des articles de recherche scientifique dans des bases de données telles que PubMed, qui peuvent contenir des informations sur les aspects médicaux du cannabis.
Sources gouvernementales locales : Si le cannabis est légalisé dans votre région, consultez le site web de votre gouvernement local pour obtenir des informations sur les lois et réglementations spécifiques à votre région.



Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

Ce que le projet ne résout pas :
Problèmes de santé individuels : Le projet peut fournir des informations générales sur le cannabis, mais il ne peut pas diagnostiquer ou traiter des problèmes de santé spécifiques. Les utilisateurs ayant des problèmes de santé devraient consulter un professionnel de la santé.
Variabilité des effets : Les effets du cannabis peuvent varier considérablement d'une personne à l'autre en fonction de facteurs individuels. Le projet peut donner des recommandations générales, mais il ne peut pas prédire de manière précise comment une personne spécifique réagira.
Dépendance et usage abusif : Le projet doit être utilisé avec précaution pour éviter la promotion de l'abus de cannabis. Il devrait inclure des informations sur les risques de dépendance et d'abus.
Problèmes légaux : Les lois et réglementations liées au cannabis varient d'une région à l'autre. Le projet peut informer les utilisateurs sur la législation générale, mais il ne peut pas donner de conseils juridiques spécifiques à chaque situation.

Considérations éthiques :
Protection de la vie privée : La collecte de données sur les préférences et l'utilisation du cannabis doit être effectuée de manière à protéger la vie privée des utilisateurs. Il est important d'obtenir un consentement éclairé et de stocker les données de manière sécurisée.
Contenu et recommandations équilibrés : Le projet doit fournir des informations objectives et équilibrées sur le cannabis, en évitant de favoriser une consommation excessive ou irresponsable.
Transparence : Les méthodes de recommandation de produits et de simulation d'effets doivent être transparentes, de manière à ce que les utilisateurs comprennent comment les suggestions sont générées.
Accès équitable : Le projet doit être accessible à tous, en évitant la discrimination et en veillant à ce que les informations soient compréhensibles pour un large public.
Éducation continue : Il est important de fournir des ressources éducatives régulièrement mises à jour pour refléter les dernières recherches et réglementations liées au cannabis.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

Le projet "Cannabis AI Hub" a le potentiel de croître et de devenir une ressource encore plus précieuse à l'avenir. Voici quelques façons dont il pourrait évoluer et se développer :
Expansion des fonctionnalités : Vous pourriez élargir les fonctionnalités de la plateforme en ajoutant de nouveaux outils d'IA, tels que des simulateurs plus avancés, des outils de dosage en temps réel, ou des chatbots pour des réponses instantanées.
Internationalisation : Vous pourriez étendre le projet pour prendre en charge différentes langues et régions, en fournissant des informations spécifiques à chaque localisation.
Partenariats : Collaborer avec des laboratoires de test de cannabis, des entreprises de l'industrie, des experts en santé et des organismes gouvernementaux pour accéder à des données de haute qualité et à des ressources.
Applications mobiles : Développer des applications mobiles pour rendre le projet plus accessible aux utilisateurs sur leurs smartphones et tablettes.
Formation et sensibilisation : Organiser des ateliers, des webinaires et des programmes de formation pour éduquer le public, les professionnels de la santé et les dispensaires de cannabis sur les meilleures pratiques.
Intelligence artificielle avancée : Explorer des domaines avancés de l'IA, tels que l'apprentissage en profondeur, pour améliorer la précision des recommandations et des simulations.

Pour faire évoluer ce projet, vous aurez besoin de diverses compétences, notamment :

Développement d'applications web et mobiles : Pour étendre les fonctionnalités et offrir une expérience utilisateur de haute qualité.
Expérience en intelligence artificielle : Pour améliorer les modèles d'IA, développer de nouveaux outils et garantir des recommandations précises.
Connaissance du domaine : Une compréhension approfondie des aspects médicaux, légaux et culturels du cannabis est essentielle.
Protection de la vie privée et sécurité des données : Pour garantir la confidentialité et la sécurité des données des utilisateurs.
Éducation et sensibilisation : Pour informer le public et les professionnels de la santé sur les avantages et les risques du cannabis.


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
