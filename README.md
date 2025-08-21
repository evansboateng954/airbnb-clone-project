# airbnb-clone-project
Simulation of the airbnb backend

This is a simulation of the airbnb which is a booking system, the goal is to build the backend 
This enhaces API development and security,

This application is scalable 

## Team Roles ##

### Front end developer 
- Builds the **user interfaces** 
- Implements features like search, services and watchlist.
- Works with backend APIs to display dynamic content.
- Ensures the system is responsive for both web and mobile.

### UI/UX designer 
- develops a persona.
- build a prototype or wireframe.
- conducts reseach on user interactions.
- Designs the user interace.

### Backend developer 
- Ensures API performance.
- Ensures efficiency.
- Queries the database for data used by front end.

### Project Manager 
- Oversees the development of the system.
- Assighs tasks to team members.
- Updates team members on changes. 
- Ensures the product is delivered on time and within budget.

### Database Administrator 
- builds the database schema .
- Ensures the security of the database.

 ## Technology Stack
 - **Django**
   - promoting clean and pragmatic design.
   - Fascilitating scalability and security.
   - Encourages rapid design.
    
 - **MySQL**
   - Data management.
   - Scalability and performance.
   - Reliability and security.
     
 - **GraphQL**
   - Precise data fetching.
   - Real time capabilities.
     
## Database Design

  - **Users**
     - username
     - contact
     - gender
    
  - **Properties**
     - type
     - location
     - description
   
  - **Bookings**
    - date
    - id
    - type
      
  - **Reviews**
    - type
    - date
    - description
    
  - **Payment**
    - type
    - id
    - date


   Users can book multiple properties.
   A property can have multiple reviews.

   ## Feature Breakdown
   - **user management**
     Manages users and keep track of their interests in order to give them a better experience such as recommending restaurant that serves their favorite dishes or a property that alighs
     with thier choices.
   
   - **property management**
    Manages properties in order to match it to a certain user and also determine wheather a property is booked or not.

   - **booking system**
     Provides an interface for users to place an order for a car or rent a property.Users can also add a property to thier
     watchlist and rent them in future.

   - **Payment System**
      Users make payments to thier bookings in order to fill thier slot, the booking is validated by generating a reciept of payment by the system . Users can also view the pricing of properties before booking.
   
  
