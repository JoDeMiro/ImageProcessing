Image Processing - Digitális képfeldolgozás

Dr. Várkonyiné Dr. Kóczy Annamária, egyetemi tanár, DSc Digitális képfeldolgozás tantágyához


A tantárgy célja: A tantárgy célja megismertetni a hallgatókat a digitális képfeldolgozás, a
számítógépes grafika, a digitális képelemző és a geometriai modellező rendszerek klasszikus
és nemkonvencionális módszereivel, valamint azok alkalmazásához szükséges elméleti és
gyakorlati ismeretekkel. A kurzus elvégzése megalapozza és segíti a hallgatók területhez
kapcsolódó kutatói készségének, új módszerek, algoritmusok, és modellek kifejlesztési
képességének kialakulását.

A tantárgy tartalma:
A digitális képfeldolgozás és gépi látás módszerei, algoritmusai és modelljei. Geometriai
transzformációk. A digitális jel- és képfeldolgozás transzformált tartománybeli módszerei, 1D
és 2D Fourier transzformációk, Wavelet transzformáció. Lágyszámítási módszereken alapuló
eljárások, fuzzy, neurális, genetikus, anytime technikák. Zajelnyomás, információkiemelés,
élkeresés, csúcspontdetektálás, objektumkeresés és felismerés, gépi látás, számítógépes
modellezés, 3D rekonstrukció, adattömörítés, kamerakalibráció, valósidejű feldolgozás,
kódoptimalizálás. HDR eljárások. Mintapéldák, esettanulmányok.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master)

# Jupyter Notebook
A program használatához nem szükséges semmit sem telepíteni.
A fenti 'Google Colab' ikonra kattintva a Google Colab oldalán automatikusan megnyilik a
program.


- Alapok
- Képek felépítése, típusok, több dimenziós tömbök
- Mátrix transzformációk [[Mátrix transzformáció]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/10_Image_Matirx_transzformaciok_1.ipynb)
- 2D Konvolúciók [[2D Konvolúciók]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/05_Image_Convolution_1.ipynb)
- Szűrők és konvolúciók [[Szűrők és konvolúciók]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/02_Images_Filtering.ipynb)
- Automatikus színkorrekciók [[Automatikus színkorrekciók]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/04_Image_Color_manipulation.ipynb)
- Kép additivitás [[Kép additivitás]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/06_Image_Compositions.ipynb)
- Éldektálás
- Kép szegmentálás
- Objektum detektálás [[YOLOv3]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/15_Image_Object_Detection_YOLOv3.ipynb)
- Arc és kulcspont detektálás [[MTCNN]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/16_Image_Face_Detection_1.ipynb)
- Arc és 48 kulcspont azonosítás [[Dlib]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/17_Image_Face_Landmark_Detection_1.ipynb)
- Arc maszk azonosítás [[PyTorch ResNet101]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/18_Image_Mask_Detection_with_ResNet.ipynb)
- Segédletek [[Integrálszámítás NumPy könyvtárral]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/97_Integrálszámítás_Numpy_könyvtárral.ipynb)
- Segédletek [[Lineáris algebra - Mátrixok NumPy könyvtárral]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/98_Lineáris_Algebra_Mátrixok.ipynb)
- Segédletek [[Lineáris algebra - Vektorok NumPy könyvtárral]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/99_Lineáris_Algebra_Vektorok.ipynb)
- Pédák [[Baktérium számlás képszegmentálással]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/03_Images_Example_2_.ipynb)
- Példák [![megnyitás]](https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master)


<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/10_Image_Matirx_transzformaciok_1.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/2DMatixScale.gif?raw=true"></img>
</a>

<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/EdgeDetection1.png?raw=true"></img>

<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/02_Images_Filtering.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/blur_1.png?raw=true"></img>
</a>


<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/16_Image_Face_Detection_1.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/face_detection_1.png?raw=true" width="500" height="500"></img>
</a>
<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/16_Image_Face_Detection_1.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/face_detection_2.png?raw=true" width="500" height="500"></img>
</a>


<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/17_Image_Face_Landmark_Detection_1.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/face_landmark_1.png?raw=true" width="500" height="500"></img>
</a>
<a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/17_Image_Face_Landmark_Detection_1.ipynb" target="_blank">
<img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/face_landmark_2.png?raw=true" width="500" height="500"></img>
</a>


<div valign="center">
  <p align="center">&nbsp;
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/18_Image_Mask_Detection_with_ResNet.ipynb" target="_blank">
      <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/MaskDetection1.png?raw=true"></img>
    </a>
  </p>
</div>


<div valign="center">
  <p align="center">&nbsp;
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/02_Images_Filtering.ipynb" target="_blank">
    <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/Convolution1.png?raw=true"></img>
    </a>
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/02_Images_Filtering.ipynb" target="_blank">
    <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/Convolution2.png?raw=true"></img>
    </a>
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/02_Images_Filtering.ipynb" target="_blank">
    <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/EdgeDetection2.png?raw=true"></img>
    </a>
  </p>
</div>


<div valign="center">
  <p align="center">&nbsp;
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/03_Images_Example_2_.ipynb" target="_blank">
      <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/BacteriaDetection1.png?raw=true"></img>
    </a>
  </p>
</div>


<div valign="center">
  <p align="center">&nbsp;
    <a href="https://colab.research.google.com/github/JoDeMiro/ImageProcessing/blob/master/97_Integrálszámítás_Numpy_könyvtárral.ipynb" target="_blank">
      <img src="https://github.com/JoDeMiro/ImageProcessing/blob/main/images/integral_1.png?raw=true"></img>
    </a>
  </p>
</div>










