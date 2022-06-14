# Tennis Shot Recognition Using Neural Nets

## Data
We use the THETIS dataset for our project.
http://thetis.image.ece.ntua.gr/

Sofia Gourgari, Georgios Goudelis, Konstantinos Karpouzis and Stefanos Kollias. THETIS: THree Dimensional Tennis Shots A human action dataset. In CVPR, International workshop on Behavior Analysis in Games and modern Sensing devices, June 2013


## Models
Our model files are in the "Code" directory. We extract frames from the videos, and try out 4 models - a base CNN with all 12 class, a CNN with 2 classes, changing our inputs from 3D to 4D and trying out the same CNN with 2 classes, and finally LRCNN. The last model has been referenced from the existing work done by Vincent Chow and Ohi Dibua. The link for their repository is as below:
https://github.com/chow-vincent/tennis_action_recognition



