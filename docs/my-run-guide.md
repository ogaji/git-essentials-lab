Running the library demo

You need Git 2.23 or later, JDK 17 or later, and Python 3.9 or later.
Make sure both ‘java’ and ‘javac’ work in your terminal.
Open a terminal in the folder containing ‘run.py’ and run:
‘‘‘bash
python3 run.py demo
‘‘‘
On Windows, I used ‘py -3 run.py demo’.
The demo shows the borrowing limits, searches the catalog, and then
borrows and returns a book. Both students and faculty can borrow two
books. Searching for ‘git’ returns an empty list because the search
is case-sensitive.
Alex borrows ‘Git Essentials’ and receives a due date of 2026-09-15.
The demo uses a fixed date of 2026-09-01, so these dates do not depend
on when you run it. After the book is returned, the fee is 0 and
there are no active loans.