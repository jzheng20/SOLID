---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: 
      subtitle: ''
      text:
    design:
      columns: '2'
      background:
        image: 
          filename: ubc_vancouver_upscaled_4k.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: over
          text_color_light: true
      spacing:
        padding: ['150px', '0', '150px', '0']
      css_class: narrow-hero

      
  - block: markdown
    id: home
    content:
      title: |
          <strong>Now Solving:</strong>  Global Optimal AI
      subtitle: ''
      text: |
        <br>
        <div class="text-center">
         <p class="text-base font-light">We focus on <strong class="text-2xl font-bold">S</strong>calable <strong class="text-2xl font-bold">O</strong>ptimization, <strong class="text-2xl font-bold">L</strong>earning, and <strong class="text-2xl font-bold">I</strong>ntelligent <strong class="text-2xl font-bold">D</strong>ecision-making (SOLID).</p>
         <p class="text-xs font-light" style="font-size: 18px;"><strong>SOLID Lab</strong> is embedded in the
         <a href="https://chbe.ubc.ca" class="text-blue-600 underline hover:text-blue-800" target="_blank">Department of Chemical and Biological Engineering</a> at <a href="https://www.ubc.ca/" class="text-blue-600 underline hover:text-blue-800" target="_blank">The University of Britis Columbia</a>.<br></p>
         <br><br>
         <a href="/#research" class="btn btn-primary">Learn Us</a>
         <a href="/#positions" class="btn btn-outline">Join Us →</a>
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'   
      spacing:
        padding: ['80px', '0', '80px', '0']

  
  

  - block: markdown
    id: news
    content:
      title: <hr class="section-divider">  Lab News 
      text: |
        <div style="display: flex; align-items: center; gap: 2rem;">
        <div> <img src="/uploads/logo2.png" style="width: 10rem; height: 10rem;" class="rounded-full object-cover"></div>
        <div class="vertical-line" style="height: 600px;"></div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8"> 


        <!-- News Card 0 -->
        <div class="news-card rounded-lg border-l-4 border-green-500 shadow p-6 bg-white" style="background-color:#eff6ff;">
        <p style="font-style: italic; font-weight: 600; color: #1e40af;">Journal Paper</p><img src="https://img.shields.io/badge/Top%2010%25%20Most%20Downloaded-lightblue" alt="Top 10% Most Downloaded" style="display:inline; margin-left: 8px;">

        <p style="border-left: 8px solid #dc2626; padding-left: 0.5rem;” class="text-base"> <strong class="italic underline">  Towards Self-Driving Processes: A Deep Reinforcement Learning Approach to Control</strong>
        </p>
        <p>Steven P. Spielberg, Aditya Tulsyan, <em>Nathan P. Lawrence</em>, Philip D. Loewen, R. Bhushan Gopaluni</p>

        <p><em>AIChE Journal.</em> 2019</p>
        <a href="/#research" class="btn btn-primary">PDF</a>
        <a href="/#research" class="btn btn-light">CODE</a>
        <a href="/#research" class="btn btn-info">CITE</a>
        </div>


    
         <!-- News Card 1 -->
         <a href="https://nips.cc/" target="_blank" style="text-decoration: none; color: inherit;">
          <div class="news-card rounded-lg border-l-4 border-green-500 shadow p-6 bg-white" style="background-color:#eff6ff;">
            <p style="border-left: 8px solid #dc2626; padding-left: 0.5rem;” class="text-base"> <strong class="italic underline">  Two Papers Accepted at <span class="text-indigo-600">NeurIPS 2025</span></strong>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| 12 May 2025 </span>
            <p><em>Congratulations to our team on getting two papers accepted to NeurIPS 2025! Topics include global optimization and decision transformers.</em></p>
            </p>
          </div>
         </a>

         <!-- News Card 1 -->
         <a href="https://nips.cc/" target="_blank" style="text-decoration: none; color: inherit;">
          <div class="news-card rounded-lg border-l-4 border-green-500 shadow p-6 bg-white" style="background-color:#eff6ff;">
            <p style="border-left: 8px solid #facc15; padding-left: 0.5rem;” class="text-base"> <strong class="italic underline">  Two Papers Accepted at <span class="text-indigo-600">NeurIPS 2025</span></strong>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| 12 May 2025 </span>
            <p><em>Congratulations to our team on getting two papers accepted to NeurIPS 2025! Topics include global optimization and decision transformers.</em></p>
            </p>
          </div>
         </a>

         <!-- News Card 1 -->
         <a href="https://nips.cc/" target="_blank" style="text-decoration: none; color: inherit;">
          <div class="news-card rounded-lg border-l-4 border-green-500 shadow p-6 bg-white" style="background-color:#eff6ff;">
            <p style="border-left: 8px solid #dc2626; padding-left: 0.5rem;” class="text-base"> <strong class="italic underline">  Two Papers Accepted at <span class="text-indigo-600">NeurIPS 2025</span></strong>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| 12 May 2025 </span>
            <p><em>Congratulations to our team on getting two papers accepted to NeurIPS 2025! Topics include global optimization and decision transformers.</em></p>
            </p>
          </div>
         </a>

         <!-- News Card 1 -->
         <a href="https://nips.cc/" target="_blank" style="text-decoration: none; color: inherit;">
          <div class="news-card rounded-lg border-l-4 border-green-500 shadow p-6 bg-white" style="background-color:#eff6ff;">
            <p style="border-left: 8px solid #22c55e; padding-left: 0.5rem;” class="text-base"> <strong class="italic underline">  Two Papers Accepted at <span class="text-indigo-600">NeurIPS 2025</span></strong>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| 12 May 2025 </span>
            <p><em>Congratulations to our team on getting two papers accepted to NeurIPS 2025! Topics include global optimization and decision transformers.</em></p>
            </p>
          </div>
         </a>
     

        </div>
        </div>

    design:
      view: card                    
      columns: '1' 


    
 

   
  
  
 

  - block: markdown
    id: research
    content:
      title:  Research
      text: |
         <p class="text-xl font-light mt-2">SOLID Lab focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse decision-making paradigms such as <em>machine learning</em>, <em>data analysis  and estimation</em> as well as <em>stochastic optimization</em>, <em>optimal control</em>, and <em>complex networks</em>.  Our algorithms combine mathematical techniques and emerging high-performance computing hardware (e.g., multi-core CPUs, GPUs, and computing clusters) to achieve computational scalability. The goal is to make these developments accessible to academic and industrial users by implementing algorithms on easy-to-use and extensible software libraries.</p>
         <p class="text-xl font-light mt-2"> Furthermore, We have applied the algorithms and tools to help collaborators address engineering and scientific questions that arise in diverse application 
            domainsincluding conflict resolution in energy system design, robust control of crystallization systems, predictive control of wind turbines, power management in 
            large networks, estimation of microbial growth models, and image classification for contaminant detection.</p>
         <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8">

          <!-- Left: Image Panel -->
          <div class="bg-gray-100 rounded-lg p-4 text-center shadow">
            <!--<h3 class="text-xl font-bold text-blue-700 mb-4">Machine Learning</h3>-->
            <img src="/uploads/Overview_yankai_v3.jpg" alt="Overview Research" class="mx-auto w-full max-w-xs rounded">
          </div>
          <h3 class="text-xl font-bold text-blue-700 mb-4">Selected Publications</h3>
          <!-- Right: Publication Card -->
          
          <div style="display: flex; align-items: center; gap: 2rem;">
          <div> <img src="/uploads/logo2.png" style="width: 10rem; height: 10rem;" class="rounded-full object-cover"></div>
          <div class="vertical-line" style="height: 150px;"></div>
          <div class="rounded-lg border-l-4 border-blue-500 shadow p-6 bg-white">
          <div>    <h3 class="text-xl font-bold">An example journal article</h3>
               <p class="text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.</p> </div>
          </div>
          </div>

          <div class="rounded-lg border-l-4 border-blue-500 shadow p-6 bg-white">
          <div style="display: flex; align-items: center; gap: 2rem;">
          <div> <img src="/uploads/logo2.png" style="width: 10rem; height: 10rem;" class="rounded-full object-cover"></div>
          <div class="vertical-line" style="height: 150px;"></div>
          <div>    <h3 class="text-xl font-bold">An example journal article</h3>
               <p class="text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.</p> </div>
          </div>
          </div>

         </div>

  - block: collection
    id: publications
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: table
      columns: '1' 

 

 
    
    

   

  - block: collection
    id: publications
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
 

 
  - block: markdown
    id: positions
    content: 
      title: Positions
      text: |
        <!-- 白色背景是默认的，无需加 -->

          <p class="text-2xl font-bold"><strong>We are actively seeking future postdoctoral researchers, graduate students, visiting students, and undergraduate students.</strong></p>

          <p class="text-2xl font-light" style="text-indent: 2em;">
             ➤ Please <strong>send your CV to</strong> <u>yankai.cao@ubc.ca</u>, and <strong>provide the following information:</strong> degree program and university, graduation year, GPA, class rank, English proficiency test score, desired start date, research summary, and future research plans (for postdocs). 
          </p>

          <p class="text-2xl font-light" style="text-indent: 2em;">
            ➤ Please apply through <a href="https://www.grad.ubc.ca/prospective-students/application-admission" target="_blank" class="text-decoration: none; color: inherit;"><u>UBC Graduate School</u></a>.
          </p>
 

          <a href="/#positions" class="btn btn-outline">→ See Funding Opportunities →</a>

    
          <div class="rounded-xl shadow p-6 max-w-4xl mx-auto" style="background-color: #f3f4f6;"> <!-- 灰色卡片 -->
          <div class="bg-gray-100 rounded-xl shadow p-6 space-y-4"> 
          <p class="border-left: 8px solid #dc2626; padding-left: 0.5rem;text-3xl font-bold" style="font-family:Times New Roman, serif;">
            <strong>To Ph.D./ Master Candidates:</strong>
          </p>

          <p class="text-2xl font-light italic" style="font-family:Times New Roman, serif;">
            Ideal candidates will have a strong background in process modeling, control, optimization, and excellent communication skills. Students with a major in Control Engineering, Chemical Engineering, Automation Engineering, Systems Engineering, Industrial Engineering, Computer Science or Applied Mathematics are preferred.
          </p>
          </div>
          </div>

 
 
 


  - block: slider
    id: gallery
    content:
      title: Gallery
      slides:
      - title:  
        content: 🎉🎓 Celebrate Jingyi’s Graduation (2025)
        align: left
        background:
          image:
            filename: WechatIMG208-scaled.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#666'
          background-size: contain
        link: 
          text: See Full Gallery
          url: ../gallery/
      - title:  
        content: 🔥 Group BBQ (2023)
        align: right
        background:
          image:
            filename: picture3-e1745732324801.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
          background-size: contain
        link: 
          text: See Full Gallery
          url: ../gallery/
      - title:  
        content: 🍽️ Group Dinner (2022)
        align: left
        background:
          image:
            filename: picture2-e1745732281446.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
          background-size: contain
        link: 
          text: See Full Gallery
          url: ../gallery/
        #link:
         # icon: 
          #icon_pack: 
          #text: See Full Gallery
          #url: ../gallery/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      slide_weight: '700px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 100
      fit: contain
  
  - block: contact
    content:
      title: Contact
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: test@example.org
      phone: 888 888 88 88
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'
 
---
