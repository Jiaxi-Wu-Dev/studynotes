**Week 2**

Business Process is your bread and butter

What is a thing that a business wants to do and what are the steps that the business takes to get it done.

marketing is a funnel, try to create as many leads as possible
Marketing team finds leads

Events, Webinars, Social Media, Paid Ads, Referrals -> Leads

Sales qualifies the leads from marketing -> convert it to an account, contact, or opportunity

Recruiting is a form of sales

contacts are people
accounts are organizations

lead -> qualify it -> convert to account

Salesforce comes with out of the box processes but you can create specific processes via Path for any object

Lead Stages
Open - Not Contacted -> Working - Contacted -> Closed - Not Converted -> Converted

Opportunity Stages
Prospecting -> Qualification -> Needs Analysis -> Value Proposition -> ID Decision Makers -> Perception Analysis -> Proposal/Price/Quote -> Negotiation/Review -> Closed - Won or Lost

Opportunity - an active sales cycle that will require time and effort to close

Leads are anyone who is out there who could possibly interest in buying your stuff. If we find out they can buy it and actually have an interest, we convert them to a contact. They then get more attention from the sales team

Vocab This Week -
Lead
Contact
Account
Opportunity
Campaign
Parent Campaign
Case Assignment Rule
Escalation Rule

Monitering activity is IMPORTANT, helps to convert

Two types of activities
Task - something with a due date
Event - kinda like salesforce weekly meetings, its an event

MQL = Marketing Qualified Leads
SQL = Sales Qualified Leads
MQL might look good on paper, e.g. have the right job title or demographic data, so the marketing team adds them to a campaign. But when passed to Sales, they need to requalify them to see. ifthey're actually interested.

**Chatter**
Goals

    -Post to your profile feed and other feeds.
    -Get answers to your questions.
    -Create and respond to Chatter polls.

Customize Your Chatter Experience

    -Respond to a post.
    -Keep up-to-date by following people and records.
    -Get people’s attention using mentions.
    -Understand who sees your Chatter content.

You post on your own profile. Who can see this post?

the original post, plus your added remarks, are posted to your profile. They also appear in the What I Follow feed of anyone who’s following you.

You post on a colleague's profile. Who can see this post?

You're sharing a post with lots of comments and two file attachments. What is shared?

What is the result of following someone?

When you mention someone in a group they don't have access to, the mentioned person:

Week 2
Trailmix Learning Objectives

    Opportunity Management
    Leads and Opportunities for Lightning Exp.
    Customize a Sales Path for Your Team
    Products, Quotes, & Contracts
    Service Cloud For Lightning Experience
    Create a Process for Managing Support Cases
    Chatter for Lightning Experience
    Sales Productivity

Week 3
Salesforce Fundamentals

User Setup and Management
You're the admin, and the rest of the company are your users. This is how you'll get them set up correctly in Salesforce.

Add New Users

    Describe a user account and the type of information it contains.
    Add a single user or multiple users.
    Use the Salesforce mobile app to manage users on the go.

Users - A user is anyone who logs in to Salesforce. Users are employees at your company, such as sales reps, managers, and IT specialists, who need access to the company's records.

The user account identifies the user, and the user account settings determine what features and records the user can access. Each user account contains at least the following:

    Username
    Email Address
    User's First and Last Name
    License
    Profile
    Role (optional)

The username must be formatted like an email address and must be unique across all Salesforce organizations. It can be the user's email address, so long as it is unique.

To view and manage the users in your organization, from **Setup**, enter Users in the Quick Find box, then select Users. The user list shows all the users in your organization. From the list, you can:

    Create one or more users.
    Reset passwords for selected users.
    View a user's detail page by clicking the name, alias, or username.
    Edit a user's details.
    Log in as any user if the system permission is enabled or if the user has granted you system administrator login access.

User Licenses
A user license determines which features the user can access in Salesforce.

Profiles
Profiles determine what users can do in Salesforce. They come with a set of permissions which grant access to particular objects, fields, tabs, and records.

Roles
Roles determine what users can see in Salesforce based on where they are located in the role hierarchy.

If a users account is compromised, go to the compromised user’s profile page, then tap and select Freeze.

**Control What Your Users Can Access**

    Describe the difference between object and field level security
    Describe how to set org–wide default sharing settings

**Organization–wide default**s specify the default level of access users have to each others' records.

**Role hierarchies** open up access to those higher in the hierarchy so they inherit access to all records owned by users below them in the hierarchy.

**Sharing rules** enable you to make automatic exceptions to organization–wide defaults for particular groups of users, to give them access to records they don't own or can't normally see.

