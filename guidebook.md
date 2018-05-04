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

Getting Started - Log on to Your Training Instance 
====================================================

1. Navigate to the unique instance URL provided to you.  

1. Log on with the provided credentials.  

1. Review your homepage.  
    You can change your homepage to System Administration by selecting it from the dropdown list in the top-left of the page. \
    \
    ![Homepage](./media/image2.png)

1. Review your favorite applications by clicking the **star**
    ![Star](./media/image3.png) next to the application.

    ![Navigator](./media/image4.png)

1. Discover the GRC applications and its modules by typing the first few
    letters of **Policy and Compliance**, **Risk Management**, or **Audit
    Management**.\
    \
    ![Navigators](./media/image5.png)  
  
  
Check Your Homepage
===================

1. Click the **ServiceNow** logo.

    ![Logo](./media/image6.png)

1. In the homepage window (1), from the dropdown list, search for compliance.

    ![Complicance](./media/image7.png)

1. Select **Compliance Overview**.

1. Review the initial Compliance status.  
    You should see the **GDPR Compliance**
    report as empty for now. The related **gauges/reports** are updated
    as you progress with the lab.

# Authority Document GDPR

## Goal

This lab explores the GDPR authority document. It also explains the
different citations for regulatory requirements.

## GDPR Authority Document

1. In the Filter Navigator, enter **authority**, and then click **Authority Documents**.

1. Under **Authority Documents**, in the **Common Name** field, search for **\*EU** (3).

    ![EU](./media/image8.png)  

    **Note:** Refer to the example below. If your **Type** field for **EU GDPR** Authority Document is empty, you can add the relevant type by double-clicking on the empty field.
    
    ![List](./media/image10.png)

1. Click the **EU General Data Protection link (begins with AD00)**.  
    You might have different authority document number.

1. Review the overall **GDPR** information.

1. Scroll to **Related Lists** and click **Citations**.

1. In the **Reference** field, search for **Art. 35**.

1. Review the relevant article, information, and respective subsections.

    ![Article](./media/image11.png)

# Policy Creation

## Goal

This lab explains how to create an organizational policy and policy statements that matches requirements and describes the outlines for GDPR.

## Policy Creation

1. Navigate to the **Policy & Management** application.

1. Search for **Policies**, and then click **Policies** to list them.

1. At the top of the policies page, click **New**.

    ![Policies page](./media/Policy_creation.png)  

    On the top of the record, a full **Policy Life Cycle Stages** list appears.

1. Fill out the new policy record with the following information.  
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
    
    **Note:** For the purpose of this lab, you can provide any valid dates. For simplicity, we have skipped any additional policy reviewer step here.

1. To save the record, right-click the policy header bar, and then from the dropdown menu click **Save**.

    ![Right Click](./media/image16.png)
    
1. In the Filter Navigator (1), enter **Knowledge**, and then click the **Knowledge** application (2).

    ![Knowledge application](./media/image17.png)
    
1. In the search bar, search for **\*gdpr** (3), and then press enter to continue.

    The Lab Data Protection Policy appears.

1. Open the **Policy**.  
    The **Lab Data Protection Policy** (4) describes the different sections required for a Data Protection policy.   
    
1. Review the policy content.

    ![Lab Protection Policy](./media/image18.png)

1. Copy the content of the Lab Data Protection Policy.

1. To return to your policy, click the Your history icon ![History Icon](./media/image19.png) (1), and then click the **Policy** (2) you just created.  
    
    ![Policy Record](./media/image20.png)
      
    You should now be back in the policy record.

1. Paste the copied content into the **Policy Text** field.

1. To save the record, right-click the header bar and then click **Save** from the dropdown menu.

    ![Policy Record](./media/image21.png)
    
1. Assign relevant **Policy Statements** to the policy.
    
1. In the top-right of the page, click **Add Statements** to generate Policy Statements that are defined for the policy.
    
    ![Policy Statement](./media/image22.png)

    a. Scroll to Related Lists and click **Policy Statements**.

    You should see nine policy statements added to the policy.

    ![Policy Statements List](./media/image23.png)
    
    b. Click any Reference number; for example 1. 
       A Policy Statement window opens with underlying reference number. 
       
    ![Policy Statement](./media/image24.png)
    
    c. Under related lists, click the **Citations** tab and verify that at least one EU GDPR Regulation citation is aligned with that policy statement.  

