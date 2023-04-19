SIGN-LANGUAGE TRANSLATOR


Problem Statement
To design a real time software system that will be able to recognize  hand-gestures and text input  using deep learning techniques. This project aims to predict the 'alphanumeric' gesture of the ISL system.

Objective
The objective of a sign language translator project is to create a system that can interpret spoken language and translate it into sign language in real-time. This system would enable people who are deaf or hard of hearing to communicate more easily with individuals who do not understand sign language. The project aims to improve accessibility and inclusivity for deaf and hard of hearing individuals by breaking down communication barriers.

Scope
The sign language translator project involves developing an algorithm that can accurately recognize spoken language and translate it into sign language and vice versa using video or animation. The ultimate goal of the project is to provide a reliable and user-friendly tool that can help people with hearing disabilities to communicate effectively and efficiently in various settings.

Technology Used

•	OpenCV
•	Keras
•	Python
•	Scraping
•	Tensorflow
•	Tkinter
•	Gif
•	Cloud



Methodology
The project of creating a sign language translator from audio to sign and sign to text involves developing a system that can recognize spoken language, translate it into sign language, and then convert the sign language into written text.

The project would involve several stages, including:

Sign language animation: The second step would be to develop a system that can translate the written text into sign language animations. This would involve creating a database of sign language gestures and movements, and mapping these to the written text using a machine learning algorithm.

Sign to text: In the opposite direction, we could also develop a system that can recognize sign language gestures and convert them into written text. This would involve using computer vision techniques to analyse video input and identify the sign language gestures being made.

Overall, the project aims to create a reliable and accurate system that can facilitate communication between people who use sign language and those who do not. By enabling real-time translation between audio, sign, and text, the system would help to break down communication barriers and promote inclusivity and accessibility for people with hearing disabilities.

Challenges Faced
•	Unlike spoken languages, sign languages have limited datasets available for training machine learning algorithms. This scarcity of data makes it challenging to develop accurate and reliable sign language recognition and translation models.
•	Sign language communication often occurs in real-time, which means that any sign language translator must work quickly and accurately to keep up with the conversation. Achieving real-time translation requires sophisticated algorithms and hardware.




Result
Upon training the image dataset without any augmentation, the training accuracy achieved was very high  but, the real time performance was not up to the mark. It was predicting incorrectly most of the time because in real time hand-gestures were not placed exactly at the centre and aligned vertically. In order to overcome this shortcoming, we trained our model by augmenting our dataset. The training accuracy was reduced to 89% but the real-time predictions were predominantly correct. Offline testing of about 9000 augmented images showed an accuracy of 92.7% .

Future Scope
•	We can develop a model for ISL word and sentence level recognition. This will require a system that can detect changes with respect to the temporal space.
•	We can develop a complete product that will help the speech and hearing impaired people, and thereby reduce the communication gap.
