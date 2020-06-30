# Going All-In on Open-Source AI


Author: Han Xiao, Founder & CEO of Jina AI.  
Edited by Bing He.


In early 2020, I left Tencent AI and founded my startup Jina AI. Jina AI is a neural search company that provides cloud-native neural search powered by AI and deep learning. On April 28th 2020, we released our core product *Jina* as open source. You can use Jina for searching anything: image-to-image, video-to-video, tweet-to-tweet, audio-to-audio, code-to-code, etc. To understand our ambition at Jina AI, I often explain with two analogies:


* _**"Tensorflow" for search.**_ Tensorflow, Pytorch, MXNet, Mindspore, are universal frameworks for deep learning. You can use them to tell cats from dogs, or play Go and DOTA. They're powerful and versatile but not optimized for a specific domain. In Jina, we're focusing on one domain only: Search. We're building on top of the universal deep learning frameworks and providing infrastructure for any AI-powered search application.



* _**A design pattern.**_ There are design patterns for every era: from functional programming to object-oriented programming. The same goes for search systems. Thirty years ago, it all started with a simple textbox. Many design patterns have been proposed for implementing search systems behind this, some of which are incredibly successful commercially. In the era of neural search, queries go beyond a few keywords: They can be an image, video, code snippet, or audio file. When traditional symbolic search systems can't handle these data formats effectively, people need a new design pattern for building neural search systems. That's what Jina is: a new design pattern for a new era.

<center> 

![Jina is a neural search company](https://lh6.googleusercontent.com/KY_Fx9crkb2mmLlNJWJsMdD0DEe5eeuuknXdd6xN6o8Ymro87rqyIqu2-W39MgYNLojuwIMcB5vT3pdjpqWaoVhBSxHDnCPi6vhE6sFLzcAFRm5BigbE5G-rgusaTc4V7omnXkGL)

</center>



## Who set me on this path?

I've been working in AI, especially in open-source AI, for quite some time. You may have heard of or used my previous work on [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist) and [bert-as-service](https://github.com/hanxiao/bert-as-service). From 2018 to early 2020, I was an Engineering Lead at Tencent's AI Lab, where I led a team to build the search infrastructure of China's ubiquitous app, _**WeChat**_

In 2019, I represented Tencent as a board member of the [LF AI Foundation](https://lfai.foundation). That was the year I learned how professional open-source initiatives work. 

I picked up two things at the LF AI Foundation:

* Open source = Open source code + Open governance. **Community is the key.**
* Open source AI infrastructure is the future, and I need to act **now**.

I'm sure many share my vision. But my belief is so strong that it drove me to jump out of the tech giant and build Jina AI from scratch as a startup. Challenging as it is, this is the opportunity I just can't miss, and this is the future I believe in. All of my team share this belief as strongly as I do. At Jina AI, we only do what we believe in. I always tell my team: people who actually make change are the ones who believe that change is possible in the first place.


## Challenges of an open-source software company

Running an open-source software (OSS) company needs **courage, an open mindset, and a strong belief.**


As an OSS company, when you first show your codebase to the world, you need courage. The code quality now symbolizes the company. _"Are you following best practices? Are you building technical debt here and there?"_ Open source is an excellent touchstone to help you understand and improve the quality of your software engineering and development procedures.

Embracing community is vital for every OSS company. It needs an open mindset. Doing open source is not the same as making a press release or giving a spotlight speech: it is not one-way communication. You need to walk into the community, talk to them, solve their issues, answer their questions, and accept their criticisms. You have to manage your ego and do trivial things like maintenance and housekeeping.


## The best time for AI engineering

<center> 

![Jina as a framework](https://lh3.googleusercontent.com/mv1pTEq9C42gCIz93TFVGnbVyp0j51jtgfn_ZRsHSdStG7zYscR-RKUeMBPdWta6-qG2k-_TKMoiwl69B52nIqj9itVgCSQsu6FSzkStak39hGl5mmwdGNLJSgr5GJ5FxMsXvX95)

</center>

For engineers who want to do open source AI, the time is now. Thanks to deep learning frameworks and off-the-shelf pre-trained models, there are so many opportunities in the end-to-end application market for anyone to make a significant contribution. Ask your colleagues or friends "which AI package do you use for daily tasks like machine translation/image enhancement/data compression/code completion?" - You'll get different answers every time. That's often a sign that the market is still uncontested, and there is ample opportunity for growth.

One thing I like to remind AI open-source developers about is the **sustainability** of a project. With new AI algorithms popping up every day, how do you keep up the pace? What is the scope of your project? How do you maintain the project when facing community requests? When I was developing bert-as-service, I got so many requests to extend it to AlBERT, DistilBERT, BioBERT etc. I prioritized those that fit my roadmap. Sometimes this means hard feelings for some people. But let's be frank: You can't solve every issue, not on your own. That's not how open source works and certainly not how you work. The biggest risk of open-source software is that the core developers behind it burn out. The best open source may not be the shiniest, but the one that survives the longest. So stay enthusiastic and play the long game!



## Doing open-source is doing a startup

In the end, doing open source projects is like running a startup: Technical advantage is only part of the story.

Uploading code to Github is just a starting point, and there are tasks like operations, branding, and community management to consider. Like entrepreneurship, you need to draw a "pie" that captures the passions and dreams of the community. You need to have determination and precise targets so you don't get sidetracked by community issues.

As someone with a Machine Learning Ph.D., I've never believed that some black-magic algorithm would be the competitive advantage of an open-source project. Instead, I'm more convinced that sound engineering, attention to detail, slick user-experience, and community-driven governance ultimately drive user retention.

Often, the most important thing is your understanding and belief in open source. If you're an idealist, then you'll inspire idealists to march with you. If you're detail-oriented, every little feature in your project will be worshipped by those who sweat the small stuff. If you're warm-hearted, then the community you build up will appreciate your selfless giving.



Whatever kind of person you are, it's always **your belief in open source that makes open source what it is**.


