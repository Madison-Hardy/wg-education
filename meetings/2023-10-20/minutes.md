# .NET Education Committee Meeting
10/20/2023

### In attendance:
* Katie Savage
* Frank Odoom
* Kevin Griffin
* Nicole Miller
* Tori Brenneison
* Murat Kurtbogan
* Aman Agrawal
* Richard Hawkins
* Madison Hardy

### Recording
[10/20 Education Committee Meeting](https://dotnetfoundation.sharepoint.com/:v:/g/EUMlBJSacxlEtH-hEWpfnmwBCcJxsCGo1UzoFi1y8uAXyg)

### Attachments
* [Content submission survey](https://forms.office.com/Pages/ResponsePage.aspx?id=3G8HFsH8FUqxyjLJolWQDm8F03uiB2VCoiyUmNsltiBUNVNVOFlCT01YTU9SNkxDVFBWUlJXVEs2Sy4u)
* [Collaboration form](https://forms.office.com/Pages/DesignPageV2.aspx?subpage=design&FormId=3G8HFsH8FUqxyjLJolWQDm8F03uiB2VCoiyUmNsltiBUNVNVOFlCT01YTU9SNkxDVFBWUlJXVEs2Sy4u&Token=717e75e6ec0448c2b83f288191ae5f04)

## Agenda
The Education Committee invited and hosted Tori Brenneison of Tech Elevator to discuss how Tori and Tech Elevator are teaching .NET, how they develop curriculum, and what support DNF can provide. The conversation is summarized below, and the full details are available in the meeting recording:

* Katie: As an educator yourself in this space, do you know if the boot camp you went to is still around, and what did they teach you there?
    * Tori: It is and it's not. When I went through, I was with the first actual paid full-time cohort they hosted. Back in 2015, it was relatively new. The curriculum was really the founder winging it, and it's still around and I know they've gotten better, but I can't speak to what they're doing now.

* Katie: What kind of roles were they setting you up for? And how was that experience of getting a job after the boot camp?
    * Tori: I'm from Cleveland, so in this area there's a lot of banking, insurance, and healthcare, so there's a lot of large enterprise-scale applications. There's a lot of .NET development happening, so we would have companies come in, sometimes HR representatives or senior developers, and they would talk to us about what they were doing. I ended up at Highland Software which is a .NET shop document and content management. But this is really one of the reasons that we have a .NET Program at Tech Elevator because the .NET ecosystem in Cleveland is pretty strong. We were thinking of introducing the .NET curriculum in our National Library remote program recently, but that initiative stalled out a bit.

* Katie: From my understanding, it seems like the education you get from a boot camp is very applied and practical to the type of job you would be going for. What other resources, in addition to speakers, would they provide?
    * Tori: Tech Elevator has a curriculum development team that's responsible for maintaining the curriculum. So as an instructor, I was provided a curriculum and had the freedom to change certain things about it as long as I'm still teaching the same objectives on the same timeline. As far as other resources, we have a student book that was written by one of our curriculum developers. We also have representatives from our hiring partners come in and talk.
    * Katie: What is a student book?
    * Tori: The developers write a book for students as an internal resource.

* Katie: Can you talk more specifically about the curriculum at Tech Elevator?
    * Tori: Our program is split up into three modules and there's roughly four weeks of instruction for each one. The first module is object-oriented programming, so a "teach .NET" track, a track for Java, etc., the bare bones instruction. The .NET track recently moved up to the latest version of Visual Studio and we're running C# 11 currently.
    * At the end of module one, the students build a small capstone project. The model is a vending machine, and the code has to run the vending machine, tracking money in and items out. It's my favorite project that they do.
    * In the second module, we switch over to a client server to program patterns, so they're in SQL servers with SQL server management studio. After that, we teach them a bit of database design. At the end of module 2, they have a client program and a server program that are talking to each other, sending data back and forth into a database.
    * Module three is all HTML, JavaScript to focus on front-end framework. Their final capstone is an empty Visual Studio project and an empty database, and we ask them to build a full stack application based on our requirements using a scrum framework.

* Katie: That's a lot of ground to cover in 12 weeks. Are you seeing that students are able to secure jobs or internships after the program? How successful are they at navigating that?
    * Tori: The goal is getting a job within six months to a year. Students have career support through Tech Elevator for as long as they want it. Our job placement rate overall is around 80%, which is lower than it has been due to market conditions. We used to only track their outcomes for 180 days, but recently upped that to a year.

* Katie: Do you see any gaps in what's currently provided, or do you wish there were additional resources like mentoring to help students succeed?
    * Tori: For a while, we had support instructors that would host additional sessions with students, but the students weren't taking advantage of it. So we've been directing students to Microsoft because the material is relatively bite-sized and beginner friendly. The students can pick one, work through it, and see the instructors with additional questions.

* Katie: Can you give a little overview of the students' backgrounds? Are they doing the boot camp full time, or do they have other things going on, like a second career?
    * Tori: The program I teach is a full-time, in-person program. We have a part-time online program, and a fully remote online option that's full-time. The average student is 30 years old, has a Bachelor's degree, and seven years of non-programming work experience. The interesting thing is that we're seeing more and more students come in and do the boot camp instead of a two- or four-year degree because it's less expensive. So it's a new demographic, but the majority of students are transitioning to a new career.

* Nicole (via chat): Do you get into Open Source for the students?
    * Tori: We don't really, just because we don't have the time. But I do try to pull up a couple of Open Source projects because students need at least some exposure - they don't always believe me when I tell them that when they get into the workforce, these solutions aren't going to be the teeny, tiny solutions they see at Tech Elevator. The first time they see an actual code base often overwhelms them.

* Katie: Are there any kind of opportunities that we can do with our maintainers, ask them if there are any smaller issues that are more beginner friendly? And at what point do you think someone would be ready to contribute to an Open Source project?
    * Tori: Honestly, I don't think most of them would know where to begin.
    * Katie: Understandable; I think the step from "student" to "contributor" is quite a big one. Do the students learn GitHub?
    * Tori: Absolutely, we start on GitHub right away. There's an upstream that holds the lecture code, and they run a GitHub instance for their homework that integrates with the software that grades their homework. The process is automated, and at the end of the cohort we help them move everything from the private GitHub instance to their own repositories so they can keep all their code from the program.

* Aman: Do you utilize GitHub pages also with the repositories? (Allowing students to create a page within GitHub that houses every repository the student creates)
    * Tori: There's no requirement in the curriculum that they set up a page like that, but we want them to have the repository, so that's a good idea.

* Katie: You mentioned earlier the curriculum maintainers - how are you staying up to date with the curriculum? What resources do you use, or are there things you follow to make sure all the curriculum stays fresh?
    * Tori: It's a group effort, a constant, ongoing discussion. If any of the educators identify something that could be improved, there's a process to address it. Sometimes it's as small as a homework question that needs to be reworded because all the students are struggling with it; other times, it's an opportunity to evaluate an entire piece of the curriculum and decide whether it sets the students up for success in the future. We get feedback from our alumni support staff about what they wish they could have learned during the program, or new things they learned at a conference.

* Katie: What kind of opportunities or areas of support that you wish you knew were available to you as an educator to your boot camp, things this group could provide? We have access to awesome speakers all over the world, a big knowledge-base that could contribute some kind of content, Open Source opportunities, etc. Basically, how can we better support you?
    * Tori: One thing we do have a bit of trouble with is getting speakers to come to our panel discussions. We're supposed to introduce our students to people, but our pool of speakers is kind of small. We want speakers to talk to students about what being a developer looks like, what working security looks like. Even it there's a webinar or recorded content, we just want facetime with other professionals.
    * Katie: Well, Nicole has stepped up as a matchmaker!
    * Nicole: We have a lot of sponsors that are looking for fresh talent, so I think this is a good way for them to come together. We also have the mentorship program that we're trying to run through the Membership Committee.
    * Katie: As a committee we'll discuss and figure out how we can create a system of these connections.

Special thanks to Tori for joining and sharing her insights! Reach out to Katie or Frank if you have any questions or suggestions about how to move forward with this initiative.
