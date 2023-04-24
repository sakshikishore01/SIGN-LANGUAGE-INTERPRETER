# sign-language-interpreter

TS- WEB/CC/AI TRACK CAPSTONE PROJECT

Presented By:

1. Miss Sakshi (Leader) - GBPEC Delhi 

2. Miss Khyati (Teammate) – GBPEC Delhi


Guided By:- Bharti Verma Ma'am


Hand gesture is one of the method used in sign language for non-verbal communication.
It is most commonly used by deaf & dumb people who have hearing or speech problems to communicate  with normal people.
Hence in this project introduced software which presents a system prototype that is able to automatically recognize sign language to help deaf and dumb people to communicate more effectively with normal people.
Gesture recognition are the developing fields of research. By considering in mind the similarities of human hand shape with four fingers and one thumb, the software aims to present a real time system for recognition of hand gesture on basis of detection of some shape based features like orientation, Centre of mass centroid, fingers status, thumb in positions of raised or folded fingers of hand.
In this way our model will detect the real time sign gestures and detect the correct sign language as the output .

To create a model or project which can detect sign language gestures performed by deaf and dumb people then that gesture will be fed to a machine-learning algorithm performed by a neural network which is then detected by the neural network and translated on display\console so that a normal person can understand what the sign gestures meaning.


![image](https://user-images.githubusercontent.com/93922575/234105232-c6bf545d-a618-4c6f-91c1-d3ce7f8b777b.png)


In future our model will detect or decode full sentences by gestures which will make communication  more easier. 

 Our model will be useful for many purposes. By our model we can resolve a lot of problems:-
 
• It reduce communication barrier between physically impaired (deaf and dumb) people and us. People will easily understand impaired people.

•It raise awareness about sign language in among who don’t know anything about sign language .

•Use in learning sign language .


 STEPS FOLLOWED :-
 
 Step 1. Clone this repository
 
 Step 2. Create a new virtual environment
 
python -m newenv TFOD

Step 3. Activate your virtual environment

source tfod/bin/activate # Linux

.\tfod\Scripts\activate # Windows 


Step 4. Install dependencies and add virtual environment to the Python Kernel

python -m pip install --upgrade pip

pip install ipykernel

python -m ipykernel install --user --name=tfodj

step 5. Collect images using the Notebook "Image collection"

Step 6. Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders.

\TFOD\Tensorflow\workspace\images\train
\TFOD\Tensorflow\workspace\images\test


Step 7. Begin training process by opening "Trainning and detection"

step 8. Train the model, inside of the notebook, you may choose to train the model from within the notebook or the seperate terminal on the windows machine.

Step 9. You can optionally evaluate your model inside of Tensorboard. Once the model has been trained and you have run the evaluation command

Navigate to the evaluation folder for your trained model 
e.g.
 cd Tensorlfow/workspace/models/my_ssd_mobnet/eval


and open Tensorboard with the following command

tensorboard --logdir=. 


Tensorboard will be accessible through your browser and you will be able to see metrics including mAP - mean Average Precision, and Recall.


