***#Day 1 Systems Thinking***






***Deliverables***



***1. Requirements Document***

LearnLanka — Requirements Document



&#x09;(1) Problem Statement

&#x09;Learnlanka is an online learning platform that connects (Ordinary level / advanced level) students with a tutor virtually for a one-on-one online sessions.



&#x09;(2) Personas
	Goal: What they wants to achieve.

&#x09;Frustration: What makes it difficult.

&#x09;
#STUDENT 

Goals

* Search and Find qualified tutor who he/she can trust.
* The students need to search for a tutor who undergoes their requirements like language, subject, price per session and the available time.



Frustations

* Difficult to know whether a tutor is trustworthy.
* Can't promise if the tutor would complete the teaching path.
* Will the tutor be available at the said timings.
* online payments feeling unsecure.



\#TUTOR

Goals

* Find the correct audience who suit their teaching style.
* Reach more students
* Support every student who need more improvement.



Frustations

* Difficulty managing time and session bookings.
* Difficulty attracting new students and getting bookings.





\#OPERATIONS ADMIN

Goals

* Make the system run smoothly.
* Making Only genuine qualified tutors to be able to register themselves.
* Maintaining the trust between Tutors and Students
* Ensuring the payments , bookings and complaints are handled well on their own terms.





Frustations

* Difficulty in filtering and identifying unqualified teachers.
* Difficulty in checking and taking action on every filed complaints.
* Difficulty in maintaining the Student-tutor network and students making the payments on time.
* Difficulty in handling too many bookings and  cancellations.



&#x09;(3) Functional Requirements



STUDENT

* The system shall allow students to register and create an account.
* shall search for a Tutor based on the subject, grade , language and pricing.
* Be able to book a 1 hour session with their desired Tutor.
* Be able to view the date and time of the booked sessions.
* Make the payments after the session is concluded.
* Able to comment and rate on tutors.


TUTOR

* Be able to register their self with their qualifictions and current occupation status.
* Be able to be viewed and reached by students.
* Be able to publish availability slots. 
* accept or decline bookings.
* cancel bookings with at least 12 hours notice.
* Be able to comment students.


OPERATION ADMIN

* Review tutor profiles before approving them.
* View registered student profiles.
* Verify / Remove unqualified Tutors.
* View \& Manage complaints filed.







&#x09;(4) Non-Functional Requirements



|***Category***|***Metric***|***Target***|***How we'll measure it***|
|-|-|-|-|
|Performance|Tutor search response time|Under 800 ms for 95% of searches|Run search performance tests|
|Availability|Booking endpoint uptime|99.5% per month|Monitor endpoint uptime|
|Security|Payment card data storage|No card data stored on LearnLanka servers|Review database and payment integration|
|Scalability|Simultaneous video sessions|2000 sessions|Run a load test with 2000 concurrent sessions|





&#x09;



(5) Assumptions
* Students must create an account before booking a tutoring session.

* Tutors must submit their qualifications for verification before their profiles are approved.

* Students need a stable internet connection and a compatible device to attend online sessions.

* Students can book a tutor only if the selected time slot is available.

* If a payment fails, the booking will remain unconfirmed until the payment is completed.




&#x09;(6) Out of Scope

* An integrated Learning Management System (LMS) for students, including tutorials, notes, and books provided by tutors.
* A feature allowing tutors to access their session history for up to two years.
* A feature allowing students to access their past booked-session history for up to two months.
* Free trial sessions before booking a paid tutoring session.



