# CamJam

A near-realtime view of London from TFL's JamCams

Doc to come, but if you want to hack on it:
* Sorry this code is really bad
* Install go
* `go build`
* `PORT=:8080 go run camjam.go` or `PORT=:8080 ./CamJam`
* open localhost:8080


1. Find out London sunrise
    * Sunrise API
    * Run continuosly, or have a dynamic cron?
    * Sunrise schedule?
1. Kickoff the job at sunrise 
    * get the video, or videos
    * add together into a timelapse
    * fast forward
    * export to mp4
1. Post to twitter
    * Create account
    * authorise 
    * Post video