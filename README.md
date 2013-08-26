
These are the slides for my talk "Server-Side Cookies at Booking.com", delivered at YAPC 2013 Kiev.

The talk was recorded and is available for viewing:
https://www.youtube.com/watch?v=dwbauqh0kK4 I suggest watching it as the
slide-deck is deliberately minimal and only includes major themes from the
talk.

To create the slides I used [RemarkJS](http://remarkjs.com), which turns
markdown into a nice HTML/JS slideshow.

To view the slides, you'll need something that can serve the contents of the
directory over http.  If you don't have one, you can install the one I used:

    go get github.com/dgryski/trifles/servedir
    go install github.com/dgryski/trifles/servedir
    ./servedir

Then browse to http://localhost:8080/slides.html
