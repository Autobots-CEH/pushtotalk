## What is Push To Talk?

What issues does it address? 
Website contact forms have always been rubbish. 
The rely on email which quickly got spammed to death. 
This was solved for the most part by apps like 
Facebook Messenger, offering simpler, more personal, 
and more fun ways of connecting customers with  
business owners. 
There are some very real downsides to running your 
Customer Service on Social Media, even though it's easy

With modern JavaScript we can use fancy pants 
events for pretty much everything, but in this case we wanted 
something more old skool. Like a heart beat

Sometimes doing things at the speed of JavaScript isn't good 
for a user. They are human and they don't measure time in millseconds. 
They measure it in seconds, so we do too

The App's heart beats once per second. Clockwork exposes hooks 
which let us execute actions in a more human timeframe

We send a chunk of JSON to our Google Cloud Functions 
serverless Node backend. The function adds the JSON 
, which we'll call a <strong>ting</strong> to our NoSQL 
Firestore Database

Such operations are async. You can see them happening 
by the Linear Progress Bar which can be seen when synching 
is done or check your Network tab