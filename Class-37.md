#  S3 Storage

## Introduction to Amazon S3

 1. **What is Amazon S3?**

    Amazon S3 (Simple Storage Service) is a scalable object storage service provided by Amazon Web Services (AWS). 
    It is designed to store and retrieve any amount of data from anywhere on the web. S3 is widely used for data backup,
    archiving, content distribution, and application data storage.

 2. **List at least three features that it offers to its users.**
    - Scalability: S3 can handle virtually unlimited amounts of data and traffic, making it suitable for a wide range 
      of use cases.
    - Durability and Reliability: S3 ensures high durability by storing data redundantly across multiple facilities.
      It is designed to provide 99.999999999% (11 nines) durability.
    - Security: S3 offers access control features, allowing users to define access policies and permissions for their 
      data. It also supports data encryption at rest and in transit.
    
 3. **What is an object key?**
    An object key is a unique identifier assigned to each object (file) stored in an S3 bucket. It is used to organize 
    and retrieve objects within a bucket. The key can include slashes ("/") to form a hierarchy, simulating a folder 
    structure. 

## S3 with Amplify

 1. Which dependencies are needed to install Amplify AWS S3 to your android application?

    ```implementation 'com.amplifyframework:aws-storage-s3:1.0.0'```

    ```implementation 'com.amplifyframework:core:1.0.0' ```

 2. What is needed in order to upload data to your bucket?
    - Initialize Amplify in your application.
    - Configure the AWS S3 category with your S3 bucket details.
    - Use the Amplify Storage category to upload data to your bucket.
    
 3. What method(s) initialize(s) the Amplify Auth and Storage categories?

    By using the `Amplify.addPlugin()` method. 

