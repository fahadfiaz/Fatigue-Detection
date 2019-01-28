<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  
<h2 id="fatigue-detection">Fatigue Detection</h2>

A Desktop based application that can automatically detect driver fatigue in a real-time video stream<br>
and generate an alarm if the eye Aspect ratio is less than 0.25.</p>
<h2 id="quick-start">Quick Start</h2>
<p>To start using Fatigue_Detection application:</p>
<h2 id="get-code">Get code</h2>
<p>Clone repo via git<br>
<a href="https://github.com/fahadfiaz/Fatigue-Detection">https://github.com/fahadfiaz/Fatigue-Detection</a></p>
<h2 id="install-dependencies">Install Dependencies</h2>
<ol>
<li>OpenCV</li>
<li>immutils</li>
<li>dlib</li>
<li>scipy</li>
<li>Python 2.7 or higher</li>
<li>Open Drowsiness_Detection.py file and update the path where Shape_predictor_68_face_landmarks.dat file is located</li>
</ol>
<h2 id="algorithm">Algorithm</h2>
<p>Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:<br>
<img src="https://lh3.googleusercontent.com/RL1cX-zxDGQxWpai8Z8PtmRn23GI6DRunJV-g4ZZFOikPRg7O31RYEwDtOolqZT7wHWkVmA5qFE" alt="enter image description here"></p>
<h2 id="condition-for-fatigueness">Condition for fatigueness</h2>
<p>It checks 20 consecutive frames and if the Eye Aspect ratio is lesst than 0.25, Alert is generated.</p>
<h4 id="relationship">Relationship</h4>
<p><img src="https://lh3.googleusercontent.com/-7f-eHsQVGTGiCqlYmM9iAb6085RPgrW-lAb3FRO0y1CqT-GLft7GEfC_SJgNgky5vohGftTTrY" alt="enter image description here"></p>
<h4 id="conclusion">Conclusion</h4>
<p><img src="https://lh3.googleusercontent.com/YCaGFFmMZFOi4W4h6Y7aRHArlGSP1JlzXOjx2FZHoM0xUUMkw7--Fk8H9E07EVoA_-1vU_ZPIkY" alt="enter image description here"></p>
<h2 id="execution">Execution</h2>
<p>To run the code, type <code>Fatigue_Detection.py</code></p>
</div>
</body>

</html>
