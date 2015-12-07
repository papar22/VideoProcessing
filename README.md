# VideoProcessing
A project supported by Max Plack Institute of Intelligent System
The main aim of the work is to automatically create an appropriate layout for online courses and lectures.  In this case, a proper framework should be composed of both the lecture slides and the speaker/teacher. To this aim, computer vision and machine learning  based algorithms are applied.

There are many advantages to online and computer-based learning when compared to traditional face-to-face courses and lectures, however, there are a few disadvantages as well.
Online courses are great for self-motivated individuals who want to learn new skills and advance their careers and their knowledge without attending in the college or university. Getting education online will also save tons of money. Although some would argue that online education is only an awesome alternative to traditional education because of the savings and convenience, there are actually many other advantages. Only online education fully integrates itself into today’s educational technology. It is also more efficient for fast and especially motivated learners and offers skills that lack resources in traditional education despite high demand from employers. 

Class work can be scheduled around work and family.
It reduces travel time and travel costs for off-campus students.
Students may have the option to select learning materials that meets their level of knowledge and interest.
Students can study anywhere they have access to a computer and Internet connection.
Self-paced learning modules allow students to work at their own pace.
Flexibility to join discussions in the bulletin board threaded discussion areas at any hour, or visit with classmates and instructors remotely in chat rooms.
Instructors and students both report e-Learning fosters more interaction among students and instructors than in large lecture courses.
e-Learning can accommodate different learning styles and facilitate learning through a variety of activities. Develops knowledge of the Internet and computers skills that will help learners throughout their lives and careers.
Successfully completing online or computer-based courses builds self-knowledge and self-confidence and encourages students to take responsibility for their learning.
Learners can test out of or skim over materials already mastered and concentrate efforts in mastering areas containing new. information and/or skills.
In this case, the demand of taking online classes is increasing and there are many universities and educational organizations which offer free online courses. Therefore, there are some attempts to provide students and online-audiences with a high quality and interesting videos so that they can follow all of the course material in a desire manner. For this purpose, besides the slides/board including the taught sections, it is worthy to watch the speaker/teacher's reactions during the class.

As it was mentioned, we try to have both speaker and slide parts in a single video and then broadcast it on the net. In summer school 2013, there were some efforts to do it manually or to make it by helping of two cameras. One camera has been concentrated on the slides to record the video and another one has been manually controlled by a person to track the speaker during the lecture. But the synchronization of two cameras is challenging and recording the videos for speakers' movements is time consuming. Thus, a high resolution 4k camera is used in Livius project to record the lectures and by means of image analysis, computer vision and machine learning approaches, one detects not only the slides, but also tracks the speaker in an intelligent manner as automatic as possible.


One can see the whole framework of the project in the figure. The whole project can be divided into three major tasks. The first one is video processing and it is related to all algorithms, pre- and post-processing steps for slide detection and speaker tracking. Here, the processing tasks can be done either on the video file itself or on the separate frames. The second one can be called video editing and it includes all necessary works for the codecs of the video, the final layout, the background image, the logo and concatenating all together to form the final version of the video. The third part is audio processing and it refers to all works on audio signal either stereo or mono. Finally, the improved version of audio signal will be reconnected and synchronized with video file to create the final video with desired layout). 
