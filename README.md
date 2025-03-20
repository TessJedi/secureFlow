# secureFlow
Déploiement d'une application web sécurisée avec intégration continue de tests de sécurité automatisés, en utilisant des conteneurs Docker et des outils open source.

## File structure

secureFlow/
│
├── src/                    # Code source de l'application
│   ├── app/
│   ├── config/
│   └── utils/
│
├── tests/                  # Tests automatisés
│   ├── unit/
│   ├── integration/
│   └── security/
│
├── docs/                   # Documentation du projet
│   ├── architecture/
│   ├── security/
│   └── api/
│
├── scripts/                # Scripts d'automatisation
│   ├── ci/
│   ├── deployment/
│   └── security/
│
├── config/                 # Fichiers de configuration
│   ├── dev/
│   ├── prod/
│   └── security/
│
├── tools/                  # Outils et utilitaires
│   ├── linters/
│   ├── scanners/
│   └── analyzers/
│
├── Jenkinsfile         # Configuration CI/CD
├── Dockerfile              # Configuration Docker
├── docker-compose.yml      # Configuration Docker Compose
├── README.md               # Documentation principale
└── .gitignore              # Fichiers à ignorer par Git

## TO DO