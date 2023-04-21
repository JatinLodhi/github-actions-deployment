# github-actions-deployment

1) Create Repo
2) go to ACTIOn and set up your workflow
3) Copy and paste code in main.yml
4) create s3 bucket in AWS
5) Then Go to IAM to create User and give permission .
6) Copy Secret keys and paste in github repo's setting
7) Add secret key and Id --> secrets and variable
8) Copy name of bucket and paste in main.yml
9) Just enable static website in s3
10) When you hit this URL and got error :-403 Forbidden.
11) Its means you need to give bucket's policy permision in s3 .
12) Successfully All job completed...
