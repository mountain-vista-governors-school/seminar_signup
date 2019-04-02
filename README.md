# seminar_signup
An app to facilitate seminar signups at MVGS

Text From Initial Email:
I thought I'd go ahead and send out some of my thoughts for the capstone as they have changed a bit.  Tell me if this sounds good to you guys.  I decided having you jump on to the quizbowl project might be a bit jarring for all of us as we would have to figure out how to get you up to speed and have you build a portion of the site that would fit in an existing structure.  I thought it might be more fun to have you build something from the ground up so it will be completely yours, so here is my idea.

I'd like to have a application that the school uses for seminar signups.  The app would need to allow teachers at each campus to input what seminar options are available then send an email/web sign-up form to students who would be able to rank their order of preference of seminars and then allow teachers to sort students into seminars based on those choices.  Does that make sense?

Here would be my proposed requirements:

1.) This application would be something that would be used by both campuses for a long time to come so you'd leave your mark on the school.  It would need to be well put together using sound OOP practices and well documented so modifications can be made as the needs of the school evolve.  

2.) It would need to be mobile friendly (or dynamic so it looks good on any device).

3.) It would need to have a teacher setup side that allows for non-technically adept (meaning Burton doesn't have to go manipulate a DB or code anything) to create a new seminar term (i.e. Fall 2019), designate campus for that term, and input seminar title/description/teacher/maxParticipants, etc. It would also need to allow for a deadline for students to fill out their end of things.

4.) It would need to have a student form that presents the seminar options, collects basic information (name/email/grade/campus) from the student and allows them to choose their first, second, third, and fourth choices.  It would need to have some validation like checking to make sure a student does not fill out the form twice (but maybe allows them to replace their choices before the due date).  It would need to validate student data against a simple csv file of student email addresses (or something equally easy to manage) to help in determining that their information is correct AND in helping identify who has not signed up yet.

5.) It would need a teacher sorting side that automatically sorts students to their first seminar choice then allows teachers to "approve" them as being in their seminars then send those not approved on to their 2nd and third choices until all seminars are filled.  This side would need to allow for an easy way to manually sign up a student who did not fill out the form (or messed up).  It would need to lock out students signing up after the deadline.  It would need to validate that all students have been placed in a seminar.

6.) It would need to provide a finalized list (web page) of seminar rosters (names only).  It would also need to provide a roster of just emails that is easy for teachers to copy and paste into Gmail for emailing instructions to those in their respective seminars.  

What's Next:

I will make a directory on our server called "seminar" and a DB called "seminar" and will set up a set of credentials for your guys to use to access those.  You guys will need to set up a single private repository on GitHub and invite the other  and me to collaborate.  

Unless you have a better idea, I propose we work in php since I can help a good bit with that language.  

We will need to meet on Thursday as planned and probably plan on doing that every couple of weeks until we get the project off the ground.  After that, I would just like to have email updates (or maybe a blog or something) every two weeks to hear about your progress (I realize some periods may be fairly slow, but it will help us keep it on the brain).  

Are you guys planning on using Eclipse or do you have another IDE we need to install on your laptops?  I recommend setting up a local testing server on your laptop which we can do at our next meeting if you go ahead and download it (I've been using XAMPP).  

This will be your "baby" so to speak.  I will help and consult, but I think this is a manageable project to take on and you'll enjoy it more since it will be yours.  
