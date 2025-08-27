---
layout: page
title: 2025 Syllabus
permalink: /2025/syllabus/
---

# Course Introduction and Learning Goals

This course charts the evolution of automatic speech recognition by exploring the central question: *what does it mean to statistically model speech*? We begin with the foundational HMM-GMM tradition, which treated speech as a sequence of acoustic events modeled by probabilistic state machines. These acoustic models were historically guided by separate n-gram language models that imposed statistical constraints on word order. We then pivot to the modern deep learning era, examining how neural network architectures—which leverage components like attention, convolutions, and recurrent layers—revolutionized feature representation and sequential modeling to learn a single, unified statistical representation directly from audio.

As a result of taking this course and fully engaging with the material and required work, you will be able to:

* Explain the fundamental principles of statistics, probability, information theory, and computation that underpin various computational and data-driven disciplines.
* Understand and analyze trending machine learning practices for speech, including audio feature extraction, complex neural architectures around convolution and attention, and fine-tuning of neural nets.
* Develop proficiency in a Linux/Unix environment, including the command line interface, file systems, common utilities, and scripting.
* Employ version control systems (specifically `git`) and write reproducible, well-documented code to support maintainable projects.


# Essential Logistics

## At a Glance

* Course number: COSI136A

* Prerequisites: Successful completion of a foundational machine learning course, specifically either

  * COSI 104A Introduction to Machine Learning, or 

  * COSI 114A Fundamentals of Natural Language Processing I

  * Or permission by the instructor

* Class Meeting: Tuesdays, Fridays, 9:35 - 10:55am at Rosenstiel 118	

* Teaching Team

  * Instructor: Kyeongmin “Keigh” Rim, [krim@brandeis.edu](mailto:krim@brandeis.edu)

  * Teaching Assistant: Yangyang Chen, [yangyangchen@brandeis.edu](mailto:yangyangchen@brandeis.edu) 

  * Office Hours (subject to rescheduling)

    * Tu, 11:00-11:45 am, 3:30-4:15 pm, Volen 256 (K)

    * Fr, 11:00-11:45 am, 3:30-4:15 pm, Volen 256 (K)

    * OH sign-up and meet links available on class moodle

## Class communication

Let's talk about how to reach out!

* **Moodle Message Boards are your go-to** for pretty much everything else: course announcements, shared readings, and any general, non-code questions. I'll be posting all important updates there, so please check your Moodle notifications regularly. Just a heads-up, all Moodle messages, and my personal emails, will only be sent to your official Brandeis email account.

* For **private messages and individual requests, please use email**. We'll do our best to get back to you within 24 hours, not including holidays and weekends.

* Now, this is super important: **all technical questions about coding homework must go through the (private) GitHub Issue tracker**. Seriously, if you send code questions by email, we won't be able to answer them, and they'll be discarded. Also, make sure you use proper Markdown syntax and the provided question templates on GitHub, **not dumping screenshots** of your work. Issues that don't follow the templates or syntax will also be closed without an answer.Again, we'll do our best to get back to you within 24 hours, not including holidays and weekends. This system helps us keep all our technical discussions organized, ensures you receive the most efficient support possible, and helps you learn standard practices in the coder-writer community.

* And finally, our **office hours** are a great opportunity to connect! You can schedule an in-person appointment using the scheduler link on Moodle. To help us prepare, please send a quick note about the specific question or topic you'd like to discuss, if you can. If you prefer **a private conversation, please explicitly request** this in your scheduler note. Otherwise, **all office hour sessions are open to walk-ins, and you are welcome to drop by without an appointment**. However, scheduled appointments will ensure your questions and topics are prioritized. Please keep an eye on the scheduler for any adjustments due to holidays or personal matters; we'll also announce changes during class meetings. We look forward to seeing you!

* To foster a more engaged and interactive learning environment, **lecture recordings will not be provided**. We encourage everyone to be present and attentive during class!

## Required books and other materials

