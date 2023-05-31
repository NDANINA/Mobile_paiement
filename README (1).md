
### Projet Paiement Mobile sur un site de vente  de voiture
Table "users_table":

Cette table stocke les informations sur les utilisateurs du site.
Chaque utilisateur a un identifiant unique (id_user) qui s'incrémente automatiquement (auto_increment) lors de l'ajout d'un nouvel utilisateur.
Les champs "nom", "adresse", "numero_telephone", "username" et "mot_de_passe" enregistrent respectivement le nom, l'adresse, le numéro de téléphone, le nom d'utilisateur et le mot de passe de l'utilisateur.
Les champs "nom", "adresse", "numero_telephone", "username" et "mot_de_passe" sont définis comme "not null", ce qui signifie qu'ils doivent tous avoir une valeur lors de l'ajout d'un nouvel utilisateur.
Table "produit":

Cette table contient les informations sur les produits disponibles sur le site.
Chaque produit a un identifiant unique (id_prod) qui s'incrémente automatiquement lors de l'ajout d'un nouveau produit.
Le champ "Nom_prod" enregistre le nom du produit, tandis que le champ "prix" enregistre le prix du produit.
Les champs "Nom_prod" et "prix" sont définis comme "not null", ce qui signifie qu'ils doivent tous avoir une valeur lors de l'ajout d'un nouveau produit.
Table "payment_lumicash":

Cette table enregistre les informations sur les paiements effectués via le service "Lumicash".
Chaque paiement effectué a un identifiant unique (id_pay_lumi) qui s'incrémente automatiquement lors de l'ajout d'un nouveau paiement.
Les champs "Numero_de_votre_Sim", "Kabanga", "Shiramw_igitigiri_c_amahera" et "Servisi_ya_lumicash" enregistrent respectivement le numéro de votre SIM, la valeur de Kabanga, le montant Shiramw_igitigiri_c_amahera et le service Lumicash utilisé pour le paiement.
Les champs "Numero_de_votre_Sim", "Kabanga", "Shiramw_igitigiri_c_amahera" et "Servisi_ya_lumicash" sont définis comme "not null", ce qui signifie qu'ils doivent tous avoir une valeur lors de l'ajout d'un nouveau paiement.
Table "payment_carte":

Cette table enregistre les informations sur les paiements effectués via une carte bancaire.
Chaque paiement effectué avec une carte a un identifiant unique (id_carte) qui s'incrémente automatiquement lors de l'ajout d'un nouveau paiement.
Les champs "Nom", "CVV", "N_de_la_carte_bancaire" et "Date_d_expiration" enregistrent respectivement le nom du titulaire de la carte, le code CVV, le numéro de la carte bancaire et la date d'expiration de la carte.
Les champs "Nom", "CVV", "N_de_la_carte_bancaire" et "Date_d_expiration" sont définis comme "not null", ce qui signifie qu'ils doivent tous avoir une valeur lors de l'ajout d'un nouveau paiement.
Ces explications détaillées devraient vous donner une meilleure compréhension de la structure et du but de chaque table utilisée dans le projet "Site Cars".