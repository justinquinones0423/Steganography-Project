# Steganography-Project

I learned how to embed hidden messages into normal-seeming image files. Within my VM, I had the option to choose preloaded images and decided to choose the mountain.jpg photo. Then using the command nano, I created message.txt and included a quote in the txt file. I then concealed the message.txt with the embed command onto the mountain.jpg. I used the steghide info command to ensure that I had did it the right way. Afterwards, I used the -xf command in order to be able to extract the hidden message from the image file in order for me to see the comparison of the newly extracted data with the original data that I had embedded.

### The steghide info screenshot shows the embedded data.

### The steghide extract screenshot shows the extraction of the embedded data.

### The steghide cat screenshot shows the "cat" command displaying the extracted message.
