# QPEC QGIS Plugin

![QGIS Minimum Version](https://img.shields.io/badge/QGIS->=3.0-blue)
![License](https://img.shields.io/badge/License-GPLv2-green)

**QPEC** is a QGIS plugin designed to perform Positional Accuracy Assessment based on the PEC PCD (Padrão de Exatidão Cartográfica para produtos Cartográficos Digitais).

## About

This plugin performs the Planimetric and Altimetric Positional Accuracy Assessment of point features using the method from the **ET-CQDG** (Especificação Técnica para Controle de Qualidade de Dados Geoespaciais), created in 2016 by the DSG (Diretoria do Serviço Geográfico). The evaluation is done considering the PEC PCD.

## Features

- **Planimetric Positional Accuracy Assessment**
- **Altimetric Positional Accuracy Assessment**
- Conforms to **ET-CQDG** standards
- Integrates directly into QGIS as an analysis tool

## Installation

1. Clone or download this repository.
2. Place the `QPEC` directory into your QGIS plugins folder:
   - **Windows:** `C:\Users\YOUR_USERNAME\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins`
   - **Linux:** `~/.local/share/QGIS/QGIS3/profiles/default/python/plugins`
   - **macOS:** `~/Library/Application Support/QGIS/QGIS3/profiles/default/python/plugins`
3. Open QGIS.
4. Go to `Plugins -> Manage and Install Plugins...`
5. Find **QPEC** in the "Installed" tab and check the box to enable it.

## Author

**Elias Nasr Naim Elias**
📧 [elias_naim2008@hotmail.com](mailto:elias_naim2008@hotmail.com)

## Repository and Issue Tracking

- **Repository:** [https://github.com/eliasnaim/Thesis_Scripts_PositionalAccuracy](https://github.com/eliasnaim/Thesis_Scripts_PositionalAccuracy)
- **Bug Tracker:** [http://bugs](http://bugs)

## License

This project is licensed under the **GNU General Public License v2 (GPLv2)**. See the `LICENSE` file for more details.
