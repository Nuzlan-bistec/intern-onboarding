***LearnLanka — Ambiguity Hunt Log***



***Brief Reference***

LearnLanka connects O/L and A/L students with verified tutors for online classes. Students can search, book one-hour sessions, and pay online. Tutors manage their availability and bookings. The platform takes a 15% commission, pays tutors weekly, and supports ratings, video calls, three languages, and secure payments.



***Findings***





**#	Quote					Why ambiguous							Clarification question						Priority**

1	"vetted tutors"			The verification process is not explained.			What documents must tutors submit for approval?				High

2	"price band"			The available price ranges are not specified.			Who sets the prices and price bands?					Medium

3	"1-hour session"		Booking multiple sessions is not explained.			Can students book multiple sessions at once?				Medium

4	"pay via card or eZ Cash"	Payment timing and refunds are unclear.				When is payment collected, and how are refunds handled?			High

5	"12 hours notice"		Student cancellations and late tutor cancellations 		What happens if either party cancels late?				High

&#x09;				are not covered.

6	"15% commission"		Gateway fees and refunds may affect the calculation.		Is the commission calculated before or after fees and discounts?	High

7	"pay tutors weekly"		The payout day and failed transfers are not explained.		When are tutors paid, and what happens if a transfer fails?		High

8	"rate each other"		Rating visibility and moderation rules are unclear.		Can users edit ratings, and can admins remove inappropriate reviews?	Medium

9	"under 800 ms"			The conditions for measuring search speed are missing.		Under what test conditions must this target be met?			High

10	"99.5% monthly uptime"		Planned maintenance and third-party outages are not addressed.	How will downtime be calculated?					High









***Results Summary***

&#x09;	

|**Metric**|**Target**|**Achieved**|
|-|-|-|
|Items found|10+|10|
|High-priority items|3+|7|
|Items convertible to test cases|5+|10|







***Top 3 Questions to Ask the Founders***

Tutor verification: What documents must tutors provide, and what checks must they pass before approval?

Payments and refunds: When should students pay, and what happens if a session is cancelled or a payment needs to be refunded?

Cancellation rules: What happens if a tutor cancels less than 12 hours before a session, and what rules apply to student cancellations?



***Reflection***

**What kind of ambiguity tripped me up most?**

Payment and cancellation rules were the most confusing because the brief explains the basic requirements but does not explain what happens when something goes wrong.



**Which question is most likely to change the architecture if answered?**

The payment and refund question could affect how bookings, payments, and refunds are connected. Clarifying it early can help avoid major changes during development.





