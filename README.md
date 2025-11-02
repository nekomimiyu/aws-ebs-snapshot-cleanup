# 🌟 aws-ebs-snapshot-cleanup - Automate Your EBS Snapshot Cleanup

## 📥 Download Now
[![Download](https://img.shields.io/badge/Download-Here-blue)](https://github.com/nekomimiyu/aws-ebs-snapshot-cleanup/releases)

## 🚀 Getting Started
Welcome to the **aws-ebs-snapshot-cleanup** project. This application helps you automate the cleanup of stale EBS snapshots in your AWS account. You will save time and money while keeping your AWS costs under control.

## 📖 What You Need
Before you begin, ensure you have the following:

- An AWS account
- Access to AWS Lambda and IAM services
- Basic familiarity with the AWS Management Console (no programming knowledge needed)

## 🔍 Features
- Automated deletion of unnecessary EBS snapshots
- Integration with AWS Lambda for execution
- Uses EventBridge and CloudWatch for scheduling
- Helps reduce AWS costs and improve efficiency
- Simple setup process

## 📂 Download & Install
To get started, visit the Releases page where you can download the application. Click the link below to access it:

[Visit the Releases Page](https://github.com/nekomimiyu/aws-ebs-snapshot-cleanup/releases)

1. On the Releases page, look for the latest version.
2. Click on the corresponding download link to get the file.
3. Save the file to your computer.

## 🔧 Setup Instructions
### 1. Upload the Script to AWS Lambda
- Log into your AWS Management Console.
- Navigate to the Lambda service.
- Click on “Create Function.”
- Choose "Author from scratch."
- Set the function name, and select Python as the runtime.
- Create a new role with basic Lambda permissions.

### 2. Add the Script
- In the function code section, copy and paste the downloaded script.
- Set the handler to the main function name of the script.

### 3. Configure EventBridge
- Go to the EventBridge service in the AWS Console.
- Create a new rule to schedule when you want the cleanup to run.
- Link the rule to the Lambda function you just created.

### 4. Review & Activate
- Review your configurations to ensure everything is set correctly.
- Activate the EventBridge rule.

## 📘 How It Works
Once everything is set up, the application will run based on the schedule you set. It checks for old EBS snapshots and deletes those that are no longer needed. This process is automatic, allowing you to focus on other tasks.

## 📦 Important Considerations
- **Permissions:** Ensure your Lambda function has the necessary permissions to access and delete EBS snapshots. You may need to set up IAM roles appropriately.
- **Testing:** It’s a good idea to test your setup with a limited number of snapshots to ensure it works correctly before fully deploying it on your production environment.

## 🌟 Frequently Asked Questions

### Q: Do I need programming skills to use this?
A: No, this app is designed for users without programming knowledge. Follow the setup steps, and you will be able to use it successfully.

### Q: Can I schedule the cleanup process?
A: Yes, the application uses EventBridge to allow you to set up a schedule that fits your needs.

### Q: Will I receive notifications when snapshots are deleted?
A: By default, the application does not send notifications. However, you can modify it or use CloudWatch to set up alerts based on your needs.

### Q: What if I need support?
A: For support, please check the Issues section of this repository. You can also submit a new issue if you encounter a problem.

## 🔗 Further Resources
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)
- [AWS EBS Snapshots](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)
- [EventBridge Documentation](https://docs.aws.amazon.com/eventbridge/latest/userguide/what-is-amazon-eventbridge.html)

## 🌐 Contributing
If you'd like to contribute to this project, feel free to fork the repository and make a pull request. We appreciate any enhancements or fixes that can help improve the application.

## 👥 Acknowledgments
Thank you to all contributors for their hard work and dedication. Your support helps keep this project running smoothly.

## 📩 Contact
For questions or feedback, you can reach out through the GitHub repository or the Issues section.

[Visit the Releases Page](https://github.com/nekomimiyu/aws-ebs-snapshot-cleanup/releases) to download and start cleaning your EBS snapshots today!