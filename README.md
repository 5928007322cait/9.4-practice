# 9.4 practice
 html
 <!DOCTYPE html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Contact Form</title>
     <style>
         body {
             font-family: Arial, sans-serif;
             margin: 20px;
         }
         fieldset {
             border: 2px solid #ccc;
             padding: 10px;
             margin-bottom: 20px;
         }
         legend {
             font-weight: bold;
             padding: 0 10px;
         }
     </style>
 </head>
 <body>

 <h1>Contact Us</h1>

 <form action="#" method="post">

     <fieldset>
         <legend>Your Information</legend>
         <label for="name">Name:</label><br>
         <input type="text" id="name" name="name" required><br><br>

         <label for="email">Email:</label><br>
         <input type="email" id="email" name="email" required><br><br>

         <label for="phone">Phone:</label><br>
         <input type="tel" id="phone" name="phone"><br><br>
     </fieldset>

     <fieldset>
         <legend>Message Details</legend>
         <label for="subject">Subject:</label><br>
         <input type="text" id="subject" name="subject" required><br><br>

         <label for="message">Message:</label><br>
         <textarea id="message" name="message" rows="4" required></textarea><br><br>
     </fieldset>

     <input type="submit" value="Submit">

 </form>

 </body>
 </html>

