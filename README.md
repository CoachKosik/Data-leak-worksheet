# Data leak worksheet - Determine appropriate data handling practices

### Overview
In this activity, you will review the results of a data risk assessment. You will determine whether effective data handling processes are being implemented to protect **information privacy**.

Data is among the most valuable assets in the world today. Everything from intellectual property to guest WiFi networks should be protected with a combination of technical, operational, and managerial controls. Implementing the **principle of least privilege** is essential to protect information privacy.

### Scenario
You work for an educational technology company that developed an application to help teachers automatically grade assignments. The application handles a wide range of data that it collects from academic institutions, instructors, parents, and students.

Your team was alerted to a data leak of internal business plans on social media. An investigation by the team discovered that an employee accidentally shared those confidential documents with an external business partner. An audit into the leak is underway to determine how similar incidents can be avoided.

A supervisor provided you with information regarding the leak. It appears that the principle of least privilege was not observed by employees at the company during a sales meeting. You have been asked to analyze the situation and find ways to prevent it from happening again.

First, you'll need to evaluate details about the incident. Then, you'll review the controls in place to prevent data leaks. Next, you'll identify ways to improve information privacy at the company. Finally, you'll justify why you think your recommendations will make data handling at the company more secure.

### Step 1: Access the template
Step 1: Access the template
To use the template for this course item, click the link and select Use Template.

Link to template: 
<a href="https://docs.google.com/document/d/1y0MesBW_6yjRF6M3Uuu23VydaBvfLq8TItNfsNAsuMw/edit?usp=sharing">Data leak worksheet</a>

### Step 2: Analyse the situation
The principle of least privilege is a fundamental security control that helps maintain information privacy. However, least privilege starts to lose its effectiveness when too many users are given access to information. Data leaks commonly happen as information gets passed between people without oversight.

To start your analysis, review the following incident summary provided by your supervisor:

*A customer success representative received access to a folder of internal documents from a manager. It contained files associated with a new product offering, including customer analytics and marketing materials. The manager forgot to unshare the folder. Later, the representative copied a link to the marketing materials to share with a business partner during a sales call. Instead, the representative shared a link to the entire folder. During the sales call, the business partner received the link to internal documents and posted it to their social media page.*

After reviewing the summary, write **20-60 words (2-3 sentences)** in the **Issue(s)** row of the Data leak worksheet describing the factors that led to the data leak.  

### Step 3: Review current data policy controls
Data leaks are a major risk due to the amount of data handled by the application. The company used the NIST Cybersecurity Framework (CSF) to develop their plan for addressing their information privacy concerns.

Review the **Security plan** snapshot resource of the worksheet. Then, review the **NIST SP 800-53: AC-6** resource of the worksheet.

After, write **20-60 words (2-3 sentences)** in the *Review** row of the Data leak worksheet to summarize what you've learned about NIST SP 800-53: AC-6.

### Step 4: Identify control enhancements 
The company's implementation of least privilege is based on NIST Special Publication 800-53 (SP 800-53). NIST developed SP 800-53 to provide businesses with a customizable information privacy plan. It's a comprehensive resource that describes a wide range of control categories, including least privilege.

Use the **NIST SP 800-53: AC-6** resource to determine two control enhancements that might have prevented the data leak. List the **two improvements** in the **Recommendation(s)** row of the worksheet.

### Step 5: Justify your reccomendations
At the end of your analysis, it's time to communicate your findings to your supervisor. It's important to justify your recommendations so that the supervisor can relay this information to other decision makers at the company.

Consider the issues you identified earlier. Then, write **20-60 words (2-3 sentences)** in the **Justification** row describing why you think the control enhancements you recommend will reduce the likelihood of another data leak.

# Completed Data Leak Worksheet
**Incident summary:** A sales manager shared access to a folder of internal-only documents with their team during a meeting. The folder contained files associated with a new product that has not been publicly announced. It also included customer analytics and promotional materials. After the meeting, the manager did not revoke access to the internal folder, but warned the team to wait for approval before sharing the promotional materials with others.

During a video call with a business partner, a member of the sales team forgot the warning from their manager. The sales representative intended to share a link to the promotional materials so that the business partner could circulate the materials to their customers. However, the sales representative accidentally shared a link to the internal folder instead. Later, the business partner posted the link on their company's social media page assuming that it was the promotional materials.

