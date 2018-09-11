# Audio/Video Setup Guide
This document was created by Chris Bovard, Director of A/V for World IA Day 2015. It is meant to guide you to a basic understanding of audio / visual configurations, but keep in mind there are many possible configuration options. It is important to work with someone who has knowledge in this subject, if possible.

If you have any questions or need assistance, reach out: av@worldiaday.org

## Sample A/V Systems

###  Setup for Small Spaces

Use this configuration if there will be no use of audio reinforcement equipment (microphones, soundboard, mixer, amplifier).  The presenter’s laptop will be connected directly to the large display.  This configuration is only good for small spaces as hearing becomes difficult in larger spaces without sound reinforcement.
![AV setup for small spaces](/img/av-setup-small-space.png)

### Setup for Larger Spaces

This configuration builds upon the basic setup and adds sound reinforcement to the system.  It uses microphones and a soundboard to amplify the presenter’s voice and also allow for sound/music playback through the system.
![AV setup for larger spaces](/img/av-setup-large-space.png)

### Setup for Presentation + Live-Streaming and Recording

This configuration uses the previous A/V Setup for Large Spaces and indicates two “feeds” in red showing how audio and video are inserted into a streaming or recording system.  The second diagram shows a simple streaming setup.
![AV Setup for Presentation + Live-Streaming and Recording](/img/av-setup-presentation-streaming-recording.png)
![AV Setup for Streaming and Recoding](/img/av-setup-streaming-recording.png)

## Audio Video Encoder
The purpose of the Audio Video Encoder is to convert the content coming from the presenter’s laptop AND the audio system into a digital format that can be saved locally to a hard drive and also streamed live to an internet streaming service.  There are many different options for encoders.  We’ll explain two main ones below.

### Software Encoder

A software encoder is a program that runs on a local computer at the venue.  Any audio or video inputs that can be made available to the computer can be encoded for recording and streaming.  In this scenario, a high-end digital camera is not a valid source, allowing only USB webcams to be used.

- Pros: inexpensive (sometimes free)
- Cons: requires the use of a dedicated computer and may be limited on the sources that can be used

### Hardware Encoder

A hardware encoder is a hardware appliance that can switch and encode various video and audio sources for recording and streaming (Search ‘Matrox Encoder’ on Google to find common models). As a hardware appliance, it requires less configuration and no software to download nor a dedicated computer for encoding.

- Pros: can accept a much wider range of sources including high end video cameras
- Cons: expensive - check with venue technicians who may have one already

## Camera Selection
If you plan to use a camera to record or stream the event, below are some details to keep in mind:

- Consider the encoder you’re using. Software encoders can only handle inputs that the computer accept. This likely rules out cameras that output HD-SDI and HDMI. Hardware encoders also have various input types and must match your camera’s video output format. Bottom line: choose the encoder BEFORE choosing the camera.
- Many digital cameras designed photography include a video output (this includes many DSLR cameras). These cameras WILL NOT WORK for prolonged video capture for a live event. Please avoid this type of configuration.

While the video quality is lower, there are USB cameras designed for video conferencing that can work well with a software encoder. Ample light and close proximity to the presenter are important if using a USB camera.

## Setting up a streaming and/or recording system
The following instructions will walk you through using YouTube along with a freely available software encoder (Wirecast).  This configuration will allow for the capture of the presentation and video from a webcam.

> NOTE: This is only a sample of a streaming configuration and software encoder.  There are an unlimited number of ways to accomplish a live stream.  As always, it is best to consult an expert at the venue or in your area for specific assistance.

## Setup YouTube for Streaming
1. Create a new Google account for WIAD. This will create a YouTube account as well. https://accounts.google.com/signup For name information, enter the following:
  - First Name = WIAD
  - Last Name = Your location name
  For your current email address, use your official WIAD email address.

> IMPORTANT: You will need to enable Live streaming capabilities to your Youtube account. You must also create your streaming event in Youtube. This can be done accessing the “Creative Studio Tool” and then following the steps on the “Live Streaming Option” on the left menu of your Youtube Dashboard.

 For further help on livestreaming on YouTube, visit their [support center](https://support.google.com/youtube/answer/2474026?hl=en).

2. [Download WireCast Play (free)](http://www.telestream.net/wirecastplay/landing.htm): (http://www.telestream.net/wirecastplay/landing.htm)

3. Open Wirecast

4. Add your source content in the bottom section of the application. Sources are likely webcam(s) plus local or remote desktop. The audio source should be the line input of the computer if there are microphones in the system or the mic input from the webcam. These settings will vary greatly depending upon the setup of your system.
![Adding WireCast Audio Source](/img/av-setup-wirecast-mic.jpg)

5. Authenticate your YouTube account by selecting “Output Settings on the top menu” and make sure settings match the image below (except user name).
![Authenticate YouTube account by selecting "Output Settings"](/img/av-setup-auth-youtube.jpg)
And make sure the settings match the image below (**except user name**).
![Output Settings for WireCast](/img/av-setup-output-settings.png)

6. Press the Stream button on the top of the Wirecast:
![Stream button on WireCast](/img/av-setup-wirecast-stream.jpg)

7. Return to YouTube and confirm your stream has gone live.
  a. Go to your channel
  ![Confirm Go Live on YouTube](/img/av-setup-golive-YouTube.png)
  b. In the dropdown labeled “All activities”, select Live Streams.  If your content is live, it will appear here.
  c. Select your live stream
  d. Using the Share option below the video, copy the link
  ![Share option on YouTube](/img/av-setup-livestream-url.png)

8. Add this link to your Event page. This is an important step because we will be promoting our website as the main source of information for all of our celebrations. Posting this information will give people the ability to attend your celebration virtually.


## Contact
Feel free to reach out for assistance: av@worldiaday.org


## Related Resources
[YouTube encoding resource](https://support.google.com/youtube/answer/2907883?hl=en&authuser=1)



## Definitions
|Term| Definition |
|-----|----------- |
|HDMI | a standard for connecting high-definition video devices.|
|DVI | (for older monitors) Digital Visual Interface (DVI) is a video display interface developed by the Digital Display Working Group (DDWG).|
|VGA | (for older monitors) A standard for defining colour display screens for computers.|
|Feed| A sequence of images/audio processed electronically into an analog or digital format and displayed on a screen with sufficient rapidity as to create the illusion of motion and continuity.|
|Encoder| A device, circuit, transducer, software program, algorithm or person that converts information from one format or code to another, for the purposes of standardization, speed or compression.|
