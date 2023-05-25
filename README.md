# DE-MRI_Classificacio_CNN
CNN de classificació d'imatges DE-MRI (normals o patològiques) que cobreixen el ventricle esquerre en patològiques o normals. 

  **_dataset_:** carpeta on trobem la base de dades pública del challenge EMIDEC (Evaluation of Myocardial Infarction from Delayed-Enhancement Cardiac MRI).
  https://emidec.com/
  
       **_entrenament_:** subcarpeta que conté les imatges (.nii) etiquetades. Trobem una carpeta amb les imatges dels pacients sans ("_normal_") i una carpeta          amb els pacients que han patit infart de miocardi ("_patologic_").
       
       **_test_:** subcarpeta que conté les imatges (.nii) no etiquetades per fer les prediccions.
       


  **1. Visualització.ipynb:** codi per visualitzar les DE-MRI dels pacients.
  
  **2. Preprocessat.ipynb:** codi per convertir les imatges 3D (.nii) a 2D (.png) i guardar-les al Drive. 
  
  **3. Entrenament_final_CNN.ipynb:** codi per entrenar el model CNN amb les imatges de la base d'entrenament i avaluació del rendiment del model. 
  
  **4. Model2_CNN.ipynb:** codi per fer les prediccions d'imatges no etiquetades a partir del model entrenat. Avaluació de cada pacient segons si s'han obtingut        resultat de DE-MRI normals, patològiques o si hi ha hagut un error.  
