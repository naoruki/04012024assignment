Answer the following:
- Does SNS guarantee exactly once delivery to subscribers?
  yes
- What is the purpose of the Dead-letter Queue (DLQ)? This a feature available to SQS/SNS/EventBridge.
  it's a special queue that temporarily store messages that a software system cannot proccess due to errors.
- How would you enable a notification to your email when messages are added to the DLQ?
  use cloudwatch to create alarms for messages that are added to the DLQ
