# CLOUD SECURITY IMPLEMENTATION

**COMPANY**:  CODTECH IT SOLUTIONS

**NAME**:     GAYATHRI.N

**INTERN ID**: CT08NPC

**DOMAIN**: CLOUD COMPUTING

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTHOSH KUMAR

**DESCRIPTION**:

**TASK-4:** CLOUD SECURITY IMPLEMENTATION

**Project Overview**
**Objective:** Implement security measures on AWS using IAM policies, encrypted storage, and monitoring tools like AWS CloudTrail and AWS Config.

**Key Security Features:**
✅ S3 Encryption – Secured storage with AES-256/KMS
✅ IAM Policies – Restricted access with least privilege
✅ CloudTrail – Logs all security events & access
✅ AWS Config – Monitors misconfigurations and compliance

**2️⃣ Step-by-Step Implementation**
🔹 **Step 1:** Created an Encrypted S3 Bucket
Bucket Name: secure-data-bucket
Encryption: AES-256 (Amazon S3-Managed Keys)
Public Access: Blocked to prevent unauthorized access
🔹 **Step 2:** Created IAM Policy for Secure S3 Access
Policy Name: SecureS3Policy
Permissions Given:
✅ s3:ListBucket
✅ s3:GetObject
✅ s3:PutObject
**Attached To:** IAM user for controlled access
🔹 **Step 3:** Created an IAM User and Attached the Policy
User Name: secure-s3-user
Access Type: Programmatic Access (Access Key & Secret Key)
Attached Policy: SecureS3Policy
🔹**Step 4:** Enabled AWS CloudTrail for Security Monitoring
Trail Name: SecurityTrail
Applies to All Regions: ✅ Yes
Logs Stored In: S3 bucket
Purpose: Tracks all access & API activities
🔹 **Step 5:** Enabled AWS Config for Security Compliance
Monitors: S3 Bucket, IAM Policies, and Security Misconfigurations
Compliance Rules:
❌ Detects if S3 is public
❌ Detects non-encrypted resources
✅ Sends alerts on non-compliance

4️⃣ Conclusion
🔹 Security policies were successfully implemented on AWS
🔹 IAM policies ensure least-privilege access to S3
🔹 CloudTrail logs all activities for security auditing
🔹 AWS Config continuously checks for compliance

✅ AWS Cloud Security Implementation is successfully completed! 🎯

SCREENSHOTS & DEMO VEDIO:
