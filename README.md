# DRonA and MLSynergy
**Repository for GEOparser, DRonA and MLSynergy algorithms**

##### Requires Python 2.7 for GEOparser and Python 3.0 for DRonA and MLSynergy

## Downloading packages

```
git clone https://github.com/viveks-baligalab/DRonA_MLSynergy.git
```

## Installing required packages
```
pip2 install -r GEOparser_requirements.txt
pip3 install -r DRonA_MLSynergy_requirements.txt
```

## Running instructions:
**GEOparser -**
```
python2 GEOparser.py --help --prjname <> --coldir <> --refseq <> -gsmidfile <> [OPTIONS]
```
**DRonA -**
```
python3 DRonA.py --help --command <> --classifier[conditional] <> --metadata <> --data <> --ref_ids <> --output <> [OPTIONS]
```
**MLSynergy -**
```
python3 MLSynergy.py --help --command <> --[conditional]classifier <> --[conditional]metadata <> --[conditional]combinaitons --[conditional]data <> --[conditional]ref_ids <> --output [OPTIONS]
```
