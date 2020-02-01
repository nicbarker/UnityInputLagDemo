# UnityInputLagDemo

This is a demonstration of the 20-100ms input delay visible _only_ in built application for Mac OSX on Unity. I've observed it on 2019.2.10 through to 2019.3.0f6. WebGL export has no input lag, and even using the editor on a mac the "play" window displays no input lag, whereas built applications experience a visible input delay at 60fps.

The easiest way to test this using "Build and run" in this repository project, while also running the game inside the editor. Place the windows next to eachother, and try clicking the large orange sprite. You'll observe that there is a noticable delay between clicking and the sprite turning black.

<img width="1719" alt="Screenshot 2020-02-01 16 05 38" src="https://user-images.githubusercontent.com/2264338/73586073-620afc80-450d-11ea-8573-7d2154c57083.png">
