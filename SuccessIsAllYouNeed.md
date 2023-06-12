
*** DRAFT ***
________
# Success is All You Need (for better prompts)

(and some clear goals to know when you achieve it)

The capabilities of modern LLM's like GPT-4, Claude+, and Bard to create new value are enormous, but we are at the very beginning of understanding how to access it.  To get better outputs, a lot of progress can be made through improving the inputs by composing more effective prompts. To get the best results for what you hope to achieve, the real magic of better prompting starts with a certain kind of thinking about what it is you actually want, and how you would objecively know when you get it.

As prompt engineering, and related work on improving use of LLMs evolves, I continually come back to the need to measure success.  There are many, many different aspects of LLMs that would benefit from the right success measures, but today I want to narrowly focus on some ways to apply success metrics to the end-user art and skill of prompting the rights things in the right way. The kind of success metric I want to talk about is the objective assessment we use to evaluate whether a business hypothesis has been proven. 

First, a little background on this relatively unknown thing called a "business hypothesis".  I've been on teams using various ways to establish success metrics for technology projects since the late 1990's, but it wasn't until the 2010's that I encountered the idea of a business hypothesis that can be used as a way of doing business.  It was The Lean Startup book (https://en.wikipedia.org/wiki/The_Lean_Startup) that made it clear to me how aspirational business goals can be framed in a way that is testable, measurable, and iteratively achievable. 

The essential insight is to be able to articulate "we will know we have succeeded when" a given objective criterion is met.  This depends on a clear problem statement or goal definition, and this can't be applied without objective measurement, but the main idea is to be able to somehow pin down the quintessential marker of when that goal has been attained.  For me, the fundamental value of this approach is not simply in measuring relevant things, checking criteria boxes, and reporting successfully performing activities.  Rather, it's about verifiably achieving the intended outcomes. 

When I realized this type of objective experimentation could be applied outside of the scientific method, it changed the way I approached many challenges and problems in business and has even extended to certain legal and policy initiatives.


## Examples of Goals, Success Criteria, and Measuring Options


### Example 1 - DMV Innovation Strategy

Prompt 1: Generate three different plans a big four consultant can deliver for an innovation strategy to a state department of motor vehicles. A successful plan meets each of the following three success criteria: 1) significantly and measurably improves service delivery for individual citizen license renewals and businesses such as taxi, trucking, and delivery fleets; 2) leverages COTs technology and widely used open source; and 3) will eventually reduce ongoing costs for the department of motor vehicles.

Prompt 2: Rate each plan against each of the three success criteria.  Display in a single markdown table with rows for each plan and columns for each success criteria.  Rate from 1 (lowest) to 5 (highest).  Include a row below each plan to describe the rationale for each rating.  In a row below the rationale, describe how success would be measured.

Prompt 3: Based on this analysis, please devise a single plan that takes the best elements of each of the 3 proposed plans to create a plan that rates overall higher for each criteria.  Again, display this in a single markdown table with the plan on a row and each success criteria in columns, and please include a row below the plan to describe how this new plan would perform better than any of the previous plans and a row below that to describe how success would be measured.


**User**

Generate three different plans a big four consultant can deliver for an innovation strategy to a state department of motor vehicles. A successful plan meets each of the following three success criteria: 1) significantly and measurably improves service delivery for individual citizen license renewals and businesses such as taxi, trucking, and delivery fleets; 2) leverages COTs technology and widely used open source; and 3) will eventually reduce ongoing costs for the department of motor vehicles.
ChatGPT

#### ChatGPT Response 

**Plan 1: Digital Transformation and Automation**

1. Implement a robust online portal that allows individual citizens and businesses to renew licenses, update information, pay fees, and schedule tests. This portal could leverage a combination of COTS (Commercial Off-The-Shelf) products and open-source technologies like Java or Python for backend development, React or Angular for frontend, and PostgreSQL or MongoDB for database management.

2. Invest in AI-powered chatbots to handle queries, guide users through processes, and resolve issues in real-time, thereby reducing the load on DMV personnel. This could involve the use of open-source machine learning libraries such as TensorFlow or PyTorch.

3. Introduce a queue management system to minimize waiting time and improve efficiency in physical offices. This can be achieved by integrating COTS products with existing systems.

4. Optimize internal operations by automating administrative tasks, such as record keeping, compliance monitoring, and reporting, using Robotic Process Automation (RPA) tools.

