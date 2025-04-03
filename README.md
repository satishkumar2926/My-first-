# My-first-
<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Expense Tracker</title> 
  <link rel="stylesheet" href="styles.css"> 
 </head> 
 <body> 
  <div class="container"> 
   <h1>Expense Tracker</h1> 
   <form id="expense-form"> 
    <input type="text" id="expense-name" placeholder="Expense Name" required> 
    <input type="number" id="expense-amount" placeholder="Amount" required> <button type="submit">Add Expense</button> 
   </form> 
   <ul id="expense-list"></ul> 
  </div> 
  <script src="script.js"></script> 
 </body>
</html>
