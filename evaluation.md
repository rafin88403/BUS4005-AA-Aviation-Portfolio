
# Evaluation of AI Prompt Engineering Portfolio

## 1. Introduction

This section evaluates the proposed AI prompt engineering workflow developed for AA Aviation Sdn Bhd. The evaluation focuses on how effectively the ten AI prompts support the flight booking process, from the initial passenger request to final ticket delivery.

The proposed AI solution aims to improve administrative efficiency, information accuracy, consistency and customer service while maintaining appropriate human supervision.

## 2. Evaluation of the Ten AI Prompts

| Prompt | Function | Expected Contribution |
|---|---|---|
| P01 | Booking Request Intake | Organises initial passenger booking requests |
| P02 | Passenger Detail Extraction | Extracts relevant passenger information |
| P03 | Passenger Information Validation | Identifies missing or inconsistent information |
| P04 | Flight Availability Checking | Supports flight availability enquiries |
| P05 | Fare Quotation and Comparison | Organises flight prices and available options |
| P06 | Passenger Quotation and Approval | Prepares quotations and records passenger decisions |
| P07 | Flight Booking and Reservation Creation | Supports reservation documentation |
| P08 | Booking Verification and Quality Assurance | Checks booking information for inconsistencies |
| P09 | Flight Ticket Issuance | Supports the preparation and verification of ticket information |
| P10 | Ticket Delivery and Booking Closure | Organises ticket delivery and final booking records |

Each prompt addresses a specific stage of the booking workflow. Together, they provide a structured approach to supporting routine administrative activities.

## 3. Effectiveness of the Proposed AI Solution

The proposed AI solution offers several potential improvements to the flight booking process.

### 3.1 Improved Administrative Efficiency

AI can assist employees with repetitive activities such as extracting passenger information, organising booking requests and preparing quotations. This may reduce the time required for routine administrative work.

### 3.2 Improved Information Consistency

Using standardised prompts encourages employees to follow consistent procedures when processing passenger information and preparing booking documentation.

### 3.3 Better Information Processing

AI can help organise large amounts of booking information into structured formats. This makes it easier for employees to review passenger details, flight options and quotation information.

### 3.4 Improved Customer Service

Faster preparation of booking information and quotations may help employees respond to passenger enquiries more efficiently.

## 4. Limitations and Risks

Although AI provides potential benefits, several limitations must be considered.

### 4.1 Information Accuracy

AI-generated information may contain errors or incorrect assumptions. Passenger details, flight information and fare quotations must therefore be checked against reliable sources.

### 4.2 Real-Time Flight Information

AI cannot independently guarantee current flight availability, prices or reservation status without access to authorised airline or booking systems.

### 4.3 Data Privacy and Security

Passenger information is confidential and must be handled carefully. Employees should follow company data protection procedures and avoid entering sensitive passenger information into unauthorised AI platforms.

### 4.4 Dependence on AI

Employees should not rely entirely on AI-generated recommendations. Professional judgement and human verification remain essential throughout the booking process.

### 4.5 System Integration

The proposed prompts do not automatically guarantee integration with airline reservation platforms, payment systems or ticketing databases. Additional technical development would be required for full automation.

## 5. Human Oversight and Control

Human supervision is essential to ensure that the proposed AI-assisted workflow operates reliably.

The following activities should remain under authorised employee control:

- Checking passenger information and travel documents.
- Confirming flight availability and current fares.
- Obtaining passenger approval before proceeding.
- Verifying reservation details and booking references.
- Confirming payment through authorised systems.
- Approving final ticket issuance.
- Checking ticket details before delivery.

AI should function as an administrative support tool rather than an independent decision-maker.

## 6. Recommendations for Improvement

To improve the proposed AI solution, AA Aviation Sdn Bhd should consider the following recommendations:

1. **Regular Prompt Testing:** Test all ten prompts using different booking scenarios to identify errors and improve output quality.

2. **Employee Training:** Provide employees with training on effective prompt usage, AI limitations and responsible handling of passenger information.

3. **Data Protection:** Establish clear guidelines for handling confidential passenger information when using AI tools.

4. **System Integration:** Explore secure integration with authorised flight reservation and ticketing systems where technically and legally appropriate.

5. **Human Verification:** Introduce mandatory employee checks before important booking decisions and ticket issuance.

6. **Continuous Evaluation:** Review AI-generated outputs regularly and update prompts when business procedures change.
7. 
# 7. Testing Methodology