**Plan 2: Data-Driven Innovation**

1. Develop a unified data platform, integrating data from various sources into a single, easy-to-navigate system. Utilize open-source data management systems like Hadoop or Apache Cassandra, and COTS business intelligence tools for data visualization and reporting.

2. Use predictive analytics and machine learning to anticipate service demand, optimize resources, and proactively address potential issues. This can improve customer service by ensuring adequate staffing during peak periods and timely maintenance of systems.

3. Implement advanced analytics to understand trends in customer behavior, preferences, and dissatisfaction areas. Use this insight to refine the DMV's services continuously.

4. Employ IoT technology in monitoring and maintaining fleet vehicles for businesses. This would involve real-time data collection from vehicles to identify issues before they become major problems, thus reducing downtime and repair costs.

**Plan 3: Customer-Centric Innovation**

1. Establish a mobile application, using open-source mobile development frameworks like React Native or Flutter, to provide on-the-go access to DMV services. The application could include features like real-time tracking of application status, digital licenses, reminders for renewals, and online payment options.

2. Utilize COTS Customer Relationship Management (CRM) systems to improve customer service by providing personalized assistance, tracking customer interactions, and improving communication.

3. Introduce self-service kiosks at DMV offices, leveraging COTS technologies, to automate simple transactions like renewals, payment of fines, and information updates.

4. Initiate a feedback system to continuously gather input from customers, identify pain points, and drive continuous improvement. Employ open-source tools for survey generation and data collection, like LimeSurvey or SurveyJS, and data analysis tools like Python's Pandas or R.

All three plans would drive efficiency, improve customer service, and in the long run, reduce operational costs by lowering the requirement of manual work and reducing system downtime. Furthermore, they would make services more accessible to citizens and businesses, hence improving overall satisfaction.

#### Prompt: 

Rate each plan against each of the three success criteria.  Display in a single markdown table with rows for each plan and columns for each success criteria.  include short description of each plan in the cell for each of the three plans. Rate from 1 (lowest) to 5 (highest).  Include a row below each plan to describe the rationale for each rating.  In a row below the rationale, describe how success would be measured.

#### Output

ChatGPT
|              | Improve Service Delivery | Leverages COTS and Open Source | Reduce Ongoing Costs |
|--------------|--------------------------|--------------------------------|----------------------|
| **Plan 1** (Digital Transformation and Automation)      |            5             |              5                 |           4          |
| Rationale    | This plan's main focus is to provide better and faster services via digital transformation and automation, including an online portal, AI-powered chatbots, a queue management system, and automating administrative tasks.   | It extensively uses COTS products for developing online portals, queue management systems, and open-source technologies for backend and frontend development and machine learning libraries. | While it will reduce the workload on DMV personnel and improve efficiency, the initial cost for digital transformation and maintenance could be substantial. |
| Success Metrics | Increased number of online transactions, reduced waiting times, increased customer satisfaction rates, reduction in administrative errors. | Successful integration of COTS products and open-source technology without significant issues, achieving desired functionalities. | Reduction in operational costs over time, reduction in staffing needs for administrative tasks. |

|              | Improve Service Delivery | Leverages COTS and Open Source | Reduce Ongoing Costs |
|--------------|--------------------------|--------------------------------|----------------------|
| **Plan 2** (Data-Driven Innovation) |            4             |              4                 |           5          |
| Rationale    | By creating a unified data platform and employing predictive analytics, customer service could be improved. However, the benefits might not be immediate. | It utilizes open-source data management systems and COTS business intelligence tools. But the successful integration of these technologies could be complex. | This approach targets optimization of resources and predictive maintenance, which could lead to significant cost savings over time. |
| Success Metrics | Improved resource allocation, fewer system downtimes, proactive issue resolution, improved vehicle maintenance for businesses. | Successful integration of COTS products and open-source technology, with the unified data platform delivering accurate insights. | Reduction in operational costs over time, decrease in downtime costs for businesses using fleet vehicles. |

