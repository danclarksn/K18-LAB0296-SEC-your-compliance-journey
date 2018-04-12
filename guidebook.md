# Apps and Dashboard

## Goal

The goal of this lab is to understand General Data Protection
Regulation (GDPR) requirements, its impact on your organization, and how
ServiceNow can help your compliance journey to GDPR. ServiceNow
Governance, Risk, and Compliance (GRC) helps bring order to an
enterprise's compliance requirements to GDPR. It provides best practices
to meet the GDPR requirements.  
This lab explains key ServiceNow
application to support GDPR and names the key citations (regulatory
requirements) for GDPR.

Getting Started -- Log on to Your Training Instance 
====================================================

1.  Navigate to the unique instance URL provided to you.  

2.  Log on with the provided credentials.  

3.  See your homepage. You can change your homepage to system dministration by selecting it from the homepage dropdown list. \
    \
    ![Homepage](./media/image2.png)

4.  See your favorite applications by clicking on the **star**
    ![Star](./media/image3.png) next to the application.

    ![Navigator](./media/image4.png)

5.  Discover GRC applications and its modules by typing the first few
    letters of **Policy & Compliance**; **Risk Management** **& Audit
    Management**.\
    \
    ![Navigators](./media/image5.png)

Check Your Homepage
===================

1.  Click the **ServiceNow** logo.

    ![Logo](./media/image6.png)

2.  In the homepage window, search for compliance from the dropdown list.

    ![Complicance](./media/image7.png)

3.  Select **Compliance Overview**.

4.  See initial Compliance status.  
    You should see the **GDPR Compliance**
    report as empty for now. The related **gauges/reports** are updated
    as you progress with the lab.

# Authority Document GDPR

## Goal

This lab explores the GDPR authority document. It also explains the
different citations for regulatory requirements.

## GDPR Authority Document

1.  In the **Filter Navigator**, enter **authority** to search Authority > Documents.

2.  Click **Authority Documents**.

3.  Under **Authority Documents** in the **Common Name** field, search for **\*EU**.

![EU](./media/image8.png)

**Note:** See the example below. If your **Type** field for **EU GDPR** Authority Document is empty, you can add the relevant type by double-clicking on the empty field.
    
![List](./media/image10.png)

4.  Click the **EU General Data Protection link (begins with AD00)**.  
    You might have different authority document number.

5.  See the overall **GDPR** information.

6.  Scroll to **Related Lists** and click **Citations**.

7.  In the **Reference** field, search for **Art. 35**.

8.  See the relevant article, information, and respective subsections.

    ![Article](./media/image11.png)

# Policy Creation

## Goal

This lab explains how to create an organizational policy and policy statements that matches requirements and describes the outlines for GDPR.

## Policy Creation

1.  Navigate to the **Policy & Management** application.

2.  Search for **Policies**, and then click **Policies** to list them.

3.  At the top of the policies page, click **New**.

    ![Policies page](./media/Policy_creation.png)

5.  On the top of the
    record, a full **Policy Life Cycle Stages** list appears.

6.  Fill out **New Policy Record** with input as shown below.  
    You can click the
    ![Icon ](./media/image13.png) icon to add yourself (**System
    Administrator**) or click the lock icon to add **Policy
    Approver**.
    
    * Name: Data Protection Policy
    
    * Owner: Policy Owner
    
    * Type: Policy
    
    * Owning group: Policy Management
    
    * Description: Data Protection Policy
    
    
    ![New Policy Record](./media/image14.png)
    
    **Note:** You can provide any valid dates for the purpose of this lab. For simplicity, we have skipped any additional Policy Reviewer step here.

7.  To save the record, right-click the **Policy Record bar**, open the dropdown menu, and then click **Save**.

    ![Right Click](./media/image16.png)
    
8.  In the Filter Navigator, enter **Knowledge**.

9.  Click **Knowledge** application.

    ![Knowledge application](./media/image17.png)
    
10. Search for **\*gdpr** in the search bar. Press enter to continue.

11. You see a Lab Data Protection Policy.

12. Open the **Policy**.

13. The **Lab Data Protection policy** describes different sections required for a Data Protection policy. Pl. review the policy content.

    ![Lab Protection Policy](./media/image18.png)

