# eugenechamberofsecrets.github.io

Welcome to the Eugene Chamber of Secrets! This guide will help you find glimmers of fire on your journey down the dark tunnels.

1. Get the comic onto the site. Make sure it's legal to upload that particular image.
<br>a. Go to the Folder Called "images"
<br>b. Upload the image
2. Edit the index.html file
<br>a. Copy the example html below
```
<br>
<figure>
    <img src='image.jpg' alt='missing' />
    <figcaption>Caption goes here</figcaption>
</figure>
```
<br>b. Where it says, 'image.jpg', replace that with 'images/myimage.fileextension'
<br>c. Where it says, Caption goes here, provide a caption or delete that entire line.
<br>d. Paste the edited code under the `<h1>` tag.

Here's what it should look like after you add two images:
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eugene Chamber of Secrets</title>

    <script>document.addEventListener("DOMContentLoaded",function(){const z=(x)=>document.querySelector(x);const y=(w)=>document.createElement(w);const v=(u)=>document.getElementById(u);const a=z('body');const b=y('dialog');b.id='a';const c=y('p');c.innerHTML='&#71;&#111;&#111;&#100; &#106;&#111;&#98; &#111;&#110; &#102;&#105;&#110;&#100;&#105;&#110;&#103; 	&#109;&#101;! &#71;&#111;&#111;&#100; &#108;&#117;&#99;&#107; &#111;&#110; &#99;&#108;&#111;&#115;&#105;&#110;&#103; &#109;&#101;!';b.appendChild(c);a.appendChild(b);const d=y('button');d.innerHTML='&#105;\'&#109; &#115;&#111; &#104;&#105;&#100;&#100;&#110;';d.style.color='transparent';d.style.backgroundColor='transparent';d.style.border='none';d.onclick=()=>{const d = v('a');d.setAttribute('open','');};a.appendChild(d);});</script>
    
    <style>
        * { font-family: 'Times New Roman', Times, serif; }
        body { margin: 0; padding: 0; background-color: cornsilk;}
        h1, figure { margin: 0 auto; width: fit-content; }
    </style>
</head>
<body>

    <h1>Welcome to the Heugene Chamber of Secrets!</h1>
    <br>
    <figure>
        <img src='images/example.jpg' alt='missing' />
        <figcaption>Here's my example caption</figcaption>
    </figure>
    <br>
    <figure>
        <img src='images/example2.jpg' alt='missing' />
        <figcaption>Here's my second example caption</figcaption>
    </figure>
</body>
</html>
```