|              | Improve Service Delivery | Leverages COTS and Open Source | Reduce Ongoing Costs |
|--------------|--------------------------|--------------------------------|----------------------|
| **Plan 3** (Customer-Centric Innovation)       |            4             |              4                 |           4          |
| Rationale    | It directly improves service delivery by providing more personalized and on-the-go services. But the improvement would depend on the user adoption rate of new systems like mobile apps and kiosks. | The plan uses COTS for CRM systems and open-source frameworks for mobile application development, but integrating them seamlessly with the existing system could be challenging. | Although it has the potential to reduce ongoing costs by automating transactions and improving efficiency, the savings might not be as substantial compared to Plans 1 and 2. |
| Success Metrics | Increase in customer satisfaction rates, increase in the number of transactions completed via the mobile app or self-service kiosks, improved customer communication. | Successful integration and operation of the CRM system, mobile app, and self-service kiosks. | Reduction in the costs related to handling customer inquiries and transactions, reduction in staffing needs for customer-facing roles. |


### Example 2 - Mobile App


Prompt 1: Generate three different plans a big four consultant can deliver for a mobile app developer to use A/B testing to improve ROI on their least profitable simcity style game with a free tier, a monthly subscription tier, and in-game purchase options. A successful plan meets each of the following three success criteria: 1) it defines a clear and discrete potential improvement for user action; 2) if the improved use action was deployed to the entire customer base costs would reduce or revenue would increase; and 3) the user action would not decrease user satisfaction with the app.


Prompt 2: Rate each plan against each of the three success criteria.  Display in a single markdown table with rows for each plan and columns for each success criteria.  Rate from 1 (lowest) to 5 (highest).  Include a row below each plan to describe the rationale for each rating.  In a row below the rationale, describe how success would be measured.


#### Output for Prompt 1

**Plan 1: Improving User Engagement through Tutorial Enhancement**

*Objective: Enhance the introductory tutorial to improve user understanding and engagement, leading to increased conversions to the subscription tier and in-game purchases.*

1. **A/B Test Hypothesis**: Users who understand the game better will engage more and be more likely to make in-game purchases or subscribe. By testing an enhanced tutorial against the existing one, we can evaluate if increased understanding drives revenue.

2. **A/B Test Implementation**: Split the new user base into two groups. Group A receives the existing tutorial, while Group B receives the enhanced tutorial. Collect data on subsequent user engagement and conversion rates.

3. **Expected Outcome**: If the enhanced tutorial is effective, Group B should show higher engagement and a higher conversion rate to the subscription tier and in-game purchases.

4. **ROI Improvement**: Increased conversions would result in higher revenue without necessitating an increase in costs.

5. **User Satisfaction**: An effective, engaging tutorial should improve the user experience and increase satisfaction, not decrease it.

**Plan 2: Balancing In-Game Rewards**

*Objective: Adjust the balance of in-game rewards to encourage more frequent usage and incentivize in-game purchases.*

1. **A/B Test Hypothesis**: By adjusting the in-game rewards, users may be more motivated to engage more frequently with the game and consider in-game purchases to advance quicker.

2. **A/B Test Implementation**: Create two versions of the game: one with the current reward structure (Group A) and one with the revised reward structure (Group B). Measure user engagement, frequency of logins, and rate of in-game purchases over a defined period.

3. **Expected Outcome**: If the hypothesis is correct, Group B should show increased engagement, more frequent usage, and a higher rate of in-game purchases.

4. **ROI Improvement**: If more users are incentivized to make in-game purchases, revenue should increase without significant additional costs.

5. **User Satisfaction**: If executed well, adjusting in-game rewards should increase enjoyment and engagement without negatively impacting user satisfaction.

**Plan 3: Subscription Tier Benefit Optimization**

*Objective: Enhance the benefits offered in the monthly subscription tier to increase conversions from the free tier.*

1. **A/B Test Hypothesis**: By offering additional benefits in the subscription tier, users may perceive more value and be more likely to convert from the free tier.

2. **A/B Test Implementation**: Maintain the current subscription tier benefits for Group A, while Group B receives the enhanced subscription tier. Measure the conversion rate from the free tier to the subscription tier over a set period.

3. **Expected Outcome**: If the hypothesis holds true, Group B should show a higher conversion rate to the subscription tier.

4. **ROI Improvement**: An increase in subscription conversions leads directly to increased monthly revenue with no additional costs.

5. **User Satisfaction**: Enhanced benefits should increase perceived value and satisfaction for users without detracting from the experience of those on the free tier.


#### Output for Prompt 2

