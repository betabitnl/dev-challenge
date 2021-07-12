# Welcome to The Shop

This is a refactoring exercise in C#. Imagine that this is part of a larger enterprise system and you are given this code to review before it goes into production. 
Please treat this code as you would in a real situation so that this solution adheres to your standards.

The code is fairly straightforward. There's a `ShopService` that has the ability to display, order and sell items. The client code (`Program.cs`) orders and sells items and also displays those that it has been able to find and hasn't been able to find in the Shop.

When ordering an article, the Shop needs to find the article amongst the given suppliers (It can be any external service) where the product is in stock 
and the price is not higher than the maximum a client is willing to pay for the product. 

If naming and structure doesn't suit you, fell free to change them.

Introducing tests to the existing code is more than welcome.  
Once you're finished with coding, create a Pull Request with your changes. Should you have any questions or feedback for the assignment, feel free to contact us.
