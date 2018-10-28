# M1 - Fiki and Project Description

### 1. Project title - Automated Testing Framework (ATF)

* *Test automation provides sanity checks for ever-changing production code. Automation framework consists of the integration of tools, libraries and utilities needed to interact with the system under test. Automated tests are scripted scenarios that drive the framework to query the application through a series of steps, and then use the information the framework gathered to determine the state of your test.* 

### 2. Present the team and assign the roles (such as FR, BE, PO, PM, etc)

* **What we want to achieve?** 
   * Test automation is living, breathing code and is developed to provide sanity checks for ever-changing production code. Building an automated testing framework can make your testing scalable, reliable, efficient, cost-effective and less brittle.

* **What we need?** 
   * The team needed an experienced understanding of software testing and QA to know how to achieve the right balance of manual, UI, integration (API) and unit tests. To achieve that, we create the **AGILE team**:

      `Front-End Engineer & UI/UX Designer`: Andreea Alistar 
        * Role: Product Owner
          * Email: andreealistar@gmail.com
          * Linkedin: https://www.linkedin.com/in/andreea-alistar-305331101/
          * Facebook: https://www.facebook.com/alistar.andreea

      `Front-End Engineer`: Eugeniu Draguteanu
          * Email: eugeniu.draguteanu@gmail.com
          * Linkedin: https://www.linkedin.com/in/eugeniu-draguteanu-510798103/
          * Facebook: https://www.facebook.com/eugen.draguteanu
        
      `Backend Architect + QA`: Cirimpei Dumitru 
        * Role: Scrum Master
          * Email: cirimpei.dumitru@gmail.com
          * Linkedin: https://www.linkedin.com/in/dumitru-cirimpei/
          * Facebook: https://www.facebook.com/mitrumd
        
      `Full Stack + QA Engineer`: Andrei Crividenco
          * Email: acrividenco@gmail.com
          * Linkedin: https://www.linkedin.com/in/andrei-crividenco-76538814b/
          * Facebook: https://www.facebook.com/zdxf.adf

### 3. Describe the problem that you have noticed

* Manual testing is a thing of the past;
* The current frameworks have limited features;
* Expensive for what if offers (license or subscription costs of commercial automation solutions);

### 4. Your solution / value proposition

* Reduce the work of manual testing (time savings + staff performance);
* Earlier bugs identified before the users are impacted (spot smallest imperfections);
* Easy management of the test cases;
* Intuitive GUI that immediately shows when, where and how the execution failed;
* Our solution is to build a framework to help make your test automation code:
  * Reusable AND Maintainable AND Stable
* Benefits:
  * Reduces the time and effort you need to spend on QA while providing quick feedback and expanding code coverage => better product
  * ROI: if executed properly, introducing automation into your organization is worth the investment.
  * Minimal manual intervention
  * Lower maintenace costs
  * Performance
  * Load
  * Security
  * Accesibility
  * Production monitoring
  * Mitigate RISK: Can help Stakeholders and POs better manage risk by addressing many of their concerns early in the process. Moreover, the cost of change to a system is greatly reduced by test automation, so it’s much easier when a bug fix or feature enhancement needs to be pushed to production.
  * Turnaround time
  * Less tester fatigue (time-consuming)
  * Decreased human error

### 5. Customer segment/s

* Corporate IT with complex software solutions;
* Small and medium businesses which contribute with software to the bigger picture;
* Independent people or students working on software projects;

### 6. Competition

|                 |     Price    |      Platform     |                          Supported languages                          |        Tested apps        |              Coding skills required              |
|:---------------:|:------------:|:-----------------:|:---------------------------------------------------------------------:|:-------------------------:|:------------------------------------------------:|
|     **Selenium**    |     Free     | Windows/Mac/Linux |             Java, Python, C#, PHP, JavaScript, Ruby, Perl             | Web, mobile (with Appium) |                  Advanced skills                 |
|   **TestComplete**  |  $4600/$9000 |      Windows      | VB, JavaScript, Jscript, C++, C#, Delphi, Angular, Ruby on Rails, PHP |    Web, mobile, desktop   | Minimum skills/Advanced skills for pro scripting |
| **Tricentis Tosca** | Custom, high |      Windows      |                               Javascript                              |    Web, mobile, desktop   | Minimum skills/Advanced skills for pro scripting |
|  **Katalon Studio** |     Free     |    Windows/Mac    |                              Java/Groovy                              |        Web, mobile        | Minimum skills/Advanced skills for pro scripting |
|       **UFT**       |  $2500/$3500 |      Windows      |                                VBScript                               |    Web, mobile, desktop   | Minimum skills/Advanced skills for pro scripting |
|      **Watir**      |     Free     |      Windows      |                     Ruby (Java/.Net alternatively)                    |            Web            |                  Minimum skills                  |
|     **Ranorex**     |  $2800/$850  |      Windows      |                        C#, VB.Net, Iron Python                        |    Web, mobile, desktop   | Minimum skills/Advanced skills for pro scripting |

### 7. Your advantage over the competition

* Cost: open source + free license cost;
* Customization;
* Control;
* Ease of use;
* No advertising, no clutter;
* Fast support;
* No unnecessary features;

### 8. Key metrics

* Customer satisfaction;
* Failure rates;
* Server uptime;
* Adoption rate;
* Tests running overhead;

### 9. Cost structure

* Marketplace for special plugins and features, like: storing tests in the cloud, scm for the tests, custom user intefaces;
* A donation button will be available on the main download page;

