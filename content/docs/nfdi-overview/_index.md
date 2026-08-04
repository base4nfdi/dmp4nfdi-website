---
title: NFDI DMP Services
summary: NFDI DMP Services Supported by DMP4NFDI
date: 2026-07-29
show_lastmod: false
type: book

---
<!-- wenn es mehr Punkte gibt, headings nutzen, die dann rechts im Menu stehen -->
<!-- ## Linked RDMO Information and Documentation -->

## NFDI DMP Services supported by DMP4NFDI

We work with NFDI consortia to develop and enhance data and software management services for their research communities. This overview highlights the current collaboration status and implementation level for each consortium, making it easy to identify existing services, resources and ongoing developments.

<p style="font-size: 16px;"> ✅ = Available | 🟢 = RDMO test client done | 🟡 = In progress | ⚪ = Not supported at the moment </p> 

<style>
/* Remove Bootstrap/Hugo Blox zebra striping */
.table {
  --bs-table-bg: transparent;
  --bs-table-striped-bg: transparent;
  --bs-table-accent-bg: transparent;
}

.table thead th {
  background-color: #45546b;
  color: white;
  font-weight: 700;
  border-color: #45546b;
}

/* Category headers */
.table-group th {
  background: #0BBBEF !important;
  font-weight: 700;
  text-align: left;
  padding: 0.75rem;
}

/* Muted consortium names */
.text-muted {
  color: #9ca3af;
}

/* Hover effect */
.table-hover tbody tr:not(.table-group):hover > * {
  background-color: rgba(0, 0, 0, 0.05) !important;
}

/* ---------- Dark mode ---------- */

/* Remove Hugo Blox zebra striping */
.dark table.table tbody tr:not(.table-group):nth-child(2n+1) > td,
.dark table.table tbody tr:not(.table-group):nth-child(2n+1) > th {
  background-color: transparent !important;
}

/* Dark mode category headers */
.dark table.table tbody tr.table-group > th {
  background-color: #0BBBEF !important;
  color: inherit;
}

/* Dark mode category header text */
.dark table.table tbody tr.table-group > th {
  color: #1f2937 !important;
}

/* Keep category headers unchanged on hover */
.dark table.table.table-hover tbody tr.table-group:hover > th {
  background-color: #0BBBEF !important;
  color: #1f2937 !important;
}

.dark table.table.table-hover tbody tr.table-group:hover {
  color: inherit !important;
}

/* Hover only normal rows */
.dark table.table.table-hover tbody tr:not(.table-group):hover > td,
.dark table.table.table-hover tbody tr:not(.table-group):hover > th {
  background-color: #b3bbc7 !important;
  color: #212529 !important;
}

/* Muted consortium names */
.dark .text-muted {
  color: #7d8590 !important;
}
</style>

