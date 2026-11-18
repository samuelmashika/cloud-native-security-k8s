# Sécurité des architectures Cloud Native

Projet de Master 1 Sécurité des Systèmes d'Informations (ESMT, année académique 2025-2026).
Enseignant : M. Doudou FAYE.

## Sujet

Isolation multi-tenant et protection de la chaîne d'approvisionnement des conteneurs (K8s) intégrés à l'hyperviseur.

Le travail étudie et met en œuvre des mécanismes permettant de limiter les interactions non autorisées entre tenants, de contrôler l'utilisation des ressources et de renforcer la sécurité des images de conteneurs.

## Outils

- **Kubernetes** (distribution légère **K3s**)
- **Trivy** : analyse des vulnérabilités
- **Syft** : génération de SBOM
- **Cosign** : signature et vérification des images
- **Kyverno** : contrôle d'admission des déploiements

## Structure du dépôt

```
.
├── docs/        Rapport du projet (PDF)
├── captures/    Captures d'écran des essais et des configurations
└── README.md
```

## Plan du rapport

- **Résumé**
- **Chapitre 1** : Sécurité des architectures Cloud Native (virtualisation, conteneurs, K3s, isolation multi-tenant, chaîne d'approvisionnement)
- **Chapitre 2** : Architecture de la solution (objectifs, technologies, architecture, modèle de menace)
- **Chapitre 3** : Mise en place de l'environnement expérimental
- **Chapitre 4** : Mise en œuvre de l'isolation multi-tenant
- **Chapitre 5** : Sécurisation de la chaîne d'approvisionnement des conteneurs
- **Chapitre 6** : Tests de sécurité, remédiation et validation
- **Chapitre 7** : Analyse critique et recommandations
- **Conclusion générale**
- **Annexes** A à G (environnement technique, configuration du cluster, politiques réseau, analyse des images et SBOM, registre local et signature, contrôle d'admission Kyverno, commandes de vérification)
