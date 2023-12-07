# PQC500 Dataset
In this repository, we provide the pineapple dataset : Pineapple Quality Classification 500 (PQC500), as described in the following paper:

Yi-Lu Jiang, Wen-Chang Chang, and Chih-Yi Chiu, "Pineapple Quality Classification in a Multimodal Audio-Visual Dataset," <br>
2023 IEEE International Conference on Big Data (Big Data), Sorrento, Italy, Dec. 15-Dec. 18, 2023.

We compile a pineapple dataset consisting of 500 pineapples of the Tainung No. 17 variety with two modalities: one is tapping a pineapple to record the sounds, and the other is taking pictures by cameras. Each pineapple was tapped at the side and bottom regions to generate 20 soundtracks (recorded by five surrounded microphones) and 16 photos (captured by two cameras(cam-1, cam-2) from different views).

We define four classes for the pineapple quality by the water selection approach : 
1. hollow sound (H)
2. semi-hollow sound (SH)
3. semi-solid sound (SS)
4. solid sound (S).
   
They have been labeled as 0, 1, 2, 3 in sequence.

<div align="center">
  <img src=figures/Data_distribution.jpg><br>
  Fig. 1. The number of pineapples per class.
</div>

* ### Example
  <table>
  <tr>
    <td align="center" valign="center">Pineapple Number</td>
    <td colspan="2" align="center" valign="center">001</td>
  </tr>
  <tr>
    <td align="center" valign="center">Label</td>
    <td colspan="2" align="center" valign="center">0</td>
  </tr>
  <tr>
    <td rowspan="2" align="center" valign="center">Image</td>
    <td align="center" valign="center">bottom</td>
    <td align="center" valign="center">side</td>   
  </tr>
  <tr>
     <td align="center" valign="center"><img src=figures/bottom.JPG></td>
     <td align="center" valign="center"><img src=figures/side.JPG></td>
  </tr>
  <tr>
     <td rowspan="2" align="center" valign="center">Audio</td>
     <td align="center" valign="center">bottom</td>
     <td align="center" valign="center">side</td>
  </tr>
  <tr>
     <td align="center" valign="center">
        
  https://github.com/ncyuMARSLab/PQC500/assets/47770780/0a3f3676-622c-41ed-8469-69686298d534
  
     </td>
     <td align="center" valign="center">
        
  https://github.com/ncyuMARSLab/PQC500/assets/47770780/f07dced4-ea39-4d99-b636-a6bfad59c516
  
     </td>
  </tr>
</table>

# Get the Dataset

* [Training set](https://drive.google.com/drive/folders/139WZZxhfqy4RucsbOBUVxgkyaTGmkSYS?usp=sharing)

* [Test set](https://drive.google.com/drive/folders/1h5Zgut1VToTHIdTU-c7JzuwNUVh21DDa?usp=sharing)

# Citation
