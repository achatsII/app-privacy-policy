# Politique de Confidentialité — QuickDictate

Ce document contient la politique de confidentialité de l'application mobile **QuickDictate** en français.
Vous pouvez consulter la [version anglaise (English version)](../en/privacy-policy.md).

---

**Dernière mise à jour : 24 juillet 2026**

Intelligence Industrielle (« nous », « notre » ou « nos ») accorde une importance primordiale à la protection de votre vie privée et de vos données personnelles. Cette Politique de Confidentialité a pour but de vous expliquer de manière transparente comment l'application mobile **QuickDictate** (l' « Application ») collecte, utilise, stocke et protège vos informations lors de son utilisation sur les plateformes Apple iOS et Google Android.

En installant et en utilisant l'Application, vous acceptez les pratiques de traitement des données décrites dans cette Politique de Confidentialité.

---

### 1. Renseignements généraux sur l'Application

QuickDictate est une application mobile de dictée vocale conçue pour enregistrer la voix, transcrire l'audio en texte via la passerelle sécurisée d'Intelligence Industrielle, puis historiser, classer par tags et résumer automatiquement ces notes sous forme de journal de bord à l'aide d'outils d'intelligence artificielle (IA).

Ces fonctionnalités reposent sur des fournisseurs d'IA tiers. **Aucune donnée n'est transmise à ces fournisseurs sans votre consentement explicite et préalable**, recueilli directement dans l'Application (voir la section 6).

---

### 2. Données collectées et finalités du traitement

Pour assurer le fonctionnement des services de l'Application, nous collectons les informations suivantes :

- **Données audio (Enregistrements vocaux) :** Lorsque vous lancez un enregistrement, l'Application capture votre voix via le microphone de votre appareil. Ces enregistrements sont chiffrés et envoyés de manière sécurisée à notre passerelle pour y être transcrits, uniquement après que vous ayez accepté le partage avec les services d'IA (section 6). Les fichiers audio originaux ne sont pas conservés de façon permanente sur nos serveurs après la réussite de la transcription.
- **Transcriptions et textes générés :** Le texte résultant de vos dictées, vos annotations, les classifications par tags (manuels ou générés par IA), ainsi que les résumés quotidiens et hebdomadaires de votre journal de bord sont stockés de façon sécurisée dans notre base de données afin de vous fournir votre historique.
- **Données d'authentification :** L'authentification utilise le protocole sécurisé OAuth 2.0 avec PKCE. Vos jetons d'authentification (jetons d'accès et de rafraîchissement) sont stockés localement sur votre appareil de façon hautement sécurisée à l'aide de l'API native de stockage sécurisé (`expo-secure-store`).
- **Données de synchronisation hors-ligne :** Si l'enregistrement d'une transcription dans votre historique échoue (absence de connexion Internet ou erreur serveur), le texte transcrit correspondant est conservé localement sur votre appareil, dans le stockage chiffré, puis renvoyé automatiquement vers votre historique dès que la connexion est rétablie, afin d'éviter toute perte de données.
- **Données techniques et de diagnostic :** Nous pouvons collecter des informations techniques anonymisées ou pseudonymisées (modèle de l'appareil, version du système d'exploitation, rapports de plantage/crash logs) afin de diagnostiquer les dysfonctionnements et d'améliorer la stabilité de l'Application.

---

### 3. Autorisations requises (Permissions)

L'Application requiert l'accès à certaines fonctionnalités de votre appareil pour exécuter ses tâches essentielles. Vous pouvez activer ou désactiver ces permissions à tout moment dans les réglages système de votre appareil :

- **Microphone (`RECORD_AUDIO`, `FOREGROUND_SERVICE_MICROPHONE`) :** Indispensable pour capturer votre voix. L'accès au microphone est activé uniquement pendant que vous enregistrez une note vocale.
- **Service de premier plan & Audio en arrière-plan (`FOREGROUND_SERVICE`, `UIBackgroundModes: audio`) :** Permet de maintenir l'enregistrement actif et stable même si l'écran de votre appareil s'éteint ou si vous basculez sur une autre application.

---

### 4. Utilisation de vos données

Vos données sont traitées pour :

- Fournir et maintenir les fonctionnalités de dictée et de transcription vocale.
- Générer des classifications par tags et des résumés de productivité (journal de bord IA).
- Assurer la synchronisation et la sauvegarde en temps réel de votre historique de dictées.
- Assurer la sécurité de votre compte et prévenir les accès non autorisés.

Vos données ne sont utilisées à aucune autre fin. Elles ne servent ni à la publicité, ni au profilage, ni à l'entraînement de modèles d'intelligence artificielle.

---

### 5. Partage et transfert des données

Nous nous engageons à ne jamais vendre, louer ni commercialiser vos données personnelles à des tiers.

**Passerelle d'Intelligence Industrielle**

Vos données transitent de façon chiffrée (HTTPS/TLS) vers notre passerelle officielle (`https://gateway.intelligenceindustrielle.com`), qui les relaie ensuite aux fournisseurs d'IA ci-dessous.

**Fournisseurs d'intelligence artificielle tiers**

