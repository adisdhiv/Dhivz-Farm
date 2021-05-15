# MyProducts

This project is to sell my products

# Features
 1. Admin can list all products that is available for purchase
 2. User can view and purchase the product
 3. When a user attempts to purchase the product, it is locked for 15 minutes to enter the payment info
 4. While locked, no other user can purchase the product, it is unlocked after 15 minutes
 5. Products can be edited if they are not locked
 6. Add reviews for each product
 7. Add number of purchases for the product
 8. Add notifications for recent activity happened in the website. Ex: someone has purchased the product now
 9. Notifications about product facts
 10. Admin can update the quantity in stock everyday
 11. Products should become out of stock if the stock is empty
 12. Add to cart functionality available
 13. Dates of people bought and add reminders for next purchase
 14. Subscription
 15. Product Page
     1. Prebook product in growing stage
     2. Plant growing product indicator and activity logs, ETA for yield
     3. Add recipes with product - later
     4. Nutritional facts about product
 16. Option to choose to buy quantity or kg - Prorates
 
 # Architecture
 * Client - NextJS
 * Common library
 * Independent services - node, mongo
    * Expiration - Redis
    * Any - Postgres
 * Event bus - NATS
 
