Server-less Media Orchestration Stream using Amazon S3 and CloudFront
Description
This document serves as a demonstrational guide for building a server-less video streaming solution using Amazon S3 and CloudFront. The setup allows global video content distribution with minimal latency, leveraging Amazon's edge locations.

Key Steps
Store Video Content in Amazon S3:

Upload video files to an Amazon S3 bucket, configuring it for static website hosting to serve content publicly or with controlled access.
Set Up Amazon CloudFront:

Configure CloudFront with the S3 bucket as the origin. This enables global distribution, with edge locations providing low-latency content delivery.
Customize CloudFront settings, including cache behavior and TTL (time-to-live) for optimal performance.
Secure the Content:

Apply fine-tuned access control policies on the S3 bucket.
Enable SSL/TSL encryption for secure data transmission.
Embed CloudFront URL:

Integrate the CloudFront URL into a video player, allowing users to stream content seamlessly.
This setup allows the system to deliver smooth, secure, and scalable video streaming.

Services Used
Amazon S3: for video content storage and static website hosting.
Amazon CloudFront: for content delivery and caching at edge locations.
Benefits :
Scalability
Low Latency
Security
