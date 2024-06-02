# ML-TADF


Modèle de Machine Learning pour la conception inverse des TADF

Pour la conception inverse des TADF, Tartarus a utilisé le modèle génératif de type VAE(Variational Autoencoder) qui est utilisé pour générer de nouvelles molécules 
candidates ayant des propriétés TADF souhaitées. 

La conception inverse est une méthode qui consiste à trouver des molécules qui respectent les propriétés de la conception d'un matériau.
Dans le cas des TADF je l'utiliserai pour trouver des molécules qui ont des propriétés photophysiques,... pour la conception des OLED a fluorescence retardée.

Pour le ML, j'utiliserai la base de données GDB-13. Je donnerai en entrée à mon modèle des propriétés et en sortie, j'obtiendrai des molécules
Le modèle que j'utiliserai est un approche combinée : une combinaison des approches suivantes : un modèle génératif couplé à un modèle de prédiction des propriétés TADF et
de la méthode d'optimisation , qui peut permettre une conception moléculaire plus performante.

