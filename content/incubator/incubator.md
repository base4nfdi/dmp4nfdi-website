---
title: Incubator Projects
summary: Call for incubator projects and how to join
date: 2025-01-07
type: landing

sections:
  - block: markdown
    content:
      title: Incubator Projects
      subtitle: Set up your DMP service 
      text: |
        <div style="text-align:left;">
        
        DMP4NFDI supports consortia in providing a DMP service to their community. For onboarding new consortia we hold a [regular call](#call) for incubator projects.  

        An incubator project is a short-term engagement (3–6 months) with a clearly defined goal. Typical focus areas include: 
                
         - **RDMO hosting**  

         - **DMP template development**  

         - **Training and community outreach support**  

         - **Integration with other consortium services via plugins**
        
        </div>
    design:
      columns: '1'

  - block: markdown
    id: call
    content:
      title: Next call for incubators
      subtitle: Nov 2025 
      text: |
        Our first call for incubators opens on **Nov 17, 2025**. We will publish a planning template once the call begins.

        Do you already have ideas for an incubator? Please reach out in advance to discuss them: [Contact us](/contact/)!
        
        Send your submissions (PDF) to **[dmp4nfdi@lists.nfdi.de](mailto:dmp4nfdi@lists.nfdi.de)**.  
        
        **Deadline:** Dec 2, 2025.  
    design:
      columns: '2'

  - block: markdown
    content:
      title: "Current incubator projects"
      text: |
        <p>Explore our current incubator projects below. You can filter by service type.</p>

        <!-- Filter bar -->
        <div id="usecase-filter" class="usecase-filter not-prose">

          <select id="f-service" aria-label="Service">
            <option value="">All Services</option>
            <option>RDMO Hosting</option>
            <option>Template Development</option>
            <option>Training & Outreach</option>
            <option>RDMO Integration</option>
          </select>

          <button id="usecase-clear" type="button">Clear</button>
          <span id="usecase-count" aria-live="polite"></span>
        </div>

        <!-- Use case cards grid -->
        <div class="usecase-card-grid">
        <div class="usecase-card-grid">
          <div class="usecase-card" data-service="RDMO Hosting">
            <img src="/images/nfdi4microbiota_logo.png" alt="NFDI4Microbiota Logo">
            <h2>RDMO Hosting</h2>
            <h5>Goal:</h5><p>NFDI4Microbiota will use RDMO to provide and continuously maintain a tailored DMP template for the microbiological research community. A dedicated test environment already supports current catalog development and evaluation, with the productive system scheduled for release by the end of 2025. Data stewards from the consortium's help desk will receive manager rights to offer first-level support and ensure wide user adoption.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting">
            <img src="/images/nfdi4energy_logo.png" alt="NFDI4Energy Logo">
            <h2>RDMO Hosting</h2>
            <h5>Goal:</h5><p>Establishing an RDMO environment tailored to the consortium’s needs. During the incubator project, a test client will be set up, followed shortly by a productive system to enable early evaluation within the community by utilising existing RDMO catalogs and templates, e.g. by NFDI4ING. User access will be managed through the NFDI-AAI login, providing federated authentication based on institutional accounts.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting">
            <img src="/images/nfdi-matwerk_logo.png" alt="NFDI-MatWerk Logo">
            <h2>RDMO Hosting</h2>
            <h5>Goal:</h5><p>Implementing an RDMO client to serve the consortium’s research data management activities. A pilot version will be launched for internal testing. A productive instance is foreseen after validation of the pilot.</p>
            <h5>Duration:</h5><p>September 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting">
            <img src="/images/nfdi4bioimage_logo.png" alt="NFDI4BioImage Logo">
            <h2>RDMO Hosting</h2>
            <h5>Goal:</h5><p>Setting up an RDMO client to explore integration with existing data workflows and to develop initial catalog structures. Create familiarity with the template system and build up Know-How to enable guidance and teaching of users. Integration with the NFDI-AAI Didmos login is planned to provide seamless and secure user authentication. </p>
            <h5>Duration:</h5><p>October 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting">
            <img src="/images/nfdi4health_logo.png" alt="NFDI4Health Logo">
            <h2>RDMO Hosting</h2>
            <h5>Goal:</h5><p>The goal is to set up a dedicated RDMO client for NFDI4Health, which will provide a Data Management Plan (DMP) service for the health research community. A test system will be set up in the first incubator project to facilitate the implementation, development and testing of the catalogue. Work on the catalogue will likely form part of another incubator project prior to migration to a productive RDMO system. The RDMO client will support authentication via the NFDI-AAI, enabling users to securely log in with their institutional credentials.</p>
            <h5>Duration:</h5><p>October 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Integration">
            <img src="/images/mardi_logo.png" alt="MaRDI Logo">
            <h2>RDMO Integration</h2>
            <h5>Goal:</h5><p>MaRDI offers its MaRDMO service to all researchers using mathematical methods in their research, regardless of discipline background. In this incubator project, the MaRDMO plugin collection for RDMO is further enhanced to include instrument data bases. The plugin will be able to query different instrument databases across NFDI consortia, and to store instrument metadata inside the MaRDMO template.</p>
            <h5>Duration:</h5><p>September 2025 - December 2025</p>
          </div>
          
          <div class="usecase-card" data-service="Training & Outreach">
            <img src="/images/nfdi4chem_logo.png" alt="NFDI4Chem Logo">
            <h2>Training & Outreach</h2>
            <h5>Goal:</h5><p>NFDI4Chem has a productive RDMO client with a DMP template that has been optimised for the special requirements of chemists and can be used by everyone. The consortium is organising training activities for its community to showcase the use of RDMO for creating and managing DMPs based on the developed template. In this incubator project, DMP4NFDI supports the consortium by providing available Open Educational Resources (OERs) and other training materials, as well as a checklist for data stewards based on the Train-the-Trainer concept for DMPs and RDMO. This checklist will highlight key considerations for delivering introductory workshops on DMPs and the use of RDMO.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>              

        </div>

        <!-- minimal CSS for filters -->
        <style>
          .usecase-filter { display:flex; gap:.5rem; align-items:center; margin:1rem 0 1.5rem }
          .usecase-filter select, .usecase-filter button { padding:.4rem .6rem; border:1px solid #e3e3e3; border-radius:.5rem; background:#fff; cursor:pointer }
          .usecase-card-grid { display:grid; gap:1rem; grid-template-columns:repeat(auto-fit, minmax(400px, 1fr)); }
          .usecase-card { padding:1rem; border:1px solid #e3e3e3; border-radius:.5rem; background:#fff; text-align:left; }
          .usecase-card img, .usecase-card h2 { display: block; margin: 0 auto; text-align: center; }
          .usecase-card p { text-align: left; margin-top: .5rem; }
          .usecase-card img { width:auto; height:100px; margin-bottom: 1.5rem; }
          .usecase-card-grid .usecase-card[hidden]{ display:none !important }
          #usecase-count { margin-left:auto; font-size:.9rem; opacity:.8 }
        </style>

        <!-- filtering script -->
        <script>
          (function(){
            const q = s => document.querySelector(s);
            const qa = s => Array.from(document.querySelectorAll(s));
            const cards = qa('.usecase-card-grid .usecase-card');
            const serviceFilter = q('#f-service');
            const clearBtn = q('#usecase-clear');
            const counter = q('#usecase-count');

            function apply(){
              let visible = 0;
              const val = serviceFilter.value.trim().toLowerCase();
              cards.forEach(card=>{
                const ok = !val || card.dataset.service.toLowerCase() === val;
                card.hidden = !ok;
                if(ok) visible++;
              });
              counter.textContent = visible + ' shown / ' + cards.length + ' total';
            }

            serviceFilter.addEventListener('input', apply);
            clearBtn.addEventListener('click', ()=>{
              serviceFilter.value = '';
              apply();
            });

            apply();
          })();
        </script>

    design:
      spacing:
        padding: ["pt-4", "pb-4"]
  
---