# Ideas for startups

Here are some ideas which I would love solutions for. Primarily arising from my experience of running [SigNoz](https://twitter.com/SigNozHQ) 

Though, being an enterpreneur myself, I would really want to work on a few of these ideas. But I have my plate full currently :) 

Of course, I haven't looked at all the products in the world, so may be there is a product which already solves one of these. If you know about them, please share with me by creating and issue/ PR and I will update.

So, open sourcing it in case someone finds it useful.


(Listed in no particular order)

----

### 1. Mailchimp alternative which is not markety and sends email in plain text/ minimal formating

I am looking for a way to send newsletter to our community, which ideally works with .md formatting. Mailchimp is too markety

Also, should not be priced for mid market/ Enterprise. i.e. similar pricing structure as Mailchimp

I need minimal formating options. Also, should have good deliverability rate and options/best practices to improve deliverability

#### 1. MimePost

Mimepost is a email sending platform. The platform is mostly focused on developers. The main difference between MimePost and other ESP is that the MimePost delete user's email address just after sending it. So even in case if their system got hacked then also no one will get any data. 

Still the platform is able to generate reports and analytics dashboards because they create a unique hash (irreversible) for every emails, which is then used to generate all the reports.

The platform provides both SMTP and API.

They have 2 pricing plans:

##### Free Plan
You pay $0 for every month

You can send **100,000 emails** every month for **FREE** (SPAM NOT ALLOWED)

##### Premium Plan
You pay $50/month
100k as in free plan + $0.1 for every 1,000 emails you send after that.


You can signup at their website: **https://mimepost.com/**

----

### 2. Bi directional sync between slack threads and Notion 

We use slack actively for team communications, and Notion for longer term docs like PRD, strategic plans, etc.

I would love to sync some of the interesting conversations in Notion for future reference. Current tools, only synce the first message in the thread. Can there be a tool which syncs the complete thread and keeps it synced as new comments/replies come.

I think slack link could work for this, but needs to click another link. Many times currently I add screenshots of conversations. I think there could be something better here

----

### 3. Bi directional sync between slack threads and CRM tools (Hubspot) 

Many of our user conversations happen in slack community. I would love to sync some of the interesting conversations in our CRM for future reference. Current tools, only synce the first message in the thread. Can there be a tool which syncs the complete thread and keeps it synced as new comments/replies come.

---

### 4. Tools to run open source GPT3 like models ( like Stable Diffusion) in our own infra

I would like to try if we can provide chat like interface as a feature for some parts of the product. Transformer models like GPT3 seem quite good at it
But using GPT3 model itself would be cost prohibitive from a business models perspective ( each search would cost dollars)

I think, if we run the models in our own infra - cost much more manageable (atleast not linearly scale with API calls)

