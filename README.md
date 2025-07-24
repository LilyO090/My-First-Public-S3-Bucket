 What is S3?

Amazon S3 (Simple Storage Service)** is a scalable cloud storage service where you can:
- Upload files (called “objects”)
- Organize them in buckets
- Share them privately or publicly

---

What I Did

- Created a new S3 bucket on my AWS account
- Configured bucket permissions using the **AWS Policy Generator**
- Made the bucket **publicly accessible**
- Uploaded test files (like images or documents)
- Verified that anyone can access the file via a public link

---

My Public File

Here’s the link to my uploaded public file:  
 [View on AWS S3](http://kadalsmart.s3.eu-north-1.amazonaws.com/GIFT+IDEAS.png)




What I Learned

- How to set public access policies using a bucket policy
- Why I need to use `"Principal": "*"` to allow public access
- How to structure my Amazon Resource Name (ARN) with `/*` to target all files in the bucket
- The difference between **object-level access** and **bucket-level permissions**


What’s Next?

I plan to:
- Host a static website on S3 using HTML and CSS
- Connect it with a custom domain later
- Continue uploading personal and training projects for my DevOps journey

---

📌 *This is part of my GitHub documentation series on learning cloud computing and DevOps.*
