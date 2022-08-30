# Forest carbon fuelmap

Reducing the risk of wildfires and emissions is highly relevant. This project assists indigenous stewards to do this while creating renewable energy, offsets, fertilizers, biodiversity and jobs.

### Technology
Python, jypyter notebooks, GDAL, InVEST

### Deployment environment 
AWS SageMaker Notebooks, local device or container.

### Requirements
Python version 3.8+
Packages: GDAL, natcap.invest, terracatalogueclient
Free account at for the Terrascope service for looking up map segments
https://vitobelgium.github.io/terracatalogueclient/installation.html

### Installation
The workbook is standalone and contains all necessary code.
You will also need
- Deadwood prognosis file (a sample is supplied in /input)
- A free account to use the terracatalogue (see above)
- A login secrets file. A placeholder is supplied in input (a placeholder is supplied. Fill it out)
- A ground class  classification .csv file (supplied in input)

### Running the analysis
Just start the notebook and execute each line or just run the whole notebook. Results are shown on screen and resultant files are output to the temp directory.




