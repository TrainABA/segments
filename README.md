# Segments
This repository is a proof-of-concept for managing TrainABA framework for fieldwork hours via Github. 

Why would that matter? TrainABA framework would achieve it's highest level of organization if this concept works. See below.

(i) Supervisors fork the Segments master branch directly from TrainABA, preserving integrity of the official and original information (organized perfectly for the TrainABA system since we do it in-house).

(ii) Now supervisors have the TrainABA framework on their Github accounts. They tell their supervisess to fork the supervisor's repo (NOT TrainABA repo). Now, the supervisor has control of how their supervisees use TrainABA framework. It is customizable to that supervisor's needs. The supervisor's repo is "downstream". I think supervisors should keep it public, but more on that later.

(iii) Supervisors make changes directly to the forked repo on their own Github accounts, to make the content more specific. They change a meeting agenda item here, add/remove a learning objective, fill in the blanks on an item, etc.  

(iv) Since the rest of the team is "following" the supervisor's forked repo, they get emailed with changes as they happen. 

(v) A supervisor may assign something for the supervisee to do, related to the forked repo, such as linking to a learning objective on a TrainABA open source elearning course. The supervisee can add that update to the master meeting agenda by creating a pull request. The supervisor can review it and has total control. They can send a quick note that lines 3-4 need to be changed, for example. If it's perfect, the supervisor merges the pull request into the branch. Now it's in the main supervision repo for the current and future supervision cohorts. This is very helpful in keeping the team organized going forward.

(vi) Over time, you will develop your own specialized training materials for a specific purpose at your company. TrainABA can develop guidelines on this going forward, to make sure it all stays compatible. More on that later. 




### Why public?

Should I make this private or public?
Public! For so many reasons. Do what works for your organization, but consider the pros and cons. Your Github account repos are public by default, which encourages open source development as a community. If public, your colleagues and friends can more readily access the information. They can learn from what you are doing and vice-a-versa. TrainABA can learn from what you are doing, allso. We can help each other as a community. You get better at supervising by doing it more, so with practice we can all help each other out. 

But what about competition? Will other ABA companies steal your ideas and put you out of business? Not at all. You know better than anyone the demand for autism behavior intervention is high now and the bottleneck is quality staff. Demand exceeds supply, which means you are really only competing with yourself to see how many great supervisees you can produce. 

### Bigger picture is our community 

There is a bigger picture here, which borrows from the software development industry. If there is a main framework, people build downstream customized versions on top of that. It means your business can expand to another location or even franchise forking the existing repository developed over time (maybe years of supervision cohorts). You do not have to worry about sending one of your best and most trusted supervisors to the new location (covering their caseload, dealing with staff issues in the transition, disrupting client progress, etc.) because the other location supervises with the same steps.

If you are thinking in more practical terms, think about forking this repo for the supervisee cohort you will have this year. You will learn things about what works/doesn't through the course of group and individual supervision meetings. You know what you should write down but you don't have a convenient place to write it (and you are busy helping clients, which is what you should be doing), so you keep this important knowledge in your head. There's no stable copy to compare, so your knowledge drifts off over time and nobody (including you) realizes it. The information should have been saved on your forked repo from the framework you are using. If you use Github, you fine-tune your procedures as you go. That's better for every cohort following, but also requires less non-material resources from you in keeping all these supervision cohort procedures in your head while juggling deadlines, client programs, and a million other things. 
  
Think about a deserted island situation. It means when some supervisor starts a behavioral service private company on an island somewhere in Southeast Asia or wherever, they can save a bunch of time by forking a downstream repo from a supervisor from a neighboring island who has similar supervision contingencies. If the internet is spotty, even better. One click downloads it to the laptop from the local internet cafe. The supervisor makes changes on their laptop and pushes those to the main repo next week when returning to the internet cafe. There could be someone else who was thinking about starting services on another island, but does not know how to structure it. Fork the "deserted island" repo and go!


### Master branch and packages 

Let's circle back to TrainABA to close this out. What we describe here is a main, stable branch from TrainABA. Supervisors from organizations (or solo) fork this repo. They make their own personalized changes as they deemed necessary. These deviations can become scattered and eventually incompatible with the TrainABA master branch. In software development, this is a common problem. It is solved by having a stable core (TrainABA master repo) and users building packages (their own customizations) on top of that. In practical terms, a supervisor making edits to their own fieldwork segments repo does not matter. It's not supposed to be backward compatible with TrainABA master branch since, by definition, it contains the supervisor's customizations that were not on the TrainABA master branch.

The issue of packages becomes important when supervisors (and organizations) develop customized materials for a certain problem they (but not every other service provider) faces. A school-based provider may need to train supervisors on a type of billing procedure. They build a program for that in-house, not kept on the public Github account unless it is free of personal identifiers (consult legal). The clinical director can add this to the company's forked TrainABA supervision repo. To be "compatible", the clinical director adds the billing training procedures as a meeting agenda item to each of the first ten segments. The meeting agenda has a link to the item on the company's software site. The add-on for school-based services billing training is now part of the company's TrainABA supervised fieldwork system. 

What happens to the package? Does it only live on that company's account as a secret? Let's hope not, because that means all the other companies in the world facing a similar problem will need to reinvent the wheel. If you share the package with TrainABA, we can add that to our list of packages so people can find it readily and you will get credit for helping them. They might even send you a thank you message. Somebody definitely owes you a beer/cider/soda.

They could run into another company director at a local conference next month, who is having a similr problem with school-based billing provedures. They say, "Well, we made a package for that. You could just merge our package into your TrainABA supervision repo." That person can solve their school-based billing procedures woes thanks to your package. They now owe you a beer/cider/soda. TrainABA is proud that you were a good neighbor. Your package was compatible with our master branch, so your company (and others) can incorporate it easily without disrupting their supervision cohorts. Hooray! If we keep this up, just imagine how organized our community will be in 20 years? You will still be providing services, better than ever. 
 

### Your Github account: public or private?

As far as the Github account is concerned, you have an option of making it a private organizational account. If the account is organizational, no need to make it "private" since there is no personal employee or client information. If an organization wants to include that level of information, which is not necessary for using TrainABA but could be of interest to the company, they can create an organization account on Github and pay the $7 (or so) per month to Github for private repositories. 

