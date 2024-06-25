# Localhost to GitHub to AWS S3 Bucket using the AWS CodePipeline 

|-Amazon S3 

then create-bucket
add unique name--> create

# Adding Objects in the bucket
|-go to the created bucket add object

# PIPELINE
go the Amazon Services search -> codePipeline

create a pipeline --> create new pipeline --> add unique name

*** Add Source stage *** 
--> source provider -> GitHub (Version 1) --> connect with GitHub account --> Select the repo ---> select the branch 

*** Add Build Stage ***
can AWS codeBuild or Jenkins but for now skip

*** Add Deploy Stage ***
Deploy provider -->Amazon S3
add region () -->add bucket which was created --> leave the S3 object key  ---> create pipeline

![image](https://github.com/Vinay-Khanagavi/AWS-Code-pipeline/assets/116386393/1246241f-6f9e-4123-a248-b3c0c270f9ac)
