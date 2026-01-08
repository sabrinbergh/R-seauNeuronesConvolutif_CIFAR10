# Réseau de neurones convolutif CIFAR-10

Ce projet consiste à concevoir et entraîner un réseau de neurones convolutif (CNN) pour la classification d’images à partir du dataset CIFAR-10.  
L’objectif est de mettre en place une architecture complète de deep learning, puis d’observer et comprendre le comportement du modèle tout au long de l’entraînement. Le projet ne se limite pas à l’implémentation du réseau : il s’intéresse aussi à l’évolution des performances, aux choix d’architecture et à leur impact sur l’apprentissage.

## Technologies utilisées
Le projet est réalisé en Python à l’aide de :
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

## Description du modèle

Le modèle repose sur une architecture classique de réseau de neurones convolutif.  
Les couches de convolution permettent d’extraire progressivement les caractéristiques visuelles importantes des images, tandis que les couches de max-pooling réduisent la dimension des données et limitent le nombre de paramètres. 
Après cette phase d’extraction, les représentations sont aplaties et transmises à des couches fully connected chargées de la classification finale.  
La couche de sortie utilise une fonction d’activation softmax, permettant d’obtenir une probabilité pour chaque classe.

## Entraînement et analyse des résultats

L’entraînement du modèle est suivi à l’aide des courbes de loss et d’accuracy sur les ensembles d’entraînement et de test.  
Ces courbes permettent d’analyser l’évolution des performances, de comparer les comportements train et test et d’identifier d’éventuels phénomènes comme le surapprentissage ou l’instabilité de l’apprentissage.

L’objectif n’est pas uniquement d’obtenir un bon score, mais surtout de comprendre comment le modèle apprend et comment les choix effectués influencent ses performances.

## Ce que montre ce projet

Ce projet met en avant :
- la construction complète d’un modèle de deep learning  
- la compréhension du fonctionnement d’un CNN appliqué à des images  
- l’analyse des performances à partir de courbes d’apprentissage  
- une réflexion sur les choix d’architecture et leurs effets sur le modèle
