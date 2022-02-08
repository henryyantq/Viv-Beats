# Viv-Beats
Good news!!! The 2nd version of Viv Beats (Viv Beats 2) is ready to be launched! Instead of sitting and waiting, I prepared a beta version, please check out the latest release!
![79e13960-fd70-11eb-bff4-2bfc54652939](https://user-images.githubusercontent.com/20149275/129659725-9797e295-2b22-4689-a322-8f9a2ab6f534.png)

A smartphone audio player that can follow the melody of audio to produce vibration. It is mainly designed as an Android app compatible to the Sailfish OS platform.

The app is designed using WxBit, an online IDE maintained by SCUST, stemming from the well-known App Inventor founded by MIT and some other authorities. Website: https://app.wxbit.com/

In general, this application is based on some very basic techniques that are widely used in the field of computational acoustics. The trick behind is that, we drop a window that samples the audio signal at a certain frequency, and generate a dynamic spectrum. The spectrum contains the FFT information, which consists mainly of the amplitudes of each frequency. I simply calculate the transient energy sum of all frequency channels preseted to be detected and accumulated, and generates transitory vibrations automatically according to it when an audio file is playing. The duration of each vibration corresponds to the amount of transient energy by some sort of linear transformation. Feel free to check these things out in the .aia file. The file can be loaded by any platforms affiliated to App Inventor 2, theoretically, such as Kodular, Niotron, and of course WxBit, and so on.

![e402ad70-fd6f-11eb-bff4-2bfc54652939](https://user-images.githubusercontent.com/20149275/129659753-957abcbf-dbe2-426c-b215-f8adde4e3d0a.png)

I have to say that, I'm still a rookie to this, so surely there are something unclear or wrong in what I described above as well as in the design logic of Viv Beats. Feel free to let me know!

I'll be updating this application unscheduledly ^_^

SONY has a similar but more advanced technique that has already been deployed on a few of their own flagship smartphones, by which Viv Beats is partially inspired. Unfortunately, one can never experience that technology unless one has a SONY flagship smartphone, which costs at least about 699 dollars :( The latest model's price even exceeds 1000 dollars, currently in Mainland China.