| Plan | Defines clear potential improvement | Increase in revenue or decrease in costs | No decrease in user satisfaction |
| --- | --- | --- | --- |
| Tutorial Enhancement | 5 | 4 | 5 |
| Rationale | This plan clearly defines the potential improvement: enhancing the tutorial to increase user understanding and engagement. | If the new tutorial leads to more engaged users, this could increase in-game purchases and subscriptions, thereby increasing revenue. | An enhanced tutorial should improve user understanding and enjoyment of the game, likely increasing satisfaction. |
| Success Measurement | Success can be measured by comparing tutorial completion rates and the engagement level immediately after tutorial completion between the two groups. | Success can be measured by comparing conversion rates to in-game purchases and subscriptions before and after the introduction of the new tutorial. | User satisfaction can be gauged through user feedback and a decrease in negative reviews regarding the tutorial. |
| Balancing In-Game Rewards | 5 | 4 | 4 |
| Rationale | The potential improvement is clear: adjusting the in-game rewards to stimulate more frequent usage and incentivize in-game purchases. | If the new reward structure motivates more users to engage and make purchases, this could increase revenue without significant additional costs. | Adjusting rewards could increase engagement and satisfaction, but there's a risk that some users might feel the new structure is unfair. |
| Success Measurement | Success would be measured by observing changes in the average gameplay time and frequency of logins after adjusting the in-game rewards. | Success would be measured by comparing the rate of in-game purchases before and after the adjustment of rewards. | User satisfaction would be gauged by user feedback and a change in reviews regarding the in-game reward system. |
| Subscription Tier Benefit Optimization | 5 | 5 | 4 |
| Rationale | The potential improvement is clearly defined: enhancing the subscription tier benefits to encourage more users to convert from the free tier. | Increased conversion to the subscription tier would directly lead to increased revenue without additional costs. | Enhanced benefits should increase satisfaction among subscribers, but there's a slight risk that free users might feel neglected or pressured. |
| Success Measurement | Success would be measured by comparing the conversion rates from the free tier to the subscription tier before and after the enhancement of subscription benefits. | Success would be measured by the increase in monthly subscription revenue following the enhancement of benefits. | User satisfaction among both free users and subscribers would be gauged by user feedback and a change in reviews regarding the subscription tier. |


#### Output for Prompt 1 - Second Run

**Plan 1: Optimizing the Free to Subscription Tier Transition**

**Objective:** To enhance the conversion rate of users from the free tier to the subscription tier.

1. **Proposed A/B Test:** Compare two different methods of introducing the subscription tier to free users. Group A will be presented with an introduction to subscription benefits immediately after certain achievements in the game (e.g., upon reaching a new level), while Group B will receive a time-based prompt (e.g., after two weeks of play). The call to action will be prominent in both versions.
   
2. **Potential Improvement:** By optimizing the timing and context of introducing the subscription, there can be an increase in the conversion rate from free to paid users.
   
3. **Expected ROI Impact:** Increasing the conversion rate will raise subscription revenues without incurring any substantial costs.
   
4. **User Satisfaction:** By carefully crafting the presentation and timing of these prompts, it ensures that users are not overwhelmed by constant upsell efforts, thereby preserving user satisfaction.


**Plan 2: Enhancing In-Game Purchase Decisions**

**Objective:** To increase the frequency and volume of in-game purchases.

1. **Proposed A/B Test:** Experiment with two different ways of presenting in-game purchase options. Group A sees the current format while Group B is introduced to a more gamified system where exclusive rewards or discounts are unlocked upon reaching certain milestones in the game. 

2. **Potential Improvement:** The new presentation method may incentivize users to make more in-game purchases in pursuit of exclusive rewards, improving the revenue generated from this source.
   
3. **Expected ROI Impact:** By encouraging more in-game purchases, the game's revenue increases. The development costs are low as the new gamified system can be a modification of the existing one.
   
4. **User Satisfaction:** If the gamified system for in-game purchases is designed carefully, it can increase the thrill of the game, further enhancing user satisfaction.

**Plan 3: Reducing Server Load through Optimized Synchronization**

**Objective:** To reduce server load and hence operational costs without sacrificing the user experience.

1. **Proposed A/B Test:** Implement two different methods of data synchronization between the user's device and the game servers. Group A will continue with real-time sync, while Group B will use an intelligent sync system that primarily syncs data when players make significant progress or when they're not actively playing.

