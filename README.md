# VERA Entities

This version of VERA allow to performe a read-across analysis in two different ways:
1. VERA Alerts, as described in the papers [1](https://doi.org/10.1016/j.chemosphere.2024.142232) ,[2](https://doi.org/10.3390/molecules27196605). VERA Alerts assess similarity between chemicals using structural alerts specific to the property, pre-defined molecular groups and structural similarity.
2. VERA Entities. Starting with a unsupervised analysis, VERA Entities analysed several chemical, biotic and abiotic properties indipendently from the endpoint and used this *entities* to provide the assessment.


## How the VERA Entities and Alerts GUI work

You can download the new version of VERA [here](https://edoardovigano.itch.io/virtual-extensive-read-across-vera-entities). The VERA GUI is a stand-alone application, it is not necessary to install the software.

1. Extract the .zip folder

2. Open the .exe file application doubled clicking. It will be open also a cmd window, it could be used to monitoring the VERA process in a detailed way. Open the .exe file by double-clicking it. A CMD window will also open, which can be used to monitor the VERA process in detail.

3. In a few seconds, the VERA GUI will open. Click on the _Load File_ button in the bottom left corner of the application to upload an .xlsx file containing the SMILES of the molecule you want to assess with VERA. The SMILES list should be in the first column of the .xlsx file. If you have other indentifiers, you can use the [Chemical Resolver application](https://github.com/EdoardoVigano/Chemical-Resolver) to search for SMILES.
By double-clicking on a SMILES entry, the structure will be displayed, allowing you to analyze one molecule at a time.

<p align="center">
  <img width="622" height="427" src="IMG_VERA/Figure2.png">
</p>

4. Then, you can select the Edpoint to be evaluated and the type of output, an excel document with all prediction and/or the PDF report for each molecule with all detailed information on how VERA make the assessment.

<p align="center">
  <img width="622" height="427" src="IMG_VERA/Figure1.png">
</p>

5. hhh