<table class="table table-hover">
  <thead>
    <tr>
      <th>Consortium</th>
      <th>RDMO hosting</th>
      <th>RDMO integration</th>
      <th>DMP/SMP templates</th>
      <th>Training &amp; Outreach</th>
    </tr>
  </thead>

  <tbody>

  <!-- Engineering Sciences -->
  <tr class="table-group">
    <th colspan="5">Engineering Sciences</th>
  </tr>

  <tr>
    <td>NFDI4Datascience</td>
    <td>⚪</td>
    <td>⚪</td>
    <td>🟡</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Energy</td>
    <td><a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Ing</td>
    <td><a href="https://rdmo.nfdi4ing.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
    <td>🟡</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI-MatWerk</td>
    <td>🟢*</td>
    <td>⚪</td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr class="text-muted">
    <td>NFDIxCS</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <!-- Humanities and Social Sciences -->
  <tr class="table-group">
    <th colspan="5">Humanities and Social Sciences</th>
  </tr>

  <tr>
    <td>NFDI4Culture</td>
    <td><a href="https://rdmo.nfdi4culture.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
    <td><a href="https://github.com/rdmorganiser/rdmo-catalog/tree/main/shared/NFDI4Culture" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Memory</td>
    <td>🟢*</td>
    <td>⚪</td>
    <td>🟡</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Objects</td>
    <td>⚪</td>
    <td>⚪</td>
    <td>🟡</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>Text+</td>
    <td>⚪</td>
    <td>⚪</td>
    <td><a href="https://github.com/rdmorganiser/rdmo-catalog/tree/main/shared/Text%2B" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
  </tr>

  <tr class="text-muted">
    <td>KonsortSWD</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr class="text-muted">
    <td>BERD@NFDI</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <!-- Life Sciences -->
  <tr class="table-group">
    <th colspan="5">Life Sciences</th>
  </tr>

  <tr>
    <td>FAIRagro</td>
    <td><a href="https://rdmo.fairagro.net/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
    <td><a href="https://rdmo.fairagro.net/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td><a href="https://github.com/fairagro/FAIRagro_DMP_Template" target="_blank" rel="noopener noreferrer">✅</a></td>
  </tr>

  <tr>
    <td>NFDI4Biodiversity</td>
    <td>⚪</td>
    <td><a href="https://github.com/rdmorganiser/rdmo-plugins-zenodo" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4BIOIMAGE</td>
    <td><a href="https://rdmo.nfdi4bioimage.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Health</td>
    <td>🟢*</td>
    <td>⚪</td>
    <td>🟡</td>
    <td>🟡</td>
  </tr>

  <tr>
    <td>NFDI4Microbiota</td>
    <td>🟢*</td>
    <td>⚪</td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr class="text-muted">
    <td>DataPLANT</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr class="text-muted">
    <td>NFDI4Immuno</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr class="text-muted">
    <td>GHGA</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <!-- Natural Sciences -->
  <tr class="table-group">
    <th colspan="5">Natural Sciences</th>
  </tr>

  <tr>
    <td>FAIRmat</td>
    <td><a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
    <td>⚪</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>MaRDI</td>
    <td><a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td><a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
    <td>⚪</td>
  </tr>

  <tr>
    <td>NFDI4Cat</td>
    <td>⚪</td>
    <td>⚪</td>
    <td>🟡</td>
    <td>🟡</td>
  </tr>

  <tr>
    <td>NFDI4Chem</td>
    <td><a href="https://rdmo.nfdi4chem.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>🟡</td>
    <td>🟡</td>
    <td><a href="https://zenodo.org/records/20529135" target="_blank" rel="noopener noreferrer">✅</a></td>
  </tr>

  <tr>
    <td>NFDI4Earth</td>
    <td><a href="https://rdmo.nfdi4earth.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td><a href="https://github.com/rdmorganiser/rdmo-plugins-sensorsearch" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td><a href="https://rdmo.nfdi4earth.de/" target="_blank" rel="noopener noreferrer">✅</a></td>
    <td>⚪</td>
  </tr>

  <tr class="text-muted">
    <td>DAPHNE4NFDI</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  <tr class="text-muted">
    <td>PUNCH4NFDI</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
    <td>-</td>
  </tr>

  </tbody>
</table>

<p style="font-size: 14px; font-style: italic;">(*) RDMO test client ready, productive client in preparation</p>

## DMP services available across NFDI consortia 

Do you need help creating Data Management Plans (DMPs)? Explore DMP services available across the NFDI consortia! 

<style>
.service-grid { 
  display: grid; 
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); 
  gap: 1rem; 
  margin: 1rem 0;
}
.service-tile { 
  text-align: center; 
  border: 1px solid #ddd; 
  border-radius: 0.5rem; 
  padding: 0.5rem;
  background-color: white;
  color: #1f2937; 
}
.service-tile img { 
  width: 10vw; 
  height: auto; 
  display: block; 
  margin: 0 auto 0.5rem; 
  border-radius: 0.25rem;
}
.service-tile a { 
  display: block; 
  font-weight: bold; 
  color: #0ABAF0; 
  text-decoration: none; 
}
</style>

### Engineering Sciences

