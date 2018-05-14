# LiveScribe

Building upon recent advances in speech recognition and artificial intelligence, Vonex Labs is thrilled to present LiveScribe - a live call transcription, translation, and speech to text engine.

LiveScribe is Vonex’s way of easing communication across barriers traditionally presented by language and disability. 

Eg:

“**Linda**”: Linda is French. Working primarily with English staff, she does not have a full grasp of the English language. To enable her to engage in company-wide meetings, she joins calls using LiveScribe. Now she has English speech translated to French in real time during the active call.


“**Jack**”: Jack is deaf. Previously, Jack needed to wait a number of hours after earnings calls with companies that he holds shares in to know what was said during the calls. Now, Jack can see what is being said by company directors in real time.


“**Michael**”: Michael works at a law firm. To ensure that calls with his clients are recorded and transcribed, he uses LiveScribe to have a machine automatically transcribe and record private conversations. The recording of the conversation can later be sent with the transcription to Michael’s customers as a value added service.

Currently, we support two speech to text backends for the LiveScribe platform:
Google Cloud Speech-to-Text (Note, paid after the first hour)
Vonex’s version of Kaldi GStreamer Server

Once transcribed, LiveScribe allows for language translation through a number of backends.

Combining several Deep Neural Networks (DNN), Vonex’s GStreamer Server is currently being trained to recognise some of the world's most popular languages.

We are currently prioritising English language support - noting our customer base - whilst compiling data sets for a range of additional languages. We have committed to releasing this data under a permissive open source license to help promote research and development within this space. We believe Vonex’s international text and speech models will prove valuable to researchers in the future.


#Currently supported languages
-English 
-Spanish

(Updated 10/05/2018)

#For contributors

1. Create a personal fork of the main LiveScribe repository in GitHub.
2. Make your changes in a named branch different from master, e.g. you create a branch my-awesome-feature.
3. Generate a pull request through the Web interface of GitHub.

As a general rule, please follow [Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html).




