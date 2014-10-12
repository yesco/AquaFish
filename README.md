# AquaFish

Using your webcam release fishes that then swim randomly around.

**BUT:** well, it almost works...

## What's going on?

The black dot is trail of your fist. White dot is where you stop and open your hand. The fish moves there now. There is only one fish. Also, click anywhere and the fish will move there.

But it isn't reliable. Optical recognition libraries aren't super good and reliable. So well.... it's not finished.

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
