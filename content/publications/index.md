---
widget: blank
headless: true
title: "Publications"
weight: 70
---

<div class="accordion" id="pubAccordion">

  <!-- Journal Section -->
  <div class="accordion-item">
    <h2 class="accordion-header" id="journalHeading">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#journalCollapse" aria-expanded="true" aria-controls="journalCollapse">
        📘 Journal Papers
      </button>
    </h2>
    <div id="journalCollapse" class="accordion-collapse collapse show" aria-labelledby="journalHeading" data-bs-parent="#pubAccordion">
      <div class="accordion-body">
        {{< publication_list type="journal-article" >}}
      </div>
    </div>
  </div>

  <!-- Conference Section -->
  <div class="accordion-item">
    <h2 class="accordion-header" id="confHeading">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#confCollapse" aria-expanded="false" aria-controls="confCollapse">
        🧾 Conference Papers
      </button>
    </h2>
    <div id="confCollapse" class="accordion-collapse collapse" aria-labelledby="confHeading" data-bs-parent="#pubAccordion">
      <div class="accordion-body">
        {{< publication_list type="conference-paper" >}}
      </div>
    </div>
  </div>

  <!-- Patent Section -->
  <div class="accordion-item">
    <h2 class="accordion-header" id="patentHeading">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#patentCollapse" aria-expanded="false" aria-controls="patentCollapse">
        🧪 Patents
      </button>
    </h2>
    <div id="patentCollapse" class="accordion-collapse collapse" aria-labelledby="patentHeading" data-bs-parent="#pubAccordion">
      <div class="accordion-body">
        {{< publication_list type="patent" >}}
      </div>
    </div>
  </div>

</div>
