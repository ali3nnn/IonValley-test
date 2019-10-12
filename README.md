# IonValley-test

# Here is a piece of code you cand wirte in Chrome DevTool in order to download the canvas that a page is showing

var image = canvas.toDataURL("image/png").replace("image/png", "image/octet-stream");  // here is the most important part because if you dont replace you will get a DOM 18 exception.


window.location.href=image; // it will save locally
