## How to visualise LFRiC unstructured grid output

This repository contains a small LFRiC output file and a simple Python notebook to plot the data using a combination of Iris and GeoVista tools.

### Installation
Install via git and anaconda:

<code>
git clone https://github.com/cemac/Plot_LFRiC_output.git
cd Plot_LFRiC_output
conda env create -f environment.yml
conda activate lfric_plotting
</code>

### Test data
The test data file supplied was created using the following branch: <code>main/branches/pkg/mohitdalvi/vn1.2_arch2_lfric_chem</code> (see MOSRS ticket #228: https://code.metoffice.gov.uk/trac/lfric_apps/ticket/228).

The branch code was tested using the following rose stem test: <code>lfric_atm_chem_archer2</code>.