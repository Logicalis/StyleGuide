---
name: Progress bar
---
<!-- Progress bar-->

To ensure that the label text remains legible even for low percentages, consider adding a <span class="code">min-width</span> to the progress bar.

</br>
</br>

<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="0" aria-valuemin="0" aria-valuemax="100" style="min-width: 2em;">
    0%
  </div>
</div>
<div class="progress">
  <div class="progress-bar" role="progressbar" aria-valuenow="2" aria-valuemin="0" aria-valuemax="100" style="min-width: 2em; width: 2%;">
    2%
  </div>
</div>
<!-- / Progress bar-->