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
          - Alumni0
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
      title: <hr class="section-divider">  
      text: |
        <div class="alumni-section">
          <h2>Alumni</h2>
          <p>Former students, researchers and visitors in the DAIS Lab</p>

          <table class="table table-hover" style="border-collapse: collapse; width: 100%; border: 1px solid #ccc; font-size: 14px;">
            <thead>
              <tr style="border-bottom: 2px solid #ccc; background-color: #f9f9f9;">
                <th style="border: 1px solid #ccc; padding: 6px;"> </th>
                <th style="border: 1px solid #ccc; padding: 6px;">Name</th>
                <th style="border: 1px solid #ccc; padding: 6px;">Degree</th>
                <th style="border: 1px solid #ccc; padding: 6px;">Position After Leaving/Now At</th>
              </tr>
            </thead>
            <tbody>
              <!-- 2024 年分组 -->
              <tr style="background-color: #e5e5e5;">
                <td colspan="4" style="border: 1px solid #ccc; padding: 6px;"><strong>2024</strong></td>
              </tr>
              <tr>
                <td style="border: 1px solid #ccc; padding: 6px;"><img src="/uploads/Alumni_img/avatar.png" width="36" style="border-radius: 50%;"></td>
                <td style="border: 1px solid #ccc; padding: 6px;">Nathan Lawrence</td>
                <td style="border: 1px solid #ccc; padding: 6px;"><em>Postdoc</em></td>
                <td style="border: 1px solid #ccc; padding: 6px;">Postdoctoral Researcher (UC San Diego)</td>
              </tr>

              <!-- 2023 年分组 -->
              <tr style="background-color: #e5e5e5;">
                <td colspan="4" style="border: 1px solid #ccc; padding: 6px;"><strong>2023</strong></td>
              </tr>
              <tr>
                <td style="border: 1px solid #ccc; padding: 6px;"><img src="/uploads/Alumni_img/avatar.png" width="36" style="border-radius: 50%;"></td>
                <td style="border: 1px solid #ccc; padding: 6px;">Nathan Lawrence</td>
                <td style="border: 1px solid #ccc; padding: 6px;"><em>Postdoc</em></td>
                <td style="border: 1px solid #ccc; padding: 6px;">Postdoctoral Researcher (UC San Diego)</td>
              </tr>
            </tbody>
          </table>

        </div>
    design:
      columns: '1'
      background:
        color: '#ffffff'
---
