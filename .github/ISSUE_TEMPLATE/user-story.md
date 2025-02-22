---
name: User Story
about: backlog of user stories
title: ''
labels: ''
assignees: ''

---

**As a** [customer calling the support center,]  
 **I need** [to be greeted by an automated call prompting system with clear, concise options,]  
 **So that** [I can quickly navigate to the appropriate department without waiting on hold for a live operator.]  
   
 ### Details and Assumptions
 * [The call prompting feature is designed to enhance the customer experience by providing an intuitive Interactive Voice Response (IVR) system. When a customer dials the support hotline, they should receive an automated message outlining available options (e.g., Billing, Technical Support, General Inquiries). This allows customers to select the service they need quickly, reduces wait times, and increases overall efficiency for both the customer and the support team.]
   
 ### Acceptance Criteria  
   
 ```gherkin
  Given [a customer calls the support hotline and the IVR system is active]
    When [the call is connected]
    Then [the customer hears a clear, friendly greeting and a list of options: "For Billing, press 1; For Technical Support, press 2; For General Inquiries, press 3"]
 ```
