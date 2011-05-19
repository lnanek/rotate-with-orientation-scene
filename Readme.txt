Simulates depth inside the screen of a phone, by turning a scene as you turn 
the phone. As if the phone were a cardboard box with objects inside it. You 
can see a YouTube video of this code in action here:
http://www.youtube.com/watch?v=dtWiTIJFkrw

There's also a precursor experiment with a simple object here:
http://www.youtube.com/watch?v=PjOKb7atT0g

It was inspired by this head tracking video:
http://www.tuaw.com/2011/04/11/ipad-2-gets-glasses-free-3d-display-using-front-facing-camera-fo/

Not all Android devices have front facing cameras, so I was wondering how well 
using the orientation sensor for this felt. You can't track the user's head, 
but you can track the orientation of the phone. This lets you turn the model 
when the phone is turned, as if it were a 3D object you were holding in your 
hands.

The code is mostly the very excellent ports of the NeHe OpenGL tutorials with 
a few brutal changes. You can see the originals here:
http://nehe.gamedev.net
http://www.insanitydesign.com/
