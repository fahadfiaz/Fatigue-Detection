<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fatigue_Detection</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__html"><p>**</p>
<h2 id="fatigue-detection">Fatigue Detection</h2>
<p>**<br>
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
<p>Each eye is represented by 6 (x, y)-coordinates, starting at the left-corner of the eye (as if you were looking at the person), and then working clockwise around the eye:</p>
<h2 id="condition-for-fatigueness">Condition for fatigueness</h2>
<p>It checks 20 consecutive frames and if the Eye Aspect ratio is lesst than 0.25, Alert is generated.</p>
<h4 id="relationship">Relationship</h4>
<h4 id="conclusion">Conclusion</h4>
<h2 id="execution">Execution</h2>
<p>To run the code, type <code>Fatigue_Detection.py</code></p>
</div>
</body>

</html>
