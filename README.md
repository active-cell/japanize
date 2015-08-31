# japanize
first commit
##Context
I stumble upon this beautiful program on reddit made by vvdr12. 
https://www.reddit.com/user/vvdr12

I took the code and put it in an jupyter notebook to leverage the interaction widget and make it into a small app for easier usage.

original post
https://www.reddit.com/r/glitch_art/comments/1kztnf/japanization_python_pixel_editing_bug/


##Change to the orginal program
 * at the end of the process the generated image is merged to the source using PIL's difference method
 * encapsulated the orignal program into a japanize function
 * got the threshold in the main function to allow for interaction at higher level
 * used interact_manual widget to let the user play with the settings

The images are locate on an img subfoder, all the images are form pexels
pexels.com
