# Localhost to GitHub to AWS S3 Bucket using the AWS CodePipeline

## Amazon S3 

<div>
  - Create a bucket:
    - Add a unique name --> create
</div>

## Adding Objects in the Bucket

<div>
  - Navigate to the created bucket and add objects:
    - Enable ACLs
    - Enable Bucket Versioning
</div>

## PIPELINE

<div>
  - Go to Amazon Services and search for CodePipeline
  - Create a pipeline:
    - Create new pipeline
    - Add a unique name

  ### Add Source Stage 
  - Source provider -> GitHub (Version 1)
  - Connect with your GitHub account
  - Select the repository and branch

  ### Add Build Stage
  - Can use AWS CodeBuild or Jenkins, but for now, skip this stage

  ### Add Deploy Stage
  - Deploy provider -> Amazon S3
  - Add region
  - Add the bucket which was created
  - Leave the S3 object key blank
  - Create pipeline
</div>

## Bucket Hosting 

![Bucket Hosting Image](https://github.com/Vinay-Khanagavi/AWS-Code-pipeline/assets/116386393/c0609279-ba9a-4b25-b226-6c94069f1444)
