# Final Project Biography

A short written description of the project's development, structured so as to address each enumerated category on the Final Project Rubric.

## Author

Ryan Ditcham

## Body

### Framing

The issue that I sought to address with my final project was that of uncomplicating the business certificate application process in the City of Cambridge. Individuals seeking to start their own business are faced with an enormous number of formalities that they must comply with when going through the business registration process, one of which is certification. The form that must be filed if one is seeking to certify their business spans four pages, contains dozens of fields, and is riddled with terms of art and acronyms that the average non-lawyer member of the general public would likely not understand. The form is extremely daunting all on its own, and that's before you even think about filing or trying to go through any of the other steps associated with business registration. So my goal was to streamline the process of filling out the business certificate application for the City of Cambridge so as to assist potential new business owners in getting their business up and running as swiftly and painlessly as posible. I targeted Cambridge specifically because of its notoriety with regards to being a hub for biomed, biotech, and pharmaceutical businesses, and because of how common it is for individuals to try and start new businesses in Cambridge. The main potential stakeholders for my interview are those individuals seeking to certify their business who might be confused or overwhelmed by the business certification application form, as well as both the State of Massachusetts and the City of Cambridge, since my interview should allow for new businesses to be more easily certified in the City of Cambridge. My main goal is to hopefully get more health-serving and publicly-benefical businesses certified and operational in Cambridge as efficiently as possible. The main two model personas of indidviduals who will be using my interview are those seeking to certify a new business and those seeking to renew an existing business certification.

### Research

As far as currently available options go, there really isn't much. Prospective new business creators have the obvious option of trying to fill out the form themselves which, as I addressed in my Framing section, is a tall order. Additionally, individuals seeking to fill out the City of Cambridge Business Certificate Application could bring the blank form to a law firm or private attorney and pay them for their time and assistance in filling out the form, but this would cost money that indidviduals in such a position might not be willing to spend. Finally, I got in touch with the City of Cambridge Clerk's Office, and they informed me that there some online form-filling assistance programs available to aid individuals in filling out their applications, but once again, these came at a price. That's really it as far as currently available options go, and as you can see, it really isn't much. That's why I hope to offer a free solution that bridges the gap between the user not having to pay to file the form and being able to receive some assistance in doing so.

### Ideation and Prototyping

In deciding which technical solution or design configuration to make use of in the creation my solution to the issue of the City of Cambridge's complicated Business Certification Application, I wanted to find an option that struck the perfect balance between ease of use, clarity, and clear direction to the user. The first idea that I considered was that of a QnA Markup interview, but I eventually decided against using it as my tool since I felt as though the UI was a bit harsh and bare, and I felt as though it would have lent itself better to a flow-chart than it would to the automation of my court form. I then considered using some type of step-by-step walkthrough using the Jupytr notebooks that we explored briefly in class, but I ultimately determined that this interface once again did not lend itself well to the automation of a court form. After the Jupytr Notebook, I explored the option of using any of the other tools that we discussed in class such as regular expressions, data scraping, or machine learning, but none of them really seemed appropriate or applicable when trying to apply them to the automation of a court form. Therefore, I came to the conclusion that a guided online interview through the DocAssemble platform would provide the best combination of the factors that I identified at the start of this section of ease of use, clarity, and clear direction to the user. This led to my running the Business Certificate Application through Documate to assign names and variables to the many fields on my form, before giving it a pass through the AssemblyLine Weaver, and eventually coming out with a very rough outline of a guided online interview for the form.

### User Testing

I engaged in two rounds of user testing in order to hopefully arrive at the best possible version of my interview that I had time to complete within the bounds of the class and the semester. First of all, before engaging in any form of user testing, but after running my form through the weaver, I engaged in a large amount of coding work on the form to really work out the logic of the interview to a point where I thought it made logical sense. Additionally, I did some work on the wording of the questions, but not much, just so that I could get them to a point where they would be understood by a user for testing purposes. I then began my first round of user testing by having 4 different users (1 for New Business with Signatures; 1 for New Business with No Signatures; 1 for Business Renewal with Signatures; 1 for Business Renewal with no Signatures; and 1 for neither New Business or Business Renewal) run through the interview and document their experience on a Google Form that I created and sent to them. The user feedback indicated that the wording of a lot of the questions wasn't that great, and that some of the answer formats weren't the most logical. I then went about attempting to implement changes that would address the issues that were raised in the first round of user testing, and eventually sent the same 5 users the interview again. This began the second round of user testing, except this time I constructed it in an A-B format by providing the users with a new Google Form that asked them to compare this version of the interview with the old version. The feedback was resounding that the updated version was superior to the prior version, and that is the version that I have submitted for my Final Project, with some very minimal changes to things like the Next Steps document.

### Refinement

As I mentioned in my User Testing section, I received feedback that my question wording and answer/field selection could use some work, so I sought to implement  changes that would address those issues after receiving such feedback. I went through the interview and overhauled the plain language of the questions so that all questions with entry fields were worded with a "please enter..." question while check box or yes/no questions were worded with actual sentence-style questions. Additionally, I changed the questions from Question being a brief statement of the field being filled out (i.e., Signature County) and Subquestion being the actual question (i.e., In which county was the form signed?) to only having the question in the Question area, and using the subquestion area to explain confusing parts of the questions themselves. I additionally changed the nested hide/show yesnoradio fields for the New Business and Business Renewal questions to be two separate questions with yes and no buttons. These changes were implemented into the version of the interview that I then sent back out to the same 5 testers who were then asked to compare the new version of the interview with the version that they had completed previously. The feedback on the second round of Google Forms indicated that the users all much preferred the question Plain Language structure of the second interview to that of the first. Additionally, the users seemed to be happy with the change from the nested yesnoradio questions to that of two separate questions with yes and no buttons, as well as an extra screen that would return you to the start of the interview or exit it entirely if you said no to both New Business and Business Renewal. From this point on, I only worked on updating the pre-interview instructions and the Next Steps document and left the interview as it was, as the users seemed happy with the product. It's worth noting here that no users pointed out the fact that the Business Address ZIP Code was appearing where it shouldn't on the first page, and that the date on the second page did not fully fit into the field as it should. I have tried to address these issues and was unable to find a fix to them.

### Complexity and Robustness



### Impact and Efficiencies



### Fitness and Completeness



### Documentation



### Real World Viability



### Sustainability

