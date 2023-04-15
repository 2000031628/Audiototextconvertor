Hello Everyone!!..

I am so excited to share a new article regarding a simple project which was done using Amazon Web Services. This project will explain about how to convert audio file to text by using amazon s3 and amazon transcribe.


Prerequisits:
1.creating a s3 bucket
2.creating a job in amazon Transcribe


Amazon Transcribe:
Amazon Transcribe is a cloud-based automatic speech recognition (ASR) service provided by Amazon Web Services (AWS). It enables developers to add speech-to-text capabilities to their applications, allowing them to transcribe audio recordings into text in real-time or in batch mode.
With Amazon Transcribe, users can transcribe audio files in a variety of formats, including MP3, WAV, and FLAC, among others. The service also supports multiple languages, including English, Spanish, French, German, Japanese, and Mandarin Chinese, among others.



Amazon S3:
Amazon S3 (Simple Storage Service) is a cloud-based object storage service provided by Amazon Web Services (AWS). S3 is designed to store and retrieve any amount of data from anywhere on the web, making it an ideal storage solution for a wide range of applications and use cases.
S3 provides durable, scalable, and secure storage for objects, which can range in size from a few kilobytes to terabytes. The service provides a simple web services interface that can be used to store and retrieve data, and it can be integrated with a variety of other AWS services, such as EC2, Lambda, and CloudFront.
S3 also provides several features such as versioning, lifecycle policies, access controls, encryption, and cross-region replication, which allow users to manage their data effectively and securely. Additionally, S3 can be used to host static websites, and it can be integrated with Amazon Glacier, which is a low-cost archival storage service.
Steps:
->First we need to create a bucket in Amazon s3 Service![a1](https://user-images.githubusercontent.com/96177047/232237804-0d6e7b87-3e67-457f-83d9-7e27c109ddff.png)
![a2](https://user-images.githubusercontent.com/96177047/232237920-cb08e912-78c0-4d8f-85c0-914082e0e8dd.png)
successfully created a bucket
Next we need to upload audio file into the bucket

![a3](https://user-images.githubusercontent.com/96177047/232237940-55e9b9b5-b9e4-4f5a-8b40-1655a3902d20.png)
Now we need to create a job in Amazon Transcribe service

![j1](https://user-images.githubusercontent.com/96177047/232238029-dbbf8354-3dd5-4d91-81dd-f42b47effc96.png)
![j2](https://user-images.githubusercontent.com/96177047/232238053-4b9d0695-05e1-4fec-9cf6-dabff08b5543.png)
![j3](https://user-images.githubusercontent.com/96177047/232238085-02ad691e-2dd3-414b-85fd-1a081eada966.png)
successfully created a job .
![j4](https://user-images.githubusercontent.com/96177047/232238110-4ad26792-7f1d-4f75-b92c-dc9d9a7dbb0d.png)
successfully audio file converted into text file..
In conclusion, Amazon Transcribe is a reliable and efficient solution for transcribing your audio to text. It's user-friendly, customizable, and supports a wide range of audio formats and languages. By using AWS services, you can save time and resources and gain valuable insights from your audio content. Try it out and see how it can benefit your business or personal projects.
Thank you...
