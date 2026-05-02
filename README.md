Smart Invoice & Receipt Logger (n8n + AI) 🚀

A comprehensive automation project designed to receive and process invoices and receipts automatically using the n8n platform and AI technologies, aiming to eliminate manual data entry and reduce human error.
Project Overview

The Workflow was fully designed and built on the n8n platform to ensure a seamless and secure data path, starting from document upload to archiving, data logging, and stakeholder notification.
Technical Achievements:

    Form Submission: Created a form to receive data and uploaded files directly.

    File Management: Integrated the file upload path (Google Drive) for programmatic document archiving.

    AI Vision / OCR: Configured logic to accurately extract structured data from images and documents.

    Data Processing (Code Node): Wrote JavaScript code to clean outputs and convert them into a structured JSON format.

    Data Merging (Merge): Merged original file data with AI-extracted data into a single flow.

    Route Logic (Switch Node): Built logic to automatically distinguish between document types (Invoice or Receipt) for correct routing.

    Accounting Logging (Google Sheets): Prepared steps to append data to specific sheets (AR for Invoices, AP for Expenses).

    Email Automation (Gmail): Configured automated email notifications for invoices and updated the delivery status in the sheets.

Tech Stack

    n8n: The primary workflow automation engine.

    Google Gemini / AI Vision: For text and visual data extraction.

    Google Sheets & Drive: For data logging and cloud archiving.

    Gmail: For automated client communication.

Setup & Configuration

The logic and design are 100% complete; the system only requires connecting the company's official credentials to go live:

    Import Workflow: Upload the attached JSON file to n8n.

    Connect Google Drive: In the upload node to specify the storage folder.

    Connect Google Sheets: In the append/update nodes.

    Connect Gmail: In the send message node to define the sender's email.
    

    Activate AI Service: Add the company's API Key for automated data extraction
