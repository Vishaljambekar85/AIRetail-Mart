PROJECT: AIRETAIL MART - SMART BILLING & POS SYSTEM

LIVE DEMO WEBSITE:
https://ai-retail-mart-v.netlify.app/

------------------------------------------------------------------------
1. PROJECT OVERVIEW
------------------------------------------------------------------------
AIRetail Mart is a modern Billing and Point of Sale (POS) web application 
built for retail shops, supermarkets, and grocery stores. 

It automates retail checkout billing, real-time inventory management, 
GST tax calculations, printable receipt generation, and includes an 
in-built AI POS assistant.

------------------------------------------------------------------------
2. TECH STACK
------------------------------------------------------------------------
- Backend: Python 3 with Flask
- Database: MySQL (via XAMPP)
- Frontend: HTML5, CSS3, JavaScript (ES6)
- UI Framework: Bootstrap 5.3 (Emerald Mint Theme)
- Visual Analytics: Chart.js
- Database Connector: mysql-connector-python

------------------------------------------------------------------------
3. KEY FEATURES
------------------------------------------------------------------------
- Smart Billing & POS:
  * Barcode scanner input with instant cart addition
  * Real-time calculation: Subtotal, Discount %, GST (CGST/SGST), Total
  * Cash payment change calculator, Card & UPI payment support
  * Automatic inventory stock deduction on checkout

- Product & Stock Management:
  * Add, edit, delete, and restock products
  * Low-stock indicator and automated alerts
  * Search by barcode or product name

- Sales Dashboard & Analytics:
  * Today's total sales, invoice count, and product statistics
  * 7-Day sales trend graph using Chart.js
  * Low-stock warning table with 1-click restock

- Billing History & Receipts:
  * Search previous bills by invoice ID, date range, or payment type
  * Clean printable GST tax invoice receipts (Thermal / A4)

- AI POS Assistant:
  * Interactive floating chatbot answering sales queries, stock levels, 
    product prices, and recent bills in natural language

------------------------------------------------------------------------
4. HOW TO RUN LOCALLY (PYTHON + XAMPP)
------------------------------------------------------------------------
Step 1: Start MySQL in XAMPP Control Panel.
Step 2: Open terminal in project folder:
        cd C:\Users\govin\.gemini\antigravity\scratch\smart_pos
Step 3: Install dependencies:
        pip install -r requirements.txt
Step 4: Run Flask server:
        python app.py
Step 5: Open browser at:
        http://127.0.0.1:5000

========================================================================
