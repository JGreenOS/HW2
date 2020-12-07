# Responsive Portfolio #

As a digital badging pioneer, I advocate for badge earners to display their achievements proudly via social media, email footers and more.  However, I am curious on how these badges would be displayed in a responsive website portfolio as I think it would get more "traffic" for the recipients.

This project is a simple 3 page site, with an index/home page, a portfolio page showcasing how digital badges can be displayed in a responsive card format and a contact me page.  

In this project, I spent a bulk of the time experimenting with digital badge icons from my personal badge backpack. From the backpack (www.badgr.io) I can obtain dynamic, interactive content which will validate/ verify that I am the badge earner. Each badge icon is "baked" with metadata that points back to the evidence, date, learner and criterion for earning the badge.  The evidence can be a representation of the work done by the earner and the issuance of the badge demostrates the learner has met minimum 

Aside:  Quality digital badges are popular with learning communities as they represent competencies, skills and knowledge at a particular point in time.  Earning a badge is set by the badge issuer and issuers can design eye-catching emblems to represent their badges.  When the badge is issued using the Open Badges standard https://www.imsglobal.org/activity/digital-badges.  Relevant to this project is the testing of an Badge API in progress by IMS Global.

Difficulties encountered in this project inlude how to handle the data from the Badgr Backpack.  I was unable to do a direct connection from the live website to the Badgr backpack as the existing technology uses iframes.  While this is possbile to do this with CSS, it is on my list of future improvements of this page.  JavaScript is another possiblity but it is beyond the scope of this project.

After working with the link which is an API or the HTML (Sample of the source I was attempting to manipulate: 

Source 1: <iframe src="https://api.badgr.io/public/assertions/ksu78T2OSxKxuYh5O1VVqg?embedVersion=1&amp;embedWidth=330&amp;embedHeight=186" title="Badge: NI roboRIO Robot Control" style="width: 330px; height: 186px; border: 0px;"></iframe>

Source 2: <blockquote class="badgr-badge" style="font-family: Helvetica, Roboto, &quot;Segoe UI&quot;, Calibri, sans-serif;"><a href="https://api.badgr.io/public/assertions/ksu78T2OSxKxuYh5O1VVqg"><img width="120px" height="120px" src="https://api.badgr.io/public/assertions/ksu78T2OSxKxuYh5O1VVqg/image"></a><p class="badgr-badge-name" style="hyphens: auto; overflow-wrap: break-word; word-wrap: break-word;margin: 0; font-size: 16px; font-weight: 600; font-style: normal; font-stretch: normal; line-height: 1.25; letter-spacing: normal; text-align: left; color: #05012c;">NI roboRIO Robot Control</p><p class="badgr-badge-date" style="margin: 0; font-size: 12px; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #555555;"><strong style="font-size: 12px; font-weight: bold; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #000;">Awarded:</strong> Apr 12, 2019</p><p class="badgr-badge-recipient" style="margin: 0; font-size: 12px; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #555555;"><strong style="font-size: 12px; font-weight: bold; font-style: normal; font-stretch: normal; line-height: 1.67; letter-spacing: normal; text-align: left; color: #000;">Awarded To:</strong><span style="display: block;"> Julia	Green</span></p><p style="margin: 16px 0; padding: 0;"><a class="badgr-badge-verify" target="_blank" href="https://badgecheck.io?url=https%3A%2F%2Fapi.badgr.io%2Fpublic%2Fassertions%2Fksu78T2OSxKxuYh5O1VVqg" style="box-sizing: content-box; display: flex; align-items: center; justify-content: center; margin: 0; font-size:14px; font-weight: bold; width: 48px; height: 16px; border-radius: 4px; border: solid 1px black; text-decoration: none; padding: 6px 16px; margin: 16px 0; color: black;">VERIFY</a></p><script async="async" src="https://badgr.com/assets/widgets.bundle.js"></script></blockquote>

The blockquote was very difficult to work with as the styles are built into this code as I was attempting to limit the number of styles included in the responsive HTML.  In the end, I was able to complete the homework by downloading the icon and using the metadata to build the cards on the portfolio page.






