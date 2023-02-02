# Lab-1_202001180

                                                                    IT314
                                                          Software Engineering Lab-1
                                            Identifying Functional and Non-Functional Requirements
                                            
**Name - Varshil Nayak**
**ID - 202001180**

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**Q.1. Identify FRs and NFRs:**

**1. Functional Requirements:**

- Registration and Login:
  - Any new user who wants to access the resources of Library Information System (LIS) must register as a member first.
  - Only members are able to login in order to borrow or return the book.

- Borrow books:
  - Any member of LIS can borrow a book if the book is available and not borrowed by any other member.

- Return books:
  - Any member of LIS who has borrowed any book can return the book before the specified date of returning the book

- Search books:
  - Any user can search the book he/she wishes to read/borrow along with certain filters applicable.

- Extend date of borrowing:
  - The system enables a member to extend the date of his borrowing if no other booking for that particular book has been made.

- Add/remove record:
  - The Librarian can enter a new record into the system when a new book has been purchased, or remove a record in case any book is taken off the shelf.

- Remove/restrict member:
  - The admin of LIS (Library Staff) have privilege to remove or restrict a member who is not following the deadline to return the book.

**2. Non-functional Requirements:**

- Compatibility constraints:
  - The system should be created as a web application which is compatible to recent browser version and should be developed using HTML 5.

- Access:
  - The system should be accessible within the institute LAN only.

- Scalable:
  - The system should be scalable so more students become members and borrow books.

-  Security:
  - The system should take care that no confidential information (eg., passwords) is stored in plain text and must be encrypted before storing.

- Performance:
  - The system should be capable of performing tasks with low latency.

**Q.2. Identify scope, features and non-functional aspects of the following problem.**

**- Scope:**
  - As 5% of world population suffers from hearing loss, the system should be built such that it can help the audience with hearing disabilities.

**- Features:**
  - The application should used artificial intelligence to recognize key sound events of interest, such as car horns and babies.
  - The application should be able to alert the user using some kind of vibration or other thing.
  - The application is optimized for Android with low-latency so that it works in real-time for use.

**- Non-functional aspects:**
  - The application should be compatible with latest android versions.
  - The application should have an alert that vibrates.
  - The system should be scalable so it can handle large traffics.
  - The application should have latency of less than 2 seconds.