2. **Potential Improvement:** An intelligent sync system may reduce server load and associated costs significantly without affecting gameplay experience.
   
3. **Expected ROI Impact:** Reduced server load means lower operational costs, thereby improving the game's ROI.
   
4. **User Satisfaction:** As long as the intelligent sync system is designed well, players shouldn't notice a difference in their gameplay experience, keeping user satisfaction levels high.

#### Output for Prompt 2 - Second Run

| Plan/Description   | Clear and discrete potential improvement | Cost reduction or revenue increase | No decrease in user satisfaction |
|-----------------|-----------------------------------------|-----------------------------------|---------------------------------|
| Plan 1: Optimizing the Free to Subscription Tier Transition         |                 5                       |                 4                 |                4                 |
| *Rationale*     |Offers a distinct improvement in the presentation and timing of upsell prompts. | Could significantly increase monthly subscription revenue.| Careful design of upsell prompts will prevent user dissatisfaction.|
| *Success Measure* | Increase in the conversion rate from free to paid subscriptions, to be tracked using in-app analytics.| A statistically significant increase in monthly subscription revenue, monitored over a 3-month period post implementation. | Maintain or improve current user satisfaction ratings in user surveys and app store reviews over the same 3-month period.|

| Plan/Description   | Clear and discrete potential improvement | Cost reduction or revenue increase | No decrease in user satisfaction |
|-----------------|-----------------------------------------|-----------------------------------|---------------------------------|
| Plan 2: Enhancing In-Game Purchase Decisions         |                 4                       |                 5                 |                3                 |
| *Rationale*     | The gamification of in-game purchases is a clear change but it's not as distinct as Plan 1.| Could substantially increase revenue from in-game purchases.| While the plan could enhance enjoyment for some users, it might be seen as too pushy by others, potentially affecting satisfaction negatively.|
| *Success Measure* | Increase in frequency and amount of in-game purchases, monitored via in-app analytics. | A statistically significant increase in in-game purchase revenue, monitored over a 3-month period post implementation. | User satisfaction ratings, as per surveys and app store reviews, should not decrease over the same 3-month period.|

| Plan/Description   | Clear and discrete potential improvement | Cost reduction or revenue increase | No decrease in user satisfaction |
|-----------------|-----------------------------------------|-----------------------------------|---------------------------------|
| Plan 3: Reducing Server Load through Optimized Synchronization          |                 3                       |                 5                 |                5                 |
| *Rationale*     | While intelligent syncing is a distinct change, its impact is not directly observable by the users.| Significant reduction in server costs is expected.| No expected impact on user experience as the changes are behind the scenes.|
| *Success Measure* | Reduction in server load, as tracked by server usage statistics. | Decrease in operational costs related to server load, measured over a 3-month period post implementation. | User satisfaction ratings, as per surveys and app store reviews, should not decrease over the same 3-month period.|


# Problems, Goals, and Measuring What Matters