Review:
Control What Your Users Can Access

**Understand How Licenses Work**

    Explain what a Salesforce license is.
    Define platform, user, and permission set licenses.
    Describe how platform, user, and permission set licenses relate to editions and add-ons.

a **Salesforce license** is similar to a lease agreement between a property manager and a tenant. A Salesforce license, or more precisely, a license definition, is a metadata description of the Salesforce features and services that are available to your org.

**Provisioning** is the process that Salesforce administers to activate your licenses and enable functionality in your org. When your org is provisioned, it’s like a tenant shaking hands with the property manager, making the initial lease payment, and getting the office keys. Once your org is provisioned, you can get to work with Salesforce!

It’s worth noting that **provisioning** applies only to production orgs

![](/assets/images/2021-06-21-23-09-25.png)

Add-on
An optional extension for an org to supplement the functionality provided by the edition. An org can have multiple add-ons. An add-on includes one or more permission set, platform, or user licenses, or a combination of those.
Demo org
A sample org used to demonstrate Salesforce functionality to prospective customers.
Developer org
A free, non-expiring org that a developer can use to develop, test, and deploy applications.
Edition
A bundle of features and services that comprise the functionality necessary to activate an org. Salesforce offers several editions, which provide varying levels of functionality.
License
The contractual agreement between Salesforce and a specific customer, which includes a metadata description of the functionality for the associated Salesforce product that is available to the customer org.
License definition
A metadata description of the functionality for a given Salesforce product that is available to a customer org.
Permission
A metadata switch, or setting, that configures a particular aspect of product functionality. In general, permissions control access to features, such as Lightning Experience or Chatter, and certain aspects of security. Compare to preference.
Permission set license
A license that defines user-level functionality, which can be assigned to supplement the functionality in a user license. A user can be assigned multiple permission set licenses. Note that a permission set license is different from a permission set, defined in the next unit.
Platform license
A license with metadata switches, or settings, that control functionality for the org as a whole.
Preference
A metadata switch, or setting, that configures a particular aspect of product functionality. In general, preferences define settings that customers can configure, such as time zone or password options. Compare to permission.
Product license
An edition or add-on, which bundles together one or more settings licenses and other metadata in a product that the customer can purchase.
Production org
Customer’s active org where users access and work with live data.
Provisioning
The process of activating licenses and enabling functionality in an org.
Sandbox org
A replica of a production org that serves as a staging environment where the customer can test changes without affecting the production org or users.
Scratch org
A short-lived deployment of Salesforce that enables developers to emulate different Salesforce editions, features, and preferences. Each scratch org is automatically deleted after 7 days.
Setting
A metadata switch in a license that configures a particular aspect of product functionality.
Settings license
A permission set license, platform license, or user license that includes settings, metadata switches that configure aspects of product functionality.
Trial org
A free org with sample data, designed for prospective customers to evaluate Salesforce before purchasing.
User license
A license that defines user-level functionality. Each user is assigned one user license.

**Keep Up With Upgrades and Add ons**

    Define edition upgrades and add-ons.
    Explain why an admin needs to update profiles and permission sets after the customer org purchases an upgrade or add-on.
    Explain how a customer can keep their sandbox orgs in sync with their production org.

When you first sign up for Salesforce you choose the edition that best fits your business needs at the time.

A edition upgrade happens when your org transitions to a higher Salesforce edition.

An addon supplements your orgs with additional features or services without changing the dition

When you purchase an edition upgrade or an add-on, your org gets one or more new platform, user, or permission set licenses, or possibly some combination of each.

When you make any changes to production org licenses, you must push changes to the sandbox orgs if you want your test environment to mirror your production environment.

In many cases, you can refresh the sandbox org to make sure that its licensing information matches the production org’s.

Learn About Regional Settings
Describe how configuring your company settings affect your end users.
Translate the company’s business requirements into your company settings.
Implement changes to your company information and fiscal year.
Update your personal locale settings.

Salesforce includes 4 automation tools
Salesforce flow
approval process
process builder
workflow rules

get javascript superbadge
know the event loop
variable hoisting
![](/assets/images/2021-06-23-14-18-27.png)

Discover Multiple Currency Settings

    Add new currencies to your org.
    Summarize the impact of using single currency versus multiple currencies.
    Set up Advanced Currency Management.
    Edit conversion rates, and enable users to select personal currencies.

Advanced Currency Management for currency fields on opportunities and opportunity products lets you manage exchange rate start dates.

Once multiple currencies is enabled you also:

    Activate additional currencies and optionally select a new corporate currency.
    Ensure users have correct personal currencies.
    Make sure users use the correct currency when creating records.
