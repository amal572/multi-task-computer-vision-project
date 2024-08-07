# football players detection

This notebook explores the use of deep learning to tackle a dual-task problem in computer vision: detecting and classifying various objects within images from football matches. The primary aim is to develop an integrated model capable of both object detection and classification to enhance the automated analysis of football games.

* Goals
1. Object Detection: Identify and locate key objects within football images. Specifically, the goal is to detect:
Players: The football players on the field.
Goalkeepers: The players designated as goalkeepers.
Referees: The referees overseeing the match.
Ball: The football itself.
For each detected object, the model should output a bounding box that marks the object's location within the image.

2. Classification: Once objects are detected, classify them into specific categories. The classification task involves categorizing each detected object into one of the following four classes:
Ball: Identifying the football in the image.
Goalkeeper: Distinguishing the player who is in the goalkeeper role.
Player: Recognizing other players on the field.
Referee: Identifying the match referees.
