Service Cloud - supports customers from any device or channel to build loyal relationships.

Benefits of the Console

1. Split Views
2. Related Record and related list components
3. Highlight panel components
4. Compact case feed
5. Knowledge component
6. Preconfigured Utility Bar

Everything needed to quickly respond to customers is preconfigured in the console. With Service Cloud, service tools can be expanded and customized as team and company grows

Administer Service Cloud

Set up Service Cloud
use service setup to connect your customers to your service center. A dashboard for all things service.
Whether you need to turn emails into cases, integrate with Twitter and Facebook, enable a knowledge base, or create a self-service help center, you do it all in Service Setup.

You can go to the Service Setup home page to see metrics about how your channels are doing, analyze service center spikes, and view up to the minute caseload stats.

General Setup Process

Automate Case Management - route customer questions, comments, and feedback to the right people and places with as little work as possible. Analyze service metrics to spot trends and make better choices about service.

Add multiple channels—Once your case management system is in place, engage with customers on their favorite communication tools, such as phones, emails, websites, social media, and more. Sync all your channels to a console so that your team can respond to customers anywhere.

Capture knowledge—As customer engagement provides your team with insights, store all useful information in an easy-to-search Knowledge base so helpful articles are just a click away for support agents or customers.

Expand efficiencies with AI—Finally, include artificial intelligence and bots to streamline more tasks and predict service before it’s needed.

_Automate Case Management_
Case Management Tools - means organizing customer cases into one place and making sure they go to the right person, for the right answer, by the right time.

Main tools for case management - queues, assignment rules, escalation rules, auto response rules

**Create Digital Engagement on Multiple Channels**

_Digital Engagement Tools_
Email, Web form channels

Call Center & Open CTI - Boost phone productivity by integrating Salesforce with third-party computer-telephony integration (CTI) systems. See Salesforce data for incoming calls, make outgoing calls directly from the console, and report on call outcome, duration, and more.

Self-Service Help Center - Help customers find answers, log cases, and update orders on their own from self-service web experiences. Customize, create, and brand help centers with easy-to-use templates, components, and apps.

Social Customer Service - Help support agents listen, respond, and log cases for customers on social platforms like Twitter, Instagram, Facebook, and more. Use keywords, classifiers, and language detection to make sure that agents find the right posts and work the right issues.

Chat & Embedded Service - Engage with customers browsing the web with real-time, live chat. Quickly embed unobtrusive chat capabilities on company websites for both desktop and mobile browsers to let customers chat with agents and deflect cases before they get logged.

Snap-ins for Mobile & Visual Remote Assistant - Add service to mobile apps so that **customers** can get help from apps on phones and tablets. With an SDK (software development kit), developers can let customers create and manage cases, live chat with support agents, video chat and screen share with agents (Visual Remote Assistant), and view knowledge base articles on the go.

Messaging - Engage with customers using messaging apps like SMS text and Facebook Messenger, so that they can connect with support agents instantly from anywhere. Help agents manage multiple text conversations at once and see each text alongside relevant Salesforce data.

Field Service - Support onsite visits out in the field with mobile solutions like job schedules, van inventory, and more—with or without web connections.

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

What is a lightning App
An app is a collection of items that work together to serve a particular function. In Lightning Experience, Lightning apps give your users access to sets of objects, tabs, and other items all in one convenient bundle in the navigation bar.

Use the Lightning Experience App Manager to:

    View all your Salesforce apps.
    Create Lightning apps or connected apps (1).
    See which apps are visible in Lightning Experience (2).
    Easily manage apps (3).

Week 4
Security

run health check

Get To Know Your Salesforce Identity Users

    Describe how employees benefit from Salesforce Identity.
    Describe how customers and partners benefit from Salesforce Identity.
    Describe what’s important when setting up user registration.
    Know which features of Salesforce Identity benefit employees, which benefit partners and customers, and which benefit both.

Salesforce Identity

Learn the Language of Identity
Identify the industry standards used for **identity and access management**.
SAML
OAuth 2.0
OpenID Connect

    Know how SAML is related to XML.
        SAML is an XML-based protocol

    Know the difference between an identity provider and service provider.
        In the process of authenticating users, SAML exchanges identity information between the holder of the information, called an identity provider (IdP), and the desired service, called a service provider.

**SAML** - When you want users to move seamlessly between Salesforce orgs and applications without logging in repeatedly, you set up single sign-on (SSO). Security Assertion Markup Language (SAML) is the protocol that makes it happen.

What’s the difference between an identity provider and a service provider? Basically, the identity provider is the one authenticating the user. The service provider is asking for the authenticated identity. We’ll talk more about identity and service providers later on in this unit.

**SAML** is an XML-based protocol, which means that the packages of information being exchanged are written in XML. XML is supposed to be (almost) human-readable so that you can get some idea of what’s going on

**OAuth 2.0** is an open protocol used to allow secure data sharing between applications. The user works in one app but sees the data from another.

Examples of identity providers
Microsoft’s Active Directory Federation Services (ADFS), Ping Identity’s PingFederate, open-source Shibboleth, or ForgeRock’s OpenAM

**OpenID** Connect protocol adds an authentication layer on top of OAuth 2.0 to enable secure exchange of user information. Like SAML, OpenID Connect sends identity information from one service to another. Unlike SAML, OpenID Connect is built for today’s world of social networks.

Customize Your Login Process with My Domain
Explain the benefits of My Domain.
Detail how My Domain lets you control how users access your Salesforce org.
Customize your login page.

Salesforce MyDomain
My Domain is sort of like creating your own empire within the Salesforce universe. It’s a Salesforce Identity feature that lets you personalize your Salesforce org by creating a subdomain (empire) within the Salesforce domain (universe)

