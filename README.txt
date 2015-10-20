# EncryptAES_AN
Méthodes de chiffrement / dechiffrement AES Rijndael
+ méthode de génération de clé et de vecteur d'initialisation 


# Utilisation

Utilisation de l'encrypteur :

EncryptString("Le texte a chiffrer", "laclefait16carac", "vidoitfairelamemetaa");

EncryptString(Le texte qui doit être chiffré, la clé ( 16 caracteres ), Le vecteur d'initialisation qui doit être de la meme taille que le texte a chiffrer)



Utilisation du décrypteur :

DecryptString("Le texte a dechiffrer", "laclefait16carac", "vidoitfairelamemetaill");

EncryptString(Le texte qui doit être dechiffré, la clé ( 16 caracteres ), Le vecteur d'initialisation qui doit être de la meme taille que le texte a chiffrer)



( les sources proviennent de http://webman.developpez.com/articles/dotnet/aes-rijndael/ )
