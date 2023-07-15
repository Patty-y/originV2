# origin
(By the way add "Pat" and "Nah into a new folder called "classification" inside a folder called "data"
 # Facial Recognition AI Program

 This is a facial recognition AI network I put together. Its main goal, of course, is to recognize if an image, or face, that it sees is you or not. Of course, you can add more categories for more people, but keeping it down to just one person or not them as the only categories is a bit more accurate and less accessible to others if turned into a security program. 


## The Algorithm

After running the code I set inside of thingamajigger.ipynb, which imports and sets up everything you need, you should see an interface after running everything but the last set of code. This interface is where you can add photos, save and load models, train the AI, etc. First of all, you can add in as many pictures as you would like of your face into the first category, and more photos into the option of "nah," and then run the training at however many epochs you want. The epochs are basically how many tries it gives itself, meaning the accuracy will improve!
After it finishes training, you can see the loss and accuracy. The closer the accuracy is to 1, the better.


## Running this project

1. Open Jupyter Notebook (that's what I use and what it's configured to)
2. Run each set of code from top to bottom in thingamajigger.ipynb except for the last one. (Replace "Pat" in the 3rd set with your own name)
3. After doing this, you should see an interface. Choose either of your two categories and add pictures with the "add" feature until you reach your desired amount (shown next to "count"). Do the same with your second category.
4. Add next to "epochs" your desired amount of times that it trains itself on the images given. The more epochs you run, the more accurate the detection network can become.
5. Press evaluate. At this point, the "state" will go from "stop" to "live," which means it will now scan its camera to try and detect your face! Test it to see how accurate it is.
6. When you're done, press "save model" for the current working model to be saved into another directory (ex:/nvdli-nano/data/classification/my_model.pth)
7. Run the last piece of code, effectively exiting the notebook kernel.
8. You did it!!!


[View a video explanation here](https://www.youtube.com/watch?v=eIsQiTveKt4)
