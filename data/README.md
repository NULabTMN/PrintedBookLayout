
# Data

* **DTA-454p_PixLevAnnot/**: Directory containing the 454 verified
pair samples of page image (previously binarized) and corresponding
pixel-level annotated regions (in XML-PAGE format).

* **DTA-757p_PixLevAnnot/**: Directory containing the 757 extra page
images along with their pixel-level annotated regions (in XML-PAGE
format). This set was used in the self-training phase of the paper
(Sec.5.5).

* **DTA-train-round1_PixLevAnnot.lst** and **DTA-test_PixLevAnnot.lst**:
Files listing the page images from **DTA-454p_PixLevAnnot/** used for
training (318 pages) and testing (136 pages).

* **DTA-train-round2_PixLevAnnot.lst**: File listing the whole page
images (1,075 pages) from **DTA-454p_PixLevAnnot/** and
**DTA-757p_PixLevAnnot/** used for the self-training phase of the
paper (Sec.5.5).

* **DTA-RegLevAnnot.json** and **WWO-RegLevAnnot.json**: JSON files of
the whole DTA and WWO datasets containing the ground-truth region tags
used for computing the region-level metrics.



