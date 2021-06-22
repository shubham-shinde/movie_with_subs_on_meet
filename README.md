# Movie With Subs On Meet

<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Movie With Subs On Meet</h3>

  <p align="center">
    Makes easy to share movies with subtitles over Google Meet.
    <br />
    <a href="https://github.com/shubham-shinde/movie_with_subs_on_meet"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/shubham-shinde/movie_with_subs_on_meet">View Demo</a>
    ·
    <a href="https://github.com/shubham-shinde/movie_with_subs_on_meet/issues">Report Bug</a>
    ·
    <a href="https://github.com/shubham-shinde/movie_with_subs_on_meet/issues">Request Feature</a>
  </p>
</p>

## About The Project

Frequently we use to gather togather over a call to watch movie or series. With Google Meet it has become very easy to connect over a call and share screen with content. 

### Problems
There are some issue with Meet:
* Sharing Full screen doesn't connect audio. To share audio we have to share a tab to browser.
* There is no support to share local stored video content. For this we have to stream content on browser tab.
* When using normal HTML5 to share content there is no support for .srt subtitles. So we have to convert .srt to webvtt format
* Again adding webvtt direct to HTML file throws CORS error in Browsers. 

### Work Around
* Using normal HTML file with video tag will render local video file on browser and then we can share this tab on Google Meet.
* HTML5 only support .webvtt subtitles so we have to convert .srt subtitles file to .webvtt and add it to video.
* To remove CORS error we have to start a server (example: http-server in node) 
<br/>
But it's a lot of work to stream a movie!!

## Solution
Movie With Subs On Meet is build to combine all these steps into one.

## Usage
-----
