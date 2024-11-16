# Inventory Management System App

## Overview
The Inventory Management System App is a robust solution built using PowerApps to streamline inventory tracking and management. This app allows users to manage stock levels, update item details, and track inventory movements efficiently. It also includes functionality for uploading item images and associated documentation, such as invoices, using Power Automate for enhanced visibility. An admin login page provides secure access for administrators to monitor and manage inventory data and provide feedback to users.

---

## Features
- **Dynamic Inventory Tracking**:
  - View and manage stock levels in real time.
  - Update item details such as name, category, quantity, and location.
- **Document and Media Uploads**:
  - Users can upload item images and relevant documentation (e.g., invoices) to SharePoint for better traceability.
- **Admin Panel**:
  - Secure admin login page with credential validation.
  - Admins can review inventory updates, approve changes, and provide feedback to users.
- **Feedback Mechanism**:
  - Admins can give feedback on inventory adjustments, which users can view within the app.
- **Automated Email Notifications**:
  - Notify relevant personnel when significant inventory changes are made.
  - Emails include stock details, uploaded documents, and admin feedback.
- **Data Storage**:
  - Inventory data is stored in an Excel file and SharePoint for centralized access and reporting.
- **Barcode/QR Code Integration**:
  - Generate and scan barcodes or QR codes for quick item identification and updates.
- **Custom Reports**:
  - Generate inventory reports for stock valuation and movement trends.
- **Real-Time Notifications**:
  - Alerts for low stock levels or when items are added or removed.

---

## Technology Stack
- **Microsoft Power Apps**:
  - User Interface and Logic
- **Microsoft Power Automate**:
  - Automated email notifications and media uploads
- **Excel**:
  - Data storage for inventory tracking
- **SharePoint**:
  - Backend for document and media storage
- **Office 365 Outlook Integration**:
  - Email functionality
- **Barcode/QR Code Integration**:
  - For quick inventory identification and updates.

---

## How It Works
1. **Inventory Updates**:
   - Users input inventory details via the app, including stock levels, item details, and media uploads.
   - Data is stored in Excel, and supporting media is uploaded to a SharePoint Document Library.
2. **Admin Review**:
   - Admins log in securely via the admin panel to review inventory updates.
   - Admins can approve changes, provide feedback, and monitor stock levels.
3. **Media Management**:
   - Uploaded item images and documents are stored in SharePoint for centralized access using Power Automate flows.
4. **Automated Notifications**:
   - Notifications are sent to relevant personnel when updates occur or low stock levels are detected.
5. **Barcode/QR Code Integration**:
   - Users can scan or generate barcodes/QR codes for inventory items, facilitating quick stock updates.

---

## Benefits
- Improves inventory tracking with a centralized solution.
- Enhances visibility with image and document uploads for items.
- Provides secure access for admins to review and manage inventory.
- Streamlines processes with automated notifications and QR/barcode functionality.
- Simplifies stock movement tracking with feedback and real-time alerts.

---

## Future Enhancements
- Integration with Power BI for detailed analytics and dashboards.
- Support for multi-warehouse inventory management.
- Advanced forecasting features for inventory demand.

---