Salesforce requires you to have a My Domain in place to:

    Work in multiple Salesforce orgs in the same browser
    Set up single sign-on (SSO) with third-party identity vendors
    Set up authentication providers, such as Google and Facebook, so that your users can log in to your Salesforce org with their social account credentials
    Use Lightning components in Lightning component tabs, Lightning page, the Lightning App Builder, or standalone apps
    Use Financial Services Cloud, Health Cloud, or Work.com

Redirect to the same page within the domain—Let users continue to access your org from your instanced Salesforce URLs as well as your branded My Domain URLs. This option might be convenient, but it won’t require your users to access your branded org.
Redirect with a warning to the same page within the domain—Remind users to use your My Domain URLs before redirecting them to your org. This can help change user behavior so users transition to the branded URLs. For the Jedeyetech scenario purposes, this sounds like the one we want.
Don't redirect (recommended)—Require users to use your My Domain login URL when accessing your org. There is an expectation with this setting that your users have transitioned to using the new My Domain URLs.

Set Up Single Sign-On for Your Internal Users

Learning Objectives
After completing this module, you’ll be able to:

    Create a Federation ID.
        From Setup, enter Users in the Quick Find box, then select Users.
        Click Edit next to Sia’s name.
        Under Single Sign On Information, enter the Federation ID: sia@jedeye-tech.com. Tip : A Federation ID must be unique for each user in an org. That’s why the username is handy. But if the user belongs to multiple orgs, use the same Federation ID for the user in each org. SSO Settings Federation ID
        Click save
    Set up single sign-on from a third-party identity provider.
        use SAML
    Become familiar with the tools to troubleshoot SAML requests.

Restrict Login Hours and IP Ranges
Learning Objectives

In this project, you’ll:

    Restrict when and where users can log in to an organization.
        Click the Setup gear Setup icon and select Setup.
        Enter Profiles in the Quick Find box, and select Profiles.
        Click Custom: Support Profile.
        Under Login Hours click Edit and set up the schedule.
    Determine the levels of access users have to objects.
    Set up a data access model using the role hierarchy, sharing, and teams.
    Control the levels of access users have to fields.

    Darleny - marketing analytics/real estate - working in sales, marketing analytics is growing fast

    fatmata jalloh - never did networking, wants to do accounting, left their family and moved across the world

    gus rosario - graduated from hunter college - cyber security

    jessica vera -executive assistant, interested in HR - graduating from college, looking for internships

    jessie choong - born in malaysia, science background, came to nyc 3 years ago, supply chain/logistics/operations

    Kam bong Chum - learning sql wants to get certificate

    Leephenson - baruch economics, deep dive on consulting

    email everyone

Overview of Data Security

    Explain the importance of giving the right people access to the right data.
    List the four levels at which you can control data access.
        Organization
        For your whole org, you can maintain a list of authorized users, set password policies, and limit logins to certain hours and locations.

        Objects
        Access to object-level data is the simplest thing to control. By setting permissions on a particular type of object, you can prevent a group of users from creating, viewing, editing, or deleting any records of that object. For example, you can use object permissions to ensure that interviewers can view positions and job applications but not edit or delete them.

        Fields
        You can restrict access to certain fields, even if a user has access to the object. For example, you can make the salary field in a position object invisible to interviewers but visible to hiring managers and recruiters.

        Records
        You can allow particular users to view an object, but then restrict the individual object records they're allowed to see. For example, an interviewer can see and edit her own reviews, but not the reviews of other interviewers. You can manage record-level access in these four ways.
    Describe a typical scenario for limiting data access at each of the four levels.

By combining security controls at different levels, you can provide just the right level of data access to thousands of users without having to specify permissions for each user individually.

Control Access to Objects

    View existing profiles and create new ones.
    Modify access to objects using profiles.
    View all assigned users in a profile.
    Create new permission sets.
    Assign permission sets to single and multiple users.

The simplest way to control data access is to set permissions on a particular type of object.

You can set object permissions with profiles or permission sets. A user can have one profile and many permission sets.

    A user’s profile determines the objects they can access and the things they can do with any object record (such as create, read, edit, or delete).
    Permission sets grant additional permissions and access settings to a user.

Use profiles to grant the minimum permissions and settings that all users of a particular type need. Then use permission sets to grant more permissions as needed. The combination of profiles and permission sets gives you a great deal of flexibility in specifying object-level access.

Profiles usually match up with a user's job function (for example, system administrator, recruiter, or hiring manager), but you can have profiles for anything that makes sense for your Salesforce org. A profile can be assigned to many users, but a user can have only one profile at a time.

A **permission** set is a collection of settings and permissions that give users access to various tools and functions. The settings and permissions in permission sets are also found in profiles, but permission sets extend users’ functional access without changing their profiles.

Optimal way to configure object permissions for the Recruiting app is like this:

    Create two profiles: Recruiters and Standard Employees.
    Create two permission sets: Hiring Managers and Interviewers.
    Assign the Standard Employee profile to hiring managers and interviewers, and then grant the appropriate permission set for their function.

Week 5
Understand Custom & Standard Objects
Describe the perks of using objects on the Salesforce platform.
Explain the difference between standard objects and custom objects.
List the types of custom fields an object can have.

data model. A data model is more or less what it sounds like. It’s a way to model what database tables look like in a way that makes sense to humans.

we think about database tables as objects, we think about columns as fields, and rows as records. So instead of an account spreadsheet or table, we have an Account object with fields and a bunch of identically structured records.

Standard objects are objects that are included with Salesforce. Common business objects like Account, Contact, Lead, and Opportunity are all standard objects.

Custom objects are objects that you create to store information that’s specific to your company or industry. For DreamHouse, D’Angelo wants to build a custom Property object that stores information about the homes his company is selling.
