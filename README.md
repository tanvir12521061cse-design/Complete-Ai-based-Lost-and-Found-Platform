# Complete-Ai-based-Lost-and-Found-Platform
Key Features
1. AI Object Recognition
What it is: When you upload an image of a lost or found item, the app uses the TensorFlow.js COCO-SSD model.

How it helps: It automatically identifies what the object is (e.g., "cell phone," "backpack," "dog") and tags it. This makes searching and matching much more accurate.

2. Smart Matchmaking System
What it is: The app doesn't just list items; it actively looks for matches.

How it works: If you post a "Lost" item, the AI instantly scans the "Found" database for items with the same AI tag or a similar name.

3. Integrated Messenger
What it is: A built-in chat window similar to Facebook Messenger.

How it helps: When a match is found, the app automatically opens a chat window so the two parties can coordinate. It includes a "Resolve" button to remove posts once the item is returned.

4. Interactive Geo-Location (Maps)
What it is: Uses the Leaflet.js library to show a map of where items were last seen or found.

How it helps: Users can click on a mini-map when reporting to set a precise location pin.

5. User Authentication System
What it is: A complete Login and Registration flow.

How it helps: It protects data by ensuring only logged-in users can view the "Live Reports" feed and post new items.



How to Use the App
Step 1: Accessing the App
When you open the page, you will see the Login screen.

If you don't have an account, click "Register", enter your name, phone number, and a password.

Login with your credentials to access the main dashboard.

Step 2: Reporting an Item
Click the "+ Report Item" button in the header.

Select the Type (Lost or Found).

Upload a Photo of the item. Wait a second for the AI to identify it (you will see "AI Identified: [Object]").

Pin the Location: Click on the mini-map to show exactly where the item was lost or found.

Click "Submit & Match".

Step 3: Finding a Match
If the system finds a matching item in the database, a Chat Window will pop up immediately.

You can see the other person's contact number and send them a message directly through the app.

Step 4: Browsing the Feed
On the main dashboard, you can see a Map with pins of all reported items.

Below the map, a Grid View shows all cards with photos, descriptions, and contact details for every active report.

Step 5: Closing a Case
Once you have recovered your item or successfully returned it, open the chat window and click "Resolve & Delete Post". This keeps the database clean and up-to-date.
