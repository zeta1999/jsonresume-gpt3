# Almost Real Resume (GPT-3)

This uses GPT-3 API access to generate fake resumes.

In short, when using GPT-3, you pass it in a question or statement (with some parameters) and it spits back with some cool stuff.

This project was an attempt to improve the previous fake resume generator -> https://github.com/jsonresume/jsonresume-fake (It was built with PyTorch and intended as a tutorial for anyone wanting to try ML)

## Getting Started

```
pip3 -r requirements.txt install
npm i
```

## The Question

All of the generated output that you can in `./gpt3-output` was generated by one question to GPT-3.

```
I asked for a resume from programmer, and below is what I received:

Name:Thomas Davis
Job Title:Senior Javascript Developer
Summary:I’m a full stack web developer who can build apps from the ground up. I've worked mostly at startups so I am use to wearing many hats. I am a very product focussed developer who priotizes user feedback first and foremost. I'm generally very flexible when investigating new roles.
Company Name #1:Listium
Company Role #1:Developer
First Company Summary #1: Built a very large and complex React / Redux application. It works on all platforms and has IOS/Android builds due to it being a PWA. (wrapped it in React Native though only implementing a WebView)
Company #1 Highlight 1:Worked with Postgres, Redis and Dynamodb for storage.
Company #1 Highlight 2:Hosted on a mixture of Heroku Apps and EC2 servers.
Company #2 Name:Earbits
Company #2 Role:Chief Technology Officer
Company #2 Summary:Started off as a front end developer but took on the role of CTO in early 2013. The application frontend is built with Javascript and organized as a single page application that talks to a collection of Rails web servers which are connected to MongoDB.
Company #2 Highlight 1:Managed a small team of developers and designers
Company #2 Highlight 2:Built the entire frontend application with Backbone.js
Personal Reference:Thomas was hired as a lead developer and, upon the leaving of our co-founder took over as CTO of Earbits. Thomas is, hands down, one of those A Players you hear of companies dying to hire.
Interests: Music. Gardening. Politics.
=====
Name:Joey Mckenzie
Job Title:Fullstack Enterprise Software Engineer
Summary:Fullstack enterprise software engineer working primarily within the Java and .NET ecosystems, alongside modern web development with Angular and Blazor. My professional experience includes working with a variety of technologies spanning the stack from TypeScript, Spring Boot, .NET, and ILE RPG to SQL Server, DB2, and the iSeries AS/400.
Company #1 Name:Sierra Pacific Industries, Windows Division
Company #1 Role:Applications Developer
Company #1 Summary:Sierra Pacific Windows is part of Sierra Pacific Industries, the largest millwork producer and the second largest lumber company in the U.S. Sierra Pacific Industries, and produces high quality products installed in over 30 countries world wide, with a focus on residential and commercial properties in the United States.
Company #1 Highlight 1:Developing internal applications using RPG for use on the IBM iSeries AS/400 and VB.NET for desktop software
Company #1 Highlight 2:Using Rational Application Developer for i (RDi) for RPG development and Visual Studio 2019 for .NET
Company #2 Name:VSP Global
Company #2 Role:Associate Software Engineer
Company Summary:Vision Service Plan (VSP) is a company founded by vision care professionals with the primary goal of servicing patients with unmatched quality and service, both in person and through technological innovation.
Company #2 Highlight 1:Developed Java-based API solutions with Spring and Spring Boot backed by SQL Server and DB2 databases
Company #2 Highlight 2:Lead development of a tier one application rewrite using Angular with TypeScript and NPM
Personal Reference:Joey is a very capable leader and developer. I have worked alongside him for many years and have learned a lot not only about being a better developer but also about myself and what I can accomplish. He is someone that when times are tough, deadlines loom or the project is out of whack, I want on my team to help get us back on course and to completion.
Interests: Philosophy. Horse racing. Hiking.
=====
Name:Adam Kendall
Job Title:Software Engineer
Summary:I've been a full-stack web software engineer and system architect focused on delivery, or as they say, "DevOps", for over 20 years. I specialize in SOA applications using dynamic languages.
Company #1 Name:Simple Finance
Company #1 Role:Staff Infrastructure Engineer
Company #1 Summary:Lead team of infrastructure and security engineers in providing secure, PCI-DSS compliant platform for regulated financial technology company
Company #1 Highlight 1:Wrote strategy for migration from custom AWS EC2 delivery architecture to serverless platform to increase resiliency in operations
Company #1 Highlight 2:Lead effort to eliminate bespoke services for highly available third party services with larger community and/or company support
Company #2 Name:Norfolk Southern Railroad
Company #2 Role:Senior Developer
Company #2 Summary:Worked within the Intranet/Internet Systems Group specializing in security and system administration on Sun Solaris and Windows NT servers.
Company #2 Highlight 1:Evaluate the security of intranet applications written by internal development groups and outside vendors through whitebox and blackbox testing
Company #2 Highlight 2:Created policy and procedure for securing Windows NT servers used across the corporation
Personal Reference:I had the privilege to work with Adam at a time when PC networking was beginning to take hold at Advance Auto Parts (AAP.) Adam was instrumental in advocating, architecting and implementing critical infrastructure services.
Interests: Drawing. Cooking. Machine Learning.
=====
Name:
```
