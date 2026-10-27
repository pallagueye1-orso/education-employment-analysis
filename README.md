# Éducation et emploi : analyse des données ILO

Projet du M1 BIDABI (Sorbonne Paris Nord).
Il étudie le lien entre le niveau d'éducation, l'emploi et le chômage selon les pays, à partir de données de l'Organisation internationale du travail (ILO).

## Données
- `data/raw/` : fichiers ILO d'origine (emploi et chômage par sexe et niveau d'éducation)
- `data/clean/` : fichiers nettoyés (`emploi_clean.csv`, `chomage_clean.csv`)

## Contenu
- `notebooks/` : 01 nettoyage, 02 exploration, 03 analyses, 04 visualisations, 05 visualisations surprenantes, 06 conclusion, plus la figure 17
- `figures/` : 17 graphiques produits par les notebooks

## Lancer le projet
```bash
pip install -r requirements/requirements.txt
```
Lancer Jupyter depuis le dossier `notebooks/`, puis ouvrir les notebooks dans l'ordre.

## Outils
Python : pandas, numpy, matplotlib, seaborn, geopandas, Jupyter

## Équipe
- Palla Gueye : notebooks (nettoyage, analyses, visualisations)
- Karissy Zeinab Cisse : rédaction, présentation (pptx) et rapport
