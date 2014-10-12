# AquaFish

Using your webcam release fishes that then swim randomly around.

**BUT:** it doesn't work, yet...

## What's going on?

Haha.

Yes it doesn't work yet. We only had 1h to integrate our codes. The black dot is trail of your fist. White is where you stop and open your hand. But it isn't reliable. Optial recognition libraries aren't super good and reliable.

Currently, there is one fish that get moved to the white dot but it's off picture grid and it's transparently behind.

So well.... it's not finished.

## Install and preparation
- install ```git```
- install ```nodejs```
- > ```npm install connect```
- > ```npm install serve-static```

## RUN the aquarium!
> ```nodejs server.js```

open the browser [http://localhost:8080/examples/example_gesture_input.htm](http://localhost:8080/examples/example_gesture_input.htm)

## We're using a generic recognizer

https://github.com/mtschirs/js-objectdetect it's a cool tool pure javascript that uses trainable models to recognize various different things. It does hand, face etc.

## how to copy a webpage recursively (get all the stuff)
> ```wget -rkp -l3 -np -nH --cut-dirs=1 http://web.psung.name/emacstips/```

## resources 
- [git it](
http://qugstart.com/blog/ruby-and-rails/create-a-new-git-remote-repository-from-some-local-files-or-local-git-repository/)
- [how to create a repo](https://help.github.com/articles/create-a-repo/)
