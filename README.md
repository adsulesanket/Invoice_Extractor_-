# Invoice_Extractor_-
🚀 Overview
The Professional Invoice Extractor AI is a sophisticated, single-page web application designed to automate the process of extracting, verifying, and managing data from invoice documents. Leveraging the power of Google's Gemini API, this tool transforms unstructured invoice images or PDFs into structured, actionable data with a modern and intuitive user interface.

The application guides the user through a seamless four-step process: Upload, Extract, Review, and Export, making invoice processing efficient and error-free.

✨ Features
📄 Intelligent Document Upload:

Supports common image formats (JPG, PNG) and PDF files.

User-friendly drag-and-drop interface.

File preview with name and size before processing.

🧠 AI-Powered Data Extraction:

Utilizes the Gemini API for high-accuracy Optical Character Recognition (OCR).

Automatically extracts key-value pairs like Invoice Number, Dates, Totals, and Supplier/Customer details.

Parses and structures detailed line items, including description, quantity, unit price, and total.

🤖 Advanced AI Analysis & Generation:

AI Summary & Verification: Automatically generates a concise summary of the invoice and verifies if the extracted totals (subtotal, tax, line items) add up correctly, highlighting potential discrepancies.

Payment Reminder Drafting: With a single click, the AI composes a professional and polite payment reminder email using the extracted invoice data.

⚙️ Scalable Custom Fields:

Flexibly extract any additional field from the invoice on the fly by simply typing its name (e.g., "VAT Number," "Purchase Order").

✏️ Review and Edit:

An interactive form allows users to review and edit any piece of extracted data to ensure 100% accuracy before exporting.

📥 Multiple Export Options:

Download the structured data as a JSON file for use in other systems.

Export line items as a CSV file for spreadsheet analysis.

Copy all extracted data to the clipboard with a single click.

🎨 Professional User Interface:

A sleek, modern design with a glassmorphism aesthetic.

Animated progress indicators and transitions for a smooth user experience.

Responsive design for use on various devices.

🛠️ How It Works
The application follows a simple and intuitive 4-step workflow:

Upload: The user uploads an invoice file. The application performs OCR using the Gemini API to convert the document into raw text.

Extract: The raw text is sent back to the Gemini API with a structured schema. The model identifies and extracts key information, line items, and performs an AI-driven summary and verification.

Review: All extracted data is presented in an editable form, allowing the user to make corrections or additions.

Export: The final, verified data can be exported in various formats or used to generate content like a payment reminder email.

💻 Technology Stack
Frontend: HTML5, Tailwind CSS, JavaScript (ES6+)

AI & Machine Learning: Google Gemini API (gemini-2.0-flash) for:

Optical Character Recognition (OCR)

Structured Data Extraction (JSON Schema)

Natural Language Generation (Summary, Verification, Email Drafting)

