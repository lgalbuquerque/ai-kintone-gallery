# Zoom Chat Snippets
<!-- markdownlint-disable -->

* [Check-in Time Slots](#check-in-time-slots)
* [Waiting Room](#waiting-room)
* [Start](#start)
* [Live on YouTube](#live-on-youtube)
* [Install Commands {Get Started}](#install-commands-get-started)
* [Kintone Customize Uploader](#kintone-customize-uploader)
* [Workshop Steps](#workshop-steps)
* [YouTube](#youtube)
* [Create a .env File](#create-a-env-file)
* [Debugging - Let's Fix Those Problems 💪](#debugging---lets-fix-those-problems-)
* [Additional Questions 🤔](#additional-questions-)
* [Create a Kintone Web Database App](#create-a-kintone-web-database-app)
* [Kintone Customization Tutorials](#kintone-customization-tutorials)
* [Quick Check-in](#quick-check-in)
* [Looking for the Kintone Subdomain Email? ✉️](#looking-for-the-kintone-subdomain-email-️)
* [Errors related to .env](#errors-related-to-env)
* [Join our Meetup Group](#join-our-meetup-group)
* [Got Kintone Questions?](#got-kintone-questions)
* [Survey - April B Workshop](#survey---april-b-workshop)
* [Write up your experience!](#write-up-your-experience)
* [Log into Kintone Subdomain?](#log-into-kintone-subdomain)
* [step-by-step guide](#step-by-step-guide)
* [Becoming a Kintone Partner?](#becoming-a-kintone-partner)
* [What are Kintone Plug-ins](#what-are-kintone-plug-ins)
* [🚀 Have your Kintone Subdomain ready!](#-have-your-kintone-subdomain-ready)
* [Got Questions? 🤔](#got-questions-)
* [Why use Kintone?](#why-use-kintone)
* [Compile and upload the code to Kintone](#compile-and-upload-the-code-to-kintone)
* [Where to get the Subdomain, View ID, and App ID?](#where-to-get-the-subdomain-view-id-and-app-id)
* [Quick Links](#quick-links)
* [Live on YouTube](#live-on-youtube-1)

---

## Check-in Time Slots

* 10:00 - Hello
* 10:15 - Get Started
* 10:30 - What is Kintone?
* 10:45 - Create a Kintone App
* 11:00 - 1 hour left
* 11:15 - 45 min left
* 11:30 - 30 min left
* 11:45 - Wrap Up and Q&A
* 12:00 - Thank you & Survey Raffle

## Waiting Room
=   =   =   =   =   =   =   =   =   =

Hello everyone, the workshop will start real soon!

Be sure you are ready by completing the following tasks:

1. 🤖 Clone the Workshop Repository!  
https://bit.ly/kdp-ai-art

2. 🚀 Have your Kintone Subdomain ready!
If you have not already, sign up for the FREE Kintone Developer License:  
https://kintone.dev/new

✅ Use Chrome or Firefox ; ⚠️ NO Safari

Thank you for waiting & see you soon!

=   =   =   =   =   =   =   =   =   =

## Start
=   =   =   =   =   =   =   =   =   =

Hello everyone, thank you for joining the workshop!

Here is how to get started:

1. 🤖 Clone the Workshop Repository!
https://bit.ly/kdp-ai-art

2. 🚀 Have your Kintone Subdomain ready!
If you have not already, sign up for the FREE Kintone Developer License by filling out this web form:  
https://kintone.dev/new

✅ Use Chrome or Firefox ; ⚠️ NO Safari

=   =   =   =   =   =   =   =   =   =

## Live on YouTube

If you get lost, you can "rewind" on our lives stream on YouTube:
https://youtube.com/live/DBKECXKkef4

=   =   =   =   =   =   =   =   =   =

## Install Commands {Get Started}

cd Downloads

git clone https://github.com/kintone-workshops/ai-kintone-gallery

cd ai-kintone-gallery

npm install

npm install -g @kintone/customize-uploader

=   =   =   =   =   =   =   =   =   =

## Kintone Customize Uploader

npm install -g @kintone/customize-uploader

=   =   =   =   =   =   =   =   =   =

## Workshop Steps

A. Get started - clone the repo & install dependencies
B. Get your free Kintone database
C. Create a `.env` file
D. Create a Kintone web database app
--> Input Fields
--> Blank Space fields
--> Steps to create the kintone app
E. Generate an API token for Kintone app
F. Edit your customize-manifest.json
G. Create an OpenAI API key
H. Edit main.js
--> Step 1: Make a prompt
--> Step 2: Call our APIs
I. Compile and upload the code to Kintone
J. Add a record to the Kintone app to generate an image

* ai-kintone-gallery/docs
/Workshop_Steps.md
* or https://github.com/kintone-workshops/ai-kintone-gallery/blob/main/docs/Workshop_Steps.md#openai-art-generator--gallery-workshop-steps

=   =   =   =   =   =   =   =   =   =

# Where to get Kintone Web Database Subdomain?

Sign up for the FREE Kintone Developer License by filling out this web form:

https://kintone.dev/new

⚠️ NO Safari
✅ Use Chrome or Firefox

=   =   =   =   =   =   =   =   =   =

## YouTube
=   =   =   =   =   =   =   =   =   =

This is also live on YouTube:
https://youtube.com/live/DBKECXKkef4

It is a bit delayed but for those who want to "rewind", this is another great option ~

This workshop will also be uploaded to our YouTube Channel!

Kintone Developer Program
https://bit.ly/KDP_Video

Subscribe so you get notified with the workshop recording gets uploaded! 🔔

=   =   =   =   =   =   =   =   =   =

## Create a .env File

Using the .env.example file as a template, create a .env file.

Then input your Kintone credentials like the following:

KINTONE_BASE_URL="https://example.kintone.com"
KINTONE_USERNAME="MyEmail@example.com"
KINTONE_PASSWORD="ILoveKintone!"
VITE_KINTONE_SUBDOMAIN="example"
VITE_KINTONE_TOKEN="abcd2ef3g3hij2kl1"
VITE_KINTONE_APPID="1"
VITE_OPEN_AI_TOKEN="1234567890"

⚠️ DO NOT DELETE THE .env.example FILE!
.env.example is used by env-cmd to verify that the .env file is correctly configured.

=   =   =   =   =   =   =   =   =   =

## Debugging - Let's Fix Those Problems 💪

Here is a rundown of common problems that may occur & its solutions!

https://github.com/kintone-workshops/ai-kintone-gallery#debugging

If you have additional questions during the workshop, feel free to message me.

=   =   =   =   =   =   =   =   =   =

## Additional Questions 🤔

If you have questions afterwards, post them at our Kintone Developer Community

https://forum.kintone.dev/

=   =   =   =   =   =   =   =   =   =

## Create a Kintone Web Database App

How to set the Field Codes for the Kintone App?
1. Hover over the field
2. Click the top right gear icon ⚙️
3. Select Settings from the drop-down menu
4. Click the edit button Edit Button
5. Enter the new field code
6. Click the Save button

⚠️ Field Codes are case-sensitive ⚠️

Set the following Field Codes
* Radio button #1  → animal
* Radio button #2  → emotion
* Text             → random
* Check Box        → clothes
* Date and Time    → dateTime
* Attachment     → result
* Space #1    → generateButton
* Space #2    → spinner

- Save!
- Be sure to click Save and Activate App buttons! 💪

Ref:  
https://github.com/kintone-workshops/ai-kintone-gallery/blob/main/docs/Workshop_Steps.md#d-create-a-kintone-web-database-app

=   =   =   =   =   =   =   =   =   =

## Kintone Customization Tutorials

If you want additional projects to start playing around with Kintone, check out this page:

https://kintone.dev/en/landing-page/tutorial-gallery/

=   =   =   =   =   =   =   =   =   =

## Quick Check-in

Thank you for all those who DM me with questions

Looks like everyone figured out where you need to go.

If you are still stuck, please let me know ~

=   =   =   =   =   =   =   =   =   =

## Looking for the Kintone Subdomain Email? ✉️

Search the following in your email app:

Welcome to Kintone! One More Step to Developer License

The email will be from developer@kintone.com

=   =   =   =   =   =   =   =   =   =

## Errors related to .env

If you get one of the following error messages:  

* [webpack-cli] Error: Missing environment variable: KINTONE_BASE_URL
* [webpack-cli] Error: Missing environment variable: KINTONE_PASSWORD
* [webpack-cli] Error: Missing environment variable: KINTONE_USERNAME
* [webpack-cli] Error: Missing environment variable: VIEW_ID
* [webpack-cli] TypeError: Cannot convert undefined or null to object
* Failed to find .env file at default paths: [./.env,./.env.js,./.env.json]
* Failed to find .env file at default paths: [./.env,./.env.js,./.env.json]
* Failed to upload JavaScript/CSS files
* KintoneRestAPIError: [520] [CB_WA01] Password authentication failed...

Then please verify that
* your .env file has been correctly configured
* your username and password for your Kintone account are correct
* you have not modified the .env.example

=   =   =   =   =   =   =   =   =   =

## Join our Meetup Group
https://www.meetup.com/kintone-developers/

## Got Kintone Questions?

Please post them in our Kintone Developer Community!

https://forum.kintone.dev/

=   =   =   =   =   =   =   =   =   =

## Survey - April B Workshop

Enter to WIN a $25 Amazon Gift Card! 💰️

https://bit.ly/KDP23JUN

Your feedback is vital for us to improve our workshop!
Thank you for your time & input ~

=   =   =   =   =   =   =   =   =   =

## Write up your experience!

Post to Dev.to or Medium about your experience with Kintone customization ~

See what others post about Kintone
https://dev.to/t/kintone

You might be interested in
Deploy a REST API calling node.js App to Heroku article

https://dev.to/will_yama/deploy-a-rest-api-calling-node-js-app-to-heroku-2mia

React & REST API: How to render responses

https://dev.to/will_yama/how-to-render-responses-96c

=   =   =   =   =   =   =   =   =   =

If you want to check out our amChart x Data Visualization workshop content:

https://youtu.be/fHNj6MieBzw

=   =   =   =   =   =   =   =   =   =

## Log into Kintone Subdomain?

Your login link would be
YOUR_SUBDOMAIN.kintone.com

---

Subdomain: example
URL: example.kintone.com

=   =   =   =   =   =   =   =   =   =

## step-by-step guide

If you are ever lost, check out our step-by-step guide here:

https://github.com/kintone-workshops/ai-kintone-gallery/blob/main/docs/Workshop_Steps.md#openai-art-generator--gallery-workshop-steps

=   =   =   =   =   =   =   =   =   =

## Becoming a Kintone Partner?

https://www.kintone.com/en-us/become-a-partner/

=   =   =   =   =   =   =   =   =   =

## What are Kintone Plug-ins

https://kintone.dev/en/plugins/introduction-to-plug-ins/what-are-kintone-plug-ins/

=   =   =   =   =   =   =   =   =   =

## 🚀 Have your Kintone Subdomain ready!

If you have not already, sign up for the FREE Kintone Developer License by filling out this web form:

https://kintone.dev/new

✅ Use Chrome or Firefox ; ⚠️ NO Safari

=   =   =   =   =   =   =   =   =   =

## Got Questions? 🤔
Feel free to msg me with a workshop-related or a general Kintone question to me anytime ~

=   =   =   =   =   =   =   =   =   =

## Why use Kintone?
+ Super easy to use database / backend solution
+ You can use vanilla JS to build customizations right on the platform
+ Companies are hiring engineers to build Kintone integrations

More information:
+ Get Hacking with Kintone - https://kintone.dev/en/landing-page/hackathon/
+ Job Listing - Kintone Developer Forum - https://forum.kintone.dev/t/seeking-independent-contractors-with-kintone-customization-programming-skills/550

=   =   =   =   =   =   =   =   =   =

## Compile and upload the code to Kintone

1. npm run build
1. npm run upload

=   =   =   =   =   =   =   =   =   =

## Where to get the Subdomain, View ID, and App ID?

Go to your Kintone App's custom view & grab the URL
Kintone App's URL follows this template:
https://<SUBDOMAIN>.kintone.com/k/<App ID>/?view=<View ID>
Example:

https://example.kintone.com/k/1/
Subdomain = example
KINTONE_BASE_URL = https://example.kintone.com
App ID = 1

=   =   =   =   =   =   =   =   =   =

## Quick Links

🤖 Clone the Workshop Repository!
https://bit.ly/kdp-ai-art

🚀 Have your Kintone Subdomain ready!
https://kintone.dev/new

📺 YouTube live stream
https://youtube.com/live/DBKECXKkef4

⚙️ OpenAI API Token
https://platform.openai.com/account/api-keys

⚙️ OpenAI Usage
https://platform.openai.com/account/usage

=   =   =   =   =   =   =   =   =   =

## Live on YouTube

If you get lost, you can "rewind" on our lives stream on YouTube:
https://youtube.com/live/DBKECXKkef4

=   =   =   =   =   =   =   =   =   =

Direct Message with your email address if you forgot your Kintone Subdomain

=   =   =   =   =   =   =   =   =   =

The KINTONE_BASE_URL variable is based on your subdomain.

For example:
Subdomain = example
KINTONE_BASE_URL = https://example.kintone.com

=   =   =   =   =   =   =   =   =   =
