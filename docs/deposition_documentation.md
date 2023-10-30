# Documentation for CMMC deposition workflow

This is a guide to upload your data about microbial metabolites to the collaborative microbial metabolite center knowledgebase (CMMC-kb).

## Important Links:
[GNPS2 website](https://gnps2.org/homepage)

[CMMC workflow](https://gnps2.org/workflowinput?workflowname=cmmc_deposition_workflow)

[CMMC knowledgebase](https://cmmc-kb.gnps2.org/)

## What is the CMMC knowledgebase?
Microbiome-derived metabolites are vital for human health and other ecosystems, but there is no central place where the community can store, share, and reuse this knowledge. Existing resources have limited information on microbial metabolites, their sources, genes and functions. To fill this gap, we created CMMC-kb, a knowledge base that integrates microbial information with the GNPS mass spectrometry platform and the community. CMMC-kb enables users to annotate and visualize both known and unknown microbial metabolites, and to explore and interpret their biological roles. CMMC-kb is a community-driven and constantly updated microbiome resource that allows users to link any microbial metabolite, known or unknown, with its source and bioactivity information. Moreover, the web interface and analysis tools provide benefits to both data contributors and other users.

## Requirements
1. A free GNPS2 account is required to contribute data and use the CMMC-kb to analyze data.
   - Please login at the [GNPS2 homepage](https://gnps2.org/homepage)
   
   PS: Currently, the sign-up option is not available, but if you would like to contribute, please send an email with the desired username to hmannochiorusso@health.ucsd.edu

2. CMMC-kb compliant microbial metabolite information.
   - Manual completion of CMMC-kb template file - [link here](https://tinyurl.com/frku9zys)
    
   - Upload CMMC-kb compliant microbial related metabolite information, using the single upload option or batch upload option using the template file - [link here](https://gnps2.org/workflowinput?workflowname=cmmc_deposition_workflow)

## Single upload of microbial metabolites
CMMC-kb provides a platform for users to contribute their own microbial metabolites to the center knowledgebase. There are several requirements for uploading your data, see Requirements.

### Detailed step-by-step instructions:
1. Sign-up or login to your GNPS2 account

2. Navigate to “Launch Workflows” and click on the “Launch Workflows” button

![img](docs/img/CMMC_deposition/Slide1.png)

3. This will show the list of available workflows on GNPS2. from this list, select the “_cmmc_deposition_workflow_” and click on _“Launch Workflow_” to start

![img](docs/img/CMMC_deposition/Slide2.png)

4. At the “_Job Description_” field you are free to fill in what you want (eg. name of metabolite you want to deposit). This description will only be visible for you and it will be the name under which the “_Task_” will be visible in your “_Tasks_” list. This field is not uploaded to CMMC-kb.

5. At the field of the “Workflow” you will select “_Single Upload_’.

![img](docs/img/CMMC_deposition/Slide3.png)
   
6. If you scroll down you will see all the different fields that will have to be filled out with information about the metabolite you want to deposit to the CMMC-kb. The only mandatory field to be filled out is the first one: “_MS/MS identifier_”. Each field is explained in detail below under section **“Step-by-step guideline Input Fields for CMMC-kb workflow**”. Please fill out as many fields as possible for the metabolite you want to deposit.

7. Once you have finished filling out the fields, you can click on the button “_Submit workflow_”. 

![img](docs/img/CMMC_deposition/Slide4.png)

8. The task will appear in the menu “Tasks” on the top of your screen:

![img](docs/img/CMMC_deposition/Slide5.png)

9. Once the upload is complete, the status of the workflow will change from “RUNNING” to “DONE”. If the status is showing “FAILED”, please consult the FAQ section for possible solutions.

## Batch upload of microbial metabolites
Although there's an option to upload individual microbial metabolites, users seeking a more efficient approach can utilize our batch upload feature. This method allows for the simultaneous submission of multiple microbial metabolites to CMMC-kb.

### Detailed step-by-step instructions:
1. Sign-up or login to your GNPS2 account
2. CMMC-kb compliant microbial metabolite information
   - Navigate to the CMMC-kb metabolite information [template](https://tinyurl.com/frku9zys)

The template has the following format:

![img](docs/img/CMMC_deposition/Slide6.png)

3. Download the spreadsheet as tab-separated values (.tsv).
   - Save a copy of the CMMC-kb metabolite information template by going to "File - Make a copy" into a personal google drive or save a local copy to your computer (use the .tsv format or tab-delimited .txt file). 

![img](docs/img/CMMC_deposition/Slide7.png)

4. Fill in metabolite information in the respective fields or by using the drop-down menus when applicable for each microbiome related metabolite you want to upload.

5. Go to the [CMMC deposition workflow](https://gnps2.org/workflowinput?workflowname=cmmc_deposition_workflow)

6. Enter the Job description. This is just for personal tracking of the Job and is not going to be deposited in the CMMC-kb (for example: give the name of the class of metabolites you are uploading).

   -> Select **Batch Upload**

![img](docs/img/CMMC_deposition/Slide8.png)

7. Upload your .tsv file to your online environment in GNPS2:
   - Select the menu "File Browser" on the top right

![img](docs/img/CMMC_deposition/Slide9.png)

   - Another browser window will open where you will be able to see and organize your files. You can create a new folder (for example: “_CMMC_” and then select "Upload" (red arrow) at the top right. Select your file .tsv file.

![img](docs/img/CMMC_deposition/Slide10.png)

8. You can return to the browser where the workflow is open. Select the .tsv file you just uploaded in the “File browser”:
   - Click on "Select TSV file path"

![img](docs/img/CMMC_deposition/Slide11.png)

   - Select the .tsv file you want to deposit, and then click on "Add Selected File to TSV file path". 

![img](docs/img/CMMC_deposition/Slide12.png)

9. Press 'Submit Workflow'


# Step-by-step guideline Input Fields for CMMC-kb workflow (Single and Batch upload)

## Data Selection: 

### MS/MS identifier (input_usi)
_The Universal Spectrum Identifier (USI) is a standardized, unique identifier for mass spectrometry data. It provides a compact, human-readable way to specify a single spectrum derived from a mass spectrometry experiment, regardless of its origin or location._

Please input the Universal Spectrum Identifier (USI) for either an unidentified or a library spectrum. This is the sole required field. For the same molecule, you can input multiple MS/MS spectra corresponding to different adducts (e.g., [M+H]+, [M+Na]+), in-source fragments (e.g., [M-H2O+H]+), or distinct instruments (e.g., orbitrap, qtof). We recommend submitting all available USIs for any given microbial metabolite. Separate each USI using a semicolon.

**_Example:_**
_mzspec:GNPS:GNPS-LIBRARY:accession:CCMSLIB00000426629;mzspec:GNPS:GNPS-LIBRARY:accession:CCMSLIB00000425589_

## Metabolite identification: 
### Molecule name (if known) (input_name)
Please input the metabolite's recognized name. If available, use the name corresponding to PubChem (https://pubchem.ncbi.nlm.nih.gov/). For novel molecules, feel free to assign a name. If there are multiple names you want to add, separate each with a semicolon.

**_Example:_** _p-Cresol;4-Cresol_

### Structure (if known, SMILES) (input_structure)
Enter the SMILES for the molecule, if available.

**_Example:_** _CC1=CC=C(C=C1)O_

### Partial structure (input_partial_structure)
If the molecule hasn't been fully characterized yet, provide details on the known partial structures. This can include partial SMILES, descriptions of functional groups, or the molecule's class.

**_Example:_** _Based on the isotopic pattern, the molecule contains at least one Chlorine atom._

### Molecule origin (input_molecule_origin)
From the drop-down menu, choose the most fitting origin for the molecule.
The following categories are present:
  - Microbial metabolism of drugs
  - Microbial metabolism of food molecules
  - Microbial metabolism of other human-made molecules
  - Microbial metabolism of host-derived molecules
  - Microbial metabolism of microbial-derived molecules
  - Host metabolism of microbial metabolites
  - De novo biosynthesis by microbes (e.g., natural products and other specialized metabolites)
  - Unknown/Undefined

**_Example:_** 

_**Microbial metabolism of drugs:** Digoxin gets metabolized into dihydrodigoxin and dihydrodigoxigenin by gut Eggerthella lenta which are inactive metabolites. For dihydrodigoxin and dihydrodigoxigenin, the category would be: microbial metabolism of drugs._

_**Microbial metabolism of food molecules:** Glucosinolates, found in cruciferous vegetables like broccoli and Brussels sprouts, can be converted by the microbiota into isothiocyanates that have potential anti-cancer properties. For the isothiocyanate, the category would be microbial metabolism of food molecules. Another example for this category would be the short-chain fatty acids, as they are produced by bacteria from dietary fiber._

_**Microbial metabolism of other human-made molecules:** Bisphenol A (BPA), a component of many plastics, BPA can be degraded by several bacterial species, reducing its environmental persistence and potential endocrine-disrupting effects. The degradation product of BPA would fall into this category._

_**Microbial metabolism of host-derived molecules:** Bile acids turned into secondary bile acids. The secondary bile acids would fall into this category._

_**De novo biosynthesis by microbes (e.g., natural products and other specialized metabolites):** Antibiotics (eg. penicillin, streptomycin), siderophores, lipopeptides._

_**Unknown/Undefined:** When your microbial metabolite does not fit any of the catergories mentioned above, or if it is still unknown._

### Name of the original molecule that is being modified by the microbe (input_original_molecule_name)
If the metabolite results from microbial metabolism, provide the name of the precursor molecule.

_**Example:** For p-cresol this would be: p-Hydroxyphenylacetic acid;4-Hydroxyphenylacetic acid_

### Structure of the original molecule that is being modified by the microbe (input_original_molecule_structure)
If the metabolite originates from microbial metabolism, input the structure of the precursor molecule, using either SMILES or INChI format.

_**Example:** p-Hydroxyphenylacetic acid is also a microbial metabolite (besides being derived from human metabolism and diet): C1=CC(=CC=C1CC(=O)O)OC1=CC(=CC=C1CC(=O)O)O_







