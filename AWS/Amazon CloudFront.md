
Amazon CloudFront is an AWS web service that distributes static and dynamic web content, like HTML, CSS, JS files, images and other resources to the users, through a worldwide network of data centers known as [[Edge Locations|edge locations]].

When a user requests for the content, the request is sent to the nearest edge location, to deliver the content with lowest latency, and best performance.

In case the content is not present in the edge location, CloudFront will get the content from an origin as defined by the developer, which could be an [[S3 (Simple Storage Service)|S3]] bucket, or an [[HTTP server]].

![[CloudFront.png]]

