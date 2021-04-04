# Switch-case-boolean
This is a switch case and boolean logic test:::]]}
The code languages used in this masterpiece are HTML and JavaScript. 
The amount of Javascript i used in the making of this was 66.8 % and
the amount of HTML i used was 33.2 %. 

sense.js files explained code are:

if($this.isKeyPressed(Keys.space)){ //if space is pressed, then (boolean logic)

  $this.toggleVisible=false //hide
  
} //end of if statement

if($this.iskeyPressed(Keys.y)){ //if y is pressed

  $this.toggleVisible=true //show
  
} //end of second if statement


pageStarter.html files explained code is:

<html> //start of code
<br> //line break
<p> //start of paragraph
<title>testValueXrot</title> //changing the title of the selected tab
<b>PLAY</b> //writing "PLAY" in bold
  <i>PLAY</i> //writing "PLAY" in italics
    <u>PLAY</u> //writing "PLAY" underlined
</p> //end of paragraph
  
<a href="https://open.spotify.com/user/12hh5w50rmwun1exi1aq6yesd">my spotify account</a> //making it so if you press the "my spotify account", it takes you to my spotify account
  <br> //enter
<b><i><u>pLeAsE fOlLoW mE</b ></i></u> //writing "pLeAsE fOlLoW mE" in bold, italics and underline
  <br> //line break
<img src="file:///C:/Users/ianpe/Documents/frebs/c1c11388-76da-4060-9a7c-05b62249bcc4.jpg"alt="cool sloth"> //showing an image of a sloth
<audio controls > //playing a sound
<source src="horse.mp4"type="audio/mp4" > //the sound file
</audio > //end of statement
  <br> //line break / enter
  <audio controls autoplay muted > //playing a sound automatically when you run the code muted
<source src="pig.mp3"type="audio/mp3" > //the sound file
</audio > //end of audio statement
</html > //end of html code
undefined


weekreco.js files explained code is:
unfinished code - switch case
//week recogniser
switch (new Date().getDay()) {
  case 0: //if case 0 happens, the day is sunday
    day = "Sunday";
    break;
  case 1: //if case 0 happens, the day is monday
    day = "Monday";
    break;
  case 2: //if case 0 happens, the day is tuesday
     day = "Tuesday";
    break;
  case 3: //if case 0 happens, the day is wednesday
    day = "Wednesday";
    break;
  case 4: //if case 0 happens, the day is thursday
    day = "Thursday";
    break;
  case 5: //if case 0 happens, the day is friday
    day = "Friday";
    break;
  case 6: //if case 0 happens, the day is saturday
    day = "Saturday";
}
switch (new Date().getDay()) {
  case 6:
    text = "Today is Saturday";
    break;
  case 0:
    text = "Today is Sunday";
    break;
  default:
    text = "Looking forward to the Weekend";
}
var x = "0";
switch (x) {
  case 0:
    text = "Off";
    break;
  case 1:
    text = "On";
    break;
  default:
    text = "No value found";
}
switch (new Date().getDay()) {
  case 4:
  case 5:
    text = "Soon it is Weekend";
    break;
  case 0:
  case 6:
    text = "It is Weekend";
    break;
  default:
    text = "Looking forward to the Weekend";
} //end of switch case
