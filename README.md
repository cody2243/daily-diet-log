# daily-diet-log

This repository stores a daily diet log used as context for AI diet-coaching conversations.

Assumption: the user is a healthy adult with normal kidney and metabolic function. Guidance follows general healthy-adult dietary recommendations. No personalized medical data is stored here.

## Structure

guidelines.md holds the general healthy-adult dietary guidelines used as the coaching baseline. The logs folder holds one file per day, named YYYY-MM-DD.md, containing that day's meals and any notes from the coaching conversation.

## Workflow

During a conversation, the user describes or uploads a photo of a meal. The assistant records the meal in today's log file. The assistant may reference guidelines.md and recent daily logs to give feedback, and commits updates back to this repository so the log stays current across conversations.
