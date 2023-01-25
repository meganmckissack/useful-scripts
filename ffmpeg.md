
separate video into images - can adjust frames per second extracted
(example is to extract an image every 30 seconds and name frames sequentially)


`ffmpeg -i /Users/mbmckissack/Documents/undercurrents/undertones__live_cinema3.mp4 -vf fps=.3 /Users/mbmckissack/Documents/undercurrents/frames3/frame%06d.png`
