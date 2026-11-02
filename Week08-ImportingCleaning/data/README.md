# Data for Session 8

Downloaded on 2 November 2026. Files are unmodified copies, renamed for readability.

| File | Source |
|---|---|
| `resultats_t1_departements_2022.txt`, `.xlsx` | Ministère de l'Intérieur: [Résultats définitifs du 1er tour, présidentielle 2022](https://www.data.gouv.fr/datasets/election-presidentielle-des-10-et-24-avril-2022-resultats-definitifs-du-1er-tour/) |
| `elus_maires_2026.csv`, `elus_deputes_2026.csv` | Ministère de l'Intérieur: [Répertoire national des élus](https://www.data.gouv.fr/datasets/repertoire-national-des-elus-1/) (files dated 11 August 2026) |
| `wb_women_parliament.csv`, `wb_country_metadata.csv` | World Bank: [Proportion of seats held by women in national parliaments](https://data.worldbank.org/indicator/SG.GEN.PARL.ZS) (last updated 8 October 2026) |
| `departements.json` | [geo.api.gouv.fr](https://geo.api.gouv.fr/departements?fields=nom,code,codeRegion) |

The Répertoire national des élus contains names and birth dates of elected officials. The notebook drops names on import and never prints individuals.
