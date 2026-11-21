
Event Search Android App

An Android app I built for a course project. You search for events (concerts, sports, theatre, etc.) near you, look at the details, save favorites, and tweet about them. It's the mobile version of my earlier web app and uses the same Node.js backend.



What it does?

Search by keyword (with autocomplete), category, distance and location
Event details with Event, Artist/Team and Venue tabs
Artist info from Spotify for music events, plus a map for the venue
Upcoming events at a venue, with sorting
Favorites saved on the device

Built with
Java, Android Studio, Volley, Glide, Google Maps SDK
Running it
Clone the repo and open it in Android Studio.
Put your own Google Maps API key in AndroidManifest.xml and app/src/debug/res/values/google_maps_api.xml.
The backend URL is hard-coded in the Java files. The old server may be down, so you'll need to host the backend yourself and change the URL.
Run it on an emulator or a phone.





