**Name:** MAHANTESH MA

**Company:** CODTECH IT SOLUTIONS

**ID:** CT4CC4124

**Domain:** CLOUD COMPUTING

**Duration:** JULY 5th to AUGUST 5th



## Overview of the Project

### Project: Creating a Static Website with Google Cloud storage

### Objective
The objective of this  project is to create a static website using the services provided by Google cloud storage

### Key Activities
- **Set Up a Google Cloud Project**: Go to the Google Cloud Console and create a new project if you don’t have one already.
- **Enable the Required APIs**: Go to the API & Services section of the Google Cloud Console and enable the Cloud Storage API.
- **Create a Cloud Storage Bucket**: In the Cloud Storage section of the Console, create a new bucket. The bucket name must be globally unique.
- **Upload Website Files**: Make sure you have all your HTML, CSS, JavaScript, and any other assets ready.
- **Configure Bucket for Website Hosting**: Make sure that objects in your bucket are publicly readable. You can do this by setting default object ACLs or individual file ACLs.
- **Test Your Website**: Access your website using the bucket’s public URL or custom domain URL if configured.
- **Set Up a Custom Domain**: If you want to use a custom domain, verify ownership with Google Cloud.
- **Monitor and Maintain**:  Keep an eye on your bucket’s usage and performance through Google Cloud Monitoring tools.

### Technologies Used
- **Google Cloud Storage**: Object Storage, Buckets, Access Control.
- **Google Cloud Console**: The main tool for managing Google Cloud resources, including Cloud Storage buckets, API configurations, and billing.
- **Cloud Storage API**: Allows programmatic interaction with Google Cloud Storage, enabling operations like file uploads, downloads, and metadata management.
- **Google Cloud Identity & Access Management**: Used to manage who has access to your Google Cloud resources and what actions they can perform.
- **Google Cloud DNS**:Manages DNS records if you use a custom domain for your website.
- **HTML**: The core markup language for creating the structure of your web pages.
- **CSS**: Used to style the visual appearance of your website, including layout, colors, fonts, and spacing.
- **JavaScript**:  Adds interactive elements to your website, such as forms, animations, and dynamic content.
- **Text Editors/IDEs**: Tools like Visual Studio Code, Sublime Text, or Atom for writing and editing your website’s code.
- **HTTP/HTTPS**:  HTTP for non-secure and HTTPS for secure communication between users and your website.
- **Google Cloud Monitoring**:  Tools to monitor usage, performance, and potential issues with your static website.

### Key Insights
- **Cost-Effectiveness**:  Google Cloud Storage operates on a pay-as-you-go pricing model, which means you only pay for the storage you use and the bandwidth consumed by your website. This can be very cost-effective for static websites that don’t require dynamic server-side processing.
- **Scalability**: Google Cloud Storage automatically scales to handle varying amounts of traffic. You don’t need to worry about managing servers or load balancing as your website traffic grows.
- **Global Availability**: Google Cloud Storage is designed to provide high availability and durability, with data stored across multiple locations to prevent data loss. This ensures that your website remains accessible even in the event of hardware failures.
- **Simplicity**: Hosting a static website with Google Cloud Storage is relatively simple compared to managing traditional web servers. The setup mainly involves configuring a storage bucket and uploading your files
- **Public Access Configuration**: To make your static website accessible to the public, you need to configure the bucket’s permissions to allow public access. This involves setting appropriate ACLs (Access Control Lists) or bucket policies.
- **Website Configuration**:  Google Cloud Storage allows you to configure a bucket for website hosting, specifying default pages (like index.html for the main page) and error pages (like 404.html for errors).
- **HTTPS Support**: For secure connections, especially if using a custom domain, you may need to set up HTTPS. This can be achieved using Google Cloud Load Balancing and SSL certificates, either through Google’s managed certificates or your own.
- **Content Delivery Network**:  Integrating Google Cloud CDN can further enhance the performance of your static website by caching content closer to users, reducing latency and improving load times.
- **Versioning and Updates**: Google Cloud Storage supports versioning of objects, allowing you to keep track of different versions of your files. This is useful for rolling back changes or recovering previous versions.
- **Backup and Redundancy**: Google Cloud Storage provides high durability and redundancy for your data, but it's still good practice to maintain backups of your important files and configurations.
- **Integration with Other Google Cloud Services**:  You can integrate your static website with other Google Cloud services, such as Cloud Functions for serverless operations or Firebase for additional features and analytics.















