### Setup IAM policy and role for lambda
1. Create IAM policy with the help of `policy.json` file.
    - ***Don't forget to replace your source and target bucket name(line number 17 & 24)***

### Build lambda locally and upload it
1. Use linux machine to `npm install` the dependencies.
2. Zip all the files including `node_modules`. (***Do not zip the out directory***)
3. Upload the zipped file into lambda.

Follow the instructions here for complete instructions [here](https://docs.aws.amazon.com/lambda/latest/dg/with-s3-example.html).
