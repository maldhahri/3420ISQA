<h1>Processes</h1>

<p>Create New Policy for Software: this process allows the Manager to create New policy, and send it to policy database through this process.</p>
<p>Check Software for OSS Components: This process is to organize the package that being sent from Developer and send them to NIST Vulnerability Database and Scan for package license. </p>
<p>Scan for OSS Components: This process is to scan all the packages that has been sent for check licenses availability</p>
<p>Retrieve Software License and Vulnerability Info: This process is to retrieve licenses and vulnerabilities information from licenses and vulnerabilities database</p>
<p>Retrieve Software Policy: retrieve all the policy information from policy database</p>


<h1>Data Flows</h1>
<p>Software Package: Software package information that being sent from developer</p>
<p>Software Package Name: The name of the package that being sent to NIST Vulnerability Database.</p>
<p>Vulnerabilities Result: The checked result of the package from NIST Vulnerability Database</p>
<p>License Scan Results: License information results that being sent from Scan for OSS Components.</p>
<p>L&V Request: the packages of  vulnerabilities and Licenses that being requested from Developer or Manager</p> 
<p>L&V Results: The packages of vulnerabilities and Licenses results that being pulled from Licenses and Vulnerabilities Database.</p>
<p>Request for current Software Policy:  Policy information that being requested that from manager</p>
<p>Software Policy: A Package of policy information that being sent from Policy Database</p>
<p>New Policy for Software : New Policy that is made by manager</p>
<p>Edit of Policy for Software: Policy changes that are made by manager</p>

<h1>Entities</h1>
<p>Manager: A person who can request licenses and vulnerabilities results and create or edit policies.</p>
<p>Developer: A person who can submit a software package to be scanned and request licenses and vulnerabilities results.</p>


<h1>Data Stores</h1>

<p>Licenses and Vulnerabilities DB: All of the packages that being checked results needs to be stored in this database and use this organization.</p>
<p>Policy DB: The database which contains all the policies for this project.</p>
<p>NIST Vulnerabilities DB : National Institute of Standards and Technology contains software vulnerability information that allows people send package to check vulnerability information</p>


