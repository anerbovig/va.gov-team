### [View the GA dashboard for direct deposit](https://analytics.google.com/analytics/web/?authuser=0#/dashboard/T7daIpzoRw2LOg1BVHJ0Dw/a50123418w177519031p187673796/)

For fraud team metrics, [please go here](https://github.com/department-of-veterans-affairs/va.gov-team-sensitive/tree/master/products/identity-personalization/direct-deposit/analytics).

For direct deposit email analytics, [please go here](https://analytics.google.com/analytics/web/#/report/content-event-events/a50123418w177519031p176188361/_r.drilldown=analytics.eventCategory:email,analytics.eventLabel:direct-deposit-update&explorer-table.plotKeys=%5B%5D/).
  - Open = How many emails were open
  - Completed = How many emails were sent
  - Failed = How many emails failed to send
  - **Note**: We send the direct deposit confirmation email to both the sign-in email address as well as the email address on file in the VA.gov user profile. We do this as a security precaution, in case a fraudster tries to change the email in the profile to their own. As a result, we send more emails ("completed") than there are direct deposit submissions.
