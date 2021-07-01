# <img src="https://raw.githubusercontent.com/BlackPhlox/How-To-Pimp-Your-GitHub/master/05.svg?token=AF7VVOCABXX7RNUCZP2KN23A456XM"> How To Pimp Your GitHub

So, GitHub has svg support.</br> 

Not only that, did you know you can use html and css inside the svg itself? No? Well this is what you can do this:

<img src="https://raw.githubusercontent.com/BlackPhlox/How-To-Pimp-Your-GitHub/master/01.svg?token=AF7VVOF76TABNTZHU3WCT2LA45UK4">

<img src="https://raw.githubusercontent.com/BlackPhlox/How-To-Pimp-Your-GitHub/master/02.svg?token=AF7VVOF5O447O6JFKEKCVNLA45YNG&sanitize=true">

<img src="https://raw.githubusercontent.com/BlackPhlox/How-To-Pimp-Your-GitHub/master/03.svg?token=AF7VVOAAPTXNC4ENGGGDE5DA45VHQ">

# How can I make stuff like this?

Here's how to:


`test.svg` 
```svg
<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">

      <style>
        /* Put your CSS here. */
        /* Note :hover is not supported when displaying svgs on github only when shown in raw */
      </style>

      <!-- Put your HTML here -->

    </div>
  </foreignObject>
</svg>
```
