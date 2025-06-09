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
        filename: welcome.jpg
      text: |
         <br> 
         <p class="text-base font-light" style="font-family:Times New Roman, sans-serif;">We focuse on the design and implementation of large-scale local and global optimization algorithms.</p>
         <br> 
         <p class="text-xs font-light" style="font-size: 12px;font-family:Times New Roman, sans-serif;">Cao Research Group is embedded in the
         <a href="https://chbe.ubc.ca" class="text-blue-600 underline hover:text-blue-800" target="_blank">Department of Chemical and Biological Engineering</a> at <a href="https://www.ubc.ca/" class="text-blue-600 underline hover:text-blue-800" target="_blank">The University of Britis Columbia</a>.<br></p>
         <a href="/#research" class="btn btn-primary">Our Research</a>
         <a href="/#positions" class="btn btn-secondary">Publication</a>
         <a href="/#positions" class="btn btn-outline">Join Us →</a>
         <br> 
         <a href="/#positions" class="btn btn-light">Last news</a> 

    
  - block: hero
    content:
      title: |
        <strong>Now Solving:</strong> Global Optimal AI
      image:
        filename: welcome.jpg
      text: |
         <br> 
         Our research group focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse decision-making paradigms such as machine learning, data analysis, and estimation as well as stochastic optimization, optimal control, and complex networks.
      primary_action:
        text: Learn more
        url: https://hugoblox.com/templates/
      secondary_action:
        text: Joint us
        url: /#positions
      announcement:
        text: "Announcing the release of version 1."
        link:
          text: "Read more"
          url: "/#research"
    
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
      title: Research
      text: >
            <p class="text-2xl font-bold" style="font-family:Times New Roman, sans-serif;">Our research group focuses on the design and implementation of large-scale local and global optimization algorithms to solve problems that arise in diverse 
            decision-making paradigms such as machine learning, data analysis, and estimation as well as stochastic optimization, optimal control, and complex networks. Our 
            algorithms combine mathematical techniques and emerging high-performance computing hardware (e.g., multi-core CPUs, GPUs, and computing clusters) to achieve 
            computational scalability. The goal is to make these developments accessible to academic and industrial users by implementing algorithms on easy-to-use and 
            extensible software libraries.</p> <br>
            <p class="text-2xl font-bold" style="font-family:Times New Roman, sans-serif;">Furthermore, We have applied the algorithms and tools to help collaborators address engineering and scientific questions that arise in diverse application 
            domainsincluding conflict resolution in energy system design, robust control of crystallization systems, predictive control of wind turbines, power management in 
            large networks, estimation of microbial growth models, and image classification for contaminant detection. </p>  
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
      title:  Positions 
      text: >
            <p class="text-2xl font-bold" style="font-family:Times New Roman, sans-serif;">We are actively seeking future postdoctoral researchers, graduate students, visiting students, and undergraduate students.</p>
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉 Please <span class="font-bold">send your CV to</span> <span style="text-decoration: underline;">yankai.cao@ubc.ca.</span>. </p> 
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉  Please <span class="font-bold">provide the following information:</span>   degree program and university, graduation year, GPA, class rank, English proficiency test score, desired start date, research summary, and future research plans (for postdocs). </p> 
            <p class="text-2xl font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉 Please apply through <a href="https://www.grad.ubc.ca/prospective-students/application-admission" target="_blank" class="underline text-blue-600 hover:text-blue-800"> UBC Graduate School</a>.</p>
            <p class="text-2xl mb-8 font-light" style="font-family:Times New Roman, sans-serif; text-indent: 2em;">👉  <a href="funding/"> Here is for <span style="text-decoration: underline;">Funding Opportunities</span> </a>. </p>
            <p class="text-3xl font-bold" style="font-family:Times New Roman, sans-serif;"><strong>To Ph.D./ Master Candidates: </strong></p>
            <p class="text-2xl font-light italic" style="font-family:Times New Roman, sans-serif;">Ideal candidates will have a strong background in process modeling, control, optimization, and excellent communication skills. Students with a major in Control Engineering, Chemical Engineering, Automation Engineering, Systems Engineering, Industrial Engineering, Computer Science or Applied Mathematics are preferred.</p>
    design:
      view: card                    
      columns: '1'
---
