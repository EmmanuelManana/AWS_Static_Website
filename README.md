# AWS_Static_Website
The cloud is perfect for hosting static websites that only include HTML, CSS, and JavaScript files that require no server-side processing. This project, deploys a static website to AWS.

First, we create a S3 bucket, configure the bucket for website hosting, and secure it using IAM policies. Next, we will upload the website files to your bucket and speed up content delivery using AWS’s content distribution network service, CloudFront. Lastly, we will access your website in a browser using the unique S3 endpoint



Screenshots showing steps for Deploying Static Website on AWS.

The following activities has been performed:

<ol>
  <li>All website files are added to the S3 bucket.</li>
  <li>The bucket configuration is set up to support static website hosting.</li>
  <li>The S3 bucket is configured to support static website hosting.</li>
  <li>The permission access to the bucket is configured to allow public access.</li>
  <li>The S3 bucket has an IAM bucket policy that makes the bucket contents publicly accessible.</li>
</ol>

Website Distribution:

The website is distributed via Cloudfront. CloudFront has been configured to retrieve and distribute website files.

<h3>Site Url:</h3>

<a href = "http://dnnuizrnh6rns.cloudfront.net/index.html" target = "_blank">Emmanuel's Travelog</a>

<h3>CloudFront Distribution:</h3>


<img src = "./website.png">