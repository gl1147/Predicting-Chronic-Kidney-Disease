1. Load "kidney_disease.csv" in RapidMiner and perform replacing missing value using average and output the new dataset as "fill.csv"


2. Load "fill.csv" in Weka. Switch to "select attribute" tab. Perform PCA, CFS (forward selection), gain ratio and information gain individually. Save results.

3. After comparing the results, open "fill.csv" in Excel. Keep bp, sg, al, su, pc, bgr, bu, sc, sod, pot, hemo, pcv, rc, htn, dm, appet, pe, ane and remove all other attributes. Save as "reduced".

4. Load "reduced" in RapidMiner to see visualize data points.

5. Open "reduced" in Excel and delete "id" colunm. Save and exit. 

5. Load "reduced" in Weka and go to "Cluster" tab. Choose "SimpleKMeans" for clusterer. Then left click to go to configuration. Choose "k-means ++" for initializationMethod. 

6. In cluster mode, select "Classes to clusters evalutation" and choose "classification" and click "start". Save result.

7. Switch to "Classify" tab. Choose "J48" under "tree" dropdown menu. Select "use training set" in test options and click start. Save run result. Right click on run to visualize decision tree - the classifier. 

 

