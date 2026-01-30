![CC-BY-NC-ND_horizontal](https://github.com/user-attachments/assets/4e025c28-ae4c-4015-a7be-d5b4304db88a)# RANAS Analyser
<sup>_([Version française ci-dessous](#ranas-analyser-fr))_</sup>

RANAS Analyser is a tool that performs a doer / non-doer analysis of a RANAS quantitative survey, which is used in the assessment phase of a behaviour change campaign based on the [RANAS methodology](https://ranas.ch). It computes the difference in behavioural factors – called RANAS factors – between "doers" and "non-doers" of a predefined behaviour. This allows the identification of the most important factors that influence the target behaviour, so that these factors can be addressed with tailored activities during the implementation phase of the campaign.

## Excel 365 or Legacy version
The tool is an Excel file (VBA-free, i.e., no macros) and comes in two different versions, depending on the Excel version that you are running:
- The **Excel 365** version uses modern Excel functions and requires a recent version of Excel (Excel 365, Excel 2024).
- The **Legacy** version should be compatible with previous versions of Excel at least back to 2013.

Currently, both the Excel 365 version and the Legacy version have the same functionalities. The user-interface language can be set to English or French, and custom languages can be added to display in the charts and tables.

## Download
To download the most recent version of the tool, navigate to the corresponding directory ([Excel_365_version](Excel_365_version) or [Legacy_version](Legacy_version)). Two files are available:
- The "normal" file is a blank version in which you import your dataset and then configure accordingly to perform your analysis.
- The "demo version" file contains an example dataset and a "Demo" sheet that illustrates how the tool must be used.

Click on the name of the file that you want to download, then click on the "Download raw file" button (![GitHub-download-button](https://github.com/user-attachments/assets/bb09f900-8fff-49d2-ad19-0ba44d17ac96)) and save the file to your computer. The RANAS Analyser should be opened with the desktop version of Excel, because some features are not compatible with Excel Online.

Additionally, a "Previous versions" subfolder contains previous releases of the tool. The main changes made in each release are documented in the [release notes](release_notes.md).

The RANAS Analyser is meant to be a self-contained tool, with detailed instructions on each sheet on how to use it. <ins>**Be sure to read them!**</ins>
# Credentials
This project was developed by [RANAS Ltd.](https://ranas.ch), [Terre des hommes](https://www.tdh.org) (Tdh) and the [Swiss Water & Sanitation Consortium](https://) (SWSC).
It was co-funded by SWSC and the Swiss Agency for Development and Cooperation (SDC).
The ideas and opinions presented in this document do not necessarily represent those of the aforementioned co-funding agencies.

# License
![Uploadi<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<!-- Created with Inkscape (http://www.inkscape.org/) -->

<svg
   width="80.345032mm"
   height="16.933336mm"
   viewBox="0 0 80.345032 16.933336"
   version="1.1"
   id="svg1"
   xml:space="preserve"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:svg="http://www.w3.org/2000/svg"><defs
     id="defs1" /><g
     id="layer1"
     transform="translate(-24.834306,-138.26186)"><g
       id="g1"
       transform="matrix(0.26458333,0,0,0.26458333,23.379099,139.18788)">
	<circle
   fill="#ffffff"
   cx="37.785"
   cy="28.500999"
   r="28.836"
   id="circle1" />
	<path
   d="m 37.441,-3.5 c 8.951,0 16.572,3.125 22.857,9.372 3.008,3.009 5.295,6.448 6.857,10.314 1.561,3.867 2.344,7.971 2.344,12.314 0,4.381 -0.773,8.486 -2.314,12.313 -1.543,3.828 -3.82,7.21 -6.828,10.143 -3.123,3.085 -6.666,5.448 -10.629,7.086 -3.961,1.638 -8.057,2.457 -12.285,2.457 -4.228,0 -8.276,-0.808 -12.143,-2.429 C 21.434,56.452 17.967,54.109 14.9,51.043 11.833,47.977 9.5,44.519 7.9,40.671 6.3,36.823 5.5,32.767 5.5,28.5 5.5,24.271 6.309,20.205 7.928,16.3 9.547,12.395 11.9,8.9 14.985,5.814 21.08,-0.394 28.565,-3.5 37.441,-3.5 Z m 0.116,5.772 c -7.314,0 -13.467,2.553 -18.458,7.657 -2.515,2.553 -4.448,5.419 -5.8,8.6 -1.354,3.181 -2.029,6.505 -2.029,9.972 0,3.429 0.675,6.734 2.029,9.913 1.353,3.183 3.285,6.021 5.8,8.516 2.514,2.496 5.351,4.399 8.515,5.715 3.161,1.314 6.476,1.971 9.943,1.971 3.428,0 6.75,-0.665 9.973,-1.999 3.219,-1.335 6.121,-3.257 8.713,-5.771 4.99,-4.876 7.484,-10.99 7.484,-18.344 0,-3.543 -0.648,-6.895 -1.943,-10.057 C 60.491,15.283 58.604,12.465 56.13,9.987 50.984,4.844 44.795,2.272 37.557,2.272 Z m -0.401,20.915 -4.287,2.229 c -0.458,-0.951 -1.019,-1.619 -1.685,-2 -0.667,-0.38 -1.286,-0.571 -1.858,-0.571 -2.856,0 -4.286,1.885 -4.286,5.657 0,1.714 0.362,3.084 1.085,4.113 0.724,1.029 1.791,1.544 3.201,1.544 1.867,0 3.181,-0.915 3.944,-2.743 l 3.942,2 c -0.838,1.563 -2,2.791 -3.486,3.686 -1.484,0.896 -3.123,1.343 -4.914,1.343 -2.857,0 -5.163,-0.875 -6.915,-2.629 -1.752,-1.752 -2.628,-4.19 -2.628,-7.313 0,-3.048 0.886,-5.466 2.657,-7.257 1.771,-1.79 4.009,-2.686 6.715,-2.686 3.963,-0.002 6.8,1.541 8.515,4.627 z m 18.457,0 -4.229,2.229 c -0.457,-0.951 -1.02,-1.619 -1.686,-2 -0.668,-0.38 -1.307,-0.571 -1.914,-0.571 -2.857,0 -4.287,1.885 -4.287,5.657 0,1.714 0.363,3.084 1.086,4.113 0.723,1.029 1.789,1.544 3.201,1.544 1.865,0 3.18,-0.915 3.941,-2.743 l 4,2 c -0.875,1.563 -2.057,2.791 -3.541,3.686 -1.486,0.896 -3.105,1.343 -4.857,1.343 -2.896,0 -5.209,-0.875 -6.941,-2.629 -1.736,-1.752 -2.602,-4.19 -2.602,-7.313 0,-3.048 0.885,-5.466 2.658,-7.257 1.77,-1.79 4.008,-2.686 6.713,-2.686 3.962,-0.002 6.783,1.541 8.458,4.627 z"
   id="path1" />
</g><g
       id="g2"
       transform="matrix(0.26458333,0,0,0.26458333,44.457464,139.18788)">
	<circle
   fill="#ffffff"
   cx="37.637001"
   cy="28.806"
   r="28.275999"
   id="circle1-4" />
	<g
   id="g1-8">
		<path
   d="m 37.443,-3.5 c 8.988,0 16.57,3.085 22.742,9.257 6.208,6.21 9.315,13.791 9.315,22.743 0,8.991 -3.049,16.476 -9.145,22.456 C 53.879,57.319 46.242,60.5 37.443,60.5 28.794,60.5 21.29,57.356 14.929,51.07 8.644,44.784 5.5,37.262 5.5,28.5 5.5,19.739 8.644,12.158 14.929,5.758 21.101,-0.415 28.604,-3.5 37.443,-3.5 Z m 0.114,5.772 c -7.276,0 -13.428,2.553 -18.457,7.657 -5.22,5.334 -7.829,11.525 -7.829,18.572 0,7.086 2.59,13.22 7.77,18.398 5.181,5.182 11.352,7.771 18.514,7.771 7.123,0 13.334,-2.607 18.629,-7.828 5.029,-4.838 7.543,-10.952 7.543,-18.343 0,-7.276 -2.553,-13.465 -7.656,-18.571 C 50.967,4.824 44.795,2.272 37.557,2.272 Z m 8.572,18.285 V 33.642 H 42.473 V 49.184 H 32.529 V 33.643 H 28.873 V 20.557 c 0,-0.572 0.2,-1.057 0.599,-1.457 0.401,-0.399 0.887,-0.6 1.457,-0.6 h 13.144 c 0.533,0 1.01,0.2 1.428,0.6 0.417,0.4 0.628,0.886 0.628,1.457 z M 33.042,12.329 c 0,-3.008 1.485,-4.514 4.458,-4.514 2.973,0 4.457,1.504 4.457,4.514 0,2.971 -1.486,4.457 -4.457,4.457 -2.971,0 -4.458,-1.486 -4.458,-4.457 z"
   id="path1-8" />
	</g>
</g><g
       id="g2-2"
       transform="matrix(0.26458333,0,0,0.26458333,65.712435,139.18788)">
	<circle
   fill="#ffffff"
   cx="37.470001"
   cy="28.736"
   r="29.471001"
   id="circle1-45" />
	<g
   id="g1-5">
		<path
   d="m 37.442,-3.5 c 8.99,0 16.571,3.085 22.743,9.256 6.208,6.172 9.315,13.753 9.315,22.744 0,8.992 -3.048,16.476 -9.145,22.458 C 53.88,57.32 46.241,60.5 37.442,60.5 28.756,60.5 21.252,57.338 14.929,51.015 8.644,44.728 5.5,37.225 5.5,28.5 5.5,19.738 8.644,12.157 14.929,5.757 21.1,-0.414 28.604,-3.5 37.442,-3.5 Z M 12.7,19.872 c -0.952,2.628 -1.429,5.505 -1.429,8.629 0,7.086 2.59,13.22 7.77,18.4 5.219,5.144 11.391,7.715 18.514,7.715 7.201,0 13.409,-2.608 18.63,-7.829 1.867,-1.79 3.332,-3.657 4.398,-5.602 L 48.527,35.814 c -0.421,2.02 -1.439,3.667 -3.057,4.942 -1.622,1.276 -3.535,2.011 -5.744,2.2 v 4.915 H 36.012 V 42.956 C 32.469,42.92 29.23,41.644 26.298,39.129 l 4.4,-4.457 c 2.094,1.942 4.476,2.913 7.143,2.913 1.104,0 2.048,-0.246 2.83,-0.743 0.78,-0.494 1.172,-1.312 1.172,-2.457 0,-0.801 -0.287,-1.448 -0.858,-1.943 L 37.9,31.127 34.129,29.412 29.043,27.183 Z M 37.557,2.214 c -7.276,0 -13.428,2.571 -18.457,7.714 -1.258,1.258 -2.439,2.686 -3.543,4.287 L 27.786,19.7 c 0.533,-1.676 1.542,-3.019 3.029,-4.028 1.484,-1.009 3.218,-1.571 5.2,-1.686 V 9.071 h 3.715 v 4.915 c 2.934,0.153 5.6,1.143 8,2.971 l -4.172,4.286 c -1.793,-1.257 -3.619,-1.885 -5.486,-1.885 -0.991,0 -1.876,0.191 -2.656,0.571 -0.781,0.381 -1.172,1.029 -1.172,1.943 0,0.267 0.095,0.533 0.285,0.8 l 4.057,1.83 2.8,1.257 5.144,2.285 16.397,7.314 c 0.535,-2.248 0.801,-4.533 0.801,-6.857 0,-7.353 -2.552,-13.543 -7.656,-18.573 C 51.005,4.785 44.831,2.214 37.557,2.214 Z"
   id="path1-1" />
	</g>
</g><g
       id="g2-7"
       transform="matrix(0.26458333,0,0,0.26458333,88.24575,138.26184)">
	<circle
   fill="#ffffff"
   cx="32.064453"
   cy="31.788086"
   r="29.012695"
   id="circle1-1" />
	<g
   id="g1-1">
		<path
   d="M 31.943848,0 C 40.896484,0 48.476562,3.105469 54.6875,9.314453 60.894531,15.486328 64.000977,23.045898 64.000977,32 c 0,8.954102 -3.048828,16.457031 -9.145508,22.513672 C 48.417969,60.837891 40.779297,64 31.942871,64 23.293945,64 15.790039,60.857422 9.429199,54.570312 3.144043,48.286133 0,40.761719 0,32.000977 0,23.277344 3.144043,15.715821 9.429199,9.316407 15.640137,3.105469 23.14502,0 31.943848,0 Z m 0.116699,5.771484 c -7.275391,0 -13.429688,2.570312 -18.458496,7.714844 C 8.381836,18.783203 5.772949,24.954102 5.772949,32 c 0,7.125 2.589844,13.256836 7.77002,18.400391 5.181152,5.181641 11.352051,7.770508 18.515625,7.770508 7.123047,0 13.332031,-2.608398 18.626953,-7.828125 C 55.713867,45.466797 58.228516,39.353516 58.228516,32 c 0,-7.3125 -2.553711,-13.484375 -7.65625,-18.513672 C 45.504883,8.341797 39.333984,5.771484 32.060547,5.771484 Z m 12.056641,18.684571 v 5.485352 H 20.859863 v -5.485352 z m 0,10.287109 v 5.481445 H 20.859863 v -5.481445 z"
   id="path1-5" />
	</g>
</g></g></svg>
ng CC-BY-NC-ND_horizontal.svg…]()

This work is licensed under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY­NC­ND 4.0).

To view a copy of this license, visit: 
https://creativecommons.org/licenses/by-nc-nd/4.0/
</br>
</br>

# RANAS Analyser (FR)
<sup>_(Version française)_</sup>

RANAS Analyser est un outil permettant de faire l'analyse pratiquant / non-pratiquant d'une enquête quantitative RANAS, qui est utilisée lors de la phase d'évaluation d'une campagne de changement de comportement basée sur la [méthodologie RANAS](https://ranas.ch). Il calcule la différence des facteurs comportementaux – appelés facteurs RANAS – entre les «pratiquants» et les «non-pratiquants» d'un comportement prédéfini. Cela permet d'identifier les facteurs les plus importants qui influencent le comportement visé, afin que ces facteurs puissent être ciblés par des activités sur mesure au cours de la phase de mise en œuvre de la campagne.

## Version Excel 365 ou Legacy
L'outil est un fichier Excel (sans VBA, c-à-d sans macros) disponible en deux versions différentes, selon la version d'Excel que vous utilisez:
- La version **Excel 365** utilise des fonctions Excel modernes et nécessite une version récente d'Excel (Excel 365, Excel 2024).
- La version **Legacy** devrait être compatible avec les versions précédentes d'Excel remontant au moins jusqu'à 2013.

À ce jour, les versions Excel 365 et Legacy comportent les mêmes fonctionnalités. La langue de l'interface peut-être choisie entre l'anglais et le français, et des langues supplémentaires peuvent être définies pour l'affichage des graphiques et tableaux.

## Téléchargement
Pour télécharger la dernière version de l'outil, allez dans le dossier correspondant ([Excel_365_version](Excel_365_version) ou [Legacy_version](Legacy_version)). Deux fichiers sont disponbiles:
- Le fichier «normal» est une version vierge dans laquelle vous importez votre jeu de données, puis que vous configurez en conséquence pour faire votre analyse.
- Le fichier «demo version» contient un exemple de jeu de données et une feuille «Demo» qui illustre comment utiliser l'outil.

Cliquez sur le nom du fichier que vous souhaitez télécharger, puis sur le bouton «Download raw file» (![GitHub-download-button](https://github.com/user-attachments/assets/bb09f900-8fff-49d2-ad19-0ba44d17ac96)) et enregistrez le fichier sur votre ordinateur. Le RANAS Analyser devrait être ouvert avec la version bureau d'Excel, car certaines fonctionnalités ne sont pas compatibles avec Excel Online.

De plus, un sous-dossier «Previous versions» contient les versions précédentes de l'outil. Les principales modifications apportées à chaque version sont documentées dans les [notes de mise à jour](release_notes.md) (uniquement en anglais).

RANAS Analyser est conçu pour être un outil autonome, avec des instructions d'utilisation détaillées sur chaque feuille. <ins>**Veillez à les lire attentivement!**</ins>
