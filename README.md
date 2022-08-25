# Senate-Stock-Watcher

This application uses a simple Python GUI to access a PostgreSQL database which can be hosted on a separate online server (eg. Scalingo)
The database stores senator stock market trading information such as: Senate Members, Stock that was traded, Companies the Senators have worked for, and transaction details.



User Manual for the Senate Stock Watcher
-----------------------------------------------
How to setup the project:
1. Download the github repository linked above
2. Database has been hosted online and already connected
postgres://cse412_1716:rXmvrZ07nhKSr1m0FTv_@cse412-1716.postgresql.
a.osc-fr1.scalingo-dbs.com:33302/cse412_1716?sslmode=prefer
3. Run main.py from the github, you may need to install Python and any necessary
libraries if it doesn’t run right off the bat
  a. Linux
    i. pip install psycopg2
    ii. sudo apt-get install python3-pil python3-pil.imagetk
    iii. sudo apt-get install python3-tk
  b. Windows
    i. pip install psycopg2
    ii. python3 -m pip install --upgrade pip
    iii. python3 -m pip install --upgrade Pillow
4. All transactions are automatically outputted in the listbox
