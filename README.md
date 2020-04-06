# speak-to-text
A simple web page which convert voice to text. The wweb page uses the simple speech recognisation api for converting the voice to text. It may sound pretty complicated intially but its is quite easy when you jump in and try it out.



<h2>window.speechRecognition || webkitSpeechRecognition ||SpeechRecognition</h2>
<p>
Speech Recongnition interface resist in the Browser window object. We can define it by using the following code
<span>
            const SpeechRecognition = window.speechRecognition || webkitSpeechRecognition;
            const recognition       = new SpeechRecognition();
</span>
</p>

<p>

Once we deine the Speech Recognition we can make use of the build logic to when to start listening the voice

  :: <b>recognition.onstart</b> = () =>{
  // in this predefined function we can write our logic what should happen when the preson start talking......
  }
  
  :: <b>recognition.onresult = (event) =>{
   // in this predefined function we can write our logic what should happend once the text is recognized 
   } </b>


<h5>**This feature is not supported in all Browser**</h5>
</p>
