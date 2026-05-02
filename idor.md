#IDOR Real-World Example
Use: Account A (attacker) and Account B (victim). Try accessing victim data using attacker session.
Example 1: E-commerce Data Leak
Request: GET /api/orders?order_id=5502
Change to: order_id=5503
Result: Returns another customer’s order (Name, Address, Payment info).
Impact: Sensitive data exposure
