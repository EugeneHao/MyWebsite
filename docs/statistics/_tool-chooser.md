```{=html}
<ul id="choose-your-tool" class="nav nav-tabs" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="bayesian.html">
      <img src="../images/Bayesian.png">Bayesian Statistics
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="causal-inference.html">
      <img src="../images/causal-inference.png">Causal Inference
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="linear-model.html">
      <img src="../images/linear-model.png">Linear Model
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="multivariate-analysis.html">
      <img src="../images/multivariate-analysis.png">Multivariate Analysis
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="probability-theory.html">
      <img src="../images/probability-theory.png">Probability Theory
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="spatial.html">
      <img src="../images/spatial.png">Spatial Statistics
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="survey-sampling.html">
      <img src="../images/survey-sampling.png">Survey Sampling
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="machine-learning.html">
      <img src="../images/machine-learning.png">Machine Learning
    </a>
  </li>
</ul>

<br><br>

<script type="text/javascript">
document.addEventListener("DOMContentLoaded", function() {
  // get file name
  const filename = window.location.pathname.split("/").slice(-1)[0];
  
  // latch active
  const toolLinks = window.document.querySelectorAll("#choose-your-tool a");
  for (const tool of toolLinks) {
    if (tool.href.endsWith(filename)) {
      tool.classList.add("active");
      break;
    }
  }
  
   // save in local storage
  window.localStorage.setItem("tutorialTool", filename);
});

</script>
```