### 10. Revenue streams

* Donations;
  * 1$ (Ten hours of electricity for one developer PC)
  * 5$ (One day webserver hosting)
  * 10$ (5% of our monthly telecommunication costs)
  * 25$ (A quarter of a hard-drive)
  * 50$ (5% of one MS Visual Studio license)
  * …$ Of course, you can donate any amount you regard appropriate.
* Paid modules like Connect to DB, Connect to RabbitMQ, etc.;
* Running tests in parallel;
* Running tests for specific browser on specific version on specific operating system;


# M2 - Validation 1 (idea)

### 1. How you identified the problem?

  * Current solutions, while offering lots of features, also introduce a lot of overhead and complicated configurations. Much needed features like the ones proposed are never aggregated into one application(code versioning, cloud storage etc.). Graphical user interfaces are ambiguous due to the need of providing access to every feature;

### 2. What you thought is a solution for the problem?

  * An open-source application model, offering as much extensibility as possible and a freemium-based revenue (from plugins and cloud storage space) with the possibility of donations.
  * The solution has to address the main problems: stick to the most necessary features, maintain a simple interface with great performance, offer plugins for special features.

### 3. Your plan for customer discovery (short overview before going into detail).

  * There are two types of potential customers: 
    * __those who DO__
    * __those who DON'T use automated testing frameworks (but have the need to)__
  * Explain our proposed solutions to both types of customers and gather feedback. For customers who already use an automated testing framework, see which ones are willing to migrate from an existing platform and learn why others won’t (what the reasons are, what features they’re not willing to give up on etc.)

### 4. Describe the process in detail:

#### 4.1 How you identified your customer segment/s?
  
  * The main customers will be the big companies that develop web applications because they spend a lot of time for testing. Any modification to an application requires a complete regression testing of the entire application to see if any other sections of the applications have been affected.
  * At the same time, this testing process should be done as quickly as possible to make changes in production to repair some bugs or to bring new features. The solution for these companies would be to automate this process by writing automated tests and running them quickly on an infrastructure that our application will provide.

#### 4.2 How you reached them, how you collected information from them? Include the questions that you asked and all of your findings.
  
  * To interact with potential clients we decided to contact companies interested in this topic, so we interviewed representatives of the participating companies but also partners of the "ROMANIAN TESTING CONFERENCE" (https://romaniatesting.ro), which takes place annually in Cluj. 
  * So we created an online survey that was distributed to testers within interested companies. This survey included the following questions (https://docs.google.com/forms/d/e/1FAIpQLSfibey92Iiv6dQyhn6W_fFrSSLx5lPOWiEQT81tvh_lGo9Fww/viewform?usp=sf_link)

```markdown

### 1. Do you, or your current team, possess enough technical skills to build and maintain test automation?

  • Yes (10%)
  • Partially (34%)
  • No (56%)

### 2. How do you run the automated tests:

  • in an application developed in-house (12%)
  • in a commercial application (31%)
  • locally on your PC / Laptop (57%)
  • otherwise
  
### 3. How often do you run automated tests:

  • Daily (40%)
  • several times a week (47%)
  • several times a month (13%)
  
### 4. What types of tests you run (multiple responses):

  • Api (12%)
  • Smoke (37%)
  • Acceptance (46%)
  • Others (5%)

### 5. HOW do you prefer to create tests and WHY?

  • Clicking in the interface (7%, no programming skills required)
  • Writing Code (93%, better structure of tests, component reuse, creation of own logic, ...)
  
### 6. In which language do you prefer to write tests:

  • Java (21%)
  • Javascript (24%)
  • Python (18%)
  • PHP (27%)
  • Other (10%)
  
### 7. How useful do you consider the following features for you (with Useless, Useful, Very useful):

  • Running tests in serial/parallel
    ○ 7% - Useless, 65% - Useful, 28% - Very useful
  • Running defined tests via API
    ○ 15% - Useless, 73% - Useful, 12% - Very useful
  • Running testing plans on Schedule
    ○ 8% - Useless, 73% - Useful, 12% - Very useful
  • Running tests on different operating systems
    ○ 81% - Useless, 17% - Useful, 2% - Very useful
  • Running tests on different browsers
    ○ 10% - Useless, 61% - Useful, 29% - Very useful
  • Running tests on different versions of browsers
    ○ 15% - Useless, 66% - Useful, 19% - Very useful
    
### 8. What is the one main benefit of test automation you expect to gain?

  •  More confidence in the released product (27%)
  •  Higher product quality (26%)
  •  Faster releases/meeting the schedule (19%)
  •  More interesting job/skill than manual testing (7%)
  •  Creating and automating tests helps everyone better understand the system under test (7%)
  •  Show system consistency (2%)
  •  Customers finding less bugs (2%)
  •  Less support issues (2%)
  •  Finding more bugs (1%)
  •  None/no benefit (1%)
  
```

### 5. Describe how these insights have affected your product (if in any way).

  * Complaints about performance on existing products made us decide that special features have to be offered as plugins, instead of being included in the base product, so that the end product would be simple, fast and limited to basic needs, but also feature-filled if necessary. Customers not already using such a framework also wished for fast and simple way to test their applications, without unnecessary complications.

### 6. Do you consider that you are ready to move to the Customer Validation stage (to test selling)? Provide arguments.

  * Considering that we’ve covered all complaints about other existing solutions regarding Automated Testing Frameworks and that most customers are happy with our other proposals, we’re ready to move on to the next stage!!!
