# _Hood River Parks and Recreation Campaign – May 2024 Ballot_

#### By _**Jessica Hattig**_

#### _Epicodus, Capstone_

## Description
The Hood River Parks and Recreation Committee is seeking a website to promote their campaign for the local May 2024 ballot. They require a platform to display information about their ballot measure, marketing initiatives, and a feature allowing patrons to contribute donations towards the campaign.

## Requested Features
- High quality UI that emphasizes Hood River Parks and Recreation esthetics.
- Donations page
- Information on May '24 ballot measure.
- Capability to use for future campagins or continue receiving donation transactions.
- Note: In addition to these features listed, I will be meeting with Michael Howard on 2/2/24 to discuss more specifics on requested feature in addition to receiving the information PnR wants to display on this website. Michael also requests purchasing a domain.

## Domain Ideas
* Note: Domain hosting website will need to support financial transactions for the donations page. *

- Domain hosting websites in consideration include:
  - [Squarespace](https://www.bluehillsdigital.com/articles/squarespace-nonprofits-strengths-limitations-pricing/#:~:text=Squarespace%20provides%20a%20Donations%20block,account%20to%20process%20the%20payments.)
  - [Wix](https://support.wix.com/en/article/wix-forms-adding-and-setting-up-a-donation-form)
  - [GoDaddy](https://www.godaddy.com/payments)

## Meetings Notes: Meeting with Michael 2/2/24 2:00 pm - 2:41 pm.
Michael met with the committee again last week. The board oversees the Parks and Rec district, but we aren't collectively engaged in promoting this ballot. While the focus is on the ballot measure, the board itself cannot actively promote it. However, individuals are encouraged to promote it on their own.

### Information on the May '24 Ballot Measure

- Bond
- Levi: To increase funds for expanding and operating Parks and Rec (aka PnR).
    - The committee has voted on this measure, and they are now in the process of wording the ballot measure since language and explanations are very imperative.
- Committee needs to use volunteers like myself - they have a PAC (Political Action Committee) which can promote the ballot and can work individually as board members but not as a committee.
  - Board members, like Michael, can work on tasks with individuals.
    - Michael is working on social media and the webpage. The webpage aspect is where I come in.
      - There are 3.5 months to go before the ballot vote. Michael wants the bare bones of the website up as soon as possible, ideally Mid-February would be great.
      - Michael will be the middle person to add additional information or adjustments to the website.
      - Taking care of the website will come from me and Michael - requests will come to us to add to the website.
        - *Note: Michael is not sure who this information will come from, and Michael thinks I'll work with various people on obtaining information. Taking care of the website will come from me and Michael - requests will come to us to add to the website.*

### MVP
- Michael said I can use whatever I think is best to develope the website. Avoid using complexity since he does not want to take too long to roll out this website. *Time is of the essence*

- **Main Homepage**
  - A detailed overview of the ballot measures will be provided, including information about the bond and levy presented in a fact sheet format.

    - **Detailed History of Parks and Recreation District**
      - Highlighting the Parks and Recreation District's history, emphasizing its ability to operate on a shoestring budget and its continuous efforts to do more with limited resources.
        - To achieve greater impact, the Parks and Recreation District is now seeking additional funds via a historical ballot measure.

    - **Ballot Information Addendum**
      - The ballot information section offers a diverse range of details. Images will be incorporated to visually enhance the presentation.
        - Michael will be obtaining photos and diagrams for inclusion, scheduled for next week.

- **Additional Tabs or Footer**
  - Section to allow people to get involved.
    - Donations button/page.
  - Ability to link a QR code to the website.
    - QR for donations.
    - Donations will most likely use PayPal. So, the donations page needs to redirect to PayPal.
    - Primary donations link will be through PayPal.
  - Contact us email, so people can communicate with the director of PAC.
    - Michael has an idea for a second email address associated with the website. For example, tell us what YOU want to see from PnR.
      - Example, an email to receive input on elements like color.
    - Community input/suggestions (above) will go into a bucket that will be taken into consideration, but PnR will not get back to you.
  - Widgets to link Instagram to the Facebook account that the committee will be running. Also, more frequent news updates.
    - Facebook and Instagram will be updated more frequently.

- **Additional Notes** 
  - Once websites get established, there won't be frequent changes.
  - Two different web links that will route to the same hosted website.
    - One in English.
    - The second in Spanish.
      - Michael prefers not to use a translate button but recognizes it might be needed.
        - Platform does it for us?
        - Put into another language?
        - Michael wants it to be functional so people can immediately go to and see the website in Spanish (40% of the community is Hispanic, so this is important).

- **Name**: 
  - Website name options: yesyespnr.com or variations (Michael says this one is available).
  - Spanish version: sisipnr.com or sisipnr.org (both available).

- **Pay for Search Engine Promotion**
  - PAC or Michael will pay for SEO.

- **If Fails in May, Try Again in November**
  - Further promotion ideas:
    - Flyers, word of mouth, open to other ideas.  (I will most likely not do, but will keep in mind.)
    - Application to promote social media automation posts.
      - Canva.

- **PnR Special Fundraising Dinner**
  - To raise money for PAC. Chefs to offer up their labor and spacing at Celio. This event might funnel through there as well, maybe sell tickets on website?

## Website Guide and Framework

### Programming Language
- Very familiar with **C#**, **JavaScript**, and **React**.
  - **C#:** Well-versed in creating effective views for different sections of the website.
    - Database: **SQL**.
  - **React:** Proficient in building a highly responsive main page and a few additional views.
    - Database: **NoSQL**, hosted on the cloud, **Firebase**.

### English and Spanish Feature

Thoughts on having English and Spanish versions of the website.

#### Using C# (ASP.NET Core Backend):

1. **Resource Files:**
   - Store your strings, labels, and content for both English and Spanish versions in resource files. You can create separate resource files for each language.

2. **Middleware:**
   - Implement middleware to detect the user's language preference based on their browser settings or user selection. Set the selected language in a user session or cookie.

3. **Backend Logic:**
   - Use the selected language to fetch the appropriate content from the resource files and provide it to the frontend when rendering the views.

#### Using React (Frontend):

1. **Localization Libraries:**
   - Utilize localization libraries like `react-i18next` or `react-intl` to manage translations and switch between languages on the frontend.

2. **Language Switch Function:**
   - Create a function that allows users to switch the language. This function should update the language preference in the state or context and trigger a re-render of the components with the updated language content.

3. **Translate Components:**
   - Wrap components or text elements that need translation with the localization library's translation functions.

## Questions
- Can I combine programming languages, or can I only pick one programming language?
- What domain hosting website would be best to use with PayPal?


## License
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) Jessica Hattig 2024