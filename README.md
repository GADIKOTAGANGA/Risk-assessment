## Exp_05: Risk-assessment

## Name: G.Ganga devi

## Reg No: 212224240042

## AUDITING CLOUD ACTIVITY USING AWS CLOUDTRAIL

## Objective 

To audit and monitor cloud activity in AWS using AWS CloudTrail by viewing and analyzing recorded AWS events and identifying important audit information such as user identity, event name, event time, AWS service, region, and operation status.

## Requirements

AWS Account

Web Browser

Internet Connection

Amazon S3 access

AWS CloudTrail

## PART A — ACCESS AWS CLOUDTRAIL

Step 1: Login to AWS

1. Open the AWS Management Console.

2. Sign in using your AWS account.

3. In the AWS search bar, type CloudTrail.

4. Select AWS CloudTrail.

<img width="1156" height="637" alt="Screenshot 2026-09-02 104430" src="https://github.com/user-attachments/assets/601146a4-c41f-4fe4-b3cc-f822602ec31f" />

## Step 2: Open Event History

1. In the CloudTrail navigation menu, select Event history.

2. CloudTrail displays recent AWS activity.

3. Review the available events.

The Event History page may display information such as:

Event time

Username

Event name

Event source

Resource type

Resource name

<img width="1106" height="602" alt="Screenshot 2026-09-02 104613" src="https://github.com/user-attachments/assets/97c8a115-9e47-4d3a-88d3-a4efe1024140" />

## PART B — ANALYZE A CLOUDTRAIL EVENT

## Step 3: Select an Event

From the Event History list, select an S3-related event.

Click the event to open its details.

Examine the event information and the event record/JSON.

For this experiment, a CreateBucket event can be used.

## Step 4: Analyze the CreateBucket Event

The CreateBucket event indicates that an Amazon S3 bucket creation operation occurred.

Record the following information:


Meaning of Important Fields

<img width="837" height="362" alt="image" src="https://github.com/user-attachments/assets/58ff3e1a-5a60-4eb2-a037-4abf555de6d9" />

<img width="1250" height="487" alt="Screenshot 2026-09-02 104807" src="https://github.com/user-attachments/assets/e4e8c864-12d1-4d8e-beae-75f47ed37098" />

## PART C — IDENTIFY ANOTHER CLOUDTRAIL EVENT

## Step 5: Select Another Event

Return to CloudTrail → Event history.

Select another event.

Open its details.

Record the important fields.

For example, an event such as:

AutomatedDefaultVpcCreation

may be present.

This event is associated with Amazon EC2.

## Step 6: Analyze the Second Event

Record:

<img width="517" height="417" alt="image" src="https://github.com/user-attachments/assets/2c87b0ae-bee2-4d05-9ee1-a875ae45cd7e" />

<img width="1156" height="612" alt="Screenshot 2026-09-02 104937" src="https://github.com/user-attachments/assets/00783ae8-d100-46c8-bf3d-6ca728b1ee6c" />

## PART D — COMPARE THE EVENTS

## Step 7: Prepare the Audit Comparison

Compare the two CloudTrail events.

<img width="862" height="415" alt="image" src="https://github.com/user-attachments/assets/81dad125-b7c0-48df-9c0f-5b3cce8d2d12" />

## PART E — SECURITY AUDIT ANALYSIS

## Step 8: Identify Who, What, When and Where

For each event, identify:

## WHO?

Who or which identity performed/generated the activity?

## WHAT?

What AWS operation was performed?

## WHEN?

At what date and time did the activity occur?

## WHERE?

In which AWS Region did the activity occur?

## RESULT?

Was the operation successful or did it generate an error?

## Step 9: Prepare the Final Audit Table

Students should prepare a final table similar to the following:

<img width="1040" height="326" alt="image" src="https://github.com/user-attachments/assets/b5aa5739-a8c7-48d9-be53-55e468805905" />

## PART F — SCREENSHOTS TO SUBMIT

Students should capture the following screenshots:

1. AWS CloudTrail Dashboard

2. CloudTrail Event History

3. CreateBucket Event Details

4. Second CloudTrail Event Details

5. Final Audit/Observation Table

## RESULT

The cloud activities in AWS were successfully audited using AWS CloudTrail Event History. Different AWS events were examined based on event time, user identity, event name, event source, AWS Region, read-only status, and error status. The experiment demonstrated how AWS CloudTrail provides an audit trail for monitoring, accountability, and investigation of cloud activities.


