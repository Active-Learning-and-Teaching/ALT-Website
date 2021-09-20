---
layout: blocks
title: Home
date: 2021-07-19T19:30:00.000+05:30
page_sections:
- template: navigation-header
  block: header-1
  logo: "/uploads/2021/08/11/logo-svg.svg"
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
  headline: "<strong>Open Source Application for Active Learning &amp; Teaching</strong>"
  content: <br><img src="/uploads/2021/08/17/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d416e64726f69642d677265793f7374796c653d666c6174266c6f676f3d616e64726f6964266c696e6b3d68747470733a2f2f6769746875622e636f6d2f4163746976652d4c6561726e696e672d616e642d5465616368696e672f.svg">
    <img src="/uploads/2021/08/17/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2d694f532d626c61636b3f7374796c653d666c6174266c6f676f3d6170706c65266c696e6b3d68747470733a2f2f6769746875622e636f6d2f4163746976652d4c6561726e696e672d616e642d5465616368696e672f414c542f72.svg">
  cta:
    enabled: true
    url: https://github.com/Active-Learning-and-Teaching/ALT/releases
    button_text: Download
  image:
    image: "/uploads/2021/08/11/login-resized.png"
    alt_text: ALT Home
  background_image: ''
- template: 3-column-text
  block: three-column-1
  col_1:
    content: <br><br><img src="/uploads/2021/08/11/dashboard-resized.png"><br><br><strong><span
      class="light"><br></span></strong><br>An Instructor can easily create a course
      by providing the course name. A unique invite code is generated for the course
      that can be shared with the students. The students can join a course using the
      respective invite code. The app does not require any IT infrastructure support
      and thus can be used in any teacher-class setting (Schools, Colleges, Workshops).<br><br>The
      dashboard shows the ongoing courses of the instructor. The instructors can post
      announcements <span class="il">and</span> manage students in their courses.
      They can also specify email addresses for receiving responses to the quizzes
      and feedback.
    headline: 'Create & Manage Courses '
    slug: ''
  col_2:
    content: <img src="/uploads/2021/08/11/quiz-resized.png"><br><br><br><br>Short
      in-class quizzes are the key to Active Learning in lectures. An instructor can
      host in-class quizzes instantly to test the understanding of students. The quiz
      itself will be shown to students in the class (on ppt, whiteboard, ...), so
      it does not stop the flow of the presentation, <span class="il">and</span> does
      not require entering the quiz on the phone.<br><br>The quiz is started on mobile
      <span class="il">and</span> the replies are given by students in the app. Quizzes
      can be Multiple-Choice Single-Correct, Multiple-choice Multi-Correct or Alphanumeric.<br><br>A
      summary of the quiz responses is presented to the faculty at the end of the
      quiz on the phone. The student responses to quizzes are auto-graded (if answers
      are provided by the instructor) <span class="il">and</span> sent as CSV to the
      email specified by the faculty.
    headline: Host Quizzes
    slug: ''
  col_3:
    headline: Take Instant Feedback
    content: '<img src="/uploads/2021/08/11/feedback-resized.png"><br><br><br><br>Schedule
      instant student feedback during the lecture. The feedback question is presented
      in class (on ppt, said out, ...), <span class="il">and</span> students can give
      their anonymous feedback on the app. <br><br>The feedback can be on a Color-Scale
      or a Likert Scale. The student responses summary is shown <span class="il">and</span>
      also emailed to set email ID.<br><br>A small summary of feedback is shown post
      feedback. This can be used: to improve the learning environment, and understand
      how well is the audience grasping key concepts or not.'
    slug: ''
- template: full-width-media-element
  block: media-1
  image: "/uploads/2021/08/31/output-vid.gif"
  caption: ''
  slug: ''
- template: 1-column-text
  block: one-column-1
  slug: "#vision"
  headline: VISION
  content: "- Active learning is any learning exercise in which the student engages
    or interacts with the learning process instead of passively taking in the information.<br><br>-
    Studies have shown that active learning exercise during the lecture helps students
    absorb the lecture material much better. Similarly, in-class feedback on any issue
    (e.g. have you understood topic taught) is an important input to help improve
    learning during lectures.<br><br>- The challenge is how to do the Active Learning
    exercises or take feedback without breaking the flow of lecture or losing control.<br><br>ALT
    (Active Learning and Teaching) is a mobile App that allows active-learning quizzes
    and feedback during the lectures - the quizzes and feedback questions are given
    to students as part of the lecture <em>(so it does not break the faculty member's
    flow and does not require entering them on mobile), </em>while providing instant
    summaries on the phone."
- template: detail-content
  block: text-1
  headline: Built With Privacy in Mind
  content: "<p>A special feature of the app is that the system keeps <em>minimal information
    about the people and quizzes/feedback at the backend.</em></p><p>- The quiz/feedback
    questions are not even entered in the app. The answers to quizzes (or feedback
    questions) are not saved in the backend - they are processed for summarization,
    and then the detailed record is mailed to the faculty as csv (only the result
    of the last quiz is kept due to technical design).</p><p>- At the end of the course,
    the student/instructor can delete their account, and their records in the backend
    will also be deleted.</p><p><em>This enhances privacy and security (as no records
    are kept, even a hacker cannot get them!)</em></p>"
- template: simple-footer
  block: footer-1
  content: "<strong>Made with ❤︎ using React Native and Firebase</strong>"
- template: 4-column-footer
  block: footer-2
  image: "/uploads/2021/08/11/logo-svg.svg"
  col_2: Open source App
  col_3: Reach out to us on mail! <br><a href="mail:to:vishwesh18119@iiitd.ac.in"
    title="Mail">vishwesh18119@iiitd.ac.in</a><br><br>
  col_4: ''

---
