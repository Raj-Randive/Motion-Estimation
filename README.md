# motion-extractorflow
Motion extraction using 9 layered CNN on Flying Chairs Dataset

# Instructions
<ol>
  <li>Run "pip install -r requirements.txt"</li>
  <li>Add a folder named "Model" to the dir and add this model to it https://drive.google.com/file/d/1jbWiY1C_nqAUJRYZu7mwzV6CK7ugsa5v/view?usp=sharing</li>
  <li>Add images to /images/run_on_this with corresponding images having formats "{name}1.{ext}" and "{name}2.{ext}" respectively</li>
  <li>Run command python run_inference.py ./images/run_on_this ./model/flownets_EPE1.951.pth.tar</li>
</ol>
