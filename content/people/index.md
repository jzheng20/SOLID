---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    id: members
    content:
      title: Members
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigator
          - Postdoctoral Researchers
          - PhD Students
          - Master Students
          - Undergraduate Students
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true 
      view: card


  - block: collection
    id: alumni
    content:
      title: Alumni
      description: Former students, researchers and visitors in the DAIS Lab
      items:
        - year: 2024
          alumni:
            - name: Atefeh Daemi
              degree: PhD
              position: Postdoctoral Researcher (UC San Diego)
            - name: Nathan Lawrence
              degree: Postdoc
              position: Postdoctoral Researcher (UC Berkeley, Mesbah Group)
            - name: Christina Maag
              degree: Undergraduate
              position: ""
            - name: Vijay Kumar Pediredla
              degree: Postdoc
              position: Alberta News Corp
            - name: Yixiu Wang
              degree: PhD
              position: Huawei, Research Engineer
            - name: Liang Cao
              degree: PhD
              position: Postdoctoral Researcher (MIT, Braatz Group)
        - year: 2023
          alumni:
            - name: Aria Azari
              degree: Undergraduate
              position: PhD (Oxford)
            - name: Thomas Lai
              degree: Undergraduate
              position: MSc (McGill)
            - name: Siddharth Grover
              degree: Undergraduate
              position: MS Data Science (UBC)
            - name: Yiting Tsai
              degree: PhD
              position: Postdoctoral Researcher (McMaster)
              social: https://www.linkedin.com/in/yiting-tsai/
            - name: Nathan Lawrence
              degree: PhD
              position: Postdoctoral Researcher (UBC)
              social: https://www.linkedin.com/in/nathan-lawrence/
            - name: Yupeng Li
              degree: PhD (Visiting)
              position: China University of Geosciences
    design:
      view: table
      show_table_header: true

---
