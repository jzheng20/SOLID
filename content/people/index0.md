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

  - block: markdown
    id:  
    content:
      title:   
      text: |
            <div class="alumni-section">
            <h2>Alumni</h2>
            <p>Former students, researchers and visitors in the DAIS Lab</p>

            <h3>2024</h3>
            <table>
              <thead>
                <tr>
                  <th>Name</th>
                  <th>Degree</th>
                  <th>Position After Leaving/Now At</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Atefeh Daemi</td>
                 <td>PhD</td>
                  <td>Postdoctoral Researcher (UC San Diego)</td>
                </tr>
                <tr>
                  <td>Nathan Lawrence</td>
                  <td>Postdoc</td>
                  <td>Postdoctoral Researcher (UC Berkeley, Mesbah Group)</td>
                </tr>
                <tr>
                  <td>Christina Maag</td>
                  <td>Undergraduate</td>
                  <td></td>
                </tr>
                <tr>
                  <td>Vijay Kumar Pediredla</td>
                  <td>Postdoc</td>
                  <td>Alberta News Corp</td>
                </tr>
                <tr>
                  <td>Yixiu Wang</td>
                  <td>PhD</td>
                  <td>Huawei, Research Engineer</td>
                </tr>
                <tr>
                  <td>Liang Cao</td>
                  <td>PhD</td>
                  <td>Postdoctoral Researcher (MIT, Braatz Group)</td>
                </tr>
              </tbody>
            </table>
    design:
      columns: '1'
      background:
        color: '#ffffff'  

---