14. Copy content of the Lab Data Protection Policy.

15. Return to your policy by clicking on the history
    (![History Icon](./media/image19.png) icon. Click the **Policy** you just created. You should be now back in the Policy Record.
    
    ![Policy Record](./media/image20.png)

16. Paste the copied content into **Policy Text** field.

17. **Save** the record by right clicking in the top gray bar and clicking Save.

    ![Policy Record](./media/image21.png)
    
    Now assign relevant Policy Statements to the Policy.
    
    Generate Policy Statements that are defined for the policy by
    clicking **Add Statements**.
    
    ![Policy Statement](./media/image22.png)

18. Scroll to related lists and click on **Policy Statements.** You see 9 policy statements added to the Policy.

    ![Policy Statements List](./media/image23.png)
    
1. Click on any of the Reference number (e.g. 00357). A Policy Statement window opens with underlying reference number. Go to **citations** tab under Related Lists and check that at least one EU GDPR Regulation citation is aligned with that policy statement.

    ![Policy Statement](./media/image24.png)

20. Come back to your policy.

21. Move forward into Policy Life Cycle. Go to next stage and click **Ready for Review**.

    ![Ready for Review](./media/image28.png)

The policy moves to next stage **Review** in the Life Cycle Flow. A reviewer can now review the Policy. For this lab go directly to next
step: **Approval**.

1.  Click **Request Approval**. Approval request goes to **Policy Approver** & **System Administrator.** The policy form field becomes
    now read-only as shown below in 2^nd^ example.\
    \
    ![Policy](./media/image29.png)
    
    ![Data Protection Policy](./media/image30.png)

22. After requesting approval, policy life cycle state changes to **Awaiting approval** as shown below.

    ![Awaiting Approval](./media/image31.png)
    
23. Scroll to related lists and click **Policy Approvals**.

    ![Related Lists for Policy Approvals](./media/image32.png)

24. There are two records waiting for approvals. Double-click next to **Requested** (at the end of the word) and select **Approved** for each approver.

    ![Two Records](./media/image33.png)

25. Reload form. The Policy Record has moved to state **Published**.
    Also, a Knowledge Article has been published.
    
    ![Published state](./media/image34.png)

26. Scroll to **KB Article** and click the information
    ![Information Icon](./media/image35.png) icon at the end of the line.
    
    ![KB Article](./media/image36.png)

27. A Knowledge record window opens. Scroll to **View Article** under **Related links** in this record.

28. Click **View Article**.

29. See the KB-Article that has been created automatically with related requirements listed at the bottom of the article.

    ![Data Protection Policy](./media/image37.png)

You have just created a Policy, aligned with regulation requirements. You have completed a full Policy Life Cycle.

# Profile Type, Profile and Risks

## Goal

This lab explains how to create Profile Type and assign Risk Framework to assess compliance requirements for a Profile. A profile -- *An entity we need to check for compliance requirements ---* will have then associated policy and policy statements you just created. You add risks to the Profile Type and see what could be potential impact of noncompliance to a Profile.

## Profile Type, Profile & Risk Framework

1.  Return to the Policy Record by clicking on history icon. (as in Lab 2.0)

1.  Scroll to related lists and click **Profile Type** in the Policy record.

2.  Click **Edit** under **Profile Type**.

    ![Profile Type](./media/image38.png)

3.  Click **Organizations**, move it into right window, and click **Save.**

4.  You return to the Policy record. Scroll down and click on **Organizations** under **Profile Type** related list.

5.  **Profile Type** record opens in a new window. A **Profile**, **ACME Inc**., is assigned to this Profile Type.

    ![Profile](./media/image39.png)

6.  **Policies** & **Policy Statements** appear in the related list, created in earlier steps.

6.  Return to the Dashboard and check **Compliance Overview**. The **GDPR Compliance** gauge is created and in empty status.

    ![GDPR Compliance](./media/image40.png)
    
7.  Now, add **Risk Framework** to the **Profile Type** as shown below. Add **Corporate Risks** to Profile type and click **Save**. Corporate risks are related to the regulation requirements.

    ![Risk Framework](./media/image41.png)
    
30. The **Risk Framework** is now assigned to **Profile Type.** Reload the form.  **Risk Statements** are also automatically added to that **Profile Type**.

    ![Risk Framework on Profile Type](./media/image42.png)
    
8.  Click on **Risk Statements** to see assigned **Risk Statements**.

9.  You should have some **Risk Statements (6)**, including **Non-compliance with Law/ Regulations.** You revisit this **Risk Statement** later.

10. Return to **Profile** under Related lists. Click on Profile **ACME Inc**.

    ![Profile](./media/image43.png)

11. The Profile window contains **Organizations** in the **Profile
    Type** related list.

12. Click the **Controls** tab, next to **Profile Type**. There are 9 controls allocated to this **Profile** as requirements described in the Policy.

    ![Controls](./media/image44.png)    

13. Click **Risks** to see the assigned Risks.

14. Click **Non-compliance with Law/ Regulations** risk. Now you are in **Risk** Record.

15. Change the Risk Life Cycle status in the form from **none** to **Not Assessed**. Save the record.

    ![Not Assessed](./media/image45.png)
    
16. Review all the fields in this risk record. Scroll down and click on the **Scoring** tab. Check your inherent, residual and calculated scores. **Note** down Calculated scores! (ALE= Annual Loss Expectancy)

    ![Non-Compliance](./media/image46.png)

31. Without having any controls implemented to reduce this risk, the likelihood to occur this risk and in turn the impact is high. The objective we want to achieve is to reduce the risk. So, let's change the **Scoring** record for **Inherent and Residual impact & Likelihood** as following:

    ![Scoring](./media/image47.png)

17. **Save** the record. **Reload** the risk record form to see new values.

Add controls to associate GDPR requirements to the risk.

1.  Scroll down and go to related lists. Click on **Controls**. Click on
    **Add**.

1. A new window opens to choose controls to associate them with the risk.

19. Select All controls and click **Add Relationship**.

    ![Add Relationship](./media/image48.png)
    
20. There are 9 controls associated to that risk.

    ![Risk Controls](./media/image49.png)
    
21. After adding these controls, save the record. The risk score remains the same since you have not yet executed controls.

    ![Scoring](./media/image50.png)

# Attestations

## Goal

As you have prepared everything to test the compliance and risk states in previous labs, let start executing. This lab explains how to generate
attestations for Data Protection requirements described in the Policy for the ACME Inc. Depending on attestations responses, controls status changes from draft to compliant or noncompliant and has an effect on risk scoring (more non-compliant controls, higher the risk!).

1.  Return to your **Profile**.

    ![Profile](./media/image51.png)

2.  Click **ACME Inc.**

3.  Current state of all controls should be in **Draft**. Click **Generate DPIAs** (Data Protection Impact Assessments, requirement from §35 EU GDPR). Controls state now changes to **Attest**.

    ![Profile](./media/image52.png)    

4.  There are 9 **attestations** created. (Certainly, with ServiceNow GRC application, you can also create just one attestation by different category or different attestations by different categories for different stakeholders!. )

    ![Attestations](./media/image53.png)

5.  Search in filter navigator for **My Attestations** and click it.

    ![My Attestations](./media/image54.png)

6.  Expand the **Profile ACME Inc**. to see full record. You should have now 9 attestations in **Ready to Take** state.

7.  Take one **attestation** and submit it. If asked to attach evidence, attach any (small size) file from your laptop. You can also provide multiple attachments for the evidence.

    ![Evidence](./media/image55.png)

8.  Go back to the **Acme Inc.** **Profile**. Click **Controls**.

    ![Profile Controls](./media/image56.png)

9.  Depending on your response to that attestation, you see control status as **Compliant** or **Noncompliant.** 

10. Return to the Dashboard. (**Compliance Overview**). Refresh your browser.

    ![Compliance Overview](./media/image57.png)

11. See the status of **GDPR Compliance**.

12. Click on the **green part of pie** (or red for non-compliant) of the pie chart in **GDPR Compliance** gauge. There are additional citations related to that particular control in **Compliant**/**Non-compliant** status.

13. Return to the attestations and take remaining attestations.

    ![Remaining Attestions](./media/image58.png)
    ![Attestions](./media/image59.png)

14. Check **Controls** status time-to-time and dashboards as in previous steps (next example).

    ![Controls](./media/image60.png)
    
15. Check the **Compliance Overview** Dashboard. Your dashboard might look different than shown below. You may need to refresh your browser window.

    ![Compliance Overview](./media/image61.png)

After having 2-3 noncompliant controls, check the risk status as described in following steps:

1.  Go to **History** Icon
    (![History Icon](./media/image62.png)). Select **Profile ACME Inc**.

16. Select **Non-Compliance with Laws/Regulations** risk under the Risk tab in related list.

17. In the **Non-Compliance with Laws/Regulations** Risk window, select **Scoring**.

18. There is a new score for the risk. Because of some noncompliant controls, **Calculated Score** is now higher. You may have a different score than shown below.

    ![Calculated Score](./media/image63.png)
    
19. After finishing all attestations, go back to the dashboard to see the latest status of **GDPR Compliance**. Your dashboard might be different than shown below.
    
    ![GDPR Compliance](./media/image67.png)

20. Go back to your risk - Non-compliance with Laws/Regulations, while finding it to the history icon.

    ![Risk](./media/image68.png)

21. Check the final risk **scoring**.

22. Click the **Monitoring** tab to see control compliance metrics.

    ![Monitoring](./media/image69.png)

23. Scroll down and go to one of noncompliant control (if you have any) by clicking on the **Controls** tab in related list. Click the **Name** of a noncompliant control.

    ![Name controls](./media/image70.png)

24. Click the **Issues** tab in the related list. An issue has been automatically generated as result of this noncompliant control. Openthe issue record. The record is in **New** state in the Life Cycle (next example).

25. Under Details tab, the reason appears in the **Description** box. Now, an assignee can start working on resolving the issue (not part of this lab).
    
    ![Description Box](./media/image71.png)
    
You can also check out the **Task SLA** information under related lists on this form.

![Task SLA](./media/image72.png)

# Risk Dashboard

## Goal

This lab explains how to create and add new content to the Risk
Dashboard to get visibility on high impact risks instantly.

1. Search for **Risks** in filter navigator.

2. Click **All Risks.** Filter the Risks Records by **Profile: ACME Inc.** as shown below. All the risks related to **ACME Inc**. are listed (not in retired stage). **Non-compliance with Laws/Regulations** is also listed.

    ![Filtered List](./media/image75-new.png)
    
3. Make the following changes to see these risks by **Calculated Score** in the Risk Dashboard.

    ![Calculated Score](./media/image76-new.png)

4. Right-click on **Calculated Score** field, then select **Pie Chart.**

    ![Pie Chart](./media/image77-new.png)

5.  A new window opens. Enter the report name in **Report Title** (e.g., **ACME Risks**) field and click **Save**.

    ![Report](./media/image78-new.png)

6.  On the **Style** tab check the box for **Display Data labels.**

    ![Display Data Labels](./media/image80-new.png)

7.  Click **Save** at the top right of the report window. See the **ACME Risks** report.
    
    ![Click Save](./media/image82-new.png)

8.  Select **Add to Dashboard** by clicking on the **Sharing** button on the top gray banner.
    
    ![Sharing Button](./media/image84-new.png)

9.  Add to the report to your Homepage **(Risk Overview)** as shown below.

    ![Add to Dashboard](./media/image86-new.png)

10. You are automatically directed to **Risk Overview** homepage.

    ![Risk Overview Homepage](./media/image87-new.png)

# DPO Dashboard and GRC Portal

## Goal

This lab illustrates further elements -- DPO Dashboard, Portal, etc. - of overall GDPR Lab. The DPO dashboard gives you as a DPO (or controller
or processor) full visibility and transparency on current GDPR exposure.

1.  Search for **Dashboard** in filter navigator.

    ![Dashboard](./media/image82.png)
    
2.  Search for DPO in **Dashboard** drop-down menu and select **DPO Dashboard MP(v5).**

3.  Check out different **tabs** on this dashboard:

    ![Different tabs](./media/image83.png)

    **GRC Portal:** Illustration of a GRC portal example. Open a new bowser window with:
    Your Instance URL/grc_portal

    ![GRC Portal](./media/image84.png)
