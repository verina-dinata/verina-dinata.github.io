# Hello world!
Find my [Github profile](https://github.com/verina-dinata)

# Projects:
## Polyglot - [polyglot.vdin.xyz](https://polyglot.vdin.xyz/)  
![image](https://github.com/verina-dinata/verina-dinata.github.io/assets/82457559/d95d769f-73a6-466c-b98d-4dfb4b05d9c4)


### Summary
This project helps users learn Chinese quickly by focusing on the top 1000 most frequent words and sentence usage examples. Each entry comes complete with pronunciation (including tones) and English translation.

### Approach
Learn efficiently, speak accurately. By prioritizing frequently used words, users can maximize learning impact. Since tones are crucial in Mandarin, the app utilizes AWS Polly to generate audio for both words and sentences, ensuring proper pronunciation from the start.

### Technology
#### Backend
* Framework: Python with FastAPI for REST API
* Deployment: AWS Lambda for cost optimization and dynamic scaling
#### Frontend
* Framework: React App
* Deployment: AWS S3 + AWS Cloudfront for cost optimization and user experience
#### Sound generation
* Generated using AWS Polly
* Stored in AWS S3 and distributed using AWS Cloudfront
  
## Airbnb Replica - [air.vdin.xyz](https://air.vdin.xyz/)
![image](https://github.com/verina-dinata/verina-dinata.github.io/assets/82457559/5210b4f9-6b88-4ca7-a679-8420f4d9347d)


### Summary
This project attempts to recreate some functionalities of the Airbnb website.  

Scope of this project:
* Listing of holiday houses
* Complete booking flow of holiday houses
  
### Technology
#### Backend
* Framework: Ruby on Rails
* Deployment: Heroku for simplicity
#### Frontend
* Framework: Bootstrap
* Deployment: Cloudinary for image upload
* Map:  using MapBox API to display geo map inside the app


## U-Review - [rails-uni-review.herokuapp.com](https://rails-uni-review.herokuapp.com/)
![image](https://github.com/verina-dinata/verina-dinata.github.io/assets/82457559/072eb9fa-c2e9-4c7c-9134-355a1937f746)


### Summary
Empowering students with real-life reviews: This project helps future students make informed decisions by providing them with trusted reviews of universities from graduates in Singapore, Malaysia, and Australia.

Scope of this project:
* University listings, search and details
* University review capabilities by alumnae through email verification
* Forum discussion to connect alumnae and prospective student
* Favorite list for users to keep track of their university preferences
* User management: sign up, login, logout
  
### Technology
#### Backend
* Framework: Ruby on Rails
* Deployment: Heroku for simplicity
#### Frontend
* Framework: Bootstrap
* Deployment: Cloudinary for image upload
* Map: Using MapBox API to display geo map inside the app
#### Sendgrid
* Sendgrid was used to send emails related to user management and user verification
