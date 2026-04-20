# Email Developer Test Task

This repo contains a responsive promotional email template built with table-based HTML and inline CSS only.

## Files

- `email-template.html` - responsive promotional email template
- `README.md` - project notes and short answers

## Notes

- Table-based layout for broader client support
- Inline CSS only
- Maximum content width of 600px
- Mobile-friendly, single-column structure
- Built with Gmail, Outlook, and Apple Mail compatibility in mind

## Short Answers

### 1. How would you test this email across different clients and devices?

I would send live test emails to Gmail, Outlook, and Apple Mail on both desktop and mobile, then verify broader rendering in Litmus or Email on Acid. I would specifically check layout, spacing, image blocking, CTA behavior, link tracking, and dark mode changes.

### 2. What steps would you take to improve deliverability and reduce the chance of landing in spam?

I would configure SPF, DKIM, and DMARC, send from a reputable warmed domain, include a plain-text version, keep the HTML clean, and avoid spammy copy or image-only layouts. I would also maintain list hygiene, honor unsubscribes quickly, and monitor bounce and engagement metrics.

### 3. Which ESPs or email platforms have you worked with, if any?

I have not worked extensively inside an ESP yet, but I am comfortable building email-safe HTML templates and adapting them for platforms such as Mailchimp, Klaviyo, Brevo, or HubSpot.
