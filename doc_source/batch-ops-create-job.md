# Creating a Batch Operations Job<a name="batch-ops-create-job"></a>

This section describes how to create a Amazon S3 batch operations job\. For information about performing batch operations using the AWS CLI, AWS SDKs, and the Amazon S3 REST APIs, see [Performing Batch Operations](https://docs.aws.amazon.com/AmazonS3/latest/dev/batch-ops.html) in the *Amazon Simple Storage Service Developer Guide*\.

**To create a batch job**

1. Sign in to the AWS Management Console and open the Amazon S3 console at [https://console\.aws\.amazon\.com/s3/](https://console.aws.amazon.com/s3/)\.

1. Choose **Batch Operations** on the navigation pane of the Amazon S3 console\.

1. Choose **Create job**\.  
![\[Console screen shot of batch operations view showing Create job button.\]](http://docs.aws.amazon.com/AmazonS3/latest/user-guide/images/batch-ops-front-page.png)

1. Choose the **Region** where you want to create your job\.

1. Under **Manifest format** choose the type of manifest object to use\.
   + If you choose **S3 Inventory report**, enter the path to the manifest\.json object that Amazon S3 generated as part of the inventory report, and optionally the version ID for the manifest object if you want to use a version other than the most recent\.
   + If you choose **CSV**, enter the path to a CSV\-formatted manifest object\. The manifest object must follow the format described in the console\. You can optionally include the version ID for the manifest object if you want to use a version other than the most recent\.

1. Under **Operation** choose the operation that you want to perform on all objects listed in the manifest\. Fill out the information for the operation you chose and then choose **Next**\.

1. Fill out the information for **Configure additional options** and then choose **Next**\.

1. For **Review**, verify the settings\. If you need to make changes, choose **Previous**\. Otherwise, choose **Create Job**\.

## More Info<a name="batch-ops-create-job-moreinfo"></a>
+ [The Basics: Amazon S3 Batch Operations Jobs](https://docs.aws.amazon.com/AmazonS3/latest/dev/batch-ops-basics.html) in the *Amazon Simple Storage Service Developer Guide*
+ [Creating a Batch Operations Job](https://docs.aws.amazon.com/AmazonS3/latest/dev/batch-ops-create-job.html) in the *Amazon Simple Storage Service Developer Guide*
+ [Operations](https://docs.aws.amazon.com/AmazonS3/latest/dev/batch-ops-operations.html) in the *Amazon Simple Storage Service Developer Guide*