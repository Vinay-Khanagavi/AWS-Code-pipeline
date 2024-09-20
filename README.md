# Localhost to GitHub to AWS S3 Bucket using the AWS CodePipeline

## Amazon S3

<div>

**Create Bucket:**

- Navigate to Amazon S3
- Click on "create-bucket"
- Add a unique name and create the bucket

</div>

## Adding Objects in the Bucket

<div>

- Go to the created bucket
- Add object
  - Enable ACLs
  - Enable Bucket Versioning

</div>

## PIPELINE

<div>

- Go to Amazon Services and search for CodePipeline
- Create a pipeline
  - Choose "create new pipeline"
  - Add a unique name

### Add Source Stage

- Source provider: GitHub (Version 1)
- Connect with GitHub account
- Select the repository
- Select the branch

### Add Build Stage

- Can use AWS CodeBuild or Jenkins (skip for now)

### Add Deploy Stage

- Deploy provider: Amazon S3
- Add region
- Add the bucket which was created
- Leave the S3 object key blank
- Create the pipeline

</div>

## Bucket Hosting

<div>

![Bucket Hosting Image](https://github.com/Vinay-Khanagavi/AWS-Code-pipeline/assets/116386393/c0609279-ba9a-4b25-b226-6c94069f1444)

</div>
