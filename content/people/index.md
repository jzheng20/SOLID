---
title: People
date: 2022-10-24

type: landing

sections:
  - block: people
    id: members
    content:
      title: Members
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
    id: alumni
    content:
      title: Alumni
      text: |
        <div class="alumni-section">
          <h2>Alumni</h2>
          <p>Former students, researchers and visitors in the DAIS Lab</p>

          <h3>2024</h3>
          <table class="table table-hover">
            <thead>
              <tr>
                <th> </th>
                <th>Name</th>
                <th>Degree</th>
                <th>Position After Leaving/Now At</th>
              </tr>
            </thead>
            <tbody>
              <!-- 2024 年分组行 -->
              <tr style="background-color: #e5e5e5;">
                <td colspan="4"><strong>2024</strong></td>
              </tr>
              <tr>
                <td><img src="/uploads/Alumni_img/avatar.png" width="40" style="border-radius: 50%;"></td>
                <td>Nathan Lawrence</td>
                <td><em>Postdoc</em></td>
                <td>Postdoctoral Researcher (UC San Diego)</td>
              </tr>
              <tr>
                <td><img src="/uploads/Alumni_img/avatar.png" width="40" style="border-radius: 50%;"></td>
                <td>Nathan Lawrence</td>
                <td><em>Postdoc</em></td>
                <td>Postdoctoral Researcher (UC Berkeley, Mesbah Group)</td>
              </tr>
              <tr>
                <td><img src="/uploads/Alumni_img/avatar.png" width="40" style="border-radius: 50%;"></td>
                <td>Nathan Lawrence</td>
                <td><em>Postdoc</em></td>
                <td></td>
              </tr>   
            </tbody>
          </table>
 
        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'
---
