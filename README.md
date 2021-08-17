# Viv-Beats
A smartphone audio player that can follow the melody of audio to produce vibration. It is mainly designed as an Android app compatible to the Sailfish OS platform.

The app is designed using WxBit, an online IDE maintained by SCUST, stemming from the well-known App Inventor founded by MIT and some other authorities. Website: https://app.wxbit.com/

In general, this application is based on some very basic techniques that are widely used in the field of computational acoustics. The trick behind is that, we drop a window that samples the audio signal at a certain frequency, and generate a dynamic spectrum. The spectrum contains the FFT information, which consists mainly of the amplitudes of each frequency. I simply calculate the transient energy sum of all frequency channels preseted to be detected and accumulated, and generates transitory vibrations automatically according to it when an audio file is playing. The duration of each vibration corresponds to the amount of transient energy by some sort of linear transformation. Feel free to check these things out in the .aia file. The file can be loaded by any platforms affiliated to App Inventor 2, theoretically, such as Kodular, Niotron, and of course WxBit, and so on.

I have to say that, I'm still a rookie to this, so surely there are something unclear or wrong in what I described above as well as in the design logic of Viv Beats. Feel free to let me know!

I'll be updating this application unscheduledly ^_^
