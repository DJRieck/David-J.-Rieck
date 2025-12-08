# USCM Appendix C Demos

This repository contains the Python code snippets referenced in Appendix C of the USCM model manuscript.  
Each script is deterministic and can be run independently to reproduce the computational demonstrations in the appendix.

## Contents

All demos are under `appendix_c/` and map directly to the appendix sections:

- `appendix_c/C1_CHSH_Tsirelson.py`  
  Section C.1 – CHSH non-locality validation (Tsirelson bound, Werner noise scan).

- `appendix_c/C2_PageWootters_Conditioning.py`  
  Section C.2 – Page–Wootters emergent relational time via clock conditioning.

- `appendix_c/C3_DecoherenceLag_Arrow.py`  
  Section C.3 – Phenomenological damping / arrow-of-time toy model.

- `appendix_c/C4_PhotonRing_Scaling.py`  
  Section C.4 – Photon-ring scaling toy model for small entropy-driven ring anomalies.

## Requirements

- Python 3.12+
- NumPy 2.x
- QuTiP 5.x

You can install the Python dependencies with:

```bash
pip install -r requirements.txt
Usage
Clone the repository and run any script directly, for example:

bash
Copy code
python appendix_c/C1_CHSH_Tsirelson.py
python appendix_c/C2_PageWootters_Conditioning.py
python appendix_c/C3_DecoherenceLag_Arrow.py
python appendix_c/C4_PhotonRing_Scaling.py
Each script prints representative numerical output and includes simple internal checks (asserts) to verify that the expected behavior is obtained.

License
Code in this repository is licensed under the MIT License (see LICENSE).

The associated manuscript text is licensed separately under Creative Commons Attribution 4.0 International (CC BY 4.0) via its Zenodo record.

pgsql
Copy code

You can adjust the wording “USCM model manuscript” or add the exact paper title / Zenodo link later if you like, but this is already fully usable as-is.
::contentReference[oaicite:0]{index=0}
