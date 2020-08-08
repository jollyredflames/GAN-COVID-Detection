# GAN-COVID-Detection
An implementation of the pix2pix network to work for anomaly detection in chest scans. The architecture should help detect anamoly chest scans and can help reduce medical burden by pre-screening lungs which have no obvious signs of viral/bacterial infection. We envision the optimal system assigning priorities to patients to ensure the most dire patients get prioritized in healthcare, although this research only aims to measure the accuracy of the Generator/Discriminator model using the AUC curve.

======Instructions to run our files======

Pix2pixModel.ipynb

1) Load the file into Google Colab
2) Follow the cells to regenerate output
3) If an issue arises please ensure relevant permissions are granted to the notebook, this includes connecting to your drive. In addition, ensure you are running in a GPU runtime environment as our model uses Cuda to accelerate training. You may run into memory issues if your collab notebook is not upgraded to the premium subscription.

CXR_Anomaly_Detection.ipynb

1) Upload the CoronaHack_Resized.zip to drive so the path is: /CSC420_Project/CoronaHack_Resized.zip

The file can be found here: https://drive.google.com/file/d/18DuNjxQcnkkFXvgnGfrcDeWJDCHltkH-/view?usp=sharing

2) Run the CXR python book block by block
