## How to run

1. Open the website in a supported mobile browser.
2. Grant motion/orientation permission if prompted.
3. Hold the phone in the position you want to use as the reference.
4. Set the reference and choose threshold settings for the experiment.
5. Move the phone slowly to confirm that the live readings, status, and chart respond.
6. Run the Watch, Read, and Snake activities and save their sessions.
7. Open the experiment comparison and inspect the recorded distributions.

Sensor APIs generally require a secure context, such as HTTPS or localhost. Support differs by browser and device. If readings do not change, check permissions and browser compatibility.

View the live website [here](https://pranavduraisamy.github.io/ed5518-dataviz/assignment2/)

View the video [here](https://drive.google.com/file/d/1FlcfOg3b3o8_-0bu2s7Fj7uwzeBMIrNg/view?usp=sharing)

## Few Important Points to Note

 - Assuming that eye level is always normal to the plane of the screen. i.e., Im excluding cases like where one could view the phone on desk just by rolling eyes, you didnt flex your neck!

 - However, for simplicity, the current website works well as a proof of concept.

 - I also had an idea of having a live notification/popup colour coded to alert the user about his/her neck posture, But due to some compatibility issues, I had to drop it.

## Video Transcripts

Hi everyone, im pranav. I did a mobile specific web application which is a phone orientation monitoring experiment. Nowadays prolonged use of mobile phone became very common. A lot of people are using phone in a much flexed neck posture. Over the time this could lead to neck pain and disc degeneration.

the idea is to read the phones gyro sensor/orientation data: as you could see here alpha, beta and gamma., and under the assumption that one is in seated or standing position with eye level normal to the plane of the screen.,

To begin with first i need to hold the phone in a proper recommended position thats screen to the eye level and set the reference position and here in the live monitor, as i tilt the phone, the live chart responds to the sensor readings.

In the experiments tabs, you need to do different tasks, like watching a video.., reading and a quick game.. 

Based on the data collected during these activities., you can look at your report here, Like in which activity and how much time my phones orientation and my neck posture changes too much.., And in the violin plots we can see the variability of samples over each activity.

Thank you
