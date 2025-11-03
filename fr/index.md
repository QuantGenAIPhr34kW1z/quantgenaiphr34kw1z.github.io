<div class="cv">

<aside class="cv-left">
    <img src="/assets/img/martin.jpg" alt="Martin" class="avatar" />

    <h1 class="cv-name">Martin</h1>

    <p class="cv-role">Architecte système et ingénieur logiciel</p>

    <p class="cv-meta">
      Systèmes distribués · IA/LLM<br />
      Cybersécurité · Blockchain · HPC<br />
      Rust · Golang · C++ · Zig<br />
      Python · Spark · Erlang<br />
      Haskell · OCaml
    </p>

    <hr/>

    <ul class="links">
      <li><a href="https://github.com/quantgenaiphr34kw1z">GitHub </a></li>
      <li><a href="/fr/support">Soutien </a></li>
    </ul>
    <small>
       Langue : <a href="/">EN </a> · <strong>FR </strong>
    </small>

</aside>

<main class="cv-right" markdown="1">

# À propos

Je conçois et implémente des systèmes bas niveau à haute fiabilité, avec un accent particulier sur la correction, la sécurité et la maintenabilité à long terme

Mes travaux couvrent notamment :

- l'entraînement de modèles LLM, les pipelines d'inférence et les systèmes d'IA appliquée
- la cryptographie appliquée, la cryptographie post-quantique (PQC), les couches de transport sécurisées et le durcissement des systèmes
- les architectures blockchain, les protocoles décentralisés et les systèmes cryptoéconomiques
- l'ingénierie en cybersécurité, les opérations de type red team et les audits de sécurité
- les réseaux distribués et les protocoles d'overlay
- les infrastructures basées sur Kubernetes, l'automatisation et les pipelines de données à grande échelle
- le traitement Big Data et les charges de calcul haute performance (HPC)
- les outils de recherche, compilateurs et prototypes de systèmes

Les dépôts présents ici regroupent à la fois des travaux en production et des recherches expérimentales open source, visant à analyser des compromis de conception et à éclairer des architectures utilisables en conditions réelles

---

## Travaux sélectionnés

### Systèmes IA / LLM

