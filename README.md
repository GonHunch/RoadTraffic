# RoadTraffic

To run this project:  
Download [Anaconda](https://www.anaconda.com/products/individual) and [SUMO](https://sumo.dlr.de/docs/Downloads.php)  
Run Anaconda Prompt and type:  
```
conda create -name tf_gpu tensorflow_gpu
```
Download the repository on your computer  
Using Anaconda Prompt, navigate to the root folder of where you placed your downloaded repository and run:  
```
python training_main.py
```
The agent should then start training  
Upon completion, results are saved in a separate folder called "models" under the file "model_x", where x is a number starting from 1 generated automatically by the program
To test the agent, run:
```
python testing_main.py
```
The results of testing should be saved inside "model_x" folder under the file called "test"  

**Note:** if you wish to train and test another agent following the "model_2" folder name, you will have to change the "model_to_test" line to be equal to 2 in the "testing_settings.ini"  
Same case goes for any other "model_x" files where x is not 1
