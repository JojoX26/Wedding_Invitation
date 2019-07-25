# Wdding invitation online
![Platform](https://img.shields.io/badge/Platform-ios%20%7C%20win32%20%7C%20win64%20%7C%20linux-brightgreen.svg?style=plastic)
![HTML](https://img.shields.io/badge/HTML-60.1%25-green.svg?style=plastic)
![JavaScript](https://img.shields.io/badge/JavaScript-20.5%25-green.svg?style=plastic)

A simple website that allows you to send an invitation in an easy way.

### Table of Contents

- [*Introduction*](#introduction)
- [*Prerequisites*](#Prerequisites)
- [*Technologies*](#technologies)
- [*Features*](#Features)
- [*Launch*](#Launch)
- [*API Reference*](#api)
- [*Usage*](#Usage)
- [*Results*](#Results)

## Introduction

Today in our century almost everyone is connected to the network or have access to the internet almost everywhere.
In addition, it is important for us to preserve the environment and especially not to destroy it.
Therefore, this website provides both of these conditions when the main function of the site is to easily send people an invitation and to several simultaneously and effortlessly and even at no cost 
And so we kept the environment and saved time and the tree.

## Prerequisites

For the project i used windows with PhpStorm 2019.1.3.
However the code should be compatible to any operating system and compiler version as long as it support
HTML&CSS and JavaScript
- Phpstorm 2019.1.3.
- jQuery.

To ensure that it will run it is recommended to use **Chrome Dev 75.0.3770.142**

## Technologies

- HTML & CSS
- JavaScript
- Bootstrap

## Features

1. The project provides convenience for users.
2. In addition, the user will be able to choose to receive a report containing the data to which the people to whom he sent the order have provided.

## Launch

- Go [here](https://github.com/JojoX26/Yoel_Bijleveld_Wedding) and download the Zip file.
   * Click "clone for download" and download the file.
- Open the IDE editor where you want to run  
  ** NOTE: Your tools fit your requirements!!!
- Insert the downloaded files into the IDE.
- In the folders of the project there is one folder of images where you will have to put your photos to display them.

## API Reference
API for google map:
```html
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyDkM_7SBGvVcqDPOXXCQWPKMm0soTfS1Ks&callback=initMap" async defer></script>
```
API for send email:
```html
<script data-cfasync="false" type="text/javascript"
        src="https://cdn.rawgit.com/dwyl/html-form-send-email-via-google-script-without-server/master/form-submission-handler.js">
        </script>
```

## Usage
Here is an examples of JavaScript to count down to the date:
```javascript
var countDownDate = new Date("Oct 30, 2019 19:30:00").getTime();


var x = setInterval(function() {


    var now = new Date().getTime();


    var distance = countDownDate - now;


    var days = Math.floor(distance / (1000 * 60 * 60 * 24));
    var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    var seconds = Math.floor((distance % (1000 * 60)) / 1000);


    document.getElementById("days").innerHTML = days +" <small>days</small>";
    document.getElementById("hours").innerHTML = hours + " <small>hours</small> ";
    document.getElementById("minutes").innerHTML = minutes + " <small>minutes</small> ";
    document.getElementById("seconds").innerHTML = seconds + " <small>seconds</small> ";


    if (distance < 0) {
        clearInterval(x);
        document.getElementById("demo").innerHTML = "The Wedding Ceremony is Over";
    }
}, 1000);
```

## Results

as you can see this is the website should be seen

<img src="images/Screenshot (12).png" width="250"> <img src="images/Screenshot (16).png" width="250"> 
<img src="images/Screenshot (14).png" width="250"> <img src="images/Screenshot (13).png" width="250">
<img src="images/Screenshot (15).png" width="250"> 



## Contribute

The platform is right in almost every culture / event,
but I'm sure people have ideas that can integrate with the current code and even improve the code.