<table>
  <tr>
    <td><strong>Control</strong></td>
    <td><strong>Least privilege</strong></td>
  </tr>
  <tr>
    <td><strong>Issue(s)</strong></td>
    <td><i>What factors contributed to the information leak?</i>
      <p>Several factors contributed to the information leak:<br>
      <p><ul><li><strong>Lack of Access Controls:</strong>  The internal folder was not restricted to authorized personnel, allowing the sales team to access sensitive information.
      <li><strong>Human Error:</strong>  The sales representative mistakenly shared the internal folder link instead of the intended promotional materials.
      <li><strong>Insufficient Awareness and Training:</strong>  The sales team member may not have fully understood the sensitivity of the information and the potential consequences of sharing it publicly.</li></ul></p>
      </p>
    </td>
  </tr>
  <tr>
    <td><strong>Review</strong></td>
    <td><i>What does NIST SP 800-53: AC-6 address?</i>
NIST SP 800-53: AC-6 addresses the importance of implementing least privilege access controls to safeguard sensitive data. This control aims to limit user access to only the resources and information necessary to perform their assigned tasks. By minimizing user privileges, organizations can significantly reduce the risk of unauthorized access and potential data breaches.
</td>
  </tr>
  <tr>
    <td><strong>Recommendation(s)</strong></td>
    <td><i>How might the principle of least privilege be improved at the company?</i>
The company could enhance its security posture by implementing the principle of least privilege more strictly. This would involve granting employees access only to the resources necessary to perform their specific tasks. In the case of the sales team, access to internal documents should be limited to authorized personnel on a need-to-know basis. Regular audits of user privileges can help identify and rectify any unnecessary access rights.
</td>
  </tr>
  <tr>
    <td><strong>Justification</strong></td>
    <td><i>How might these improvements address the issues?</i>
      <p>By implementing these improvements, we can significantly mitigate the risk of accidental data exposure:<br>
      <p><ul><li>Restricting shared links to employees ensures that only authorized individuals can access sensitive information.
      <li>Regular audits of access permissions provide an additional layer of security, allowing for early detection and remediation of any unauthorized access.</li>
       </ul></p>
      </p></td>
  </tr>
</table>

# Security plan snapshot
The NIST Cybersecurity Framework (CSF) uses a hierarchical, tree-like structure to organize information. From left to right, it describes a broad security function, then becomes more specific as it branches out to a category, subcategory, and individual security controls.

<table>
  <tr>
    <td><strong>Function</strong></td>
    <td><strong>Category</strong></td>
    <td><strong>Subcategory</strong></td>
    <td><strong>Reference(s)</strong></td>
  </tr>
  <tr>
    <td><strong>Protect</strong></td>
    <td>PR.DS: Data security</td>
    <td>PR.DS-5: Protections against data leaks.</td>
    <td>NIST SP 800-53: AC-6</td>
  </tr>
</table>

In this example, the implemented controls that are used by the manufacturer to protect against data leaks are defined in NIST SP 800-53—a set of guidelines for securing the privacy of information systems.

**Note:** References are commonly hyperlinked to the guidelines or regulations they relate to. This makes it easy to learn more about how a particular control should be implemented. It's common to find multiple links to different sources in the references columns.

# NIST SP 800-53: AC-6
NIST developed SP 800-53 to provide businesses with a customizable information privacy plan. It's a comprehensive resource that describes a wide range of control categories. Each control provides a few key pieces of information:
  * **Control:** A definition of the security control.
  * **Discussion:** A description of how the control should be implemented.
  * **Control enhancements:** A list of suggestions to improve the effectiveness of the control.

<table>
  <tr>
    <td rowspan="4"><strong>AC-6</strong></td>
    <td>Least Privilege</td>
  </tr>
  <tr>
    <td><strong>Control:</strong><br>
    Only the minimal access and authorization required to complete a task or function should be provided to users.
</td>
  </tr>
  <tr>
   <td>Discussion:
Processes, user accounts, and roles should be enforced as necessary to achieve least privilege. The intention is to prevent a user from operating at privilege levels higher than what is necessary to accomplish business objectives.
</td>
  </tr>
  <tr>
    <td><strong>Control enhancements:</strong><br>
    <p></p><ul><li>Restrict access to sensitive resources based on user role.
    <li>Automatically revoke access to information after a period of time.
    <li>Keep activity logs of provisioned user accounts.
    <li>Regularly audit user privileges.</li><br>
</td>
  </tr>
</table>

Note: In the category of access controls, SP 800-53 lists least privilege sixth, i.e. AC-6.