1. Navigate back to your policy.

1. Move forward into Policy Life Cycle. 

1. Go to the next stage and click **Ready for Review**.

    ![Ready for Review](./media/image28.png)  

    The policy moves to the **Review** stage in the Life Cycle Flow. A reviewer can now review the policy. 

1. For this lab, go directly to the **Approval** step.

1. Click **Request Approval**.  
     The approval request goes to **Policy Approver** & **System Administrator**.  
     The policy form field now becomes read-only as shown below in the second example.\
    \
    ![Policy](./media/image29.png)
    
   ![Data Protection Policy](./media/image30.png)

   After requesting approval, policy life cycle state changes to **Awaiting approval** as shown below.

   ![Awaiting Approval](./media/image31.png)
    
1. Scroll to related lists and click **Policy approvals**.

    ![Related Lists for Policy Approvals](./media/image32.png)

    There are two records waiting for approval.  
    
1. Double-click next to **Requested** at the end of the word and then select **Approved** for each approver.

    ![Two Records](./media/image33.png)

1. Reload the form.  
    The Policy Record has moved to the **Published** state. Also, a Knowledge Article has been published.
    
    ![Published state](./media/image34.png)

1. Scroll to **KB article** and click the information
    ![Information Icon](./media/image35.png) icon at the end of the line.
    
    ![KB Article](./media/image36.png)

    A Knowledge record window opens.  
    
1. Under **Related Links**, scroll to **View Articles**.

1. Click **View Article**.

    The KB Article has automatically been created with related requirements listed at the bottom of the article.

    ![Data Protection Policy](./media/image37.png)

You have just created a policy aligned with regulation requirements. You have completed a full Policy Life Cycle.

# Profile Types, Profiles, and Risks

## Goal

This lab explains how to create a Profile Type and assign a Risk Framework to assess compliance requirements for a profile. A profile -- *An entity we need to check for compliance requirements ---* will then have the associated policy and policy statements you just created. You add risks to the Profile Type and see what could be the potential impact of noncompliance to a profile.

## Profile Type, Profile, and Risk Framework

1. Click the history icon to return to the Policy Record. (as in Lab 2.0)

1. Scroll to related lists and then, in the Policy record, click **Profile Types** (1).

1. Under **Profile Types**, click **Edit** (2).  

1. In the left-hand selection list, click **Organizations** (3), move it into the right-hand selection list, and then click **Save** (4).  
    ![Profile Type](./media/image38.png)

    You return to the policy record. 

1. Scroll down to the **Profile Types** related list and click **Organizations**.

    The **Profile Type** record opens in a new window. A profile, **ACME Inc**., is assigned to this Profile Type.  

    ![Profile](./media/image39.png)  

    The **Policies** and **Policy Statements** created in earlier steps appear in the related list.

1. Return to the Dashboard and check the **Compliance Overview**.   
    The **GDPR Compliance** gauge is created with an empty status.

    ![GDPR Compliance](./media/image40.png)
    
1. Add a **Risk Framework** to the **Profile Types** as shown below. 

    ![Risk Framework](./media/image41.png)
    
1. Add a **Corporate Risks** to the Profile Type and then click **Save**.   
    Corporate risks are related to the regulation requirements. The Risk Framework is now assigned to the Profile Type.
    
1. Reload the form.  
    The **Risk Statements** are also automatically added to that **Profile Type**.  
    
1. Click **Risk Statements** to see the assigned **Risk Statements**.   
     You should have some **Risk Statements (6)**, including **Non-compliance with Law/ Regulations**. We will revisit this **Risk Statement** later.
        ![Risk Framework on Profile Type](./media/image42.png)

1. Under related lists, return to **Profiles**, and then click the profile **ACME Inc**.

    ![Profile](./media/image43.png)

    The Profile window contains **Organizations** in the **Profile Types** related list.

