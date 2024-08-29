<h1>Case Study Preparation and Your Next Steps</h1>

<h2>Module Overview (video)</h2>
In Module 6, you'll learn how to analyze a case study for the certification exam and start developing your personalized study plan.

<h2>Analyzing a Case Study: Dress4Win (video)</h2>
<p>In preparing for the certification exam, you'll need to analyze case studies that describe fictitious business scenarios. Review official case studies from the exam guide and consider designing solutions for each case. The analysis process involves:</p>

<ol>
    <li>Understanding overarching goals.</li>
    <li>Identifying and itemizing objectives.</li>
    <li>Categorizing and prioritizing objectives.</li>
    <li>Analyzing objectives.</li>
    <li>Determining preliminary options.</li>
    <li>Refining options.</li>
    <li>Identifying the final solution.</li>
</ol>

<p>Use the provided case studies, like "Dress for Win," to practice these steps. Case studies include a company overview, solution concept, existing technical environment, business and technical requirements, and an executive statement outlining priorities and challenges.</p>

<h2>Understand overarching goals (video)</h2>
<p>The first step in analyzing a case study is to read it thoroughly to understand the overarching goals. As you review the "Dress for Win" case, consider the organization's objectives, any timelines, and limiting factors. Look for emerging themes, such as online retail or mobile applications, and note these as they guide your detailed analysis.</p>

<p>At the end of this step, identify the organization's goals and objectives. Utilize resources like the Cloud Architecture Center, which offers reference architectures, and Google Cloud's blog and YouTube channel for useful design insights. These resources can help you combine different solutions to address your needs.</p>

<h2>Identify and itemize objectives (video)</h2>
<p>The next step in analyzing a case study is to identify and itemize the objectives by breaking down complex problems into simpler ones. This helps ensure that all relevant objectives, including those not directly mentioned, are considered.</p>

<p>Rewrite each sentence from the case study as an objective. If necessary, split complex sentences into multiple objectives. Pay attention to key words like "all," "never," and "must" which might influence solution choices or eliminate options.</p>

<p>After listing the objectives, review them to ensure clarity and completeness. This methodical approach ensures no objectives are overlooked and provides a clear, actionable list for further analysis.</p>

<h2>Categorize and prioritize objectives (video)</h2>
    <p>Case Study Analysis Summary</p>
    <ul>
        <li><strong>Exam Case Studies:</strong> Business and technical requirements are clearly divided into sections.</li>
        <li><strong>Real-Life Scenarios:</strong> Identifying and itemizing objectives helps in getting stakeholder approval and ensures alignment on objectives before designing a solution.</li>
        <li><strong>Categorization:</strong> Classify objectives into solution components, technical requirements, and business requirements. This helps in understanding their importance and ensuring all requirements are met.</li>
        <li><strong>Categories:</strong>
            <ul>
                <li><strong>Existing Infrastructure:</strong> Includes components like servers and applications currently in use.</li>
                <li><strong>Technical Requirements:</strong> Related to migrating capabilities to the cloud, scalability, and other technical needs.</li>
                <li><strong>Business Requirements:</strong> Related to business goals such as innovation speed and security.</li>
            </ul>
        </li>
        <li><strong>Example from Dress4Win Case Study:</strong>
            <ul>
                <li><strong>Existing Infrastructure:</strong> Servers in a co-location facility.</li>
                <li><strong>Technical Requirements:</strong> Migration to the cloud, scalability, automation.</li>
                <li><strong>Business Requirements:</strong> Improved agility, rapid provisioning, performance optimization.</li>
            </ul>
        </li>
        <li><strong>Process:</strong> Review and categorize all case study objectives. Compare them with the provided business and technical requirements to identify any new needs.</li>
        <li><strong>Components:</strong> Understand the existing infrastructure to identify equivalent or new solution components needed. This includes databases, compute resources, and other critical elements.</li>
    </ul>
    
<h2>Analyze and determine preliminary options (video)</h2>
    <p>Summary of Component Analysis</p>
    <ul>
        <li><strong>Approach to Component Analysis</strong>: There are various methods to analyze components; the discussed process is just one example.</li>
        <li><strong>Generating Solutions</strong>: Start by listing potential solutions to avoid limiting options based on personal preferences.</li>
        <li><strong>Understanding Requirements</strong>: Ensure you grasp compute, storage, and network needs as most solutions will need these.</li>
        <li><strong>Refining Solutions</strong>: After listing potential components, refine the list to match business and technical requirements.</li>
        <li><strong>Evaluating Networking Solutions</strong>:
            <ul>
                <li><strong>Examples</strong>: Cloud VPN, Partner Interconnect, and Dedicated Interconnects.</li>
                <li><strong>Considerations</strong>: For full production migration, Dedicated Interconnect is optimal for high performance and availability.</li>
            </ul>
        </li>
        <li><strong>Message Queueing</strong>:
            <ul>
                <li><strong>Options</strong>: RabbitMQ vs. Pub/Sub.</li>
                <li><strong>Recommendation</strong>: Pub/Sub is preferable due to ease of scaling and integration with Google Cloud services.</li>
            </ul>
        </li>
        <li><strong>Analyzing Database Migration</strong>:
            <ul>
                <li><strong>Existing Environment</strong>: MySQL instance with specific requirements.</li>
                <li><strong>Options</strong>: Compute Engine or Cloud SQL.</li>
                <li><strong>Recommendation</strong>: Cloud SQL for managed services and ease of management.</li>
            </ul>
        </li>
        <li><strong>Cost Considerations</strong>: Use the pricing calculator to compare costs between different solutions.</li>
        <li><strong>Course Focus</strong>: Preparation for the Professional Cloud Architecture track, with a preference for managed services like Spanner for large databases.</li>
    </ul>
