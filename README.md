# GREEN - Letter image identification to FSL and vice versa
Project Description:
An image of a letter or a Filipino Sign Language (FSL) hand gesture will be shown and the application will output its equivalent in FSL or Filipino alphabet letter. The application will initially apply a Gaussian filter to the image in a process called Gaussian smoothing using the command “B = imgaussfilt()” to remove any unnecessary noise. It then converts the image into grayscale using “rgb2gray()” for image detection [1] and [2]. The converted image has its background removed to only have the shape of the hand retained via “graythresh()” [3]. It is then compared with the reference image found in the database via “r = xcorr(x,y)”. Xcorr is a command where the similarities between two images/signals is compared and the highest similarity among all the set images is considered as the equivalent letter [4],[5] and [6]. It then outputs the equivalent image to the user.

Final Paper: https://tinyurl.com/4AFinalPaper


Project Demonstration: https://youtu.be/PPe3et3wgvA
