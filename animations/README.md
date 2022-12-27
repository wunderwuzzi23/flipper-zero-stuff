1) Unzip the `commodore64.zip` file - it contains the `frames` and the `meta.txt`
2) Create a new folder `commodore64` in the `dolphin` folder of your Flipper Zero.
3) Copy the files (frames and meta.txt) over to the Flipper Zero folder created in step 2
4) Make sure to change the `manifest.txt` as well on the Flipper Zero. It's in the root of the dolphin folder; you need to add the new animation there - so the Flipper Zero picks the new animation up. Good idea to backup the old manifest before.

More details, and info can be found at: https://www.youtube.com/@TalkingSasquach

Addition to manifest.txt file:

```
Name: commodore64
Min butthurt: 0
Max butthurt: 10
Min level: 1
Max level: 3
Weight: 3
```