There is no required textbook. We will use selected chapters from [Speech and Language Processing (3rd ed. draft, web version](https://web.stanford.edu/~jurafsky/slp3/)), along with relevant conference and preprint papers. Additional required and recommended readings will be shared via Moodle posting. 

# Components of Course Work

* *In-class pop quizzes: 5%*
* *Class attendance: 10%* 
* *Class participation: 5%* 
* *Exams: 40%*
* *Homework: 40% (10%*4 or 8% *5) (or more if decrease attendance)* 

## Grades for the semester

Your final course grade is a weighted sum of all coursework. Letter grades are assigned using a fixed scale and a curve, ensuring a fair assessment of both absolute performance and relative standing within the class, reflecting collective understanding and course rigor.

* [100, 90) range: The top 30% will receive an A+, the remainder an A.

* [90, 80) range: The top 30% will receive a B+, the remainder a B.

* [80, 60) range: C

* [60, 40) range: D

* Remaining: Failing grade

## Grades for Pop Quizzes and Attendance

Pop quizzes will pop up sometimes, and they'll help us keep track of who's showing up! We won't be doing traditional attendance taking, but how you do on quizzes is closely linked to how we’ll measure attendance. So, here's the lowdown on how both will be graded:

* Quizzes: Each quiz will have two to four quick short-answer questions, worth one or two points each. We'll turn your raw scores into percentages, and then average those out for your final quiz score. If you miss a quiz, don't worry, it won't count against your quiz score – the only penalty is for your attendance score.

* Attendance: Your attendance will be determined by your participation in pop quizzes, and these participation percentages will be converted into points. Please refer to the policy section for information regarding unavoidable absences.

  * >90%: 10 points (full score!), >70%: 8, >50%: 6, >30%: 4, >10%: 2, Rest: 0

## Grades for Homework

Grading for each homework varies, as the required artifact differs. This could be code, a technical report, a reflection report, or an essay. Please refer to the individual handouts for specific grading rubrics.

### Homework Submission Policy

All homework should be submitted through GitHub Classroom. We'll grade your work based on the version at up to three different checkpoints (the immediate previous commit or tag): right at **the deadline, 24 hours after, and 48 hours after**. To account for late submissions, the scores will be **multiplied by 1.0, 0.9, and 0.8** respectively. We'll always take the highest score out of these three for your final grade. Just a heads-up, submissions made **more than 48 hours after the deadline** (unless you have a pre-approved extension) **won't be graded and will receive a zero**.

Extensions are only granted in justified situations, and we kindly ask that you request them at least 24 hours before the original deadline. Generally, reasons like workload, time management, or personal travel aren't considered valid for an extension. When you request an extension, please include any relevant documentation.

## Grades for Exams

There will be two major exams: one around the midpoint of the semester and another at the end. These exams will feature question types similar to those on pop quizzes but with increased complexity. The exact coverage and topics will be announced well in advance of the exam dates. These exams will be taken in class, using paper and pen. **Individual rescheduling cannot be accommodated to ensure fairness to other students and to prevent content leaks.** If you are unable to take an exam due to an unavoidable reason, an alternative assignment, possibly in an independent-research format, may be assigned.

# Important Course Policies

## Expectations for student contribution to coursework 

Success in this four-credit course is based on the expectation that students will contribute at least 9 hours of study time per week (in addition to class meeting time) in preparation for class, exams, and take-home assignments.

## Academic honesty 

You are expected to be familiar with, and to follow, the University’s policies on academic integrity. You are expected to be honest in all of your academic work. Please consult [Brandeis University Rights and Responsibilities](https://www.brandeis.edu/studentlife/srcs/rightsresponsibilities/index.html) for all policies and procedures related to academic integrity. Allegations of alleged academic dishonesty will be forwarded to Student Rights and Community Standards. Sanctions for academic dishonesty can include failing grades and/or suspension from the university. [Citation and research assistance](https://guides.library.brandeis.edu/c.php?g=301723) can be found on the [university library website](https://www.brandeis.edu/library/index.html).

## Laptop computer and cell phone use

To create a focused and engaging learning environment, we kindly request that electronic devices such as phones and tablets remain closed and unused during class meetings. The only exception is for laptops and tablets used exclusively for note-taking, with no other applications open. This allows everyone to be fully present and participate in discussions. **For quizzes and exams, please remember to bring a traditional pen, since absolutely no electronics are allowed during paper-based tests** (unless additional accommodation for medical reasons is pre-arranged, please refer to the information below regarding accommodation).

## Use of generative AI tools 

Unless instructed otherwise for individual assignment, quiz or exam, general policy for this course is to permit students to utilize instruct-tuned LLM tools (chatbots and code assistants) for all assignments. Brandeis University maintains an institutional contract for the Google Gemini web application, which students are encouraged to leverage for this course. It is the student's unequivocal responsibility, though, to critically evaluate the validity and applicability of all LLM output submitted; ultimate accountability rests with the student. Any infraction of this policy will be categorized as academic misconduct. **Students are advised that AI policies may vary across different courses at Brandeis, and it is imperative to adhere to the specific expectations established for each course.**

## Accommodations 

Brandeis seeks to create a learning environment that is welcoming and inclusive of all students, and I want to support you in your learning. If you think you may require disability accommodations, you will need to work with Student Accessibility Support (SAS). You can contact them at 781-736-3537, email them at access@brandeis.edu, or visit the [Student Accessibility Support home page](https://www.brandeis.edu/accessibility/index.html). You can find helpful student FAQs and other resources on the SAS website, including guidance on how to know whether you might be eligible for support from SAS.

If you already have an accommodation letter from SAS, please provide me with a copy as soon as you can so that I can ensure effective implementation of accommodations for this class. In order to coordinate exam accommodations, ideally you should provide the accommodation letter at least 48 hours before an exam.

## Respectful environment 

Brandeis University is committed to providing its students, faculty and staff with an environment conducive to learning and working, where all people are treated with respect and dignity. Please refrain from any behavior toward members of our Brandeis community, including students, faculty, staff, and guests, that intimidates, threatens, harasses, or bullies. Please consult [Brandeis University Rights and Responsibilities](https://www.brandeis.edu/studentlife/srcs/rightsresponsibilities/index.html) for all policies and practices related to respectful environment.

## Missed classes/assignments

If you have a truly major health, religious observance, or family emergency, please contact me as soon as possible so we can make sure you stay on track. In instances where a student misses class due to such an unavoidable reason, and a pop quiz occurs during that missed class, the student will still be counted towards the attendance for that specific class meeting. However, no quiz score will be recorded for the missed pop quiz.

# Student Support

Success in this course depends heavily on your personal health and well-being. **Recognize** that stress is an expected part of the college experience, and it often can be compounded by unexpected setbacks or life changes outside the classroom. Your other professors and I strongly encourage you to **reframe** challenges as unavoidable pathways to success. **Reflect** on your role in taking care of yourself throughout the academic year, before the demands of exams and projects reach their peak. Please feel free to **reach out** to me about difficulties you may be having that may impact your performance in this course as soon as it occurs and before it becomes too overwhelming.

Brandeis University provides a range of resources to support student well-being and academic success. You can find comprehensive information and access to these services at the university's [student support page](https://www.brandeis.edu/support/undergraduate-students/index.html).

