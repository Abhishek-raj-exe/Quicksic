# Quicksic
A desktop app for YouTube music without ads
----------------------------------------------

*quiet in alpha stage .....*

but

![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Moth%20Light%202.png)

![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/wast%202.png)


# Features
1. Built-in Ad-Block
2. No Sign-Up required
3. Customized A.I. Recommendations (in pre-production)
4. Dynamic Background Colors
5. Recent and Custom Playlists
6. Voice Search

# Current Development Issues/Problems

---I am planning on my own streamer and integrating it, resulting in more freedom and control---

1. ~~occasionally jittered/laggy playback slider (cuz YouTube doesn't let me do it directly wth keys)~~ this one is fixed prob, now I'm using a different method.
2. ~~Limited Search Results per page (provides faster response)~~ this one is being tweaked for finite (max 150) magic widgets (generated with scroll or more button)
3. No segregation of albums and videos & no profile/album preview (cuz I am stuck with other bugs)
4. Gsignup available but with localhost only, and the user is required to have the account logged in the defined browser (login works for 2 years prob)
5. ~~Ad-Block is still unstable (its webdriver. ¯\ _(ツ)_ /¯ not my fault)~~ this one is almost fixed ig and prob won't be needed
6. ~~No network connectivity notifications, but is being tracked~~ notifications are popping now.. network connectivity is being worked
7. No Video Playback: this one is not possible cuz I am directly using raw stream data; a possible workaround is caching it first but isn't healthy for SSD users; yes, I know I can use VLC, but it adds up with more dependencies plus it will play it externally which would be...
8. Dynamics aren't always attractive (cuz I'm not caching the images) hence needs a better palette algo
9. voice search isn't implemented (it is simple) becoz search provider is not yet finished
10. Top charts for songs not visible unless logged similar case with age-restricted content (I think this part might be scraped if I scrap Gsignup)
