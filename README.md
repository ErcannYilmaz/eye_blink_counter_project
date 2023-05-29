# eye_blink_counter_project

Gerekli Python Kütüphaneleri
-dlib
-OpenCV
-scipy.spatial
-imutils
-argparse
-imutils
-numpy
-matplotlib.pyplot

Bu projede "shape_predictor_68_face_landmarks.dat" veri seti kullanılarak yüz algılama işlemi yapılır. Bu algılama işleminden göz ile ilgili veriler kullanılarak göz açıklık oranı hesaplanır. Bu oranlar bir listeye eklenir. Bu listedeki en yüksek değer ve bu değerin listedeki konumuna kadar olan değerlerden en düşük olanı bulunur. Bu sayede listedeki herhangi iki eleman arasındaki en yüksek fark bulunmuş olur. Daha sonra listedeki her ikili elemanın aralarındaki farkların ortalaması hesaplanır. Bu iki değer arasındaki fark verilen belirli bir değişken (programda '10' verilmiştir) değerinden yüksek ise göz kırpılmış sayılır. Ayrıca göz açıklık oranı listesi canlı grafikde gösterilir. Programa argüman olarak bir veriseti ve video kaynağı verilmelidir. Video kaynağı argümanı olarak "webcam" verilirse cihazın kamerası kaynak olarak seçilir.   

Required Python Libraries
-dlib
-OpenCV
-scipy.spatial
-imutils
-argparse
-imutils
-numpy
-matplotlib.pyplot

In this project, face detection is performed using the "shape_predictor_68_face_landmarks.dat" dataset. From this detection process, eye-related data is used to calculate the eye aspect ratio. These ratios are added to a list. The highest value in this list and the lowest value among the values up to its position in the list are found. This way, the highest difference between any two elements in the list is determined. Then, the average of the differences between each pair of elements in the list is calculated. If the difference between these two values exceeds a given threshold value (set to '10' in the program), it is considered as a blink. Additionally, the list of eye aspect ratios is displayed on a live graph. The program should be provided with a dataset and a video source as arguments. If "webcam" is provided as the video source argument, the device's camera is selected as the source.

Dataset Link: https://drive.google.com/file/d/156k6hB1ldLolCUfGaT0d2NHal5Ve0ids/view?usp=sharing

