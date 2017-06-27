# frog-classifier
A project I started during my junior years at John Jay to distinguish a frog species using a mobile application

Please open up FrogClassifierPresentation.pdf to get general ideas on my attempt or approaching this project.

I've done this a while ago so it might not run in some of Android devices since Android .apk has sensitive issue with versions. 

At this point, the apk only records a sound of frog (if you're wondering why just not use pre-built audio recorder, I hard coded recording app just to learn). To complete this project, you should be extracting sound information from a sample audio file. For example, extracting such as value like pitch, spectrum, bass and etc is necessary so that you can compare recorded file against samples. 

Extracting sound info can be done through Python + Linux. The key challenge here is to mathematical calculate differences of two audio files and determine species based on statistics.
