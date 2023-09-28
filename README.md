# Voyage Fork:
* Image to SVG Preview and Hyperlink Detection Framework snippet for URLs and Links ..
* Used for URLs or Links that are submitted or posted in your App or Platforms ..
* It uses regex to filter out http and https, (http|https) which will detect only the Hostname of the Domain ..

&lt;?php

``
$_string = preg_match_all(regex,string,match);

switch(match[0]){

case("www.google.com):

//Insert Google SVG Logo here..

break;

default:

//Return NULL..

break;

}//
``

?&gt;