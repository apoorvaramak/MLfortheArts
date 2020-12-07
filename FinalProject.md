<span style= "font-size:16px">**Title**</span>
Rhythm Gamability

<span style= "font-size:16px">**Sketch Link**</span>
[Sketch Link](https://editor.p5js.org/aramakrishnan/sketches/tjsVl7-cn)

<span style= "font-size:16px">**One Sentence Description**</span>
A rhythm game that is much more accessible because it only requires the ability to turn the head slightly. 

<span style= "font-size:16px">**Project Summary**</span>
While this project can be expanded in many areas, it was able to do the one thing I wanted it to, allow someone to play a song with just moving their head. The song that I have coded into my p5 sketch is “Mary Had a Little Lamb” because that is a simple song with only a few notes that I thought would be a good starting point for learning the movements as a user. There is a dot on the user’s nose, and a rod with a circle on the end that moves as the user moves their head. The point is to get the circle on the end of the rod to touch the top of the “note” as it passes by. The note is a rectangle that floats up to the top of the screen in one of three columns depending on what note it plays. If the rectangle is hit, it plays the AMSynth note that the note is bound to using Tone.js and will disappear. The player wants to make sure that they hit all the notes in the end. This is similar to many other video games that already exist, like Guitar Hero or Rock Band, but I created this with accessibility in mind. Now, anyone can play a rhythm game. 

<span style= "font-size:16px">**Inspiration**</span>
I became interested in this idea because accessibility is something that I am very passionate about. After taking Intro to Assistive Tech, making sure that everything I make is accessible has become a priority for me. In that class, we worked with someone that had trouble doing everyday things, which made me realize how important it is to create with all abilities in mind. Rock Band was something that I used to love as a kid, something I could play with all my siblings and just have a lot of fun. Being stuck inside for a while has reminded me of how fun video games can be, so I wanted to create a video game that everyone can play. 

<span style= "font-size:16px">**Process**</span>
To make this, I started with the code for facial feature recognition in PoseNet. From there, I tested a few different ways to manipulate the notes so that they travelled up the screen and disappeared and did everything that I wanted them to. This took a lot of trial and error and asking for help, but in the end I was able to make it all work out. Then, I worked on creating a vector so that when the head is rotated side to side, it would move across the screen so that the person can sit in the middle of the screen and hit notes on either side. This proved to be difficult because I had to flip the camera for the movement to make sense so that it was mirrored. This meant that all the numbers on the vector and the note placement had to be reconfigured and scaled so that they would be in the right place and would move the correct direction. Using Tone.js was much easier than I thought it would be. Even though most of the documentation was in pure javascript and not p5, it was still easy enough to follow and I felt that I understood why I was doing what and why it worked. I struggled a bit with adding timing between notes because having many notes playing at once creates a big crackling sound. It still has this problem, so as the song gets nearer to the end it starts to become a little crackly and I’m still working on fixing this issue. 

<span style= "font-size:16px">**Audience**</span>
This is for everyone really but it was made with people with disabilities in mind. This is something that I think would be novel and fun for abled-bodied people to play around with for a little, but I think this could mean a lot to someone with very limited movement because they would be able to play a new video game that would’ve been harder to access earlier. This is just for fun because in the end, it’s just a video game that plays a song. The movements are pretty free, but there are only a few interactions that the person can do that will allow them to win the game, which is just moving their head side to side. I chose limit interactivity because it allows for it to be more accessible, so it was a trade off worth making. 

<span style= "font-size:16px">**User Testing**</span>
What was the result of user testing? How did you apply any feedback?: User testing was helpful because it allowed me to see what other people thought about the idea and what they thought I was trying to accomplish with each part. I got some feedback about the game not being totally clear so I tried to make it more obvious what has to be done by adding more time in the beginning that allows the user to move their head around and see the vector move before the first note appears. 

<span style= "font-size:16px">**Source Code**</span>
In the p5 [link](https://editor.p5js.org/aramakrishnan/sketches/tjsVl7-cn)

<span style= "font-size:16px">**Code References**</span>
[PoseNet Facial Features](https://editor.p5js.org/ml5/sketches/PoseNet_part_selection)

<span style= "font-size:16px">**Next Steps**</span>
If I had more time, I would definitely fix the audio issues that come up at the end. Also, I would add more songs/figure out how to play the songs without having to push each individual note into the array, as it means I would have to create hundreds of notes and push each onto the array individually if I chose a longer song. There are so many things that I could fix, like making the interface more visually interesting, but there are also so many ways in which I could move the project forward and expand it.
