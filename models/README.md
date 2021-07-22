
# Models

* **U-net_trainEvalOnDTA_round1.pth**: File of U-net model trained on
the 318 pages listed in the file
"data/DTA-train-round1_PixLevAnnot.lst".

* **U-net_trainEvalOnDTA_round2.pth**: File of U-net model trained on
the 1,075 pages listed in the file
"data/DTA-train-round2_PixLevAnnot.lst". This model was used for the
self-training phase of the paper (Sec.5.5).


Usage example of U-net models
=============================

Install P2PaLa (one U-net implementation for document layout analysis)
from [github.com/lquirosd/P2PaLA.git](https://github.com/lquirosd/P2PaLA.git).

For decoding and evaluating on the 136 pages of DTA test set:
```bash
cd Exp_U-net_Round1
P2PaLA.py --config ./config.txt \
          --prev_model ../U-net_trainEvalOnDTA_round1.pth \
	  2>>p2pala.log 1>&2
```
For an explanation about the different parameters in `config.txt` refers to the P2Pala's documentation at: [github.com/lquirosd/P2PaLA.git](https://github.com/lquirosd/P2PaLA.git).
