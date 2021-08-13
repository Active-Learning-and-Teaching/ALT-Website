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
  headline: "<strong>An Open Source Mobile Application for Active Learning and Teaching.</strong>"
  content: ''
  cta:
    enabled: true
    url: https://github.com/Active-Learning-and-Teaching/ALT
    button_text: Try it out here !
  image:
    image: ''
    alt_text: ALT Home
  background_image: "/uploads/2021/08/11/login-resized.png"
- template: 3-media-column
  column:
    left_image: "/uploads/2021/08/11/quiz-resized.png"
    left_description: |-
      Host Quizzes
      - Short in-class quizzes is the key for Active Learning in lectures. An instructor can host in-class quizzes instantly to test the understanding of students. The quiz itself will be shown to students in class (on ppt, whiteboard, ...), so it does not stop the flow of presentation, and does not require entering the quiz on the phone.

      - The quiz is started on mobile and the replies are given by students in the app. Quizzes can be Multiple-Choice Single-Correct, Multiple-choice Multi-Correct or Alphanumeric.

      - Summary of the quiz responses is presented to the faculty at the end of the quiz on the phone. The student responses to quizzes are auto-graded (if answers provided by the instructor) and sent as csv to the email specified by the faculty.
  right_column:
    right_image: "/uploads/2021/08/11/feedback-resized.png"
    right_description: |2-

      Host Quizzes
      - Short in-class quizzes is the key for Active Learning in lectures. An instructor can host in-class quizzes instantly to test the understanding of students. The quiz itself will be shown to students in class (on ppt, whiteboard, ...), so it does not stop the flow of presentation, and does not require entering the quiz on the phone.

      - The quiz is started on mobile and the replies are given by students in the app. Quizzes can be Multiple-Choice Single-Correct, Multiple-choice Multi-Correct or Alphanumeric.

      - Summary of the quiz responses is presented to the faculty at the end of the quiz on the phone. The student responses to quizzes are auto-graded (if answers provided by the instructor) and sent as csv to the email specified by the faculty.
- template: content-feature
  block: feature-1
  media_alignment: Left
  headline: "<strong>Create &amp; Manage Courses</strong>"
  slug: features
  content: '- Instructors can <span class="il">create</span> courses by just entering
    the course name - <span class="il">and</span> will get a unique code for it. They
    can let their students enroll with this unique code (to enroll, a student just
    has to enter the code).<br><br> - So, it can be used in any teacher-class setting
    by any teacher (in college, schools, continuing education, workshop/tutorial,
    ...) <span class="il">and</span> does not require any support from any IT infrastructure.<br><br>-
    The dashboard shows the ongoing courses of the instructor. Instructors can post
    announcements <span class="il">and</span> manage students in their courses. Instructors
    can specify email addresses to receive responses to the in-lecture quizzes/ feedback
    questions.'
  media:
    image: "/uploads/2021/08/11/dashboard-resized.png"
    alt_text: dashboard
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: ''
  headline: "<strong>Host Quizzes</strong>"
  content: '- Short in-class quizzes is the key for Active Learning in lectures. An
    instructor can host in-class quizzes instantly to test the understanding of students.
    The quiz itself will be shown to students in class (on ppt, whiteboard, ...),
    so it does not stop the flow of presentation, <span class="il">and</span> does
    not require entering the quiz on the phone. <br><br>- The quiz is started on mobile
    <span class="il">and</span> the replies are given by students in the app. Quizzes
    can be Multiple-Choice Single-Correct, Multiple-choice Multi-Correct or Alphanumeric.
    <br><br>- Summary of the quiz responses is presented to the faculty at the end
    of the quiz on the phone. The student responses to quizzes are auto-graded (if
    answers provided by the instructor) <span class="il">and</span> sent as csv to
    the email specified by the faculty.'
  media:
    image: "/uploads/2021/08/11/quiz-resized.png"
    alt_text: quiz
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: ''
  headline: "<strong>Take Instant Feedback</strong>"
  content: '- Schedule student feedback during the lecture. The feedback question
    is presented in class (on ppt, said out, ...), <span class="il">and</span> students
    can give their anonymous feedback on the app. <br><br>- The feedback can be on
    a Color-Scale or a Likert Scale. The student responses summary is shown, <span
    class="il">and</span> also emailed.'
  media:
    image: "/uploads/2021/08/11/feedback-resized.png"
    alt_text: feedback
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
  col_2: ''
  col_3: Reach out to us on mail! <br><a href="mail:to:vishwesh18119@iiitd.ac.in"
    title="Mail">vishwesh18119@iiitd.ac.in</a><br><br>
  col_4: ''

---
