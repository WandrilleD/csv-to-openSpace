> the files resulting from these scripts have not been tested in openSpace yet. use at your own risk ;-)

# quick and dirty transformation of a csv file into openSpace speck and asset file

The goal of this project is to provide utilities to transform data in a csv format (or any classical tabular format) into the sets of files needed to import these as simple points in openSpace.

The crux of the code is in `csv_to_openSpace.ipynb`.

Be sure to adapt variables to suite your data (input files, output names, columns which should serve as labels). This code is meant as a fairly common, simple basis rather than a complete format configuration interface.

The code should currently be configured for the toy data (which corresponds to some single cell RNAseq data) which can be found in `toyData/`. Outputs can be found in `output/`

Finally, `resources/` contains a couple of assets (texture and colormap) which get copied to the output directory as part of the conversion process.