1. Click the **Controls** tab next to **Profile Types**.   
    There are nine controls allocated to this **Profile** as requirements described in the policy.
    
    To see the assigned Risks, click **Risks**.

    ![Controls](./media/image44.png)    

1. Click the **Non-compliance with Law/ Regulations** risk.   
    You are now in the **Risk** record.

1. Change the **Risk Life Cycle** status in the form from **none** to **Not Assessed**, and then save the record.

    ![Not Assessed](./media/image45.png)
    
1. Review all the fields in this risk record.  
    a. Scroll down and click the **Scoring** tab.  
    b. Check your inherent, residual, and calculated scores. 
    c. Write down the Calculated scores! (ALE = Annual Loss Expectancy)

    ![Non-Compliance](./media/image46.png)  

    Without having any controls implemented to reduce this risk, the likelihood to incur this risk, and in turn the impact, is high. The objective we want to achieve is to reduce the risk.  
    
 1. Change the **Scoring** record for **Inherent and Residual impact & Likelihood** as follows:

    ![Scoring](./media/image47.png)

1. **Save** the record, and then **Reload** the risk record form to see the new values.

1. Add controls to associate GDPR requirements to the risk.

    a. Scroll down to related lists, click **Controls**, and then click **Add**.   

    A new window opens allowing you to select controls to associate with the risk.

    b. Select **All controls** and then click **Add Relationship**.  

    ![Add Relationship](./media/image48.png)  
    
    There are nine controls associated to that risk.  

    ![Risk Controls](./media/image49.png)
    
1. After adding these controls, save the record.  
    The risk score remains the same since you have not yet executed controls.

    ![Scoring](./media/image50.png)

# Attestations

## Goal

As you have prepared everything to test the compliance and risk states in previous labs, let start executing. This lab explains how to generate
attestations for Data Protection requirements described in the Policy for the ACME Inc. Depending on attestations responses, controls status changes from draft to compliant or noncompliant, and has an effect on risk scoring (the more non-compliant controls, the higher the risk!).

1. Return to your **Profile**.

    ![Profile](./media/image51.png)

1. Click **ACME Inc**.  
    The current state of all controls should be in **Draft**. 

1. Click **Generate DPIAs** (Data Protection Impact Assessments, requirement from §35 EU GDPR).  
    The Controls now shows changes to **Attest**.

    ![Profile](./media/image52.png)    

    There are nine **attestations** created. Certainly, with ServiceNow GRC application, you can also create just one attestation by different category or different attestations by different categories for different stakeholders!

    ![Attestations](./media/image53.png)

1. In the Filter Navigator, search for, and then click, **My Attestations**.

    ![My Attestations](./media/image54.png)

1. Expand the **Profile ACME Inc** profile to see the full record.   
    You should now have nine attestations in the **Ready to Take** state.

1. Take one **attestation** (1,2,and 3) and submit it. If asked to attach evidence, attach any (small size) file from your laptop.  
    You can also provide multiple attachments for the evidence.

    ![Evidence](./media/image55.png)

1. Go back to the **Acme Inc. Profile** (2) and then click **Controls** (3).

    ![Profile Controls](./media/image56.png)  

    Depending on your response to that attestation, you should see the control status as **Compliant** or **Noncompliant.** 

1. Return to the Dashboard (**Compliance Overview**) and then refresh your browser.

    ![Compliance Overview](./media/image57.png)

1. Note the **GDPR Compliance** status.

