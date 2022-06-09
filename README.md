# MotionAnalysisForSensorData
Cluster Analysis of the batches

![indas1](https://user-images.githubusercontent.com/25880699/172875690-c239dafc-d94a-4fa7-8bc4-38b7be3b3723.png)

<h2>Input</h2>
  450 files, containing motion data of approx. 60 seconds length
    -4 sense hats with:<br>
    -3 acceleration measurements (x, y, z)<br>
    -3 gyroscope measurements (x, y, z)<br>
    -3 orientation measurements (roll, pitch, yaw)<br>
    
 <h2>Parameter</h2>
 52 different parameter based on Sensor ID.(94-145)</br>
 e.g. 94 = sensehat1.motion.acceleration.x<br>
      95 = sensehat1.motion.acceleration.y<br>
      ........</br>
      
      
 <h2>Task</h2>
 The batches contain different load classes that have to be clustered accordingly (each batch is of oneclass)


