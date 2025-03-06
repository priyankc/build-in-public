---
layout: post
title: "New Prototype: Help you do better code reviews"
date: 2024-03-10
categories: projects
---

**Hypothesis:** Code reviews are a big part of developers job. It takes time to process at a high level what a diff is about. It leads to longer cycle times. Faster comprehension of diffs leads to quicker, higher-quality code reviews, reducing cycle times.

**Solution:** In many teams, developers walk reviewers through a diff to provide high-level context. This verbal explanation helps the reviewer load the changes into memory, making the review process more effective. Our AI aims to replicate this process by providing a guided walkthrough of any given diff. 

**Install Instructions** 

1. [Download the Zip](https://drive.google.com/file/d/1zuNjpFyAbLV3_P5CUDDhFsScUI0axu9w/view?usp=sharing)
2. Unzip & Run the application
3. When security requests, permit the application

**Usage Instructions****
1. Add a root folder of your repo (left top)
2. In the right, select the diff or branch
3. Once the instructions are ready, you will see the first instruction with a sticky. You can navigate through instructions by clicking next / prev
4. Once overview is ready you can click the Overview tab. 
5. Click the little eye / pencil icon on the tab to see it in rich view


![Screenshot](/assets/images/howto.png)


**Background**

In our last iteration, we explored improving design docs. We have got great feedback from 10+ users. Based on the learnings from that prototype, this week we wanted to learn about challenges involved in understanding code. We will focus on improving code reviews, a daily activity that requires critical reading and decision-making.

<style>
    .site-footer {
        display: none;
    }

    .post-title {
        font-size: 36px;
    }
</style>