- **[shellog](https://github.com/QuantGenAIPhr34kW1z/shellog)** - **Assistant local de commandes et de développement**<br />
  Transformation du langage naturel en commandes shell, code et explications, entièrement exécutée via une instance locale d'Ollama. Aucun cloud, aucune clé API, aucune télémétrie. Les requêtes ne quittent jamais la machine locale.
- **[lc](https://github.com/QuantGenAIPhr34kW1z/lc)** - **Assistant privé de développement logiciel**<br />
  Assistant IA embarqué destiné à l'ingénierie logicielle et aux systèmes.
- **[swarmshield](https://github.com/QuantGenAIPhr34kW1z/swarmshield)** - **Simulateur de dynamiques sociales**<br />
  Cadre analytique permettant l'analyse de données historiques, la modélisation des dynamiques présentes et l'exploration de scénarios futurs.
- **[lattice-mp](https://github.com/QuantGenAIPhr34kW1z/lattice-mp)** - **Moteur distribué de Machine Learning (MPI / HPC)**<br />
  Moteur de calcul distribué haute performance pour l'apprentissage automatique à grande échelle sur des environnements hétérogènes

### Cybersécurité et défense

- **[honeyforge](https://github.com/QuantGenAIPhr34kW1z/honeyforge)** - **Leurre réseau haute performance (honeypot)**<br />
  Système de détection et de journalisation d'attaques avancées, prêt pour un déploiement en production
- **[lanwatch](https://github.com/QuantGenAIPhr34kW1z/lanwatch)** - **Analyseur de flux réseau en temps réel**<br />
  Analyse légère du trafic LAN avec inférence ML embarquée
- **[sentinel-edge](https://github.com/QuantGenAIPhr34kW1z/sentinel-edge)** - **Défense périphérique déterministe pour systèmes embarqués**<br />
  Mécanisme de défense léger et déterministe pour routeurs OpenWrt et Linux embarqué
- **[ssh-mirage](https://github.com/QuantGenAIPhr34kW1z/ssh-mirage)** - **Tunnel SSH invisible via TLS**<br />
  Transport SSH encapsulé dans du trafic TLS standard afin de se fondre dans un flux HTTPS classique
- **[NoetherOS](https://github.com/QuantGenAIPhr34kW1z/NoetherOS)** - **Système d'exploitation mobile post-quantique sécurisé**<br />
  Système mobile durci, inspiré de GrapheneOS, conçu pour des modèles de menace souverains et post-quantiques
- **[noether-relay](https://github.com/QuantGenAIPhr34kW1z/noether-relay)** - **Appairage hors ligne sécurisé**<br />
  Cadre d'appairage air-gap pour ponts Linux compagnons sécurisés

### Robotique et drones

- **[NAVscout](https://github.com/QuantGenAIPhr34kW1z/NAVscout)** - **Navigation autonome de drones (Raspberry Pi 5)**<br />
  Navigation et suivi d'objets assistés par IA pour plateformes embarquées
- **[skywarden](https://github.com/QuantGenAIPhr34kW1z/skywarden)** - **Reconnaissance aérienne sans fil**<br />
  Systèmes de reconnaissance radio et réseau embarqués sur drones

### Ingénierie RF et communications satellitaires

- **[skyrake](https://github.com/QuantGenAIPhr34kW1z/skyrake)** - **Plateforme de reconnaissance spectrale**<br />
  Surveillance RF à l'échelle d'une flotte pour stations sol et opérations satellite
- **[spectrax](https://github.com/QuantGenAIPhr34kW1z/spectrax)** - **Plateforme de renseignement RF**<br />
  Chaîne complète de renseignement radio, de l'acquisition à l'analyse
- **[cellsigint](https://github.com/QuantGenAIPhr34kW1z/cellsigint)** - **Cadre SIGINT cellulaire**<br />
  Extraction IMSI et analyse de signaux cellulaires via Rust, tables arc-en-ciel et apprentissage automatique
- **[leo-mucpu](https://github.com/QuantGenAIPhr34kW1z/leo-mucpu)** - **Émulateur déterministe de calculateur satellite LEO**<br />
  Émulation pour validation en environnement irradié et tests d'injection de fautes
- **[ravengrid](https://github.com/QuantGenAIPhr34kW1z/ravengrid)** - **Grille de détection multi-spectrale de drones**<br />
  Détection combinant RF, acoustique, thermique, optique et bistatique satellite
- **[rfQ](https://github.com/QuantGenAIPhr34kW1z/rfQ)** - **Pile de transport sécurisée radio et satellite**<br />
  Micro-pile de transport minimaliste et durcie pour liaisons radio et satellites

### Calcul scientifique

- **[minotaur](https://github.com/QuantGenAIPhr34kW1z/minotaur)** - **MINOTAUR: Modélisation réduite de turboréacteurs à faible taux de dilution**<br />
  Cadre numérique déterministe pour moteurs compacts en régime subsonique contraint
- **[mc-quantileshield](https://github.com/QuantGenAIPhr34kW1z/mc-quantileshield)** - **MC-QuantileShield: Estimation de seuils statistiques**<br />
  Méthodes d'estimation basées sur le bootstrap
- **[mc-driftwatch](https://github.com/QuantGenAIPhr34kW1z/mc-driftwatch)** - **MC-DriftWatch: Détection de ruptures de distribution dans des séries temporelles**<br />
  Approche Monte Carlo par bootstrap en blocs
- **[curvtime-mpi](https://github.com/QuantGenAIPhr34kW1z/curvtime-mpi)** - **Corrections relativistes d'horloges**<br />
  Cadre de calcul en champ faible pour effets relativistes gravitationnels
- **[csv-r2s](https://github.com/QuantGenAIPhr34kW1z/csv-r2s)** - **Détection d'anomalies haute performance pour télémétries hostiles**<br />
  Pipelines d'analyse pour données adversariales ou dégradées

### Blockchain et systèmes cryptographiques

- **[beamrift](https://github.com/QuantGenAIPhr34kW1z/beamrift)** - **Blockchain post-quantique à haut débit**<br />
  Architecture multi-chaînes visant un débit élevé, une disponibilité continue et une résilience post-quantique
- **[orb-ledger](https://github.com/QuantGenAIPhr34kW1z/orb-ledger)** - **Registre distribué à consensus orbital (LEO)**<br />
  Registre distribué utilisant les fenêtres de contact en orbite basse comme époques de consensus, ancrées dans une mécanique orbitale déterministe
- **[tonkey](https://github.com/QuantGenAIPhr34kW1z/tonkey)** - **Passerelle Blockchain TON**<br />
  Infrastructure sécurisée de passerelle pour les systèmes basés sur TON
- **[zk-guard](https://github.com/QuantGenAIPhr34kW1z/zk-guard)** - **Moteur de politiques Zero-Knowledge et TEE**<br />
  Exécution et vérification de politiques combinant preuves à divulgation nulle de connaissance et environnements d'exécution de confiance (TEE)

### Compilateurs et langages

- **[obx07](https://github.com/QuantGenAIPhr34kW1z/obx07)** - **Compilateur Oberon-07 (Rust / LLVM)**<br />
  Compilateur minimal et auditable générant du code intermédiaire LLVM
- **[luax](https://github.com/QuantGenAIPhr34kW1z/luax)** - **Luax**<br />
  Compilateur complet et optimisant pour le langage Lua.
- **[vella](https://github.com/QuantGenAIPhr34kW1z/vella)** - **Langage fonctionnel minimal**<br />
  Petit langage fonctionnel doté d'un cœur de compilation robuste

### Outillage

- **[fcmesh](https://github.com/QuantGenAIPhr34kW1z/fcmesh)** - **Plateforme serverless minimaliste**<br />
  Environnement serverless compact basé sur des microVM Firecracker

(Voir le profil GitHub pour les développements publics actifs)

---

## Intérêts de recherche et perspectives de valorisation

J'explore ponctuellement des travaux de recherche et des prototypes de systèmes présentant un potentiel de valorisation, notamment dans les domaines suivants :

- systèmes d'IA, incluant l'entraînement, l'évaluation et les architectures d'inférence de modèles LLM
- ingénierie en cybersécurité, méthodologies de type red team et audits de sécurité
- architectures blockchain, protocoles décentralisés et systèmes cryptoéconomiques
- sécurité appliquée, cryptographie et durcissement des systèmes
- plateformes de données, traitement Big Data et pipelines haute performance
- infrastructures distribuées et systèmes à grande échelle

Les échanges exploratoires sont bienvenus

---

## Soutien

Si ces travaux vous font gagner du temps ou contribuent à vos projets, voir les options de soutien :
[Soutien](/fr/support)

![](https://komarev.com/ghpvc/?username=QuantGenAIPhr34kW1z&color=grey&label=FR%20Profile&base=1100)

  </main>

</div>