<div class="service-grid">
  <div class="service-tile">
    <img src="/images/nfdi4energy_logo.png" alt="NFDI4Energy Logo">
    <p><strong>NFDI4Energy</strong></p>
    <p><a href="https://nfdi4energy.uol.de/rdm/datenmanagementplane-in-nfdi4energy/" target="_blank" rel="noopener noreferrer">DMP Services for Energy Research</a></p> 
  </div>  
  <div class="service-tile">
    <img src="\images\nfdi4ing_logo.png" alt="NFDI4ING Logo">
    <p><strong>NFDI4ING</strong></p>
    <p><a href="https://nfdi4ing.de/rdmo/" target="_blank" rel="noopener noreferrer">DMP Services for Engineering Sciences</a></p>
  </div>
</div>

### Humanities and Social Sciences

<div class="service-grid">
  <div class="service-tile">
    <img src="\images\text+_logo.png" alt="Text+ Logo">
    <p><strong>Text+</strong></p>
    <p><a href="https://text-plus.org/en/themen-dokumentation/forschungsdatenmanagement/#rdmo" target="_blank" rel="noopener noreferrer">DMP Services for Text- and Language-oriented Humanities and Social Sciences</a></p>
  </div>
  <div class="service-tile">
    <img src="/images/nfdi4culture_logo.png" alt="NFDI4Culture Logo">
    <p><strong>NFDI4Culture</strong></p>
    <p><a href="https://nfdi4culture.de/services/details/research-data-management-organizer.html" target="_blank" rel="noopener noreferrer">DMP Services for Cultural Research </a></p>
  </div>
</div>

### Life Sciences

<div class="service-grid">
  <div class="service-tile">
    <img src="/images/dataplant_logo.png" alt="DataPLANT Logo">
    <p><strong>DataPLANT</a></strong></p>
    <p><a href="https://nfdi4plants.github.io/articles/planning-dataplan/" target="_blank" rel="noopener noreferrer">DMP Services for the Plant Research Community</a></p>
  </div>
  <div class="service-tile">
    <img src="/images/fairagro_logo.png" alt="FAIRagro Logo">
    <p><strong>FAIRagro</a></strong></p>
    <p><a href="https://fairagro.net/en/services/the-fairagro-dmp-service/" target="_blank" rel="noopener noreferrer">DMP Services for the Agrosystems Research Community</a></p>
  </div>
  <div class="service-tile">
    <img src="/images/nfdi4biodiversity_logo.png" alt="NFDI4Biodiversity Logo">
    <p><strong>NFDI4Biodiversity</strong></p>
    <p><a href="https://www.nfdi4biodiversity.org/en/services/#55a125d2-70c7-432a-91b4-2c2a810e833c " target="_blank" rel="noopener noreferrer">DMP Services for Biodiversity Projects</a></p> 
  </div>   
  <div class="service-tile">
    <img src="/images/nfdi4bioimage_logo.png" alt="NFDI4BIOIMAGE Logo">
    <p><strong>NFDI4BIOIMAGE</strong></p>
    <p><a href="https://nfdi4bioimage.de/en/services/rdmo/" target="_blank" rel="noopener noreferrer">DMP Services for Biological Imaging</a></p> 
  </div>
</div>

### Natural Sciences

<div class="service-grid">
  <div class="service-tile">
    <img src="/images/fairmat_logo.png" alt="FAIRmat Logo">
    <p><strong>FAIRmat</strong></p>
    <p><a href="https://www.fairmat-nfdi.eu/fairmat/resources-fairmat/dmp-support/dmp-overview" target="_blank" rel="noopener noreferrer">DMP Services for Physical Sciences</a></p> 
  </div> 
  <div class="service-tile">
    <img src="/images/mardi_logo.png" alt="MaRDI Logo">
    <p><strong>MaRDI</strong></p>
    <p><a href="https://rdmo.mardi4nfdi.de/" target="_blank" rel="noopener noreferrer">DMP Services for Mathematical Research Data</a></p> 
  </div>
  <div class="service-tile">
    <img src="\images\nfdi4chem_logo.png" alt="NFDI4Chem Logo">
    <p><strong>NFDI4Chem</strong></p>
    <p><a href="https://nfdi4chem.de/data-management-for-chemistry/" target="_blank" rel="noopener noreferrer">DMP Services for Chemistry</a></p>
  </div>
  <div class="service-tile">
    <img src="/images/nfdi4earth_logo.png" alt="NFDI4Earth Logo">
    <p><strong>NFDI4Earth</strong></p>
    <p><a href="https://notes.desy.de/s/1OKf1cvSU#" target="_blank" rel="noopener noreferrer">DMP Services for Sensor Based Projects</a></p> 
  </div>
