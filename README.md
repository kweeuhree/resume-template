<h1>Resume Template</h1>
<br><br>
This is a resume template. I am using a character from <i>The Fifth Element</i> - Diva Plavalaguna.
<br><br>
Header background is animated with <code>conic-gradient</code>. In keyframes I am using percentages that are smaller than the original background size. It results in a cool recursive effect.<br>
Here is a CSS code snippet: <br>
<code>
header {
    <!-- more code -->
    background-size: 100% 100%;
    background: conic-gradient(from 50deg, #d3e7e5e7, #0b113dce);
    animation: conic 25s linear infinite;
}

@keyframes conic {
    0% {background-size: 90% 50%;}
    25% {background-size: 80% 40%;}
    35% {background-size: 70% 30%;}
    55%  {background-size: 60% 20%;}
    63%  {background-size: 70% 30%;}
    80% {background-size: 80% 40%;}
    100% {background-size: 90% 50%;}
}</code>
<br><br>
Body of the page is styled with <code>box-shadow</code>. That was fun to make.
<br><br>
I tried using <code>transform:rotate()</code> to change look of <code>hr</code> in Education and Experience sections, but eventually I did not need the rotation. Not sure why.
<br><br>
<h2>when in doubt border it out</h2>