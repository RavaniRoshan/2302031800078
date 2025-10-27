# Library Management System Wireframes

This document presents the wireframes for the core functionalities of the Library Management System (LMS), covering both user and librarian perspectives. A total of eight key screens are detailed to fulfill the assignment requirements.

---

## 1. Home/Dashboard (User/Librarian)

This screen serves as the primary entry point, providing tailored access and information based on the user's role.

| Component | User View | Librarian View |
| :--- | :--- | :--- |
| **Header** | Logo, Global Search Bar, User Profile/Login | Logo, Global Search Bar, User Profile/Logout |
| **Navigation** | Home, My Account, Browse Books, Contact Us | Home, Manage Books, Manage Users, Fines/Overdue, Reports |
| **Main Content** | **Welcome Message**, Quick Search, **Featured Books** (e.g., New Arrivals, Popular), Recently Added Books. | **Dashboard Statistics** (e.g., Books Borrowed Today, Overdue Books Count, New Members), Quick Links to core librarian functions (Checkout, Return). |

---

## 2. Book Search and Listing

The main interface for users to discover and browse the library's collection.

| Component | Description |
| :--- | :--- |
| **Search Bar** | Prominent search input with options to search by Title, Author, Genre, or ISBN. |
| **Filter/Sort** | Sidebar or top bar controls for refining results by: **Genre**, **Availability Status**, Publication Year, and **Sort** by Title, Author, or Date Added. |
| **Book List** | A grid or list view displaying: **Book Cover**, **Title**, **Author**, and a brief **Availability Status**. |
| **Pagination** | Controls to navigate through multiple pages of search results. |

---

## 3. Book Details/Information

Provides comprehensive information about a selected book and options for interaction.

| Component | Description |
| :--- | :--- |
| **Visuals** | Large Book Cover Image. |
| **Core Info** | **Title**, **Author**, **ISBN**, Publication Date, Publisher, and a detailed **Description/Summary**. |
| **Status** | **Availability Status** (Available/Checked Out/On Hold), Total Copies, Available Copies, and the expected **Due Date** if all copies are checked out. |
| **Actions** | **"Borrow"** (if available), **"Place Hold"** (if all copies are out), or **"Add to Wishlist"** buttons. |

---

## 4. User Profile/My Account

Allows the user to manage their personal library interactions.

| Component | Description |
| :--- | :--- |
| **User Info** | User's Name, Member ID, Contact Details, and Membership Status. |
| **Borrowed Books** | A list of all books currently checked out, showing the **Book Title**, **Due Date**, and a **"Renew"** option. |
| **Fines Section** | A clear display of any outstanding fines, the reason for the fine, and a **"Pay Fine"** button. |
| **History** | A record of all previously borrowed and returned books. |

---

## 5. Book Checkout/Borrowing (Librarian View)

A dedicated screen for librarians to process book loans.

| Component | Description |
| :--- | :--- |
| **User Identification** | Input field to search for a user by Member ID or Name. Displays user details and borrowing eligibility upon selection. |
| **Book Identification** | Input field to search for a book by ISBN or scan a book's barcode. |
| **Transaction List** | A list of books to be checked out in the current transaction, with a running total. |
| **Action** | **"Confirm Checkout"** button to finalize the transaction and update the book/user status. |

---

## 6. Book Return/Check-in (Librarian View)

A dedicated screen for librarians to process book returns.

| Component | Description |
| :--- | :--- |
| **Book Identification** | Input field to search for a book by ISBN or scan a book's barcode. |
| **Status Check** | Automatically displays the **Borrower's Name** and checks the **Due Date**. |
| **Fine Calculation** | If the book is overdue, the system automatically calculates and displays the fine amount. |
| **Action** | **"Confirm Return"** button to check the book back into the system. |

---

## 7. Add/Edit Book (Librarian/Admin View)

Used for managing the library's catalog.

| Component | Description |
| :--- | :--- |
| **Form Fields** | Comprehensive form including: **Title**, **Author(s)**, **Genre**, **ISBN**, Publication Date, Publisher, **Description**, and **Number of Copies**. |
| **Media** | Section for **Cover Image Upload**. |
| **Action** | **"Save Book"** (for new entries) or **"Update Book"** (for existing entries). |

---

## 8. Fine/Overdue Management (Librarian View)

A central administrative tool for handling overdue items and financial penalties.

| Component | Description |
| :--- | :--- |
| **Overdue List** | A sortable and searchable table of all overdue books, showing: **Book Title**, **Borrower Name**, **Due Date**, **Days Overdue**, and **Calculated Fine Amount**. |
| **Actions** | **"Mark as Paid"** button next to each fine. **"Send Reminder"** button to notify the borrower. |
| **Summary** | Total outstanding fine amount. |
'''
