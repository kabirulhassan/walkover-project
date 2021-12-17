# walkover-project
# TechStack
1. Ejs
2. json
3. Mongo(Database)
4. AWS/Heroku(hosting)

# Mockups



# Colour Palette

   rgb(201, 201, 241);
   #809ce2
   
# Routes
1. /-> Landing Page
2. /index -> Redirect Long Url to Short Url
3. /url -> Create short Url

# Schema
URL SCHEMA
   
    urlCode: String
    
    longUrl: String
    
    shortUrl: String
    
    date: { type:String, default: Date.now}
    
 SHORTURL SCHEMA
 
  full:  
       
    type: String
    
    required: true
  
  short: 
  
    type: String
    
    required: true
    
    default: shortId.generate
  
  clicks: 
  
    type: Number
    
    required: true
    
    default: 0
    
    
# API

Prefix: /api

Endpoints:

 get
 post

# UI

Prefix: /views/index 

Endpoints:

  set
  use
  post
  get

# MVP Feature


1. Convert long URL into short Url
2. User can sign up using Auth()
3. User can see the links that are converted
4. User can track the activity of the click by the number if Clicks



