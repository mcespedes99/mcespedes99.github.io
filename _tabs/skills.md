---
layout: page
icon: fas fa-tools
order: 1
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.1">
<style>
  body {
    background-color: #333333; /* Dark gray background */
  }

  .box-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin: 0 auto;
    max-width: 800px; /* Adjust the maximum width as needed */
  }

  .box {
    flex: 1;
    width: calc(33.33% - 20px); /* 33.33% for three columns with some margin */
    background: #1E1E1E; /* Darker background color */
    color: #FFA500; /* Orange text color */
    border: 2px solid #333333; /* Dark gray border */
    border-radius: 10px;
    margin: 10px;
    text-align: center;
    padding: 10px;
  }

  .box i {
    color: #FFA500; /* Orange color for icons */
  }

  @media screen and (max-width: 768px) {
    .box {
      width: calc(50% - 20px); /* 50% for two columns on smaller screens */
    }
  }
</style>
</head>
<body>

<div class="box-container">
    <div class="box">
      <i class="fa-solid fa-code fa-4x"></i>
      <h2>Coding</h2>
      Python <br>
      Git/Github <br>
      C++ <br>
      MATLAB <br>
      Bash <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-file-medical-alt fa-4x"></i>
      <h2>Signal Processing</h2>
      Spectral analysis <br>
      Time-frequency analysis <br>
      Synchronization analysis <br>
      Statistical testing <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-brain fa-4x"></i>
      <h2>Machine Learning</h2>
      Regression techniques <br>
      Classification techniques <br>
      Image processing <br>
      Deep learning <br>
    </div>
</div>
<div class="box-container">
    <div class="box">
      <i class="fa-solid fa-microchip fa-4x"></i>
      <h2>Computer Engineering</h2>
      HW basic maintenance <br>
      Linux <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-file-code fa-4x"></i>
      <h2>ML Coding</h2>
      scikit-learn <br>
      Pytorch <br>
      Pytorch lightning <br>
      Keras <br>
      MONAI <br>
      Containerization <br>
    </div>
    <div class="box">
      <i class="fa-solid fa-user-friends fa-4x"></i>
      <h2>Soft-skills</h2>
      Teamwork <br>
      Leadership <br>
      Continuous Learner <br>

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