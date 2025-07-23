# Smart-Shopping-Cart-With-Dynamic-Pricing
Problem Statement
You need to implement a shopping cart system for an e-commerce platform that handles different types of products and applies various discount rules. The system should calculate the total price considering item-specific discounts, bulk discounts, and customer loyalty levels.

Requirements
Core Functionality:

Add/remove items to/from cart

Calculate total price with all applicable discounts

Display cart contents with itemized pricing

Product Types & Base Pricing:

Electronics: Base price + 10% tax

Books: Base price (tax-free)

Clothing: Base price + 5% tax

Discount Rules (apply in order):

Item-specific: Electronics get 15% off if quantity > 2

Bulk discount: 10% off total if cart value > $200

Loyalty discount: Bronze (5%), Silver (10%), Gold (15%) customers get additional discount on final amount

Input Format:

Items: [
  {id: 1, name: "Laptop", category: "Electronics", price: 1000, quantity: 1},
  {id: 2, name: "Book", category: "Books", price: 20, quantity: 3},
  {id: 3, name: "T-shirt", category: "Clothing", price: 25, quantity: 2}
]
Customer: {loyaltyLevel: "Silver"}
Expected Output:

Itemized breakdown showing original price, taxes, discounts applied

Final total amount
