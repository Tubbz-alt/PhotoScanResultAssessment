# An Assessment on Unmanned Aerial System (UAS) Photogrammetry without Ground Control

Mapping the landfast sea ice in fine scale is not only meaningful for  geophysical  study, but also of benefit for human activities on it.
The newly-developed Unmanned Aerial System (UAS) and Structure-from-Motion (SfM) methodology have already revolutionized the current observation paradigm. To test their feasibility in characterizing the properties and dynamics of fast ice, three flights were carried out in 2016-2017 austral summer during 33rd Chinese National Antarctic Expedition (CHINARE). focusing on the area of Prydz Bay, East Antarctic. Afterwards, 3D model and ortho-mosaics are reconstructed from 205 collected photos by SfM implemented in PhotoScan software. ![](https://github.com/bwbj/PhotoScanResultAssessment/blob/master/figures/sec3-fig02.png "main") 

Although it was quite challenging to deploy ground controls like traditionally, we still managed to assess the performance of SfM photogrammetry indirectly, through analyzing the outputs of the matching network, bundle adjustment, and Monte-Carlo simulation. Results show that matching networks are actually quite strong with a sufficient number of feature points. On the contrary, most of total errors are introduced from direct geo-referencing by inaccurate onboard position and orientation system (POS) records, especially vehicle height and yaw angle. The 3D precision map shows planimetric precision (typically 20 \textit{cm} in network center) are usually 1/3 of vertical estimate. On the other hand, shape-only errors merely account less than 5\% for \textit{X/Y} dimension and 20\% for \textit{Z} dimension. Based on the above, 6 representative surface features are selected and interpreted. Consequently, a couple of pragmatic suggestions are then offered as guidelines for the further related UAS application in sea ice study.

To our best knowledge, it is one of leading work attempting to exhaustively assess on UAS's capability on sea ice application, and could serve as the reference for future improvements.

If any feedbacks, suggestions and questions, please do not hesitate to contact me.

Email: litengbnu@foxmail.com
