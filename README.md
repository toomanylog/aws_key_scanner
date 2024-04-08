# AWS Key Scanner

## Description

AWS Key Scanner est un outil de sécurité conçu pour détecter les clés AWS exposées sur les sites web. Il utilise plusieurs techniques pour analyser les pages web et détecter les clés AWS sensibles.

## Installation

Pour installer AWS Key Scanner, vous aurez besoin de Python 3.x et de quelques bibliothèques supplémentaires. Vous pouvez installer les dépendances en utilisant pip :
```
pip install -r requirements.txt
```
## Utilisation

Pour utiliser AWS Key Scanner, vous devez fournir une liste d'URL ou d'adresses IP à analyser. Vous pouvez le faire en créant un fichier texte avec une URL ou une adresse IP par ligne. Ensuite, exécutez le script en utilisant la commande suivante :
```css
python aws_key_scanner.py -i input_file.txt -t 10 -e
```
Ici, `input_file.txt` est le fichier contenant la liste d'URL ou d'adresses IP à analyser, `10` est le nombre maximum de threads à utiliser pour l'analyse, et `-e` est un drapeau pour exporter les résultats dans un fichier JSON.

## Remarques

* AWS Key Scanner est conçu pour être utilisé à des fins de test de sécurité uniquement.
* L'utilisation de cet outil sans autorisation explicite peut être illégale et entraîner des poursuites judiciaires.
* L'utilisation de cet outil peut entraîner des faux positifs et des résultats inexacts.
* Cet outil ne doit être utilisé que par des professionnels de la sécurité expérimentés.

## License

AWS Key Scanner est publié sous la licence MIT. Voir le fichier LICENSE pour plus de détails.

---

# AWS Key Scanner

## Description

AWS Key Scanner is a security tool designed to detect exposed AWS keys on websites. It uses several techniques to analyze web pages and detect sensitive AWS keys.

## Installation

To install AWS Key Scanner, you will need Python 3.x and a few additional libraries. You can install the dependencies using pip:
```
pip install -r requirements.txt
```
## Usage

To use AWS Key Scanner, you need to provide a list of URLs or IP addresses to scan. You can do this by creating a text file with one URL or IP address per line. Then run the script using the following command:
```css
python aws_key_scanner.py -i input_file.txt -t 10 -e
```
Here, `input_file.txt` is the file containing the list of URLs or IP addresses to scan, `10` is the maximum number of threads to use for scanning, and `-e` is a flag to export the results to a JSON file.

## Notes

* AWS Key Scanner is designed for security testing purposes only.
* Using this tool without explicit permission may be illegal and result in legal action.
* Using this tool may result in false positives and inaccurate results.
* This tool should only be used by experienced security professionals.

## License

AWS Key Scanner is released under the MIT license. See the LICENSE file for more details.
