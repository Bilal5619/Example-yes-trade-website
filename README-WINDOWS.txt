YES TRADES WEBSITE DEMO
=======================

This package contains the complete front-end demonstration website.
It uses HTML, CSS and JavaScript. No database or installation is required.

QUICK METHOD: RUN WITH VISUAL STUDIO CODE
-----------------------------------------

1. Extract the ZIP file.
2. Install Visual Studio Code from https://code.visualstudio.com/
3. Open Visual Studio Code.
4. Select File > Open Folder.
5. Select the extracted "yes-trades-website" folder.
6. Install the extension named "Live Server" by Ritwick Dey.
7. Right-click index.html and select "Open with Live Server".
8. Your browser should open the website automatically.

RECOMMENDED METHOD: RUN WITH PYTHON
-----------------------------------

1. Extract the ZIP file.
2. Install Python from https://www.python.org/downloads/
3. During installation, tick "Add Python to PATH".
4. Open the extracted folder.
5. Click the folder address bar, type cmd, then press Enter.
6. In the black Command Prompt window, enter:

   python -m http.server 8000

7. Open this address in your browser:

   http://localhost:8000

8. To stop the website, return to Command Prompt and press Ctrl+C.

TEST THE MOBILE VERSION ON YOUR COMPUTER
----------------------------------------

1. Open the website in Google Chrome or Microsoft Edge.
2. Press F12.
3. Click the phone/tablet icon in Developer Tools.
4. Select iPhone 14, Samsung Galaxy or Responsive.
5. Open a bookable service such as:

   http://localhost:8000/services/epc/
   http://localhost:8000/services/boiler-service/

6. Complete the questions, postcode, date and time.
7. Press "Add to booking" to test the mobile checkout.

IMPORTANT
---------

- This is a front-end demonstration.
- The payment form does not charge a real card.
- Customer bookings are not stored in a database.
- Emails and SMS messages are not sent.
- Real Stripe payments require a secure server-side integration.
- Google Analytics, Google Ads and Meta Pixel are not connected yet.
- Do not collect real customer payment details with this demo.

MAIN FILES
----------

- index.html: website entry page
- app.js: pages, service content and booking interactions
- styles.css: main desktop and responsive design
- mobile-ordering.css: mobile-first booking improvements
- easy-booking.css: booking cart and checkout design
- inline-booking.css: same-page service booking section
- sitemap.xml and robots.txt: search-engine discovery files

When the website is moved to the real Yes Trades domain, a developer should
connect the booking system, database, Stripe, confirmation emails/SMS, security,
analytics and advertising conversion tracking.
