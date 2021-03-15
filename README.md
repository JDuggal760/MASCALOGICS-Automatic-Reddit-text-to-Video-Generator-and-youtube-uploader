video maker
You will saw alot of channel getting popular on YouTube just by uploading “Reddit to Text-To-Speech” YouTube Videos. So I decided to create a program that can automate the process of receiving, generating and uploading these videos to YouTube with as little intervention as possible. It took me one month to complete this project. I divided the project to 3 scripts.  The idea was to minimize as much manual intervention as possible and automate all the trivial tasks. However the process cannot be 100% automated. For example comments with links in them cannot be kept as quality of the video will be comprised due to the TTS. Additionally while a comment might have a large number of votes it could potentially be offensive and not safe for a YouTube video and thus must be removed. The thumbnail, while partially generated, must be edited in order to create any kind of appeal to viewers to click on your video. The same goes for the title of the video which must be clickbait-y in order to receive any attention. I have attempted to streamline the manual process with the client program and it takes me approximately 30 minutes to create 6 videos (the max that can be uploaded within 24 hours with the YouTube Data API).



# Features

1- Takes Link of the subreddit and scrap text from post title, post body and top best comments to create video.                                                                              
2- You can change Background of the video and also text colour.                                                                                                                                  
3- Supports both male and female voices.                                                                                                                                                      
4- You can also create video by just giving text script.                                                   
5- Generates Thumbnail                                                                                                                                                                
6- Background music




# Installation and Setup

1- Just download this repo to your destop.Extract it and then open cmd and type cd {location of the folder}                                                               
2- **pip install -r requirements.txt**                                                                                                                                               4
3- Open links.txt and place the links of subreddit. To create video of multiple links seperate links with comas.
1 video per line in file no matter how much u place links in single line.it will create single video

      video1 =url1,url2,url3 all three for single video
     
    
4- Then open setting.py and choose the setting for the video like, voice, font and background.                                                                                                                                                                                                             
5- Then run run.py it will create video plus into the generated folder. with description and thumbnail                                                                             
6- To upload video on youtube first create your youtube api and save credentials.json to the folder and run youtube_video_uploader.py                                                    


#Project Envirnmonent details

Windows 10                                                                                                                                                                       
Python version  3.7.4                                                                                                                                                           




