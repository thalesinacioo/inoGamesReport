# inoGamesReport
### 1. What is the primary purpose of Quality Assurance (QA)?
Defect prevention, continuous improvement, compliance with requirements, and customer satisfaction.
QA aims to identify and fix problems from the early stages of development, promote the continuous improvement of processes and products, always seeking to optimize quality and efficiency, and verify if the product meets the defined requirements, both functional and non-functional.

### 2. What is the difference between a test case and a test plan?
A test case is used to describe a specific sequence of steps to test a particular functionality or feature.
A test plan describes the overall testing strategy for a software/app.
As an example, I’ll mention one of my favorite tools for managing test cases and test plans: Qase.io. I've been using it for a while now. It’s easy to maintain test plans and cases, add or delete tests, and allows for team management of test runs. At the end of each run, it generates a report. Additionally, there’s the option to link issues directly to several managers, such as Atlassian tools (Jira or Trello), Asana, and others.

### 3. What does the term 'regression testing' refer to?
Regression testing is important because it validates the changes made, ensures that modifications don’t affect unaltered parts, and confirms that the application has not “regressed.”
I like to mention an example that happened to me once: while working at an American digital signage company, I tested web layers within the app. Following the CTO's guidance, I didn’t perform a basic video test (.MP4, .MKV, and other formats). The CTO's code change affected the video player, breaking it across all signage screens for a client that had set up automatic updates. At that moment, the CTO understood the importance of letting me run a basic regression test before releasing new .apk files.

### 4. How would you create a template to describe bugs on a software that is being constantly released?
Without knowing the methodologies and tools used, it’s a bit challenging, but I believe the basics always work. I would use four sections:

Concise and summarized title.
What happened: This section should contain a brief description of the issue, accompanied by videos or screenshots.
Steps to reproduce: Provide a step-by-step enumeration of actions to replicate the bug.
What should happen: Based on the feature’s story, UI/UX examples, and the feature’s description and expected behavior. It would be helpful to link the main ticket describing the feature's behavior.

### 5. What is the importance of test automation in QA?
It has a significant impact on development agility and quality, eliminating bottlenecks in manual testing, saving time and financial resources, and potentially increasing profits through improved productivity.

### 6. Describe the main stages of the Software testing Life Cycle (STLC)?
**Requirement analysis:** Analyze and understand the requirements to start the proccess, acceptance criteria and understanding of the product architecture. 
**Test planning:** developing test steps, assigning roles and responsibilities, and choosing the right testing approach and automation tools
**Test case design and development:** testing team creates the test steps with proper input, test execution conditions, and expected output for execution. For the test case design and development phase, the entry criteria are approved test plans and automation scripts.
**Test environment setup:** setting up a test environment to run your test cases and check the application for its efficiency. It decides the conditions to test your application and involves configuring and deploying the test environment.
**Test execution.** runs the test cases and scripts to check the quality of the application.
**Test cycle closure.** It summarizes the testing process and highlights the comparison between the actual and expected test results.
   
### 7. How would you handle a situation where a bug you reported is marked as 'not reproducible' by the development team?
I would try reproducing it on a different device or browser, record the steps using a tool that shows clicks/touches, report the version where it occurs, the current OS build, and the browser build. Then, I’d discuss it with the developers to demonstrate what’s happening.
Here’s an example from a lesson learned: once, a client found a bug that we could never reproduce in the office. One day, I asked, “What’s the processor of the device used?” We discovered a difference in the Android web view for that specific processor, which prevented a layer from rendering, blocking the user from proceeding in the app.

