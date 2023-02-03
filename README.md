# JS-Day-9
Sound Board

The HTML code sets up the basic structure of a webpage with a title "Sound Board". It uses meta tags to set the character encoding and the viewport. The webpage also includes the Bootstrap CSS v5.2.1 stylesheet for styling the webpage.

In the body of the HTML, there are 5 audio elements defined with **`id`** attributes and **`src`** attributes that point to the audio files.

The CSS code sets up styles for the body, buttons, and some basic styles for the page. It uses a Google font "Poppins" for the font family. The styles specify the background color, font, and some basic layout styles for the page.

The JavaScript code creates buttons for each of the sounds defined in the **`sounds`** array. For each sound, it creates a button element and adds a class of "btn" for styling. It also sets the text of the button to the name of the sound.

When a button is clicked, the **`stopSongs`** function is called to pause any currently playing sounds, and the **`play`** method is called on the audio element with an **`id`** that matches the name of the button. The newly clicked button will then play the corresponding audio file.

Finally, the script.js is linked in the HTML to run the JavaScript code.
