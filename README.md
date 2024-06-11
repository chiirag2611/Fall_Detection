## Introduction
Human Fall Detection from a Video Clip of a CCTV camera feed, which also alerts the user via E-mail.

## Requirements
1. MATLAB - R2019b or higher
2. MATLAB Toolboxes:
   <br>a. Image Processing Toolbox
   <br>b. Computer Vision Toolbox

## Execution
Run 'falldetection_via_videoclip.m' .
This would read 'video.mp4' and detect the falling action of a human in that video.
An e-mail alert would be send to user after fall detection.

## Modification
To edit sender's and receiver's email addresses (and password and message), modify 'sendemail.m' .

