---
layout: blocks
title: Home
date: 2021-07-19T19:30:00.000+05:30
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2021/07/19/logo.png"
  navigation:
  - link: "#features"
    link_text: Features
  - link: "#vision"
    link_text: Vision
  - link: "#team"
    link_text: Team
  - link: https://github.com/Active-Learning-and-Teaching/ALT/blob/master/README.md
    link_text: Documentation
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: "<strong>An Open Source Mobile Application for Active Learning and Teaching.</strong>"
  content: ''
  cta:
    enabled: true
    url: https://github.com/Active-Learning-and-Teaching/ALT
    button_text: 'GitHub '
  image:
    image: "/uploads/2021/07/19/1.png"
    alt_text: ALT Home
  background_image: "/uploads/2018/06/21/hero-2-bg.png"
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Create &amp; Manage Courses<br><br></strong>Instructors can create
    courses and let their students enroll with a unique code.<br>The dashboard shows
    the ongoing courses of the instructor. Instructors can post announcements and
    manage students in their courses. A robust notification system ensures that the
    users never miss an update."
  slug: features
  content: ''
  media:
    image: "/uploads/2021/07/19/2.png"
    alt_text: dashboard
- template: content-feature
  block: feature-1
  media_alignment: Right
  slug: ''
  headline: "<strong>Host Quizzes<br><br></strong>Host in-class quizzes instantly
    to test the understanding of students. The quiz can be Single-Correct, Multi-Correct
    or even Alphanumeric. The student responses are graded and visualised."
  content: ''
  media:
    image: "/uploads/2021/07/19/4.png"
    alt_text: quiz
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: ''
  headline: "<strong>Take Instant Feedback<br><br></strong>Schedule student feedback
    on the course activities. The feedback can be on a Color-Scale or a Likert Scale.
    The student responses are visualised while maintaining anonymity."
  content: ''
  media:
    image: "/uploads/2021/07/19/3.png"
    alt_text: feedback
- template: 1-column-text
  block: one-column-1
  slug: "#vision"
  headline: VISION
  content: Active learning is any learning exercise in which the student engages or
    interacts with the learning process instead of passively taking in the information.
    Studies have shown that active learning during the lecture helps students absorb
    the lecture material better. The challenge is how to do the Active Learning exercises
    to strengthen student's learning during the lecture, without losing control. ALT
    (Active Learning and Teaching) is a mobile App that allows active-learning quizzes
    during the lectures, as well as getting quick feedback from students.
- template: detail-content
  block: text-1
  headline: Built With Privacy in Mind
  content: "<p>A special feature of the app is that it keeps minimal information about
    the courses and performance in quizzes. The quizzes themselves (or the statements
    on which feedback is taken) are not given in the app but are given in the class
    (on ppt, whiteboard, paper, etc). The app allows the students to give responses,
    compiles them, and shows the summary on the faculty's app. For each quiz/feedback,
    it sends the detailed record (of responses of each student) on email (to the address
    specified by the instructor) and keeps no records. At the end of the course, the
    student/instructor can delete their account, and no record of the quizzes/feedback
    is kept on the server (other than statistical data for research on Active Learning).
    This enhances privacy (as no records are kept, even a hacker cannot get them!)</p>"
- template: simple-footer
  block: footer-1
  content: "<strong>Made with ❤︎ using React Native and Firebase</strong>"

---
