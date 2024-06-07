# PQC500 Dataset
In this repository, we provide the pineapple dataset : Pineapple Quality Classification 500 (PQC500), as described in the following paper :

Yi-Lu Jiang, Wen-Chang Chang, and Chih-Yi Chiu, "Pineapple Quality Classification in a Multimodal Audio-Visual Dataset," IEEE International Conference on Big Data (Big Data), Sorrento, Italy, Dec. 15-Dec. 18, 2023.

We compile a pineapple dataset consisting of 500 pineapples of the Tainung No. 17 variety with two modalities : one is tapping a pineapple to record the sounds, and the other is taking pictures by cameras. Each pineapple was tapped at the side and bottom regions to generate 20 soundtracks (recorded by five surrounded microphones) and 16 photos (captured by two cameras from different views). The environment layout is shown in Fig. 1.

<div align="center">
  <img src=figures/layout.jpg width="640" height="360"><br>
  Fig. 1. Environment layout.<br>
</div>
<br>

We define four classes for the pineapple quality by the water selection approach : 
1. hollow sound (H)
2. semi-hollow sound (SH)
3. semi-solid sound (SS)
4. solid sound (S)
   
The class distribution is shown in Fig. 2.

<div align="center">
  <img src=figures/data_distribution.jpg><br>
  Fig. 2. The distribution of pineapple classes.
</div>

* ### Example
  <table>
  <tr>
    <td align="center" valign="center">Pineapple Number</td>
    <td colspan="2" align="center" valign="center">0001</td>
  </tr>
  <tr>
    <td align="center" valign="center">Label</td>
    <td colspan="2" align="center" valign="center">Hollow sound (1)</td>
  </tr>
  <tr>
    <td rowspan="2" align="center" valign="center">Image</td>
    <td align="center" valign="center">loc-1</td>
    <td align="center" valign="center">loc-2</td>   
  </tr>
  <tr>
     <td align="center" valign="center"><img src=figures/b1.jpg width="130" ><text>  </text><img src=figures/b2.jpg width="130"></td>
     <td align="center" valign="center"><img src=figures/s1.jpg width="130"><text>  </text><img src=figures/s2.jpg width="130"></td>
  </tr>
  <tr>
     <td rowspan="2" align="center" valign="center">Audio</td>
     <td align="center" valign="center">bottom tapping</td>
     <td align="center" valign="center"> side tapping </td>
  </tr>
  <tr>
     <td align="center" valign="center">

  https://github.com/ncyuMARSLab/PQC500/assets/47770780/cc53542c-d4e5-4109-b80d-55f24ea57ff1
  
     </td>
     <td align="center" valign="center">
        
  https://github.com/ncyuMARSLab/PQC500/assets/47770780/ccb1189d-0c75-4112-be2a-1545b10ec4bd
  
     </td>
  </tr>
</table>

# Get the Dataset
The dataset has been split into 2 parts : training set and test set.
* [Training set](https://drive.google.com/drive/folders/139WZZxhfqy4RucsbOBUVxgkyaTGmkSYS?usp=sharing)

* [Test set](https://drive.google.com/drive/folders/1h5Zgut1VToTHIdTU-c7JzuwNUVh21DDa?usp=sharing)

* [readme.txt](https://drive.google.com/file/d/1vi7yqIkfDPeJRwRkzFrkcZ1hdFLtln5p/view?usp=drive_link)
  

# Citation
Yi-Lu Jiang, Wen-Chang Chang, and Chih-Yi Chiu, "Pineapple Quality Classification in a Multimodal Audio-Visual Dataset," IEEE International Conference on Big Data (Big Data), Sorrento, Italy, Dec. 15-Dec. 18, 2023.