L'Application partage vos données avec les fournisseurs d'IA tiers suivants, et uniquement avec ceux-ci :

| Fournisseur | Données qui lui sont transmises | Finalité |
| --- | --- | --- |
| **OpenAI, L.L.C.** | L'enregistrement audio de votre dictée | Conversion de la parole en texte (transcription) |
| **Google LLC** | Le texte transcrit de vos notes | Génération des tags de classification et des résumés quotidiens et hebdomadaires |

Aucune autre donnée n'est transmise à ces fournisseurs. Votre nom, votre adresse courriel, vos identifiants de compte et vos jetons d'authentification ne leur sont jamais communiqués.

**Protection équivalente assurée par ces tiers**

Nous avons conclu avec chacun de ces fournisseurs des ententes de traitement des données qui les obligent contractuellement à assurer un niveau de protection de vos données **égal ou supérieur** à celui décrit dans la présente Politique de Confidentialité. Il leur est notamment interdit :

- d'utiliser vos données pour entraîner ou améliorer leurs modèles ;
- de conserver vos données au-delà du délai strictement nécessaire au traitement de la requête ;
- de vendre, louer, partager ou divulguer vos données à quiconque ;
- d'utiliser vos données à toute fin autre que l'exécution du service demandé.

**Modification de la liste des fournisseurs**

Si nous ajoutons, remplaçons ou retirons un fournisseur d'IA, nous mettrons à jour la présente politique et l'Application vous demandera **à nouveau votre consentement explicite** avant tout envoi de données au nouveau fournisseur.

---

### 6. Consentement explicite au partage avec les services d'IA

Conformément aux exigences applicables en matière de protection de la vie privée, l'Application ne transmet aucune donnée à un service d'IA tiers sans votre autorisation préalable.

- **Avant toute transmission :** lors de votre première utilisation d'une fonctionnalité d'IA (enregistrement d'une dictée, tag vocal ou génération d'un journal), l'Application affiche un écran de consentement. Cet écran indique précisément quelles données sont envoyées, à quels destinataires et à quelle fin.
- **Consentement volontaire :** aucun enregistrement n'est démarré et aucune donnée n'est envoyée tant que vous n'avez pas appuyé sur « J'accepte et je continue ». Si vous refusez, les fonctionnalités d'IA restent simplement inactives.
- **Retrait à tout moment :** vous pouvez retirer votre consentement à tout moment depuis **Paramètres → Confidentialité → Retirer mon consentement au partage IA**. Après ce retrait, l'Application cessera immédiatement d'envoyer des données aux services d'IA et vous redemandera votre autorisation avant toute nouvelle transcription.
- **Nouvelle demande en cas de changement :** si la nature des données envoyées ou la liste des destinataires change, votre consentement antérieur est invalidé et l'écran de consentement vous est présenté de nouveau.

---

### 7. Stockage, rétention et sécurité des données

- **Sécurité physique et logique :** Toutes les données stockées sur nos serveurs sont protégées par des pare-feux, du chiffrement au repos et en transit, ainsi que des contrôles d'accès rigoureux.
- **Sécurité locale :** Les informations sensibles de connexion sont stockées dans le compartiment sécurisé de l'appareil mobile (`SecureStore` iOS et Android KeyStore).
- **Durée de conservation :** Vos données sont conservées aussi longtemps que votre compte utilisateur reste actif. Si vous demandez la suppression de votre compte, toutes les données associées seront supprimées définitivement de nos bases de données de production sous 30 jours.

---

### 8. Vos droits et suppression des données

Conformément aux réglementations sur la protection des données personnelles (notamment la Loi 25 au Québec, la LPRPDE au Canada et le RGPD en Europe) :

- Vous disposez d'un droit d'accès, de rectification, de portabilité et de suppression de vos données personnelles.
- Vous pouvez retirer votre consentement au partage de vos données avec les services d'IA à tout moment, directement dans l'Application (voir la section 6).
- Vous pouvez supprimer individuellement chaque transcription de votre historique depuis l'Application.
- Vous pouvez demander la suppression complète de votre compte et de l'historique associé en nous contactant à l'adresse e-mail mentionnée dans la section 11.

---

### 9. Confidentialité des enfants

L'Application n'est pas conçue pour les personnes de moins de 13 ans. Nous ne collectons pas sciemment d'informations personnelles auprès d'enfants. Si nous constatons qu'un enfant nous a fourni des données personnelles sans le consentement des parents, nous supprimerons immédiatement ces informations.

---

### 10. Modifications de la politique de confidentialité

Nous pouvons mettre à jour cette Politique de Confidentialité pour refléter des changements légaux ou techniques. La date de mise à jour au début du document sera révisée en conséquence. Nous vous encourageons à consulter régulièrement cette page.

---

### 11. Contact et Responsable de la protection des données

Pour toute question relative à la présente Politique de Confidentialité ou pour exercer vos droits, vous pouvez contacter notre responsable de la protection des données à l'adresse suivante :

- **Intelligence Industrielle**
- **Courriel :** `support@intelligenceindustrielle.com`
- **Site Web :** [https://intelligenceindustrielle.com](https://intelligenceindustrielle.com)
