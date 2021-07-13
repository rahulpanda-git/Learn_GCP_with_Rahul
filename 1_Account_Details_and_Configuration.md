# Account Details and Configuration

### Find Active GCP account ID and Project details
**Command:** gcloud config list
<br>**Output Format**
| Columns |
| ------- |
| Account Mail ID |
| Usage Reporting Enable/Disable |
| Active Project Name |

### List all GCP Account Mail ID's configured
**Command:** gcloud auth list
<br>**Output Format**
| Columns |
| ------- |
| Active Yes/No |
| Account Mail ID |

### Add and Authorize new GCP Mail ID
**Command:** gcloud auth login
| Requirement |
| ----------- |
| GCP Mail ID |
| Password |