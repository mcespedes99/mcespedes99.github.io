---
layout: page
icon: fas fa-tools
order: 1
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.ul {
    display: table; 
    margin: 0 auto;
    text-align: left;
}
.box-container{
  display:inline-block;
  width:100%;
  }
.box{
  display:block;
  width:31%;
  float:left;
  background:#808080;
  color:#333333;
  margin-left:2%;
  text-align:center;
  border-radius: 25px;
  padding-top: 10px;
  margin-bottom: 5px;
  }
.box :first-child {
    align-self: left;
}

@media screen and (max-width: 600px) {
  .box {
    width: 50%;
    margin-bottom: 10px;
    margin-left:25%;
    float:center;
  }
}
</style>
</head>
<body>

<div class="box-container">
    <div class="box">
      <i class="fa-solid fa-code fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Coding</h2>
      Python <br>
      Git/Github <br>
      C++ <br>
      MATLAB <br>
      Bash <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-file-medical-alt fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Signal Processing</h2>
      Spectral analysis <br>
      Time-frequency analysis <br>
      Synchronization analysis <br>
      Statistical testing <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-brain fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Machine Learning</h2>
      Regression techniques <br>
      Classification techniques <br>
      Image processing <br>
      Deep learning <br>
    </div>
</div>
<div class="box-container">
    <div class="box">
      <i class="fa-solid fa-microchip fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Computer Engineering</h2>
      HW basic maintenance <br>
      Linux <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-heartbeat fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Electrophysiology</h2>
      ECG analysis <br>
      EEG analysis <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-user-friends fa-4x"></i>
      <h2 style='margin-top: 10px; margin-bottom: 10px'>Soft-skills</h2>
      TBD
    </div>
</div>
</body>
</html>


<!-- feature:
- description: "Python, Bash, R, Matlab, git"
  icon: code
  icon_pack: fa
  name: Programming
- description: "FSL, ANTS, NiftyReg, 3D Slicer"
  icon: brain
  icon_pack: fa
  name: Neuroimaging
- description: "Extracellular, LFP"
  icon: "spike"
  icon_pack: "custom"
  name: "Electrophysiology" -->