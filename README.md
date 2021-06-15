# Backoffice Process

A back office is the portion of a company made up of administration and support personnel who are behind-the-scenes and not client-facing, while front office staffs are the folks in contact with the consumers or clients. Back office functions include settlements, clearances, record maintenance, regulatory compliance, accounting, and IT services. 

FinPricing provides interfaces for users to manage back office entities, such as Book/Portfolio, Counterparty, LegalEntity, and Exchange, etc. The management procedure is quite similar. Here we take book as an example.

A portfolio is a grouping of financial assets. It is more generically called book in FinPricing. A book could be a portfolio or trading strategy or desk. FinPricing portfolio management supports multi-level book(portfolio) hierarchies. 

Click the BackOffice tab at the top-left corner of the application. Then, expend BackOffice -> Portfolios -> Books. You can click the New button to create a new book or the Load button to extract an existing one.

If you click the New button, a new book template is displayed in the main window. The ParentName field allows you to build portfolio hierarchy. If there is no hierarchy, simply select NA. Fill all fields and then click the Save button. A new book has been generated.

If you click the Load button, all the existing books are loaded in the Display tab of the main window. You can modify the fields and then click the Save button to save all changes.

Note that all the bookIds above are underlined that means you can further drill down these books. Clicking a bookId (e.g., B00000012000004), all the trades within this book are displayed in the Details tab of the main window

References:

https://finpricing.com/lib/EqWarrant.html


