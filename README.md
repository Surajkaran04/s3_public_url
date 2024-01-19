# s3_public_url
how to resolve access denied url in amazon s3

{
    "Version": "2012-10-17",
    "Id": "Policy1563368389080",
    "Statement": [
        {
            "Sid": "Stmt1563368385984",
            "Effect": "Allow",
            "Principal": "*",
            "Action": [
                "s3:GetObject",
                "s3:GetObjectVersion"
            ],
            "Resource": [
                "arn:aws:s3:::onit-bucket/*",
                "arn:aws:s3:::onit-bucket/Skagen/*"
            ]
        }
    ]
}