</div>


<!-- OLD Markdown Table

| **Domain** | **Consortium** | **RDMO hosting** | **RDMO integration** | **DMP/SMP templates** | **Training & Outreach** |
|:---|:---|:---:|:---:|:---:|:---:|
| **Engineering Sciences** ||||||
|| NFDI4Datascience | ⚪ | ⚪ | 🟡 | ⚪ |
|| NFDI4Energy | <a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a> | ⚪ | ⚪ | ⚪ |
|| NFDI4Ing | <a href="https://rdmo.nfdi4ing.de/" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 | 🟡 | ⚪ | 
|| NFDI-MatWerk | ✔️ | ⚪ | ⚪ | ⚪ | 
|| <span style="color:#9ca3af;">NFDIxCS</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |
|**Humanities and Social Sciences**||||||
|| NFDI4Culture | <a href="https://rdmo.nfdi4culture.de/" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 | <a href="https://github.com/rdmorganiser/rdmo-catalog/tree/main/shared/NFDI4Culture" target="_blank" rel="noopener noreferrer">✅</a> | ⚪ |
|| NFDI4Memory | ✔️ | ⚪ | 🟡 | ⚪|
|| NFDI4Objects | ⚪ | ⚪ | 🟡 | ⚪ |
|| Text+ | ⚪ | ⚪ | <a href="https://github.com/rdmorganiser/rdmo-catalog/tree/main/shared/Text%2B" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 |
|| <span style="color:#9ca3af;">KonsortSWD</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |
|| <span style="color:#9ca3af;">BERD@NFDI</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |
| **Life Sciences** ||||||
|| FAIRagro | <a href="https://rdmo.fairagro.net/" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 | <a href="https://rdmo.fairagro.net//" target="_blank" rel="noopener noreferrer">✅</a> | <a href="https://github.com/fairagro/FAIRagro_DMP_Template" target="_blank" rel="noopener noreferrer">✅</a> |
|| NFDI4Biodiversity | ⚪ | <a href="https://github.com/rdmorganiser/rdmo-plugins-zenodo" target="_blank" rel="noopener noreferrer">✅</a> | ⚪| ⚪ |
|| NFDI4BIOIMAGE | <a href="https://rdmo.nfdi4bioimage.de/" target="_blank" rel="noopener noreferrer">✅</a> | ⚪ | ⚪ | ⚪ |
|| NFDI4Health | ✔️ | ⚪ | 🟡 | 🟡 | 
|| NFDI4Microbiota | ✔️ | ⚪ | ⚪ | ⚪|
|| <span style="color:#9ca3af;">DataPLANT</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | 
|| <span style="color:#9ca3af;">NFDI4Immuno</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | 
|| <span style="color:#9ca3af;">GHGA</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |
|**Natural Sciences**||||||
|| FAIRmat | <a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a> | ⚪ | ⚪ | ⚪ |
|| MaRDI | <a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a> | <a href="https://rdmo.nfdi4energy.org/" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 | ⚪ |
|| NFDI4Cat | ⚪ | ⚪ | 🟡 | 🟡 |
|| NFDI4Chem | <a href="https://rdmo.nfdi4chem.de/" target="_blank" rel="noopener noreferrer">✅</a> | 🟡 | 🟡 | <a href="https://zenodo.org/records/20529135" target="_blank" rel="noopener noreferrer">✅</a> |
|| NFDI4Earth | <a href="https://rdmo.nfdi4earth.de/" target="_blank" rel="noopener noreferrer">✅</a> | <a href="https://github.com/rdmorganiser/rdmo-plugins-sensorsearch" target="_blank" rel="noopener noreferrer">✅</a> | <a href="https://rdmo.nfdi4earth.de/" target="_blank" rel="noopener noreferrer">✅</a> | ⚪ |
|| <span style="color:#9ca3af;">DAPHNE4NFDI</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |
|| <span style="color:#9ca3af;">PUNCH4NFDI</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> | <span style="color:#9ca3af;">-</span> |

-->