1. On the **GDPR Compliance** gauge, click the green part of pie chart (or red for non-compliant).  
    There are additional citations related to that particular control in **Compliant**/**Non-compliant** status.

1. Return to the attestations and take remaining attestations. <!--this is not clear to me - what does take remaining attestations mean-->

    ![Remaining Attestions](./media/image58.png)
    ![Attestions](./media/image59.png)

1. Check the **Controls** status time-to-time and dashboards as in the previous steps (next example).

    ![Controls](./media/image60.png)
    
1. Check the **Compliance Overview** Dashboard.  
    Your dashboard might look different than what is shown below. You may need to refresh your browser window.

    ![Compliance Overview](./media/image61.png)

1. After having 2-3 noncompliant controls, check the risk status as described in following steps:

    a.  Go to **History** Icon
        (![History Icon](./media/image62.png)).  
    
    b. Select **Profile ACME Inc**.

    c. Under the Risks tab in related lists, select the **Non-Compliance with Laws/Regulations** risk.

    d. In the **Non-Compliance with Laws/Regulations** risk window, select **Scoring**.  

    There is a new score for the risk. Because of some noncompliant controls, **Calculated Score** is now higher. You may have a different score than shown below.

    ![Calculated Score](./media/image63.png)
    
1. After finishing all attestations, go back to the Dashboard to see the latest status of **GDPR Compliance**.   
    Your dashboard might be different than what is shown below.
    
    ![GDPR Compliance](./media/image67.png)

1. Go back to your risk - Non-compliance with Laws/Regulations; find it using the Your history icon.

    ![Risk](./media/image68.png)

1. Check the final risk **scoring**.

1. Click the **Monitoring** tab to see the control compliance metrics.

    ![Monitoring](./media/image69.png)

1. Scroll down and locate one of the noncompliant controls (if you have any) by clicking the **Controls** tab in the related list. 

1. Click the **Name** of a noncompliant control.

    ![Name controls](./media/image70.png)

1. In the related list, click the **Issues** tab.  
    An issue is automatically generated as a result of this noncompliant control. 
    
1. Open the issue record.  
    The record is in the **New** state in the Life Cycle (next example).  

    Under the **Details** tab, the reason appears in the **Description** box. Now, an assignee can start working on resolving the issue (not part of this lab).  
    
    ![Description Box](./media/image71.png)
    
You can also check out the **Task SLA** information under related lists on this form.

  ![Task SLA](./media/image72.png)

# Risk Dashboard

## Goal

This lab explains how to create and add new content to the Risk
Dashboard to get visibility on high impact risks instantly.

1. In te Filter Navigator, search for **Risks**.

1. Click **All Risks**. 

1. Filter the Risks records by **Profile: ACME Inc.** as shown below.  
   All the risks related to **ACME Inc** are listed (not in retired stage). **Non-compliance with Laws/Regulations** is also listed.

    ![Filtered List](./media/image75-new.png)
    
1. Make the following changes to see these risks by **Calculated Score** in the Risk Dashboard.

    ![Calculated Score](./media/image76-new.png)

1. Right-click the **Calculated Score** field and then select **Pie Chart**.

    ![Pie Chart](./media/image77-new.png)  

   A new window opens. 

1. Enter the report name in the **Report Title** (e.g., **ACME Risks**) field and then click **Save**.

    ![Report](./media/image78-new.png)

1. On the **Style** tab, check the box **Display data labels**.

    ![Display Data Labels](./media/image80-new.png)

1. At the top-right of the report window, click **Save** and review the **ACME Risks** report.
    
    ![Click Save](./media/image82-new.png)

1. Select **Add to Dashboard** by clicking on the **Sharing** button on the header bar.
    
    ![Sharing Button](./media/image84-new.png)

1. Add to the report on your Homepage **(Risk Overview)** as shown below.

    ![Add to Dashboard](./media/image86-new.png)

    You are automatically directed to the **Risk Overview** homepage.

    ![Risk Overview Homepage](./media/image87-new.png)  

# DPO Dashboard and GRC Portal

## Goal

This lab illustrates further elements -- DPO Dashboard, Portal, etc. - of the overall GDPR Lab. The DPO dashboard gives you as a DPO (or controller or processor) full visibility and transparency on current GDPR exposure.

1. In the Filter Navigator, search for **Dashboard** (1).

    ![Dashboard](./media/image82.png)
    
1. In the **Dashboard** dropdown menu, search for **DPO** and then select **DPO Dashboard MP(v5)** (3).

1. Review the different **tabs** on this dashboard:

    ![Different tabs](./media/image83.png)

    **GRC Portal:** Illustration of a GRC portal example. 
    
1. Open a new bowser window with:  
    Your Instance URL/grc_portal

    ![GRC Portal](./media/image84.png)
