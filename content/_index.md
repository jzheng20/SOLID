---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
          <strong>Now Solving:</strong> <br> Global Optimal AI
      image:
        filename: logo1.png
      text: |
         <br> 
         <p class="text-base font-light">We focuse on the design and implementation of large-scale local and global optimization algorithms.</p>
         <p class="text-xs font-light" style="font-size: 18px;">Cao Research Group is embedded in the
         <a href="https://chbe.ubc.ca" class="text-blue-600 underline hover:text-blue-800" target="_blank">Department of Chemical and Biological Engineering</a> at <a href="https://www.ubc.ca/" class="text-blue-600 underline hover:text-blue-800" target="_blank">The University of Britis Columbia</a>.<br></p>
         <a href="/#research" class="btn btn-primary">Learn Us</a>
         <a href="/#positions" class="btn btn-outline">Join Us →</a>
 
    
  - block: collection
    id: news
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    id: research
    content:
      title: '<p class="text-4xl font-bold">DAIS Lab Research</p>'
      text: |
        <p class="text-xl font-light mt-2">
          Our research lies at the intersection of <em>industrial process control</em>, <em>data analytics</em> and <em>machine learning</em>.
        </p>
        <p class="text-md mt-4">Recent representative publications in these areas:</p>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8">

          <!-- Left: Image Panel -->
          <div class="bg-gray-100 rounded-lg p-4 text-center shadow">
            <h3 class="text-xl font-bold text-blue-700 mb-4">Machine Learning</h3>
            <img src="/media/actor-critic.png" alt="Actor-Critic Diagram" class="mx-auto w-full max-w-xs rounded">
            <p class="text-sm text-blue-600 mt-2">Spielberg et al. 2019</p>
          </div>

          <!-- Right: Publication Card -->
          <div class="rounded-lg border-l-4 border-blue-500 shadow p-6 bg-white">
            <p class="italic text-blue-700 mb-1">Journal Paper <span class="bg-blue-100 text-blue-700 text-xs px-2 py-1 rounded ml-2">Top 10% Most Downloaded</span></p>
            <p class="text-lg font-bold text-gray-800 mb-2">
              Towards Self-Driving Processes: A Deep Reinforcement Learning Approach to Control
            </p>
            <p class="text-sm text-gray-700">
              Steven P. Spielberg, Aditya Tulsyan, <em class="underline text-red-600">Nathan P. Lawrence</em>, Philip D. Loewen, R. Bhushan Gopaluni<br>
              <em>AIChE Journal</em>. 2019 
              <a href="https://example.com/paper-link" target="_blank" class="ml-2 px-2 py-1 text-white bg-blue-500 text-xs rounded">[Paper]</a>
            </p>
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
      view: compact
      columns: '1'

  

  - block: markdown
    id: publications
    content:
      title: Latest Preprints
      text: |
            <div class="bg-white rounded-xl shadow-md p-6 mb-6 grid grid-cols-[1fr_auto] gap-4 items-start">
             <!-- 左边内容 -->
             <div>
              <h3 class="text-xl font-bold">An example journal article</h3>
                 <p class="text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.</p>
                 <p class="text-sm text-gray-500 mt-2">Nelson Bighetti <span class="text-gray-400">•</span> Robert Ford</p>
             <div class="mt-3 flex gap-2">
               <a href="#" class="px-3 py-1 border border-blue-500 text-blue-600 text-sm rounded hover:bg-blue-50">PDF</a>
               <a href="#" class="px-3 py-1 border border-blue-500 text-blue-600 text-sm rounded hover:bg-blue-50">Cite</a>
               <a href="#" class="px-3 py-1 border border-blue-500 text-blue-600 text-sm rounded hover:bg-blue-50">Code</a>
             </div>
             </div>
             <!-- 右边图片 -->
             <div class="w-[96px] h-[72px] overflow-hidden rounded shadow-sm">
             <img src="/uploads/logo2.png"  style="width: 6rem; height: 6rem;"  class="rounded-full object-cover">
             </div>
            </div>


  - block: markdown
    id: research
    content:
      title: Research
      text: >
            <p class="text-2xl font-bold">Our research group focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse 
            decision-making paradigms such as machine learning, data analysis, and estimation as well as stochastic optimization, optimal control, and complex networks. Our 
            algorithms combine mathematical techniques and emerging high-performance computing hardware (e.g., multi-core CPUs, GPUs, and computing clusters) to achieve 
            computational scalability. The goal is to make these developments accessible to academic and industrial users by implementing algorithms on easy-to-use and 
            extensible software libraries.</p> <br>
            <p class="text-2xl font-bold">Furthermore, We have applied the algorithms and tools to help collaborators address engineering and scientific questions that arise in diverse application 
            domainsincluding conflict resolution in energy system design, robust control of crystallization systems, predictive control of wind turbines, power management in 
            large networks, estimation of microbial growth models, and image classification for contaminant detection. </p>
            <img src="/uploads/aboutus.png"  style="width: 40rem; height: 30rem; display: block; margin-left: auto; margin-right: auto;" class="rounded-full object-cover">
    
    design:
      view: card                    
      columns: '1'      
    
  - block: people
    id: members
    content:
      title: Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Grad Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true 
      view: card     

  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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

          <p class="text-2xl font-bold" style="font-family:Times New Roman, serif;">We are actively seeking future postdoctoral researchers, graduate students, visiting students, and undergraduate students.</p>

          <p class="text-2xl font-light" style="font-family:Times New Roman, serif; text-indent: 2em;">
            👉 Please <span class="font-bold">send your CV to</span> <span class="underline">yankai.cao@ubc.ca</span>.
          </p>

          <p class="text-2xl font-light" style="font-family:Times New Roman, serif; text-indent: 2em;">
            👉 Please <span class="font-bold">provide the following information:</span> degree program and university, graduation year, GPA, class rank, English proficiency test score, desired start date, research summary, and future research plans (for postdocs).
          </p>

          <p class="text-2xl font-light" style="font-family:Times New Roman, serif; text-indent: 2em;">
            👉 Please apply through <a href="https://www.grad.ubc.ca/prospective-students/application-admission" target="_blank" class="underline text-blue-600 hover:text-blue- 800">UBC Graduate School</a>.
          </p>

          <p class="text-2xl font-light mb-6" style="font-family:Times New Roman, serif; text-indent: 2em;">
            👉 <a href="/funding/" class="underline text-blue-600 hover:text-blue-800">Here is for Funding Opportunities</a>.
          </p>
 
          <div class="rounded-xl shadow p-6 max-w-4xl mx-auto" style="background-color: #f3f4f6;"> <!-- 灰色卡片 -->
          <div class="bg-gray-100 rounded-xl shadow p-6 space-y-4"> 
          <p class="text-3xl font-bold" style="font-family:Times New Roman, serif;">
            <strong>To Ph.D./ Master Candidates:</strong>
          </p>

          <p class="text-2xl font-light italic" style="font-family:Times New Roman, serif;">
            Ideal candidates will have a strong background in process modeling, control, optimization, and excellent communication skills. Students with a major in Control Engineering, Chemical Engineering, Automation Engineering, Systems Engineering, Industrial Engineering, Computer Science or Applied Mathematics are preferred.
          </p>
          </div>
          </div>
  
 
 
---
