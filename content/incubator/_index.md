---
title: Incubator Projects
summary: Call for incubator projects and how to join
date: 2025-01-07
type: landing

sections:
  - block: markdown
    content:
      title: Incubator Projects
      subtitle: Set up your DMP/SMP service 
      text: |
        <div style="text-align:left;">
        
        DMP4NFDI supports consortia in providing Data and Software Management Plan (DMP/SMP) services to their community. For onboarding new consortia we hold a [regular call](#call) for incubator projects.  

        An incubator project is a short-term engagement (3–6 months) with a clearly defined goal. Typical focus areas include: 
                
         - **RDMO hosting**  

         - **DMP and SMP template development**  

         - **Training and community outreach support**  

         - **RDMO integration with other services**
        
        [-> Explore our current incubator projects](#incubators)
        
        </div>
    design:
      columns: '1'

  - block: markdown
    id: call
    content:
      title: Call for incubator projects
      subtitle: |
        <!-- We look forward to your application!

        **Deadline**: Dec 15, 2025
        -->
        Next call: 2nd Quarter of 2026
      text: |
        
        To propose an incubator project, please complete the short application template outlining your goals, team, and expected outcomes. 

        **Download the Template:** <a href="/files/DMP4NFDI-incubator-template-application.odt" target="_blank" rel="noopener">.odt</a>, <a href="/files/DMP4NFDI-incubator-template-application.docx" target="_blank" rel="noopener">.docx</a>, <a href="/files/DMP4NFDI-incubator-template-application.pdf" target="_blank" rel="noopener">.pdf</a>

        Do you already have ideas for an incubator? Please reach out in advance to discuss them: <a href="/contact/" target="_blank" rel="noopener">Contact us!</a>           
        
        Send your submissions (PDF) to **[dmp4nfdi@lists.nfdi.de](mailto:dmp4nfdi@lists.nfdi.de)**.
         
    design:
      columns: '2'

  - block: markdown
    id: incubators
    content:
      title: "Projects"
      text: |
        <p>We work with NFDI consortia to <b>develop and enhance DMP and SMP services</b> for their research communities. Browse our current and past incubator projects and filter by <b>service type</b> and <b>cycle</b> to learn more.</p>

        <!-- Filter bar -->
        <div id="usecase-filter" class="usecase-filter not-prose">

          <select id="f-service" aria-label="Service">
            <option value="">All Services</option>
            <option>RDMO Hosting</option>
            <option>RDMO Integration</option>            
            <option>Template Development</option>
            <option>Training & Outreach</option>
          </select>

          <select id="f-cycle" aria-label="Cycle">
            <option value="">All Cycles</option>
            <option>Initialisation phase</option>
            <option>Cycle 0</option>
            <!-- <option>Cycle 1</option> -->
          </select>

          <button id="usecase-clear" type="button">Clear</button>
          <span id="usecase-count" aria-live="polite"></span>
        </div>

        <!-- Use case cards grid -->
        <div class="usecase-card-grid">
        <div class="usecase-card-grid">
          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Cycle 0">
            <img src="/images/nfdi4microbiota_logo.png" alt="NFDI4Microbiota Logo">
            <h4>Cycle 0</h4>     
            <h5>Goal:</h5><p>NFDI4Microbiota will use RDMO to provide and continuously maintain a tailored DMP template for the microbiological research community. A dedicated test environment already supports current catalog development and evaluation, with the productive system scheduled for release by the end of 2025. Data stewards from the consortium's help desk will receive manager rights to offer first-level support and ensure wide user adoption.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Cycle 0">
            <img src="/images/nfdi4energy_logo.png" alt="NFDI4Energy Logo">
            <h4>Cycle 0</h4>       
            <h5>Goal:</h5><p>Establishing an RDMO environment tailored to the consortium’s needs. During the incubator project, a test client will be set up, followed shortly by a productive system to enable early evaluation within the community by utilising existing RDMO catalogs and templates, e.g. by NFDI4ING. User access will be managed through the NFDI-AAI login, providing federated authentication based on institutional accounts.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Cycle 0">
            <img src="/images/nfdi-matwerk_logo.png" alt="NFDI-MatWerk Logo">
            <h4>Cycle 0</h4>       
            <h5>Goal:</h5><p>Implementing an RDMO client to serve the consortium’s research data management activities. A pilot version will be launched for internal testing. A productive instance is foreseen after validation of the pilot.</p>
            <h5>Duration:</h5><p>September 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Cycle 0">
            <img src="/images/nfdi4bioimage_logo.png" alt="NFDI4BioImage Logo">
            <h4>Cycle 0</h4>       
            <h5>Goal:</h5><p>Setting up an RDMO client to explore integration with existing data workflows and to develop initial catalog structures. Create familiarity with the template system and build up Know-How to enable guidance and teaching of users. Integration with the NFDI-AAI Didmos login is planned to provide seamless and secure user authentication. </p>
            <h5>Duration:</h5><p>October 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Cycle 0">
            <img src="/images/nfdi4health_logo.png" alt="NFDI4Health Logo">
            <h4>Cycle 0</h4>        
            <h5>Goal:</h5><p>The goal is to set up a dedicated RDMO client for NFDI4Health, which will provide a Data Management Plan (DMP) service for the health research community. A test system will be set up in the first incubator project to facilitate the implementation, development and testing of the catalogue. Work on the catalogue will likely form part of another incubator project prior to migration to a productive RDMO system. The RDMO client will support authentication via the NFDI-AAI, enabling users to securely log in with their institutional credentials.</p>
            <h5>Duration:</h5><p>October 2025 - December 2025</p>
          </div>  

          <div class="usecase-card" data-service="Template Development" data-cycle="Cycle 0">
            <img src="/images/nfdi4culture_logo.png" alt="NFDI4Culture Logo">
            <h4>Cycle 0</h4>        
            <h5>Goal:</h5><p>The aim of this incubator project was to help cultural heritage institutions find the right software solution for organising and presenting their artefacts. To this end, we have developed a decision-making aid comprising two complementary DMP templates. One template is designed from the user's perspective (i.e. collections) to help clarify their requirements and assist in selecting suitable software for collection management. The other template enables collection management products to be described in detail from the provider's perspective, making them comparable for users. This facilitates a matching between software products and users.</p>
            <h5>Duration:</h5><p>December 2024 - September 2025</p>          
          </div>

          <div class="usecase-card" data-service="Template Development" data-cycle="Cycle 0">
            <img src="/images/nfdi4memory_logo.png" alt="NFDI4Memory Logo">
            <h4>Cycle 0</h4>        
            <h5>Goal:</h5><p>NFDI4Memory is developing a discipline-specific DMP template to support the historical research community in their application process. The questionnaire is being continually refined in close collaboration with the community. In this incubator project, the template is developed based on the existing NFDI DMP Template Framework, while adapting and extending results from the community. The project also includes the integration of the new template into the NFDI4Memory RDMO client.</p>
            <h5>Duration:</h5><p>July 2025 - Dec 2025</p>
          </div>      
          
          <div class="usecase-card" data-service="Template Development" data-cycle="Cycle 0">
            <img src="/images/nfdi4objects_nfdi4culture_logo.png" alt="NFDI4Objects and NFDI4Culture Logo">
            <h4>Cycle 0</h4>        
            <h5>Goal:</h5><p>The product of this incubator project is a DMP template to help museums and collections implement the FAIR principles. The template provides an accessible option for assessing the FAIR quality of collection data. The questions are categorised according to four typical processing phases: digitisation, documentation, publication and storage/archiving. Most of the questions within these categories are assigned to indicators from the FAIR Data Maturity Model. The template includes answer options, some recommendations for action, help texts, notes and links to useful materials. The aim is to create a template that illustrates the different levels of FAIR implementation, while also providing institutions with a roadmap to improve the quality of their data.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>

          <div class="usecase-card" data-service="Template Development" data-cycle="Cycle 0">
            <img src="/images/fairagro_logo.png" alt="FAIRagro Logo">
            <h4>Cycle 0</h4>       
            <h5>Goal:</h5><p>FAIRagro customises DMP templates of funding agencies based on the needs of the agrosystem community for efficient and straight forward usage. The close cooperation with DMP4NFDI will ensure the compatibility and reusability of the developments. During the incubator project, a customised DMP template for the agrosystem sciences will be created and made available, based on community feedback (e.g. through workshops) and aligned with the existing NFDI DMP Template Framework.</p>
            <h5>Duration:</h5><p>July 2025 - Dec 2025</p>
          </div>
          
          <div class="usecase-card" data-service="Template Development" data-cycle="Cycle 0">
            <img src="/images/text+_logo.png" alt="Text+ Logo">
            <h4>Cycle 0</h4>     
            <h5>Goal:</h5><p>The institutions involved in Text+ advise researchers on all steps of the systematic organisation of their research data. Thus, Text+ offers its community a question catalogue for structured planning, which is provided by the eResearch Alliance of the University of Göttingen (access via GRO.Plan, access with Academic ID). Based on the RDMO standard catalogue and the question catalogue of the Max Weber Foundation, the Text+ catalogue was adapted accordingly in collaboration with participants of the consortium, based on the removal of irrelevant questions, the enrichment with subject-specific examples and the integration of suitable plugins. In this incubator project, the compatibility between the Text+ catalogue and the NFDI question catalogue will be ensured, specifying and adjusting the places where the Text+ catalogue is still too generic.</p>
            <h5>Duration:</h5><p>September 2025 - Dec 2025</p>
          </div>          
         
          <div class="usecase-card" data-service="Training & Outreach" data-cycle="Cycle 0">
            <img src="/images/nfdi4chem_logo.png" alt="NFDI4Chem Logo">
            <h4>Cycle 0</h4>        
            <h5>Goal:</h5><p>NFDI4Chem has a productive RDMO client with a DMP template that has been optimised for the special requirements of chemists and can be used by everyone. The consortium is organising training activities for its community to showcase the use of RDMO for creating and managing DMPs based on the developed template. In this incubator project, DMP4NFDI supports the consortium by providing available Open Educational Resources (OERs) and other training materials, as well as a checklist for data stewards based on the Train-the-Trainer concept for DMPs and RDMO. This checklist will highlight key considerations for delivering introductory workshops on DMPs and the use of RDMO.</p>
            <h5>Duration:</h5><p>July 2025 - December 2025</p>
          </div>              

          <div class="usecase-card" data-service="RDMO Integration" data-cycle="Cycle 0">
            <img src="/images/mardi_logo.png" alt="MaRDI Logo">
            <h4>Cycle 0</h4>      
            <h5>Goal:</h5><p>MaRDI offers its MaRDMO service to all researchers using mathematical methods in their research, regardless of discipline background. In this incubator project, the MaRDMO plugin collection for RDMO is further enhanced to include instrument data bases. The plugin will be able to query different instrument databases across NFDI consortia, and to store instrument metadata inside the MaRDMO template.</p>
            <h5>Duration:</h5><p>September 2025 - December 2025</p>
            <h5>Results:</h5><p><a href="https://github.com/rdmorganiser/rdmo-plugins-generic-search" target="_blank" rel="noopener noreferrer">Generic Search RDMO Plugin</a></p>            
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Initialisation phase">
            <img src="/images/nfdi4ing_logo.png" alt="NFDI4Ing Logo">
            <h4>Initialisation phase</h4>     
            <h5>Goal:</h5><p>Use the NFDI4ING RDMO service as the reference implementation for RDMO hosting in DMP4NFDI and as a foundation for onboarding further clients to the DMP4NFDI service.</p>
            <h5>Duration:</h5><p>June 2024 - September 2025</p>
            <h5>Results:</h5><p><a href="https://rdmo.nfdi4ing.de" target="_blank" rel="noopener noreferrer">NFDI4Ing RDMO Client</a></p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Initialisation phase">
            <img src="/images/nfdi4chem_logo.png" alt="NFDI4Chem Logo">
            <h4>Initialisation phase</h4>     
            <h5>Goal:</h5><p>Host and operate the RDMO client for the NFDI4Chem consortium within the DMP4NFDI service and bring it into productive operation.</p>
            <h5>Duration:</h5><p>June 2024 - September 2025</p>
            <h5>Results:</h5><p><a href="https://rdmo.nfdi4chem.de" target="_blank" rel="noopener noreferrer">NFDI4Chem RDMO Client</a></p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting" data-cycle="Initialisation phase">
            <img src="/images/fairagro_logo.png" alt="FAIRagro Logo">
            <h4>Initialisation phase</h4>     
            <h5>Goal:</h5><p>Set up an RDMO client for the FAIRagro consortium that is ready to provide DMP templates to the community.</p>
            <h5>Duration:</h5><p>December 2024 - May 2025</p>
            <h5>Results:</h5><p><a href="https://rdmo.fairagro.net/" target="_blank" rel="noopener noreferrer">FAIRagro RDMO Client</a></p>
          </div>          

          <div class="usecase-card" data-service="RDMO Integration" data-cycle="Initialisation phase">
            <img src="/images/nfdi4biodiversity_logo.png" alt="NFDI4Biodiversity Logo">
            <h4>Initialisation phase</h4>     
            <h5>Goal:</h5><p>Develop an RDMO plugin that connects the DMP tool to Zenodo, enabling users to publish DMPs as PDFs directly from RDMO.</p>
            <h5>Duration:</h5><p>June 2024 - June 2025</p>
            <h5>Results:</h5><p><a href="https://github.com/rdmorganiser/rdmo-plugins-zenodo" target="_blank" rel="noopener noreferrer">RDMO Zenodo Plugin</a></p>
          </div>        

          <div class="usecase-card" data-service="RDMO Hosting, RDMO Integration" data-cycle="Initialisation phase">
            <img src="/images/nfdi4culture_logo.png" alt="NFDI4Culture Logo">
            <h4>Initialisation phase</h4>     
            <h5>Goal:</h5><p>Host an RDMO tenant for the NFDI4Culture consortium and integrate the consortium’s community AAI as the login mechanism for authentication and authorization. RDMO user permissions should be manageable within the NFDI4Culture community AAI. The resulting service will support researchers, cultural professionals, and cultural heritage institutions.</p>
            <h5>Duration:</h5><p>June 2025 - June 2025</p>
            <h5>Results:</h5><p><a href="https://rdmo.nfdi4culture.de" target="_blank" rel="noopener noreferrer">NFDI4Culture RDMO Client</a></p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting, RDMO Integration" data-cycle="Initialisation phase">
            <img src="/images/mardi_logo.png" alt="MaRDI Logo">
            <h4>Initialisation phase</h4>        
            <h5>Goal:</h5><p>Set up an RDMO client for the MaRDI consortium and integrate the existing MaRDMO plugin, which connects RDMO with the MaRDI knowledge graph infrastructure.</p>
            <h5>Duration:</h5><p>September 2024 - June 2025</p>
            <h5>Results:</h5><p><a href="https://rdmo.mardi4nfdi.de" target="_blank" rel="noopener noreferrer">MaRDI RDMO Client</a></p>
          </div>

          <div class="usecase-card" data-service="RDMO Hosting, Template Development, RDMO Integration" data-cycle="Initialisation phase">
            <img src="/images/nfdi4earth_logo.png" alt="NFDI4Earth Logo">
            <h4>Initialisation phase</h4>
            <h5>Goal:</h5><p>Set up an RDMO test client for the NFDI4Earth consortium to support the conversion of a community-specific DMP template (MOSES project) into an RDMO catalog. Additionally, support the consortium in developing a plugin that allows users to search sensor databases from within RDMO and import retrieved metadata directly into the DMP.</p>
            <h5>Duration:</h5><p>June 2024 - June 2025</p>
            <!--<h5>Results:</h5><p>MOSES catalog</p>-->
          </div>        

        </div>

        <!-- minimal CSS for filters -->
        <!--
        <style>
          .usecase-filter { display:flex; gap:.5rem; align-items:center; margin:1rem 0 1.5rem }
          .usecase-filter select, .usecase-filter button { color: black; padding:.4rem .6rem; border:1px solid #e3e3e3; border-radius:.5rem; background:#fff; cursor:pointer }
          .usecase-card-grid { display:grid; gap:1rem; grid-template-columns:repeat(auto-fit, minmax(400px, 1fr)); }
          .usecase-card { padding:1rem; border:1px solid #e3e3e3; border-radius:.5rem; background:#fff; text-align:left; }
          .usecase-card img, .usecase-card h2 { display: block; margin: 0 auto; text-align: center; }
          .usecase-card p { text-align: left; margin-top: .5rem; color: black; }
          .usecase-card h1, .usecase-card h2, .usecase-card h3, .usecase-card h4, .usecase-card h5, .usecase-card h6 {  color: black; }
          .usecase-card img { width:auto; height:100px; margin-bottom: 1.5rem; }
          .usecase-card-grid .usecase-card[hidden]{ display:none !important }
          #usecase-count { margin-left:auto; font-size:.9rem; opacity:.8 }
        </style>
        -->

        <style>
        /* ---------- Filter Bar ---------- */
        .usecase-filter {
          display: flex;
          gap: .5rem;
          align-items: center;
          margin: 1rem 0 1.5rem;
        }

        .usecase-filter select,
        .usecase-filter button {
          color: black;
          padding: .4rem .6rem;
          border: 1px solid #e3e3e3;
          border-radius: .5rem;
          background: #fff;
          cursor: pointer;
        }

        /* ---------- Use Case Grid ---------- */
        .usecase-card-grid {
          display: grid;
          gap: 1rem;
          grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
        }

        /* ---------- Use Case Card ---------- */
        .usecase-card {
          padding: 1rem;
          border: 1px solid #e3e3e3;
          border-radius: .5rem;
          background: #fff;   /* white background */
          color: black;       /* default text color */
          text-align: left;

          /* Optional: override theme CSS variables */
          --tw-prose-body: black;
          --tw-prose-headings: black;
          --tw-prose-links: #0abaf0; /* blue links */
        }

        /* ---------- Card Headings ---------- */
        .usecase-card h4 {
          display: block;
          margin: 0 auto 1rem;
          text-align: right;  /* centered under image */
          color: #45546a;
        }

        .usecase-card h5 {
          margin: 0.8rem 0 0.3rem;  /* spacing before/after */
          color: black;
          font-weight: bold;
          text-align: left;          /* left-aligned for labels */
          font-size: 0.95rem;        /* slightly smaller than h2 */
        }

        /* ---------- Paragraphs ---------- */
        .usecase-card p {
          margin-top: .5rem;
          color: black;
          text-align: left;
        }

        /* ---------- Links inside cards ---------- */
        .usecase-card a {
          color: #0abaf0;          /* visible blue links */
          text-decoration: underline;
        }

        .usecase-card a:hover {
          color: #45546b;          /* darker blue on hover */
          text-decoration: none;
        }

        /* ---------- Images ---------- */
        .usecase-card img {
          display: block;
          margin: 0 auto 1.5rem;
          width: auto;
          height: auto;
        }

        /* ---------- Hidden Cards ---------- */
        .usecase-card-grid .usecase-card[hidden] {
          display: none !important;
        }

        /* ---------- Counter ---------- */
        #usecase-count {
          margin-left: auto;
          font-size: .9rem;
          opacity: .8;
        }

        /* ---------- Auto-generated Service Labels ---------- */
        .usecase-service-labels {
          display: flex;
          flex-wrap: wrap;
          gap: .4rem;
          margin-bottom: .8rem;
        }

        .usecase-label {
          display: inline-block;
          background: #eef6ff;
          border: 1px solid #c7daf7;
          padding: 2px 6px;
          border-radius: 4px;
          font-size: .75rem;
          font-weight: 600;
          color: #003d77;
        }
        </style>



        <!-- filtering script -->
        <script>
          (function(){
            const q = s => document.querySelector(s);
            const qa = s => Array.from(document.querySelectorAll(s));
            const cards = qa('.usecase-card-grid .usecase-card');
            const serviceFilter = q('#f-service');
            const cycleFilter = q('#f-cycle')
            const clearBtn = q('#usecase-clear');
            const counter = q('#usecase-count');

            function apply(){
              let visible = 0;
              const serviceVal = serviceFilter.value.trim().toLowerCase();
              const cycleVal   = cycleFilter.value.trim().toLowerCase();


              cards.forEach(card => {
                // Split comma-separated values and trim whitespace
                const services = card.dataset.service.toLowerCase()
                  .split(',')
                  .map(s => s.trim());

                const cycles = card.dataset.cycle.toLowerCase()
                  .split(',')
                  .map(s => s.trim());

                // Check if selected filter value matches any of the values in the card
                const serviceOk = !serviceVal || services.includes(serviceVal);
                const cycleOk   = !cycleVal   || cycles.includes(cycleVal);

                const show = serviceOk && cycleOk;
                card.hidden = !show;
                if(show) visible++;
              });
              counter.textContent = `${visible} shown / ${cards.length} total`;
            }

            serviceFilter.addEventListener('input', apply);
            cycleFilter.addEventListener('input', apply);
            clearBtn.addEventListener('click', ()=>{
              serviceFilter.value = '';
              cycleFilter.value = '';
              apply();
            });

            apply();
          })();
        </script>

        <script>
          // ---------- AUTO-GENERATE LABELS FROM data-service ----------
          document.addEventListener("DOMContentLoaded", () => {
            const colorMap = {
              "RDMO Hosting": "#0abaf0",
              "Template Development": "#ffb74d",
              "Training & Outreach": "#4caf50",
              "RDMO Integration": "#f06292"
            };
            document.querySelectorAll(".usecase-card").forEach(card => {
              const raw = card.dataset.service || "";
              const services = raw.split(",").map(s => s.trim()).filter(Boolean);
        
              if (!services.length) return;
        
              // Create wrapper
              const box = document.createElement("div");
              box.className = "usecase-service-labels";
        
              // Create label elements
              services.forEach(s => {
                const label = document.createElement("span");
                label.className = "usecase-label";
                label.textContent = s;
                // Assign color from map, fallback to default
                label.style.backgroundColor = colorMap[s] || "#eef6ff";
                label.style.color = "#000000"; // black text for contrast                
                box.appendChild(label);
              });
        
              // Insert labels ABOVE headings
              const headings = card.querySelector("h1, h2, h3, h4, h5, h6");
              if (headings) {
                headings.insertAdjacentElement("beforebegin", box);
              } else {
                card.prepend(box);
              }
            });
          });
        </script>
        
    design:
      spacing:
        padding: ["pt-4", "pb-4"] 
  
---