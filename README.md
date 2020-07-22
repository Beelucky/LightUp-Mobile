# LightUp-Mobile
Alternative Screen Up Time

LightUp is an alternative to KeepScreen On on a mobile browser such as Android iOS and others.

The method used is to manipulate a game on a video playback and all of that is hidden and replaced with a retaining screen light

When you want another alternative for mobile android in a Apache Cordova mode you can use "LightUp.Js" to hold the light to keep screen on "Up".

So on the front page will have the first control that is press mode mouse or other events in each addition event, the initial interface is very good for making games.

Code (Execution On The Index.html): 

Everytime PageShow On *.Html..etc

<script src="LightUp.js"></script>

<script>
  // Add Variable here -->
  
var lightUp = new LightUp();

// Control Event Video Playback

document.addEventListener('mousedown', function enableLightUp() {
  document.removeEventListener('mousedown', enableLightUp, false);
  lightUp.enable();
}, false);
</script>

To switch "OFF' change EnableLightUp with >> DisableLightUp.

Maybe if it is run on a computer it will function as well as when you are watching a video playback whether the light is off? 

"Why not make a manipulation on him to hold a screen time in a mobile phone!

I have tried to hold the screen in an mobile phone like android development but it all failed or didn't work and now I just think of a video playback.

So safety and no wake lock permission !!

well,For other versions of LightUp I still have several methods such as making ping time and that is still in doubt, ok video playback for now is very good when controlling.