Before thinking about success, of course, the very first step is defining a problem to be solved or a goal to be achieved.  This is, in fact, the initializing point.  And I have noticed a recent uptick in posts about how "problem formulation" is key to effective prompts (https://hbr.org/2023/06/ai-prompt-engineering-isnt-the-future) (h/t to Liz Chase https://www.linkedin.com/posts/lizchaseld_prompt-engineering-is-not-the-future-liz-activity-7072519720574324736-uJNH and Jon Neiditz https://www.linkedin.com/pulse/problem-formulation-purpose-beyond-prompt-engineering-jon-neiditz/).  I could not agree more.  And yet, problem definition is just the starting line.  The finish line requires connecting the dots between 1) the problem and 2) how to objectively know when the solution occurs. Moreover, when it comes to dreaming up and building new things, I think we can frequently get better results by thinking in terms of positive future goals to be achieved and not necessarily past problems to be struggled with.  Some say, what you resist persists.  In any event, whether the desired result is a solution to a problem, or achievement of a fresh new goal, be sure to have clear, objective criteria for establishing when you are actually done.

There are a LOT of ways people and organizations have approached measuring aspects of success beyond the scientific method, per se.  Some of them include:

* Key Performance Indicators (KPIs): These are quantifiable measurements that reflect the critical success factors of an organization. They are a way of measuring performance against strategic and operational goals. KPIs help organizations understand if they're heading in the right direction—and if not, where they need to divert their attention to improve. It's common for KPIs to be tied to specific strategic objectives, such as increasing customer satisfaction or improving operational efficiency.
* Objectives and Key Results (OKRs): This is a goal-setting framework that helps organizations set ambitious goals with measurable results. OKRs are typically implemented on a quarterly basis and consist of an Objective, which defines a goal to be achieved, and up to 5 Key Results, which are specific measures used to track the achievement of that goal. The aim of OKRs is to ensure that everyone in the organization is moving in the same direction with transparency and clarity on expected outcomes. They are meant to set strategy and goals over a specified amount of time for an organization, teams and individuals.
* Balanced Scorecard (BSC): The Balanced Scorecard is a performance metric used in strategic management to identify, improve, and control a business's various functions and resulting outcomes. It includes financial measures that tell the results of actions already taken and complements those with measures on lead indicators: customer satisfaction, internal processes, and learning and growth.
* SMART Goals: SMART stands for Specific, Measurable, Achievable, Relevant, and Time-bound. This system is used for setting objectives in project management, employee performance management, and personal development.
* Management by Objectives (MBO): This is a management model aimed at improving the performance of an organization by clearly defining objectives that are agreed to by both management and employees.
* Key Result Area (KRA): KRAs refer to the general areas of outcomes or outputs for which a department's or individual's role is responsible. A typical role targets three to five KRAs.
* Critical Success Factors (CSFs): These are elements that are vital for a strategy to be successful. CSFs provide the key goals or objectives for your business and keep teams focused on the same crucial areas of business.
* Performance Prism: This is a performance measurement framework that focuses on stakeholders. It examines the relationship between the organization's stakeholders' wants and needs, strategies, processes, capabilities, and stakeholder contributions.
* Hoshin Kanri: Also known as Policy Deployment, it is a strategic planning method used to ensure that the strategic goals of a company drive progress and action at every level within the company.

I'm directly familiar with OKRs and KPIs, based on having been on various teams for which these were required aspects of the work.  I'm somewhat familiar with some others, but tbh, I just asked an LLM to help me identify good examples (a link to that ChatGPT session is included below).  And yes, I've at least Googled enough to confirm they all exist!. I think each of these have some useful information and perspective on ways of measuring success that can be applied to prompt composition and evaluation of LLM outputs.  The formulation "I'll know this has succeeded when XYZ" remains my anchor for purposes of this post.


# Closing Thoughts and Hopes for the Future

You may be thinking something like "I have no idea how to actually do any of this".  I find myself thinking that all the time.  As it turns out, LLMs are also quite good at generating prompts when given even very general information about what is desired.  One great way to do this is to simply prompt something along these lines: "Please help me compose a clear and effective prompt or set of prompts to [fill in your goal here].  But you can go much further, by specifying you want help defining the problem or goal, then help identifying the succes criteria.  If you are not getting good results from these approaches, another effective prompt is to ask something like "what other information would be needed in order to compose a prompt that" achieves the goal.  In preparation for publishing this post, I also consulted ChatGPT (using the GPT-4 model) to get some quick feedback on whether I was missing anything, especially in the examples above.  The chat session is here: https://chat.openai.com/share/dea4b961-a377-4c4f-971c-50f76cbe384f and it includes some good tips on ways to be even more specific, prioritizing success criteria, and surfacing risks and challenges, among other things. When it comes to using LLMs better, LLMs are your friend! 

I hope this post sparks something in you.  I hope you suddently remember, or sponteneously realize, a problem you really want to solve or (perhaps even better) and shiny new goal you want to achieve and that this approach to using LLMs is useful for you moving forward from that thought to an actionable set of steps to measurably create the better future you imagine.  And I have a slightly more selfish hope as well.  If you try the "Success is All You Need" prompt approach, or some variation of it, I invite and encourage you to share your prompts and the outputs with me.  I'd like to keep updating this post and possibly make more posts on various aspects of this, and I'd love to include some of your examples, along with your questions, issues, and ideas about this approach to prompt composition.  You can share that through this link (which include a simple, standard Creative Commons license, so I can post some of the incoming examples in future posts and generally share the knowledge on this topic, with attribution to you of course, if you wish).  Here's the form: https://forms.gle/c8j3G9uZwRqxEGXg7 
