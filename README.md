# DE-MRI_Classificació_CNN
Model de classificació CNN entrenat amb imatges cardíaques DE-MRI que cobreixen el ventricle esquerre per detectar pacients que han patit infart de miocardi.

**dataset:** carpeta on trobem la base de dades pública del challenge EMIDEC (Evaluation of Myocardial Infarction from Delayed-Enhancement Cardiac MRI).
  https://emidec.com/
  
   **_   -entrenament_:** subcarpeta que conté les imatges (.nii) etiquetades. Trobem una carpeta amb les imatges dels pacients sans ("_normal_") i una carpeta          amb les imatges dels pacients que han patit infart de miocardi ("_patologic_").
       
   **_   -test_:** subcarpeta que conté les imatges (.nii) no etiquetades per fer les prediccions.
       

**1. Visualització.ipynb:** codi per visualitzar els exàmens DE-MRI dels pacients.
  
**2. Preprocessat.ipynb:** codi per convertir les imatges 3D (.nii) a 2D (.png) i guardar-les al Drive. 
  
**3. Entrenament_final_CNN.ipynb:** codi per entrenar el model CNN amb les imatges del dataset i avaluació del rendiment del model. 
  
**4. Model2_CNN.ipynb:** codi per fer les prediccions d'imatges no etiquetades a partir del model entrenat. Avaluació dels exàmens DE-MRI de cada pacient segons els resultats obtinguts després de la classificació de les imatges. 
