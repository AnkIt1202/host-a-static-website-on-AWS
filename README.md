# Learn-how-to-host-a-static-website-on-AWS

- **STEP 1**: Create a Custom Domain Name using Amazon Route 53

- - Note: AWS may take up to 3 days to register a domain. But, it's usually done within 10 minutes

- **STEP 2**: Use an Amazon S3 Bucket to host a sample website

- - Upload the HTML code to the S3 Bucket
- - Make sure the S3 Bucket Name is the same as the Domain Name created in Step 1
- - Make sure that the S3 Bucket is enabled for Static Website Hosting
- - Edit the S3 Bucket Policy 

- **STEP 3**: Enable static website hosting and direct the domain to the S3 Bucket

- - Go to Amazon Route 53
- - Click on Hosted Zone under DNS Management
- - Click on the domain name created for this project 
- - Click on **Create Record** to point the S3 Bucket to our custom domain name
