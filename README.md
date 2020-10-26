# PFAS_Toxprints
PFAS Toxprints: A Hierarchical Structure-Based Categorization Method for Characterization of Per- and Polyfluoroalkyl Substances

## Installation

To use this file you must download and install the Chemotyper Application (https://www.mn-am.com/products/chemotyper) or MOSES (https://www.mn-am.com/moses)

No further installation required. Use the PFAS_Toxprints_v1.11.1.xml file with either application and a set of molecular structures. 

## Usage`

In the chemotyper application just use the GUI to match the latest PFAS_Toxprint file with your structure file of choice.

In MOSES, you will need to run a command similar to following on your terminal.

/mypath/username/CORINA_Symphony_14698/bin/moses -N symphony -i MyStructureFile.sdf -o results.tsv descriptors -f PFAS_Toxprints_v1.11.1.xml

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure  add/update tests as appropriate.

## License
none
