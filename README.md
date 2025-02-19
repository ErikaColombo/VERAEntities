# VERA Entities

This version of VERA allow to performe a read-across analysis in two different ways:
1. VERA Alerts, as described in the papers [1](https://doi.org/10.1016/j.chemosphere.2024.142232) ,[2](https://doi.org/10.3390/molecules27196605). VERA Alerts assess similarity between chemicals using structural alerts specific to the property, pre-defined molecular groups and structural similarity.
2. VERA Entities. Starting with a unsupervised analysis, VERA Entities analysed several chemical, biotic and abiotic properties indipendently from the endpoint and used this *entities* to provide the assessment. The publication is ongoing.


## How the VERA Entities and Alerts GUI work

You can download the new version of VERA [here](https://edoardovigano.itch.io/virtual-extensive-read-across-vera-entities). The VERA GUI is a stand-alone application, it is not necessary to install the software.

1. Extract the .zip folder

2. Open the .exe file by double-clicking it. A CMD window will also open, which can be used to monitor the VERA process in detail.

3. In a few seconds, the VERA GUI will open. Click on the _Load File_ button in the top left corner of the application to upload an .xlsx file containing the SMILES of the molecule you want to assess with VERA. The SMILES list should be in the first column of the .xlsx file. If you have other indentifiers, you can use the [Chemical Resolver application](https://github.com/EdoardoVigano/Chemical-Resolver) to search for SMILES.
By double-clicking on a SMILES entry, the structure will be displayed, allowing you to analyze one molecule at a time.

<p align="center">
  <img width="622" height="427" src="IMG_VERA/Figure2.png">
</p>

4. Then, you can select the Endpoint to be evaluated and the type of output, an excel document with all prediction and/or the PDF report for each molecule with all detailed information on how VERA make the assessment.

<p align="center">
  <img width="622" height="427" src="IMG_VERA/Figure1.png">
</p>

5. By clicking on _START CALCULATION_, the GUI will prompt you to choose a folder to save the output files. It will automatically create a _results_ folder within the selected directory to store all reports. If an output folder already exists, VERA will automatically date the output folders.
6. Then, the read-across process will start. In the Log window, you can check the current step of the algorithm, and the progress bar will indicate the percentage of molecules processed. At the end of the calculation, a window will confirm that VERA has completed the assessment of all provided substances and that the results are available in the selected folder.
7. Before process other chemicals, click on _Clean Work_.

## Contacts

Edoardo Luca Viganò - Laboratory of Environmental Chemistry and Toxicology - Department of Environmental Health Sciences - Istituto di Ricerche Farmacologiche Mario Negri IRCCS - Via Mario Negri 2, 20156 Milano, Italy - e-mail: edoardo.vigano@marionegri.it

Erika Colombo - Laboratory of Environmental Chemistry and Toxicology - Department of Environmental Health Sciences - Istituto di Ricerche Farmacologiche Mario Negri IRCCS - Via Mario Negri 2, 20156 Milano, Italy -e-mail: erika.colombo@marionegri.it