<h2>Refine options identify solution</h2>
    <ul>
        <li><strong>Refine Potential Solutions:</strong>
            <ul>
                <li>Review documentation for each potential solution.</li>
                <li>Identify strengths and weaknesses of products and services.</li>
                <li>Determine when not to use a product based on documentation.</li>
            </ul>
        </li>
        <li><strong>Evaluate Cost and Scalability:</strong>
            <ul>
                <li>Pay close attention to cost and scalability criteria.</li>
                <li>Use these factors to guide your choice of product.</li>
            </ul>
        </li>
        <li><strong>Review Best Practices:</strong>
            <ul>
                <li>Check best practices sections in documentation.</li>
                <li>Follow Google Cloud architecture framework, including systems design, operational excellence, security, reliability, cost, and performance optimization.</li>
            </ul>
        </li>
        <li><strong>Understand Best Practices:</strong>
            <ul>
                <li>As a professional Cloud architect, it's crucial to know and apply best practices.</li>
                <li>Use best practices to propose optimal solutions and avoid mistakes.</li>
            </ul>
        </li>
        <li><strong>Document and Refine Solutions:</strong>
            <ul>
                <li>Read documentation and best practices to refine your solutions.</li>
                <li>Consider alternative options in case of changes in requirements.</li>
            </ul>
        </li>
        <li><strong>Know Google Cloud Offerings:</strong>
            <ul>
                <li>Be familiar with Google Cloud products even if you haven’t used them.</li>
                <li>Example: Understand what Memory Store does.</li>
            </ul>
        </li>
        <li><strong>Use Reference Architectures:</strong>
            <ul>
                <li>Refer to architecture diagrams and documentation for guidance.</li>
                <li>Combine different reference solutions to create a suitable design.</li>
            </ul>
        </li>
        <li><strong>Interrogate Your Design:</strong>
            <ul>
                <li>Ask critical questions to find potential flaws:
                    <ul>
                        <li>Can the design scale with increased traffic?</li>
                        <li>Are there big data services that can be used?</li>
                        <li>How will the solution be managed and accessed?</li>
                    </ul>
                </li>
            </ul>
        </li>
        <li><strong>Apply to Case Study:</strong>
            <ul>
                <li>Example: Compute Engine scalability for web application servers.</li>
                <li>Consider managed compute offerings for efficiency and future implementation.</li>
            </ul>
        </li>
        <li><strong>Final Design Steps:</strong>
            <ul>
                <li>Make formal observations about requirements.</li>
                <li>Hypothesize and test solutions.</li>
                <li>Diagram the solution to communicate design and identify gaps.</li>
            </ul>
        </li>
        <li><strong>Real-Life Considerations:</strong>
            <ul>
                <li>Stakeholder review and feedback.</li>
                <li>Iterate based on feedback from stakeholders and specialists.</li>
                <li>Continue learning and stay updated with best practices and new solutions.</li>
            </ul>
        </li>
        <li><strong>Certification Maintenance:</strong>
            <ul>
                <li>Re-certify every two years.</li>
                <li>Keep learning to avoid last-minute cramming.</li>
            </ul>
        </li>
    </ul>

    
<h2>Weekly Study Goals</h2>
    <ul>
        <li>Creating a Study Plan: Use the notes from the course to develop a weekly study plan. Assess your knowledge and skills based on diagnostic questions from the course.</li>
<li>Exam Preparation Considerations: Determine when you will take the exam. Calculate the number of weeks available for preparation. Estimate the number of hours you can realistically spend each week. Calculate the total preparation time and plan to include time for review.

 <li>Study Plan Details: Allocate time for re-taking diagnostic questions and sample questions. Plan to fill any knowledge gaps before the exam.</li>

 <li>Weekly Study Goals: Use the workbook template to plan your study activities. Focus on specific exam guide sections or topics. Choose courses or modules for deeper learning. Engage with Skill Badges or labs for hands-on practice. Review relevant documentation. Use additional resources like sample questions. Plan for case study preparation.</li>

 <li>Example Study Approach: Structure a week around specific topics like managed services. Include targeted modules, Skill Badges, and documentation. Alternatively, dedicate one week to completing a course and another to focusing on a Skill Badge.</li>

 <li>Adjusting the Plan: Duplicate the weekly template based on the number of weeks needed. Adjust plans according to areas needing more focus.</li>

 <li>Additional Resources: Refer to course notes and slides for more information. Register for the exam at Google Cloud Certification.</li>
    </ul>
