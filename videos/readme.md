## Supplementary materials

The files in this folder are the test results on the CT image No.0 in the test [data set](https://drive.google.com/drive/folders/1HqEgzS8BV2c7xYNrZdEAnrHk7osJJ--2) of [Medical Segmentation Decathlon](http://medicaldecathlon.com) (file imagesTr/liver_0.nii.gz in Task03_Liver.tar). The 3D images were displayed as videos along the Z axis.

* **input.mp4**: the raw CT image (selected part with liver only)
* **labels.mp4**: the groud truth segmentation label (mask) for this image
* **predictions.mp4**: the label prediction on this CT image by the trained network (along Z axis)
* **pred_axis0.mp4**: the predicted label along X axis
* **pred_axis1.mp4**: the predicted label along Y axis
* **pred_final.mp4**: the fused label of the three directions

Since the network was trained only on Z axis, the results for X and Y axes are not accurate. This fusion result is just an explanation of the idea.