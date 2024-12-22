# CS231n-2024-Assignments
## 本人的斯坦福CS231n-2024完整作业解决方案（My solution for CS231n-2024 Assignments)
本人于九月末开启了这门课程的学习之旅，并于今日圆满完成所有作业（assignments），现将相关内容上传，一方面作为自己学习历程的纪念，另一方面期望能为在作业中遇到难题的同学提供些许助力。
I started learning this course at the end of September and have successfully completed all the assignments today. I am uploading the relevant content, on the one hand, to mark my learning journey, and on the other hand, I hope to provide some help to students who encounter difficulties in the assignments.

### 24年课程链接(Links to CS231n-2024)
- [https://cs231n.stanford.edu/](https://cs231n.stanford.edu/)
- [https://cs231n.stanford.edu/](https://cs231n.stanford.edu/)

### 解决方案链接(Links to solutions)
鉴于作业文件体积较大，不便于直接上传，在此为大家提供解决方案的链接：
Since the assignment files are relatively large and not convenient to upload directly, here is the link to the solutions for you:
- [https://drive.google.com/drive/folders/1nqAFioCTnVXYefqvg7JFJ5GbfX9Zv5L0?usp=sharing](https://drive.google.com/drive/folders/1nqAFioCTnVXYefqvg7JFJ5GbfX9Zv5L0?usp=sharing)
- [https://drive.google.com/drive/folders/1nqAFioCTnVXYefqvg7JFJ5GbfX9Zv5L0?usp=sharing](https://drive.google.com/drive/folders/1nqAFioCTnVXYefqvg7JFJ5GbfX9Zv5L0?usp=sharing)

### 配置(Configuration)
作业是借助Google云完成的，关于Google云的具体配置等问题，请前往原课程网站查询：
The assignments were completed with the help of Google Cloud. For specific configuration issues of Google Cloud, please refer to the original course website:
- [https://cs231n.github.io/assignments2024/assignment1/](https://cs231n.github.io/assignments2024/assignment1/)
- [https://cs231n.github.io/assignments2024/assignment1/](https://cs231n.github.io/assignments2024/assignment1/)
每次作业的配置步骤较为相似，成功配置一次后，后续操作便会得心应手。
The configuration steps for each assignment are relatively similar. Once you have successfully configured it once, the subsequent operations will become easier.
使用Google云时，请注意仅在必要情况下启用gpu运行（gpu的免费使用额度有限，具体的每日免费时长或使用量并不明确，不过次日会刷新。需注意，仅在完成pytorch和tensorflow相关作业时启用gpu才有实际作用，作业中也会有相应提示）。
When using Google Cloud, please note that you should only enable GPU operation when necessary (the free usage quota of GPU is limited, and the specific daily free duration or usage amount is not clear, but it will be refreshed the next day. It should be noted that enabling GPU is only useful when completing assignments related to PyTorch and TensorFlow, and there will be corresponding prompts in the assignments).

### 学习经验分享(Learning experience sharing)
1. **课程视频**：(Lecture videos)
    - 学习过程中，我结合观看了2017年（在b站）和2019年（在youtube）的课程视频，以下是具体链接：
During the learning process, I combined and watched the course videos of 2017 (on Bilibili) and 2019 (on YouTube). The following are the specific links:
        - [https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click&vd_source=fe7121321d95c24c1b3a52df81172aea](https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click&vd_source=fe7121321d95c24c1b3a52df81172aea)
        - [https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click&vd_source=fe7121321d95c24c1b3a52df81172aea](https://www.bilibili.com/video/BV1nJ411z7fe/?spm_id_from=333.337.search-card.all.click&vd_source=fe7121321d95c24c1b3a52df81172aea)
        - [https://www.youtube.com/watch?v=dJYGatp4SvA&list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r&index=1](https://www.youtube.com/watch?v=dJYGatp4SvA&list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r&index=1)
        - [https://www.youtube.com/watch?v=dJYGatp4SvA&list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r&index=1](https://www.youtube.com/watch?v=dJYGatp4SvA&list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r&index=1)
    - b站的视频翻译有时是机器翻译，听起来可能会有些晦涩难懂。对于2019年的视频，我借助了edge浏览器的沉浸式翻译插件并结合英文字幕观看，整体体验相对较好。
The translations of the Bilibili videos are sometimes machine translations, which may sound a bit obscure. For the 2019 videos, I used the immersive translation plugin of the Edge browser and watched them with English subtitles, and the overall experience was relatively good.
2. **课程资料**：(Lecture material)
    - 课程网站上提供了最新年份的每节课的ppt（遗憾的是，最新年份的视频仅供斯坦福学生访问），同时还有详尽的课程笔记以及丰富的阅读材料。
The course website provides the PPTs for each lecture of the latest year (unfortunately, the latest year's videos are only accessible to Stanford students). There are also detailed course notes and abundant reading materials.
    - 我的学习方法是先观看视频，再浏览新版ppt，两者在内容上大体没有显著变化。
My learning method is to watch the videos first and then browse the new PPTs. There are generally no significant changes in the content between the two.
3. **课程作业**：(Lecture assignments)
    - 课程作业主要侧重于熟悉一些基础的机器学习内容、深度学习框架以及pytorch和tensorflow的运用。起初可能会感到困惑，但随着学习的深入，思路会逐渐清晰。
The course assignments mainly focus on familiarizing with some basic machine learning content, deep learning frameworks, and the application of PyTorch and TensorFlow. At first, you may feel confused, but as you study further, your thinking will gradually become clear.
    - 做作业遇到问题时，可以参考ppt中的相关部分，或者查阅课程笔记。
When you encounter problems in doing the assignments, you can refer to the relevant parts in the PPT or consult the course notes.
    - 对于阅读材料，我只是选择性地阅读了部分论文的部分内容，若要全部读完，需耗费大量时间。我完成这门课程总共花费了两个月（其中还包括准备离散数学、概率论、大学物理等课程的期中期末考试的时间）。
For the reading materials, I only selectively read parts of some papers. It would take a lot of time to read them all. It took me a total of two months to complete this course (including the time for preparing for the mid-term and final exams of courses such as discrete mathematics, probability theory, and college physics).

总之，不必过于纠结学习这门课程所花费的时间，而应秉持着求知欲和探索欲全身心投入其中。祝愿各位同学在学习这门课程时都能收获满满！ 
In short, don't worry too much about the time spent on learning this course. Instead, you should devote yourself to it with a thirst for knowledge and a desire to explore. I wish all students can gain a lot when learning this course! 
