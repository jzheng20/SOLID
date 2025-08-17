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
      title: <strong>Now Solving:</strong>  Global Optimal AI
      subtitle: ''
      text: |
        <div style="display: flex; align-items: center; gap: 2rem;">
        <div class="text-center" style="max-width: 600px;">
         <h2>We focus on <strong class="text-2xl font-bold">S</strong>calable <strong class="text-2xl font-bold">O</strong>ptimization, <strong class="text-2xl font-bold">L</strong>earning, and <strong class="text-2xl font-bold">I</strong>ntelligent <strong class="text-2xl font-bold">D</strong>ecision-making (SOLID).</h2>
         <br>
         <p class="text-xs font-light" style="font-size: 18px;"><strong>SOLID Lab</strong> is embedded in the
         <a href="https://chbe.ubc.ca" class="custom-link" target="_blank"><em>  Department of Chemical and Biological Engineering </em> </a> at <a href="https://www.ubc.ca/" class="custom-link" target="_blank"> <em>  The University of British Columbia </em> </a>.<br></p>
         <br><br>
         <a href="/#research" class="btn btn-primary">Learn Us</a>
         <a href="/#positions" class="btn btn-outline">Join Us →</a>
        </div>
        <div class="vertical-line" style="height: 300px;"></div>
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8">
        <h3 style="color: #374151; font-weight: bold;"> Latest Highlight </h3>
         <!-- News Card 1 --> 
          <div class="events-card">
            <p class="text-xs" style="font-size: 17px;"> <em>  Jiayang received the Wall Research Award. </em>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| Jun 2025 </span> 
            </p>
          </div>  
         <!-- News Card 1 --> 
          <div class="events-card">
            <p class="text-xs" style="font-size: 17px;"> <em>  Jason Zhao received the Four Year Doctoral Fellowship. </em>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| March 2025 </span> 
            </p>
          </div>  
         <!-- News Card 3 -->
          <div class="events-card" style="font-size: 17px;">
            <p class="text-xs"> <em> Chaojie Ji received the Four Year Doctoral Fellowship.</em>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| September 2023 </span> 
            </p>
          </div>
          <!-- News Card 3 -->
          <a href="https://www.nature.com/articles/s41467-022-29837-w" target="_blank" style="text-decoration: none; color: inherit;">
          <div class="events-card" style="font-size: 17px;">
            <p class="text-xs"> <em> Yixiu Wang publish on Nature communication as co-first author. The paper has been cited for more than 500 times.</em>
                <span style="color: #6B7280; font-weight: normal; font-style: normal; font-family: 'Segoe UI', sans-serif;" class="bg-green-500"> &nbsp;| April 2022 </span> 
            </p>
          </div>
           </a>
        </div>
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'   
      spacing:
        padding: ['80px', '0', '10px', '0']

  - block: collection
    id: news
    content:
      title:  News & Events   
      text: ""
      count: 5
      filters:
        folders:
          - event 
    design:
      view: table
      columns: '2' 
      background:
        color: '#ffffff'  
     
  - block: collection
    id: publications
    content:
      title: Selected Publications  <a href="publication/" class="btn btn-outline">→ See More Publications </a>
      text: ""
      count: 30
      filters:
        folders:
          - publication
        publication_type: ""
        featured_only: true
    design:
      view: table
      columns: '2'
      background:
        color: '#f5f5f5'
    
 

  - block: tag_cloud
    id: research
    content:
      title:  Research
      text: |
         <p class="text-xl font-light mt-2">SOLID Lab focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse decision-making paradigms such as <em>machine learning</em>, <em>data analysis  and estimation</em> as well as <em>stochastic optimization</em>, <em>optimal control</em>, and <em>complex networks</em>.  Our algorithms combine mathematical techniques and emerging high-performance computing hardware (e.g., multi-core CPUs, GPUs, and computing clusters) to achieve computational scalability. The goal is to make these developments accessible to academic and industrial users by implementing algorithms on easy-to-use and extensible software libraries.</p>
         <p class="text-xl font-light mt-2"> Furthermore, We have applied the algorithms and tools to help collaborators address engineering and scientific questions that arise in diverse application 
            domainsincluding conflict resolution in energy system design, robust control of crystallization systems, predictive control of wind turbines, power management in 
            large networks, estimation of microbial growth models, and image classification for contaminant detection.</p>

         <!-- Left: Image Panel -->
         <div class="bg-gray-100 rounded-lg p-4 text-center shadow">
            <!--<h3 class="text-xl font-bold text-blue-700 mb-4">Machine Learning</h3>-->
            <img src="/uploads/Overview_yankai_v3.jpg" alt="Overview Research" class="mx-auto w-full max-w-xs rounded">
         </div>
 
    
      taxonomy: none
      # Choose how many tags you would like to display (0 = all tags)
      count: 0
    design:
      columns: '2'
      background:
        color: '#ffffff'
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0  
      spacing:
        padding: ['80px', '40px', '10px', '0']

    
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

          <div class="horizontal-line"></div>
          <div style="display: flex; align-items: center; gap: 2rem;">
          <div style="max-width: 700px;"> 
          <p class="text-3xl font-bold" style="font-family:Times New Roman, serif;">
            <strong>To Ph.D./ Master Candidates:</strong>
          </p>

          <p class="text-2xl font-light italic" style="font-family:Times New Roman, serif;">
            Ideal candidates will have a strong background in process modeling, control, optimization, and excellent communication skills. Students with a major in Control Engineering, Chemical Engineering, Automation Engineering, Systems Engineering, Industrial Engineering, Computer Science or Applied Mathematics are preferred.
          </p>
          </div>
          <div class="vertical-line" style="height: 200px;"></div>
          <div>
          <a href="/#positions" class="btn btn-outline">→ See Funding Opportunities</a>
    
          <a href="https://www.grad.ubc.ca/prospective-students/application-admission" class="btn btn-outline">→ Apply through UBC Graduate School</a>
          </div>
          </div>
    
    design:
      columns: '2'
      background:
        color: '#ffffff'   
      spacing:
        padding: ['80px', '40px', '10px', '0']
          


  - block: people
    id: members
    content:
      title:   Current Members
      subtitle: <a href="people/" class="btn btn-outline">Meet all members →</a>
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Postdoctoral Researchers
          - PhD Students
          - Master Students
          - Undergraduate Students
          - Visitors
          - Alumni0
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true 
      view: card
      background:
        color: '#f5f5f5'

  - block: collection
    id: news
    content:
      title:  News & Events   
      text: ""
      count: 5
      filters:
        folders:
          - event 
    design:
      view: table
      columns: '2' 
      background:
        color: '#ffffff'   
 
 
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
 

  - block: tag_cloud
    content:
      title: Research Topics & Tag Cloud
      subtitle:
      text: 
      # Choose a taxonomy from the `taxonomies` list in `config.yaml` to display (e.g. tags, categories, authors)
      taxonomy: tags
      # Choose how many tags you would like to display (0 = all tags)
      count: 20
    design:
      # Minimum and maximum font sizes (1.0 = 100%).
      font_size_min: 0.7
      font_size_max: 2.0
    design:
      columns: '2'
      background:
        color: '#ffffff' 
    
  - block: markdown
    id: contact
    content:
      title: ""
      text: |
        <div style="display: flex; justify-content: space-between; flex-wrap: wrap; gap: 2rem;">
  
          <!-- Left: Lab Info -->
          <div style="flex: 1; min-width: 250px;">
            <h3 style="color: #0055A5;"><strong>UBC SOLID Lab</strong></h3>
            <p>
              We focus on Scalable Optimization, Learning, and Intelligent Decision-making (SOLID). SOLID Lab is embedded in the Department of Chemical and Biological Engineering at The University of Britis Columbia.
            </p>
          </div>
  
  
          <!-- Right: Affiliations -->
          <div style="flex: 1; min-width: 200px;">
            <h3 style="color: #0055A5;">Affiliations</h3>
            <ul style="list-style: none; padding-left: 0;">
              <li><a href="https://www.ubc.ca/">The University of Britis Columbia</a></li>
              <li><a href="https://chbe.ubc.ca/">Chemical & Biological Engineering</a></li>
              <li><a href="https://cerc.ubc.ca/">Clean Energy Research Center</a></li>
              <li><a href="https://www.iam.ubc.ca/">Institute of Applied Mathematics</a></li>
              <li><a href="https://greencollege.ubc.ca/">Green College</a></li>
            </ul>
          </div>

          <!-- Middle: Contact -->
          <div style="flex: 1; min-width: 250px;">
            <h3 style="color: #0055A5;">Contact</h3>
            <p>Yankai Cao<br>
             Associate Professor<br> 
             Tel: 1 604 822 1346<br>
            Email: <a href="mailto:yankai.cao@ubc.ca"><em>yankai.cao@ubc.ca</em></a><br>
            Office: CHBE 237<br>
            Address: 237-2360 East Mall<br>
            Vancouver, British Columbia, Canada<br>
            V6T 1Z3</p>
          </div>
  
        </div>
    design:
      columns: '1'
      background:
        color: '#f5f5f5'
      spacing:
        padding: ['80px', '40px', '10px', '0']

  
  
  - block: contact 
    content:
      title: "" 
      text:   
      coordinates:
        latitude: '49.26262'
        longitude: '-123.24766'
      #directions: Enter Building and take the stairs to Floor 2 (CHBE 237)
      #office_hours:
       # - 'Monday 10:00 to 13:00'
       # - 'Wednesday 09:00 to 10:00'
      #appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    design:
      columns: '3'
      background:
        color: '#f5f5f5'
      spacing:
        padding: ['80px', '40px', '10px', '0']


 
---
