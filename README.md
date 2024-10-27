# Mail-order-Pharmacy

## Overview
Mail Order Pharmacy is a comprehensive web application that allows users to efficiently order medicines while enabling delivery personnel and administrators to manage their respective tasks seamlessly.

## User Scenarios

### As a User
1. **Searching for Medicines:**
   - Users can log in and search for medicines. A popup prompts for location to filter available options.
   
2. **Placing an Order:**
   - After selecting a medicine, users provide their address, email, and phone number.
   - Upon placing the order, a confirmation message appears, and users receive a confirmation email.

3. **Login Requirement:**
   - Users must log in to place an order, enhancing security and tracking.

### As a Delivery Boy
1. **Managing Orders:**
   - Delivery boys log in to view their assigned orders.
   - They can accept orders and confirm delivery via an intuitive interface.

2. **Order Tracking:**
   - Accepted orders are tracked, allowing delivery boys to update the status after delivery.

### As an Admin
1. **Drug Management:**
   - Admins can add, update, or delete drugs from the inventory.
   
2. **User and Delivery Management:**
   - Admins manage delivery boys and oversee order history.

## Technology Stack
- **Frontend:** React
- **Backend:** Node.js with Express
- **Database:** MongoDB
- **Email Notifications:** Nodemailer

## Installation Steps
1. Clone the repository:
   bash
   git clone https://github.com/VineethaPamujula/Mail-order-Pharmacy.git
