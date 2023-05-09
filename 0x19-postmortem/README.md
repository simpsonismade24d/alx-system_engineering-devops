Postmortem

My employer recently released a new version of our software (Web server software for both Employees and External Customers) and soon after, we started receiving reports from users that the software was crashing frequently. The IT team was compelled to conduct a postmortem analysis to understand the root cause of the issue, the impact it had on users and the business, and how to prevent it from happening again in the future. Though I am not in IT or development department, I however volunteered to be part of this project.

Duration:
The Postmortem lasted for 12 hours, however the issue was already days
old before successful intervention, as the development team didn’t get
to know the root cause early enough. They hardly thought about the update
that was done 4 days earlier. Because to them, the system performed
efficiently as expected 3 days after the update, so the issue with update
was not a consideration.
After diligent postmortem exercise was carried out, 5 whys was also employed-
where questions were asked considering when the issue started and the event
that preceded the occurrence. It was discover that the issue stated after
the upgrade. Their solution was now focused around the upgrade done.

Impacts:
1.Employees and customers were experiencing frequent crashes (slow response
or sudden auto log out), which was impacting their ability to use the software
and almost to frustration and loss of trust in the company.
2.The company's reputation could have been damaged if news of the crashes spread further.
3.The company might experience financial losses if users stop using the software or
request refunds.
4.This might cause eventual shutdown of the facility

Root Cause:
• The development team made a change to the software that introduced a bug that
was causing the crashes.
• The bug was not caught during testing or was not adequately tested.
• The company did not have a process in place for catching and addressing issues that arose after release.

Corrective Measures:
• The development team to identify and fix the bug that is causing the crashes.
• The team would need conducted additional testing to ensure that the fix is
effective and does not introduce new issues.
• The company released a patch or update to the software as soon as possible
to address the issue.
• The development team reviewed their development and testing processes and
identified areas for improvement and ensured that similar issues do not arise in the future.

Preventive Measures:
• Henceforth, it was established that the company would need to establish a process for catching and addressing issues that arise after release.
• The development team would need to conduct more rigorous testing before releasing updates or new versions of the software.
• The company may consider implementing a bug bounty program or other incentives to encourage users to report issues promptly.
• The development team would need to review their development and testing processes to identify areas for improvement and ensure that similar issues do not arise again in the future. 



![postmortem](https://github.com/simpsonismade24d/alx-system_engineering-devops/assets/111156398/e98839ba-392b-4dc9-8f55-40e56ac6b9cf)


