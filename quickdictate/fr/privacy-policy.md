# Politique de Confidentialité — QuickDictate

Ce document contient la politique de confidentialité de l'application mobile **QuickDictate** en français.
Vous pouvez consulter la [version anglaise (English version)](../en/privacy-policy.md).

---

**Dernière mise à jour : 16 juin 2026**

Intelligence Industrielle (« nous », « notre » ou « nos ») accorde une importance primordiale à la protection de votre vie privée et de vos données personnelles. Cette Politique de Confidentialité a pour but de vous expliquer de manière transparente comment l'application mobile **QuickDictate** (l' « Application ») collecte, utilise, stocke et protège vos informations lors de son utilisation sur les plateformes Apple iOS et Google Android.

En installant et en utilisant l'Application, vous acceptez les pratiques de traitement des données décrites dans cette Politique de Confidentialité.

---

### 1. Renseignements généraux sur l'Application

QuickDictate est une application mobile de dictée vocale conçue pour enregistrer la voix, transcrire l'audio en texte via la passerelle sécurisée d'Intelligence Industrielle, puis historiser, classer par tags et résumer automatiquement ces notes sous forme de journal de bord à l'aide d'outils d'intelligence artificielle (IA).

---

### 2. Données collectées et finalités du traitement

Pour assurer le fonctionnement des services de l'Application, nous collectons les informations suivantes :

- **Données audio (Enregistrements vocaux) :** Lorsque vous lancez un enregistrement, l'Application capture votre voix via le microphone de votre appareil. Ces enregistrements sont chiffrés et envoyés de manière sécurisée à notre passerelle pour y être transcrits. Les fichiers audio originaux ne sont pas conservés de façon permanente sur nos serveurs après la réussite de la transcription.
- **Transcriptions et textes générés :** Le texte résultant de vos dictées, vos annotations, les classifications par tags (manuels ou générés par IA), ainsi que les résumés quotidiens et hebdomadaires de votre journal de bord sont stockés de façon sécurisée dans notre base de données afin de vous fournir votre historique.
- **Données d'authentification :** L'authentification utilise le protocole sécurisé OAuth 2.0 avec PKCE. Vos jetons d'authentification (jetons d'accès et de rafraîchissement) sont stockés localement sur votre appareil de façon hautement sécurisée à l'aide de l'API native de stockage sécurisé (`expo-secure-store`).
- **Données de synchronisation hors-ligne :** En cas d'absence de connexion Internet, les enregistrements audio en attente de transcription sont mis en file d'attente locale et persistante sous forme chiffrée, puis synchronisés et transcrits automatiquement dès le retour de la connexion pour éviter toute perte de données.
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

---

### 5. Partage et transfert des données

Nous nous engageons à ne jamais vendre, louer ni commercialiser vos données personnelles à des tiers.

- **Passerelle d'Intelligence Industrielle :** Vos données transitent de façon chiffrée (HTTPS/TLS) vers notre passerelle officielle (`https://gateway.intelligenceindustrielle.com`).
- **Sous-traitants technologiques (Transcription et IA) :** Pour réaliser la transcription de l'audio en texte et générer les résumés/tags, les données requises peuvent être transmises de manière sécurisée à des API spécialisées de confiance (telles que Google Cloud, OpenAI ou Anthropic). Ces sous-traitants sont liés par des accords de confidentialité stricts et il leur est contractuellement interdit d'utiliser vos données pour entraîner leurs propres modèles.

---

### 6. Stockage, rétention et sécurité des données

- **Sécurité physique et logique :** Toutes les données stockées sur nos serveurs sont protégées par des pare-feux, du chiffrement au repos et en transit, ainsi que des contrôles d'accès rigoureux.
- **Sécurité locale :** Les informations sensibles de connexion sont stockées dans le compartiment sécurisé de l'appareil mobile (`SecureStore` iOS et Android KeyStore).
- **Durée de conservation :** Vos données sont conservées aussi longtemps que votre compte utilisateur reste actif. Si vous demandez la suppression de votre compte, toutes les données associées seront supprimées définitivement de nos bases de données de production sous 30 jours.

---

### 7. Vos droits et suppression des données

Conformément aux réglementations sur la protection des données personnelles (notamment la Loi 25 au Québec, la LPRPDE au Canada et le RGPD en Europe) :

- Vous disposez d'un droit d'accès, de rectification, de portabilité et de suppression de vos données personnelles.
- Vous pouvez demander la suppression complète de votre compte et de l'historique associé en nous contactant à l'adresse e-mail mentionnée dans la section 10.

---

### 8. Confidentialité des enfants

L'Application n'est pas conçue pour les personnes de moins de 13 ans. Nous ne collectons pas sciemment d'informations personnelles auprès d'enfants. Si nous constatons qu'un enfant nous a fourni des données personnelles sans le consentement des parents, nous supprimerons immédiatement ces informations.

---

### 9. Modifications de la politique de confidentialité

Nous pouvons mettre à jour cette Politique de Confidentialité pour refléter des changements légaux ou techniques. La date de mise à jour au début du document sera révisée en conséquence. Nous vous encourageons à consulter régulièrement cette page.

---

### 10. Contact et Responsable de la protection des données

Pour toute question relative à la présente Politique de Confidentialité ou pour exercer vos droits, vous pouvez contacter notre responsable de la protection des données à l'adresse suivante :

- **Intelligence Industrielle**
- **Courriel :** `support@intelligenceindustrielle.com`
- **Site Web :** [https://intelligenceindustrielle.com](https://intelligenceindustrielle.com)
