# Self-Evaluation: Emoji Vacation

## Checklist

### Correctness

- [x] Image background shows trees 60% of the time, and mountains 50% of the time (mountains and trees may both appear in one image)
- [x] The program draws a “family” of emojis, containing a number of emojis based on the parameters to `createFamily()`
- [x] Each emoji in the family is randomly selected, based on your implementation of `createRandomEmoji()`
- [x] When run, your program iterates through an endless slideshow of these emoji photos, each with randomized backgrounds and emoji styles
- [x] There is a pause for three seconds on each image so that a viewer may enjoy the slideshow!
- [ ] (Optional) Additional randomly-selected background scenery
- [ ] (Optional) A dark transition between each slide of the slideshow
- [ ] (Optional) Child and adult emojis are shown in a random order
- [ ] (Optional) Modify the background to include multiple times of day in the random scenery

### Code Style

Check these items from the [Comp 127 Style Guide](https://comp127.innig.net/resources/style-guide/):

- [x] all classes are in packages
- [x] package names start with a lowercase letter
- [x] newly created Java files have a header comment with
    - [x] author name
    - [x] brief description of class, and
    - [x] acknowledgement, if appropriate
- [x] identifier (variable and method) names are descriptive
- [x] variable and method names are in lowerCamelCase (no CapitalizedNames,
  names_with_underscores)
- [x] class names are singular nouns
- [x] class names are in UpperCamelCase
- [x] proper indentation:
    - [x] opening curly braces (“{”) are at the end of the line
    - [x] closing curly braces (“}”) are on their own line
    - [x] the indentation of closing braces is the same as the indentation of the
      opening statements they match
    - [x] lines are indented according to how deeply they are nested
- [x] completed TODOs are deleted
- [x] extra blank lines are deleted
- [x] unneeded commented lines of code are deleted
- [x] print statements used for testing are deleted


## Reflection

Briefly reflect in writing on your experience solving this exercise. Just a
sentence or two in response to each question is plenty.

**What did you miss? What did you wish you did better?**

I had to get help with the slideshow step. I was able to make the infinite loop that created a new picture every three seconds. I tested this by having a print statement in generateVacationPhoto to make sure the loop was working. The thing I missed was the canvas.draw() line to immediately draw the canvas. 

**What challenges did you face, and how did you overcome them?**

I had some challenges particularily with the position of the emojis. I had to mess around with the code for a while to get them in a good spot. Then, when I went to do the task to make it so that there were multiple adults and children. I was working on this code for a long time and it wasn't showing multiple emojis. I finally realized that with the code I wrote for the position wouldnt change the x value/spacing, so all the emojis were stacked on top of each other. 

**What is something that was interesting or exciting, or a lesson you learned from this experience that you want to remember?**

I really liked working with the canvas and drawing aspect of this activity. I haven't done this type of activity before so it was very interesting. 

