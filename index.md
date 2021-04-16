---
layout: blocks
title: Homepage
date: 2021-04-11T02:20:00.000-04:00
page_sections:
- template: navigation-header-w-button
  block: header-2
  logo: "/uploads/2018/06/21/forestry-full.svg"
  navigation:
  - link: "/"
    link_text: TermSetter
  - link: "#view"
    link_text: View
  - link: "#register"
    link_text: Register
  - link: "#about"
    link_text: About
  - link: "#demo"
    link_text: Demo
  cta:
    url: https://code.cs.umanitoba.ca/3350-winter-2021-a02/group-6/aurora-but-better-a02-group-6
    button_text: Visit gitLab
- template: hero-banner-w-image
  block: hero-2
  slug: features
  headline: A new registration application<br><strong>TermSetter</strong>
  content: A tool that allows you to explore offered courses and enhanced the registration
    process.
  cta:
    enabled: true
    url: https://code.cs.umanitoba.ca/3350-winter-2021-a02/group-6/aurora-but-better-a02-group-6
    button_text: See on GitLab
  image:
    image: "/uploads/2021/04/16/login.png"
    alt_text: Product Shot
  background_image: "/uploads/2021/04/16/cyan.jpg"
- template: content-feature
  block: feature-1
  media_alignment: Left
  slug: register
  headline: "<strong>Browse &amp; Register</strong>"
  content: Browse the courses offered from four different departments (Accounting,
    Actuarial Study, Computer Science, and Mathematics) and get in the classes of
    your choice. Course selection and navigation is made more convenient by TermSetter!
  media:
    image: "/uploads/2021/04/16/sections.png"
    alt_text: uBuild Blocks Mock-Up
- template: content-feature
  block: feature-1
  media_alignment: Right
  slug: view
  headline: "<strong>View &amp; Organize</strong>"
  content: TermSetter will organize your courses and provide summaries to make you
    keep on track! Have your transcript by your fingertips, it had never been this
    easy
  media:
    image: "/uploads/2021/04/16/termsetter_transcript.png"
    alt_text: Customize Blocks
- template: 3-column-text
  block: three-column-1
  col_1:
    headline: Better than Aurora
    slug: ''
    content: TermSetter is user-friendly. No zoom ins, no accidentally press wrong
      rows of text, no getting kicked out. Just pure enrollment.
  col_2:
    headline: Made by local students who care
    slug: ''
    content: TermSetter is an app by students and for students. We love us a tech
      that will make our lives easier and enrollments less stressful.
  col_3:
    headline: Open-source?
    slug: ''
    content: Yes! TermSetter is open source. That means if you are a developer, you
      are welcome to share ideas and contribute on how to make TermSetter better
- template: detail-content
  block: text-1
  headline: Steps to build TermSetter!
  content: <ol><li><p>Clone the source code from our <a href="https://code.cs.umanitoba.ca/3350-winter-2021-a02/group-6/aurora-but-better-a02-group-6"
    title="">GitLab</a></p></li><li><p>Open the source code with Android Studio (i.e.
    Open an Existing Project)</p></li><li><p>Run the app (or press Shift + F10) after
    Gradle sync is completed</p></li><li><p>Feel free to create an account, browse
    and enroll in courses offered in Winter 2021!</p></li></ol>
