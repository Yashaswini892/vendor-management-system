# Vendor-management-system

Developed a Vendor Management System using Django and Django REST Framework. This system will handle vendor profiles, track purchase orders, and calculate vendor performance metrics.

## Prerequisites

- Python (version 3.x recommended)
- Django
- Django REST Framework

## Installation

1. Clone the repository
   ```
   git clone https://github.com/Yashaswini892/vendor-management-system.git
   ```
   ```
   cd vendor-management-system
   ```
2. Install dependencies:
   - pip install django
   - pip install djangorestframework
  
3. Database setup:
   ```
   python manage.py makemigrations
   ```
   ```
   python manage.py migrate
   ```
## Running the server

1. Start the server:
   ```
   python manage.py runserver
   ```
Access the application at localhost:8000

## Core features

1.Vendor Profile Management:
  - Create, retrieve, update, and delete vendor profiles.
  - Track vendor information including name, contact details, address, and a unique vendor code.
    
2.Purchase Order Tracking:
  - Create, retrieve, update, and delete purchase orders.
  - Track purchase order details such as PO number, vendor reference, order date, items, quantity, and status.
    
3.Vendor Performance Evaluation:
  - Calculate vendor performance metrics, including on-time delivery rate, quality rating average, average response time, and fulfillment rate.

## Access Django Admin:
 Open the Django admin at http://127.0.0.1:8000/admin/ and log in using the superuser credentials.The superuser already created with username:yashaswini, password: yashaswini This is to access the database as a admin user.

## API endpoints

### Vendor Profile Management
- POST /api/vendors/: Create a new vendor.
- GET /api/vendors/: List all vendors.
- GET /api/vendors/{vendor_id}/: Retrieve a specific vendor's details.
- PUT /api/vendors/{vendor_id}/: Update a vendor's details.
- DELETE /api/vendors/{vendor_id}/: Delete a vendor.
- UPDATE /api/vendors/{vendor_id}/: Update a vendor.

### Purchase Order Tracking

- POST /api/purchase_orders/: Create a new order.
- GET /api/purchase_orders/: List all orders.
- GET /api/purchase_orders/{vendor_id}/: Retrieve a specific order's details.
- PUT /api/purchase_orders/{vendor_id}/: Update a order's details.
- DELETE /api/purchase_orders/{vendor_id}/: Delete a order.
- UPDATE /api/purchase_orders/{vendor_id}/: Update a order.

## Screenshots:

- Vendor list
  ![Screenshot 2024-05-08 005535](https://github.com/Satyaswarup11/temp_vendors/assets/85070271/085f7ad8-5220-427a-9733-6214dd126033)
- Admin panel for vendor details
  ![Screenshot 2024-05-08 005349](https://github.com/Satyaswarup11/temp_vendors/assets/85070271/1948b6ac-1826-4669-a596-1b68074ab621)
