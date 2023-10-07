# Quicksic
A desktop app/client for YouTube music without ads
----------------------------------------------

*current version 0.8b, demo will be pushed soon*

Light Theme

![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-10-07%20142228.png)
Dark Theme

![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-10-07%20142640.png)

<details open>
  <summary>Features</summary>
  <li><details close>
  <summary>Video Player</summary>
  https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-10-07%20143120.png
  </details></li>
  <li><details close>
  <summary>Lyrics</summary>
  https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20005232.png
  </details></li>
  <li><details close>
    <summary>Related info</summary>
    <li><details open>
      <summary>Similar Tracks & Recomended playlists/album</summary>
      https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20005043.png
    </details></li>
    <li><details open>
      <summary>Artist top songs & similar artists</summary>
      https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20004902.png
    </details></li>
    <li><details open>
      <summary>Artist albums and about</summary>
      https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20004944.png
    </details></li>  
  </details></li>
  <li><details close>
    <summary>Search Tracks & videos</summary>
  https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20011437.png
  </details></li>
  <li><details close>
    <summary>Search Albums & Playlist</summary>
    https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-10-04%20193958.png
    <li><track-list close>
    https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-10-04%20193924.png
    </details></li>
  </details></li>
</details>

# Features
1. Zero Ads
2. No Sign-Up required
3. Tailored Recommendations (in pre-production)
4. Dynamic Background Colors
5. Recent and Custom Playlists
6. Likes and basic functionality (authorised users)
7. Voice Search 
8. Sole Video / audio player
9. Lyrics and related suggestion

# Current Development Issues/Problems/Resitriction adapted
Total performance boost gained this week is about 10-12x
1. player is fixed since Azure media services is retiring next yr, which was my streamer platform i found much lighter builtin work around which also supports video
2. Searches are limited to 100 for performance
3. ~~no profile/album preview yet~~ album preview are added no profile visits yet
4. [not implented in main code]Gsignup available but with localhost only, and the user is required to have the account logged in the defined browser (login works for 2 years prob)
5. ~~Ad-Block is still unstable (its webdriver. ¯\ _(ツ)_ /¯ not my fault)~~ fixed no need 4 adblock anymore
6. ~~No network connectivity notifications, but is being tracked~~ notifications are popping now.. network connectivity is being worked
7. ~~No Video Playback: this one is not possible cuz I am directly using raw stream data; a possible workaround is caching it first but isn't healthy for SSD users; yes, I know I can use VLC, but it adds up with more dependencies plus it will play it externally which would be...~~ fixed (video player implented)
8. Dynamics aren't always attractive (cuz I'm not caching the images) hence needs a better palette algo
9. ~~voice search isn't implemented (it is simple) becoz search provider is not yet finished~~ voice search implemented
10. Top charts for songs not visible unless logged similar case with age-restricted content (I think this part might be scraped if I scrap Gsignup)
11. Recommendation are not implented
12. ~~rarely some video thumbnails might not pop up~~ fixed
13. ~~response speeds are slow~~ after furious attemps to speed up the app , using multiple workarounds with cython and smart syntax , the wisdom i gained is the app is working best with its dependencies and any changes only
    end-up either hampering/damping the process to much worse extent.
14. Jammed a clutter full code to cython and now is just a module resulting clearer code & performance boost (+-20/50 ms) sounds small but on operation cycle saves many minutes of load
# UI - Improvements
alpha 0.2
![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/progress/Screenshot%202023-08-21%20011547.png)
beta 0.4
![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/progress/Moth%20Light%202.png)
beta 0.8
![Screenshot](https://github.com/Abhishek-raj-exe/Quicksic/blob/main/ss/Screenshot%202023-08-21%20010658.png)
