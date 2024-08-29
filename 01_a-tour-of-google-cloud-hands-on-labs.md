<h1>A Tour of Google Cloud Hands-on Labs</h1>
<p><b>GSP282</b></p>
<p>Google Cloud is a comprehensive suite of cloud services provided by Google, covering areas such as computing, storage, data analytics, machine learning, and networking. Google Cloud Skills Boost offers a range of labs and courses to help users build cloud skills, track progress, and earn badges, with Qwiklabs serving as the platform for these resources. This introductory lab focuses on familiarizing users with the Google Cloud Console, teaching the basics of Google Cloud features and the lab environment. It's ideal for those new to cloud computing or looking to understand Google Cloud and Qwiklabs better.</p>

<h2>Objectives</h2>
<p></p>
<li>Navigate and identify key features of the lab platform.</li>
<li>Access the Cloud Console using specific credentials.</li>
<li>Understand Google Cloud projects and common misconceptions about them.</li>
<li>Use the Google Cloud Navigation menu to explore various services.</li>
<li>Explore basic roles and use the Cloud IAM service to view user actions.</li>
<li>Examine the API library and its main features.</li>

<h2>Prerequisites</h2>
This introductory lab is ideal for those new to Google Cloud. If you are already familiar with the Cloud Console, you might consider starting with labs on Cloud Shell and gcloud or creating a virtual machine instead. To avoid issues with credentials, sign out of any personal or corporate Google Cloud accounts before starting the lab, and if using a Pixelbook, run the lab in an Incognito window.

<h2>Lab Fundamentals</h2>
<p></p>All Google Cloud labs share a similar interface, with key features including:</p>
<li>Start Lab Button: Initiates a temporary Google Cloud environment with necessary services and credentials, and starts a countdown timer.</li>
<li>Credit: Represents the cost of the lab, typically 1 Credit = 1 USD, though some introductory labs are free.</li>
<li>Time: Indicates the duration you have to complete the lab before the environment and resources are deleted. Ensure to focus on the lab to avoid losing progress.</li>
<li>Score: Tracks your completion of the lab's steps; you need to follow all steps in order to receive credit.</li>
<li>Paying for a Lab: Some labs require payment. You'll choose to start the lab with an access code or credits, or buy credits if needed.</li>
<li>Reading Instructions: Instructions are in one browser tab, while the Google Cloud console opens in another. You may need to switch tabs or use multiple monitors.</li>

<h3>Test your understanding</h3>
<li>Start Lab: This builds a temporary environment in Google Cloud.</li>
<li>When the timer reaches 00:00:00, you will lose access to your temporary Google Cloud environment.</li>
<li>Some labs have tracking, which scores your completion of hands-on lab activities.</li>

<h2>Task 1. Accessing the Cloud Console</h2>
<p>To start your lab:</p>
<ol>
        <li>Click "Start Lab": Wait for the environment to set up. Once the timer starts and the button changes to "End Lab," you're ready to log in.</li>
 <li>Do Not Click "End Lab" Early: Clicking this button before finishing will invalidate your credentials and prevent you from accessing your work.</li>
 <li>Lab Details Pane: Once your lab is running, check the Lab details pane on the left for:
	<ul><li>Open Google Cloud Console Button: Opens the Cloud Console where you'll do most of your work.</li>
	<li>Project ID: A unique identifier for your Google Cloud resources.</li>
	<li>Username and Password: Temporary credentials for accessing Google Cloud during the lab.</li></li></ul>
 <li>Sign In:
	<ul><li>Click "Open Google Console" to go to the sign-in page.</li>
	<li>Use the lab-provided username (e.g., googlexxxxxx_student@qwiklabs.net) and password.</li>
	<li>Accept Google's terms of service to access the Cloud Console.</li></li></ul>
</ol>
<p>Ensure to use the provided student credentials and not your personal or company email. After signing in, you’ll be ready to begin the lab tasks.</p>

<h3>Test your understanding</h3>
<li>System admin: is not found in the left pane</li>
<li>The username in the left panel, which resembles googlexxxxxx_student@qwiklabs.net, is a Cloud IAM identity.</li>

<h2>Task 2. Projects in the Cloud console</h2>
<p>A Google Cloud project organizes your resources, like virtual machines and databases, and includes settings and permissions. Each project has a name, number, and ID used when interacting with Google Cloud services. You might have access to multiple projects in different labs. To view all projects, click the drop-down menu in the console title bar and select "All," noting that "Qwiklabs Resources" is a shared project with read-only access. This project contains files and datasets for labs but cannot be modified. Your current project is temporary and will be deleted after the lab ends. Start each new lab with a new project specific to that lab's tasks.</p>
<p>All products: https://cloud.google.com/products</p>

<h3>Test your understanding</h3>
<li>Google Cloud Project: An organizing entity for anything you build with Google Cloud</li>
<li>Qwiklabs Resources is shared (read only) with all Qwiklabs users, which means that you cannot delete or modify it.</li>
<li>False: Qwiklabs Resources is the project where you run all of your lab steps.</li>

<h2>Task 3. Roles and permissions</h2>
Google Cloud uses Cloud IAM to manage permissions and roles for resource access. To view roles and permissions, go to IAM & Admin > IAM in the Navigation menu. Locate your "@qwiklabs" username to see its roles—typically, "Editor" for basic permissions, allowing modification of resources but not member management. Basic roles include:
<li>Viewer: Read-only access.</li>
<li>Editor: Modify resources.</li>
<li>Owner: Manage roles, permissions, and billing.</li>

<h3>Test your understanding</h3>
<li>Navigation menu: Offers quick access to the platform's services and also outlines its offerings.</li>
<li>Basic roles set project-level permissions and, unless otherwise specified, control access and management to all Google Cloud services.</li>
<li>Edior role: Provides all viewer permissions, plus permissions for actions that modify state, such as changing existing resources.</li>

<h2>Task 4. APIs and services</h2>
<p>Google Cloud APIs, covering over 200 areas from business to machine learning, are essential for integrating with Google Cloud projects and applications. APIs can be accessed directly or via client libraries, following resource-oriented design principles. Labs often automatically enable necessary APIs for you, but you'll need to enable them manually for personal projects. Most APIs offer detailed usage metrics, such as traffic, error rates, and latencies, to help troubleshoot issues with applications using Google services.</p>

<p>Diagflow: https://developers.google.com/apis-explorer/#p/dialogflow/v3/</p>
<p>API directory: https://developers.google.com/apis-explorer/#p/</p>

<h3>Test your understanding</h3>
<li>False: When you start a lab, you need to enable APIs in your project to start working with Google Cloud.</li>

<h2>Task 5. Ending your lab</h2>
<p>Click "End Lab" and "Submit" to finish. Rate the lab and leave feedback, as Google appreciates your input. Ending the lab revokes access to the project and your work. You will be signed out of the Cloud console, so you can close that tab.</p>

<h2>Recap</h2>
In this lab, you gained a solid understanding of the Cloud console, including projects, roles, and services. You practiced using Cloud IAM and API libraries, and you're now prepared for more labs.
