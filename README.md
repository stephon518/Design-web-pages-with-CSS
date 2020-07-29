# **Design web pages with CSS**

hTml5: adding hTml5 audio To Your Pages. HTML5 introduced the <audio> element to include audio files in your pages. As with HTML5 video, browsers expect different formats for the audio.
The <audio> element has a number of attributes which allow you to control audio playback.


HTML
 <!DOCTYPE html>
<html>
  <head>
    <title>Adding HTML5 Audio</title>
  </head>
  <body>
<audio src="audio/test-audio.ogg"
controls autoplay>
<p>This browser does not support our audio format.</p>
    </audio>
  </body>
<

**Multiple Audio Sources**

It is possible to specify more than one audio file using the <source> element between the opening <audio> and closing </audio> tags (instead of the src attribute on the opening <audio> tag).
This is important because different browsers support different formats for audio files.
MP3: Safari 5+, Chrome 6+, IE9 Ogg Vorbis: Firefox 3.6, Chome
6, Opera 1.5, IE9

html
 <!DOCTYPE html>
<html>
<head>
<title>Multiple Audio Sources</title>
  </head>
  <body>
<audio controls autoplay>
<source src="audio/test-audio.ogg" /> <source src="audio/test-audio.mp3" /> <p>This browser does not support our audio format.</p>
    </audio>
  </body>
</html>
    
**Color**

Color not only brings your site to life, but also helps convey the mood and evokes reactions.
There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
Color pickers can help you find the color you want.
It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

Examples


<!DOCTYPE html>
<html>
<head> <title>Color</title> <style type="text/css">
body {
background-color: silver;
color: white;
padding: 20px;
font-family: Arial, Verdana, sans-serif;}
h1 {
background-color: #ffffff; background-color: hsla(0,100%,100%,0.5); color: #64645A;
padding: inherit;}
p{
padding: 5px; margin: 0px;}
p.zero {
background-color: rgb(238,62,128);}
p.one {
background-color: rgb(244,90,139);}
p.two {
background-color: rgb(243,106,152);}
p.three {
background-color: rgb(244,123,166);}
p.four {
background-color: rgb(245,140,178);}
p.five {
background-color: rgb(246,159,192);}
p.six {
background-color: rgb(245,176,204);}
p.seven {
background-color: rgb(0,187,136);}
p.eight {
background-color: rgb(140,202,242);}
p.nine {
background-color: rgb(114,193,240);}
t
