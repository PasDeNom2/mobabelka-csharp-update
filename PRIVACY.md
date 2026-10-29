# Politique de confidentialité de NutShell

*Dernière mise à jour : 29 octobre 2026*

NutShell (« NutShell Remote » sur le Microsoft Store) est un gestionnaire de connexions à distance (SSH, RDP, SFTP, VNC, web). Cette page explique quelles données l'application traite et pourquoi.

## Sans compte

Utilisé sans compte, NutShell ne transmet aucune donnée personnelle à son éditeur. Vos sessions, identifiants, clés et réglages restent sur votre PC, dans `%APPDATA%\NutShell`, chiffrés par votre mot de passe maître ou par Windows.

## Avec un compte NutShell (facultatif)

Le compte sert à retrouver vos sessions sur plusieurs PC.

- **Adresse email** : identifiant du compte, utilisée pour la connexion, les codes de confirmation et de réinitialisation du mot de passe.
- **Vos données (sessions, dossiers, identifiants, modèles, espaces de travail)** : chiffrées **sur votre PC** avant l'envoi (chiffrement de bout en bout). Le serveur ne stocke que des données chiffrées et ne peut ni les lire ni connaître votre mot de passe.
- **Appareils** : nom du PC et date de dernière synchronisation, pour la liste « Appareils connectés ».
- **Connexion avec Google** : NutShell reçoit seulement votre adresse email et votre identifiant Google, pour vous connecter. Une clé de chiffrement de vos données est alors conservée par le compte, accessible uniquement après connexion à ce compte.

Hébergement : Supabase, dans l'Union européenne (Francfort). Emails : Brevo (France).

Vous pouvez supprimer votre compte à tout moment dans **Paramètres → Compte → Supprimer le compte** : le compte, les données chiffrées et la liste des appareils sont effacés du serveur.

## Autres échanges réseau

- **Vos connexions** (SSH, RDP, web…) vont directement de votre PC vers les serveurs que vous choisissez, sans passer par l'éditeur.
- **Vérification des fuites de mots de passe** (uniquement si vous la lancez) : seuls les 5 premiers caractères de l'empreinte SHA-1 du mot de passe sont envoyés au service Have I Been Pwned ; le mot de passe ne quitte jamais votre PC.
- **Mises à jour** : la version Store est mise à jour par le Microsoft Store ; la version téléchargée sur GitHub vérifie les nouvelles versions sur GitHub.

NutShell ne contient **ni publicité, ni statistiques d'usage, ni traceur**. Les journaux de l'application restent sur votre PC.

## Vos droits

Conformément au RGPD, vous pouvez accéder à vos données, les rectifier ou les supprimer (la suppression du compte est disponible directement dans l'application). Pour toute question : [ouvrir une demande](https://github.com/PasDeNom2/nutshell-update/issues).