- template: 1-column-text
  block: one-column-1
  slug: "#about"
  headline: What is TermSetter?
  content: TermSetter is an Android Application that you can use as an alternative
    to U of M Aurora. You can use TermSetter to log in, explore offered courses, and
    register for courses you want. It also provides a better GUI as well.<br><br>Termsetter
    is intended to be used primarily by university students, motivated by the necessity
    to improve upon the current Aurora system used for class enrollment. Basic features
    provided include an interface allowing student registration and login, as well
    as a student information hub. This hub will allow students to both manage account
    information and display academic progress, such as course history, final grades,
    and tuition fees.<br><br>Termsetter will introduce two unique features. A section
    dedicated to course enrollment will allow exploration and self-enrollment in currently
    offered classes. Termsetter explores and self-enrolls currently offered classes.
    The offered classes view first displays all categories of classes. When a category
    is chosen, a list of classes under that category appears. Classes will include
    the class name, section, instructor, class time, and cost. The student is able
    to enroll in a class if it does not have time conflicts with other classes and
    if they have met the prerequisites for the classes. Otherwise, there will be a
    visual signifier indicating that they cannot take these classes.<br><br>The class
    timetable displays the classes that a student is currently enrolled in like a
    day or week view. The day view sorts the classes from the earliest to the latest
    and displays them as a list. The week view will display the classes under each
    day side by side. The course tree displays a graphical view of the core classes
    in the student’s program. Branches will indicate what classes are required by
    others as prerequisites. The student’s graduation progress is visually signified
    by moving through the course tree and is noted by the remaining number of credits
    for core classes and electives.<br><br>Prior to release, early iterations of the
    Termsetter will use simulated data to represent students, courses, and administrative
    entities. These will be used to perform early unit tests, prior to the implementation
    of various database structures. Later, these structures will store student-defined
    data, which are to be included in the final release of the project.<br><br>Termsetter
    will present a variety of improvements to the currently used Aurora system by
    specifically addressing usability issues brought to light by users. While Termsetter
    provides the same functionality for class enrollment, its unique features aim
    to improve ease of use, locatability of items, and quicker completion of tasks.
    The intended design direction will combine lookup and enrollment in one feature,
    providing a more simplified workflow in contrast to Aurora. The addition of a
    course tree will assist in the visualization of degree completion.
- template: 1-column-text
  block: one-column-1
  slug: "#demo"
  headline: TermSetter Demo
  content: Link to YouTube Video
- template: detail-content
  block: text-1
  headline: Postmortem
  content: "<p><strong>What took the most time? The least? Any surprises?</strong></p><p><strong>Kevin</strong>:
    Setting up HSQLDB took us the most time. Making a presentation video took the
    least time (and surprisingly my voice sounds very different from I hear)</p><p><strong>Andrea</strong>:
    Working with Enrollment took me by surprise. I thought it would be one of the
    shorter ones, assigning it an estimate of 2 days. It seems as simple enough as
    adding one SQL statement. I did not expect the depth of integration it will require:
    conflict logics, class limits, schema restructuring, dynamically generating sections,
    and passing all course and section information back and forth through seams. It
    ended up being the longest feature to implement - counting 10 days!</p><p><strong>What
    did you learn about team or large project development? What will you start doing,
    keep doing, or stop doing next time?</strong></p><p><strong>Eriq</strong>: Two
    people looking up things on Stackoverflow is better than one! Honestly, working
    in a group of talented programmers and designers put me at ease. Trusting people
    you don't know is very hard and I feel that I have an entry level understanding
    of the development cycle and how a team must work together to make the vision
    statement a reality. In the future, I plan to communicate with my team more and
    not ghost them entirely. It took a lot of communication and annoying my teammates
    with dumb questions to learn the many different ways you can do something. Everyday
    we relied on each others strengths to move us forward.</p><p><strong>Can you draw
    any conclusions from what you've done?</strong></p><p><strong>Mika</strong>: Android
    Studio is the Tim Hortons of software consistency</p><p><strong>Andrea</strong>:
    Diving headfirst to Android Studio(with its mediocre documentation) and learning
    the strings from scratch is not an easy feat. Our team took great risks implementing
    functionalities our way and meddling with unfamiliar libraries. Next time, we
    should remember that a sample project exists and that we should copy its existing
    patterns</p>"
- template: 1-column-text
  block: one-column-1
  headline: TermSetter Velocity Graph
  content: <img src="/uploads/2021/04/16/termsetter_velocity_graph.png"><br>As we
    progressed through iterations our estimates became better, partly due to the fact
    that they were more difficult to apply in the beginning. Features in later iterations
    were reliant on code established in earlier iterations so It became easier to
    measure how much we could get done between them.
  slug: ''
- template: simple-footer
  block: footer-1
  content: TermSetter © 2021<br>Made with love by Andrea, Eriq, Farjad, Kevin, Mika,
    and Tuan (Group 6, A02)

---
