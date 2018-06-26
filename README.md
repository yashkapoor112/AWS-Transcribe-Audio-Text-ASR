This project Converts the required Audio to Text using Amazon's Transcribe.

The application is fully hosted on an ubuntu instance.
Anyone who wants to access the project needs to have his/her own AWS Account and a machine running with Ubuntu AMI.

The s3 bucket used here is CORS Configured.

This is just a test application demo and hence it is not Secured with Certificated but you can get the hang of it if you disable the securities in your respective browsers.
(Prefer Firefox)

The language supported is English only.
The whole proces takes around 20 seconds to complete and the result is mostly accurate provided the audio is clear and not much noisy.

Flow of Control:
1.	Open the following Link on Firefox only:
	http://ec2-13-59-51-159.us-east-2.compute.amazonaws.com/Final-Project/demo01.html
2.	Allow the microphone access to the webpage

3.	Now record the audio of your choice and save it to a directory of your choice.


4.	Now open the same link on chrome with disabled CORS. 
	(Note – Steps to disable CORS on chrome at last.

5.	Click the Browse button and chose the desired file you want to convert to text. (You can use the recorded voice or any other file for conversion mp3 or wav)

6.	Now upload the chosen file.

7.	Your converted text should appear on AWS Transcribe Jobs page on US-east(Ohio) region
	https://us-east-2.console.aws.amazon.com/transcribe/home?region=us-east-2#jobs



Disabling CORS on Chrome:
1.	Open Run on windows 

2.	Type “chrome.exe –disable-web-security” without quotes.

3.	Hit enter.

4.	Use the window that appears to open the link provided above.

Note – Make sure that during this process all the instances of chrome are closed.







