# Patch français du format alternatif VAACT

Traduction française approximative du [format alternatif Yu-Gi-Oh VAACT](https://github.com/Mazorn/VAACT-Very-Accurate-Anime-Character-Tournament-)

Basé sur la version A1.0.6 du format VAACT

[Comparateur des cartes version originale/version traduite](https://kevinraphael95.github.io/vaact_verif_traduction/)

# Installation

ProjectIgnis/config/user_configs.json

```
{

	"repos": [
		{
		"url": "https://github.com/Team13fr/IgnisMulti",
		"repo_name": "Team13.fr Multilanguage updates",
		"repo_path": "./config/languages",
		"is_language": true,
		"language": "",
		"data_path": "",
		"should_update": true,
		"should_read": true
		},
		{
		"url": "https://github.com/Mazorn/VAACT-Very-Accurate-Anime-Character-Tournament-",
		"repo_name": "VAACT",
		"repo_path": "./expansions/VAACT",
		"is_language": false,
		"language": "",
		"data_path": "",
		"should_update": true,
		"should_read": true
		},
		{
		"url": "https://github.com/Mazorn/VAACT-Very-Accurate-Anime-Character-Tournament-Deck",
		"repo_name": "VAACT-Deck",
		"repo_path": "./deck/VAACT",
		"is_language": false,
		"language": "",
		"data_path": "",
		"should_update": true,
		"should_read": true
		},
		{
		"url": "https://github.com/kevinraphael95/VAACT-patch-fr",
		"repo_name": "VAACT FR",
		"repo_path": "./config/languages/Français",
		"is_language": true,
		"language": "Français",
		"data_path": "",
		"should_update": true,
		"should_read": true
		}
	],

	"urls": [
	],
    	"servers": [
  			{
			"name": "VAACT",
			"address": "146.59.225.202",
			"duelport": 7911,
			"roomaddress": "146.59.225.202",
			"roomlistprotocol": "http",
			"roomlistport": 7922
		}
	]
}
```
