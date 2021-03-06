## Artificial Sign Learner
The American Sign Language is one of the most commonly used sign languages. As The Paralympic Games come near, the need for learning sign languages is expected to rise. However, a good sign language teacher is sometimes difficult to find and the lessons can be costly to take. Motivated by this, our team designed an AI-based sign language learning program. With this program and its 3 built-in modes, you will be able to learn how to sign all the alphabets in ASL and test yourself for the learning outcome.

### Usage

#### Download this Github Repository
Run `git clone https://github.com/moose-not-found/ASL`


#### Install dependencies
Run the command `pip install -r requirements.txt`


#### Start the program
Run the command `python main.py`


### Different modes of the program
<img src="pictures/main_page.png"></div>

#### Learning Mode
In this mode, the user will be able to input an alphabet that you would like to query and learn, and the program will enable the user's camera and pop up a live-feed window. There will be a reference picture in the frame and the user can imitate the picture to study the sign for that alphabet. After the learning is done, the user can press <b>Q</b> on the keyboard while signing to the camera. The program will then stop the live feed and evaluate the user's learning outcome.

<img src="pictures/learning_mode.png"></div>

#### Training Mode
In this mode, the user can practice signing the alphabets learned from Learning Mode into the camera live feed. After a short while, the program will tell you the 3 most possible alphabets that you just signed with probabilities.

<img src="pictures/training_mode.png"></div>

#### Quizzing Mode
In this mode, the user will be quizzed. The program will randomly generate alphabets for the user to sign. Once the user sign correctly, the program will provide the next alphabet to sign. After about 20 seconds, the quiz will end and the program will indicate how many correct ones the user signed.

<img src="pictures/Quiz_mode.png"></div>


### Reference
Credit of our CNN model goes to <a href="https://github.com/jonathanoheix/Real-Time-Face-Expression-Recognition">Jonathan Oheix</a>

Our database is from <a href=https://www.kaggle.com/grassknoted/asl-alphabet>here</a>