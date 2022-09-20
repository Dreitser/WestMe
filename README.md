# WestMe
An optimized web app to convert an image into western style. Written in Rust, WASM and JS 
<img width="1146" alt="Screen Shot 2022-09-19 at 11 54 38 PM" src="https://user-images.githubusercontent.com/2120817/191187791-5babb6b3-cea5-480b-8ff3-dbeb8bdfb83e.png">
## HOW IT WAS MADE
I used raw JS with tailwind to create the front-end.
The User is able to upload an image.
The image is passed from JS to Rust WASM using Base64 encoding.
Rust WASM modifies the image, loads it into a buffer and it's diplayed by the front-end.

Try it LIVE: https://west-me.vercel.app/
