

# OWASP Testing Checklist Generator for SwiftnessX

This script generates a JSON file based on the OWASP Testing Checklist Excel file. The generated JSON file can be used for integrating OWASP testing procedures into the SwiftnessX application.

## Prerequisites

1. Download the OWASP Testing Checklist Excel file:
   - [OWASP WSTG Checklist.xlsx](https://github.com/tanprathan/OWASP-Testing-Checklist/blob/master/OWASP_WSTG_Checklist.xlsx)

2. Install the necessary Python modules.

---

## Usage

### English

1. **Download the OWASP Testing Checklist Excel file:**
   - You can download it directly from the [OWASP Testing Checklist repository](https://github.com/tanprathan/OWASP-Testing-Checklist/blob/master/OWASP_WSTG_Checklist.xlsx).

2. **Install the required Python modules:**
   To install the required Python modules, run the following command:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the script:**
   Once the modules are installed, you can run the script by providing the Excel file as input. For example:
   ```bash
   python generate_checklist.py OWASP_WSTG_Checklist.xlsx
   ```

   You can also specify an output JSON file name:
   ```bash
   python generate_checklist.py OWASP_WSTG_Checklist.xlsx output_checklist.json
   ```

4. **Output:**
   The script will generate a JSON file (`owasp_checklist.json` by default) with the structured OWASP Testing Checklist data. This JSON can be used for further processing or integration with SwiftnessX.

### French

1. **Téléchargez le fichier Excel de la checklist OWASP :**
   - Vous pouvez le télécharger directement depuis le [dépôt OWASP Testing Checklist](https://github.com/tanprathan/OWASP-Testing-Checklist/blob/master/OWASP_WSTG_Checklist.xlsx).

2. **Installez les modules Python nécessaires :**
   Pour installer les modules Python requis, exécutez la commande suivante :
   ```bash
   pip install -r requirements.txt
   ```

3. **Exécutez le script :**
   Une fois les modules installés, vous pouvez exécuter le script en fournissant le fichier Excel en entrée. Par exemple :
   ```bash
   python generate_checklist.py OWASP_WSTG_Checklist.xlsx
   ```

   Vous pouvez également spécifier un nom de fichier JSON de sortie :
   ```bash
   python generate_checklist.py OWASP_WSTG_Checklist.xlsx output_checklist.json
   ```

4. **Sortie :**
   Le script générera un fichier JSON (`owasp_checklist.json` par défaut) avec les données structurées de la checklist OWASP. Ce fichier JSON peut être utilisé pour un traitement ultérieur ou pour l'intégration dans SwiftnessX.

---

## Files

- `generate_checklist.py`: The script that converts the OWASP Testing Checklist from Excel to JSON format.
- `requirements.txt`: Contains the necessary Python dependencies for the script.

---

## Python Modules Required

- `openpyxl`: Used for reading Excel files.
- `uuid`: Generates unique identifiers for each checklist item.

You can install the required dependencies using the command:
```bash
pip install openpyxl
```

---

Feel free to contribute to the repository if you have any improvements or bug fixes!

---
