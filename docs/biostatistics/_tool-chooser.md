```{=html}
<ul id="choose-your-tool" class="nav nav-tabs" role="tablist">
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="dose-finding.html">
      <img src="../images/dose-finding.png">Dose Finding
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="dose-optimization.html">
      <img src="../images/dose-optimization.png">Dose Optimization
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="dynamic-borrowing.html">
      <img src="../images/dynamic-borrowing.png">Dynamic Borrowing
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="hypothesis-testing.html">
      <img src="../images/hypothesis-testing.png">Hypothesis Testing
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="survival-analysis.html">
      <img src="../images/survival-analysis.png">Survival Analysis
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="decision-making.html">
      <img src="../images/decision-making.png">Decision Making
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="multiple-comparison.html">
      <img src="../images/multiple-comparison.png">Multiple Comparison
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="targeted-learning.html">
      <img src="../images/targeted-learning.png">Targeted Learning
    </a>
  </li>
  <li class="nav-item" role="presentation">
    <a class="nav-link" href="estimand.html">
      <img src="../images/estimand.png">Estimand
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
