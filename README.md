# Scary Barbie (AT2021lwx): NEOWISE dust echo

Code and data for the Research Note "Dust Echo Properties of AT2021lwx
from Its Complete NEOWISE Light Curve" (Febin S, 2026).

## Files
- `scary_barbie.ipynb`: the full analysis (Google Colab), steps 1 to 6
- `barbie_lightcurve_mJy.csv`: NEOWISE difference-image light curve, 21 visits
  (2014 to 2024). `band` 1 = W1, 2 = W2. `flux`/`err` in image counts,
  `mJy`/`mJy_err` calibrated
- `barbie_ztf_alerce.csv`: ZTF alert photometry from ALeRCE (`fid` 1 = g, 2 = r)
- `barbie_results.csv`: dust temperature (K), log luminosity (erg/s) and
  radius (pc) per flare visit, as 16th/50th/84th percentiles, before (`Traw`)
  and after (`T`) removing the flare's light
- `barbie_figure1.png`: Figure 1 of the note

## How to run
Open the notebook in Google Colab and run the cells in order. Steps 1 and 2
download the NEOWISE images from IRSA and take several minutes.

## License
MIT