## 7.1 Testing Approach

A scenario-based testing approach was selected to evaluate the effectiveness, accuracy, consistency and reliability of the ten AI prompts developed for AA Aviation Sdn Bhd.

The testing process uses fictional flight booking scenarios to simulate realistic customer booking requests. Each prompt is tested using relevant input information, and its output is assessed against predefined acceptance criteria.

The purpose of testing is to identify errors, missing information, unsupported assumptions and areas requiring improvement before the prompts are considered suitable for operational use.

## 7.2 Testing Procedure

The following procedure is used:

1. Prepare a fictional flight booking scenario with passenger and travel information.
2. Enter the relevant information into the corresponding AI prompt.
3. Generate the AI response.
4. Compare the response against the expected output and acceptance criteria.
5. Identify missing information, inaccuracies or unsupported assumptions.
6. Record the test result as Pass or Fail.
7. Revise the prompt where necessary and conduct a retest.

## 7.3 Testing Criteria

Each prompt is assessed using the following criteria:

| Testing Criteria | Expected Outcome |
|---|---|
| Accuracy | Information is correctly extracted and processed. |
| Completeness | All required information is included. |
| Consistency | Outputs follow the requested structure and instructions. |
| Reliability | The prompt avoids unsupported assumptions. |
| Error handling | Missing or unclear information is flagged. |
| Human oversight | Important decisions are referred to authorised staff. |

## 7.4 Test Scenarios

The following scenarios are used to assess the ten prompts:

| Test ID | Testing Scenario | Expected Result |
|---|---|---|
| T01 | Customer submits a flight booking request. | Booking details are organised correctly. |
| T02 | Passenger provides personal and travel information. | Relevant passenger details are extracted. |
| T03 | Passenger submits incomplete information. | Missing information is identified. |
| T04 | Flight availability information is reviewed. | Availability is checked using verified information. |
| T05 | Airline fare and baggage conditions are reviewed. | Unverified fare and baggage details are flagged. |
| T06 | Customer receives a fare quotation. | A clear and accurate quotation is prepared. |
| T07 | Booking requires customer approval. | Approval status is clearly identified. |
| T08 | Booking information is prepared for ticket issuance. | Required booking information is organised. |
| T09 | Ticket information undergoes quality checking. | Errors and inconsistencies are identified. |
| T10 | Final ticket and itinerary are prepared for delivery. | Final booking information is checked before delivery. |

## 7.5 Testing Results and Prompt Improvements

Testing should document both successful outputs and identified weaknesses.

One important improvement involved fare and baggage information. An earlier version of the fare quotation prompt could infer a baggage allowance without verified airline information.

The prompt was revised to instruct the AI to identify unknown baggage information as "UNKNOWN – airline confirmation required" rather than making an unsupported assumption.

This improvement demonstrates how testing can identify weaknesses in AI-generated outputs and how prompt refinement can improve reliability.

## 7.6 Testing Limitations

The testing uses fictional booking scenarios and simulated AI outputs. It does not represent a live integration with airline reservation systems or Global Distribution Systems (GDS).

Actual flight availability, airline fares, baggage allowances, passenger identity documents and payment information must be verified through authorised sources.

Human supervision remains necessary for fare confirmation, customer approval, payment verification and final ticket issuance.

## 7.7 Testing Conclusion

The scenario-based testing approach provides a structured method for evaluating the ten AI prompts. It helps identify errors, improve prompt instructions and establish appropriate human checkpoints.

Although the prompts can support routine administrative activities, they should be treated as decision-support tools rather than replacements for trained aviation personnel.


## 8. Overall Evaluation

Overall, the proposed ten-prompt AI workflow demonstrates how generative AI can support administrative activities within the flight booking process at AA Aviation Sdn Bhd.

The prompts provide a structured approach to booking request intake, passenger information processing, flight selection, quotation preparation, reservation documentation, ticket issuance and booking closure.

However, the effectiveness of the solution depends on the accuracy of the information provided, the quality of the prompts, access to reliable booking systems and appropriate human supervision.

The proposed solution should therefore be considered an AI-assisted administrative framework rather than a fully automated flight booking system.

## 9. Conclusion

The evaluation indicates that AI prompt engineering has potential to improve efficiency, consistency and information management in AA Aviation Sdn Bhd's flight booking workflow.

By combining structured AI prompts with employee supervision, data protection measures and reliable booking systems, the company can explore a more organised and efficient approach to managing flight booking activities.
