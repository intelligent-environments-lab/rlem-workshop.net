---
layout: default
title: Important Dates
---

<h1 class="display-5 mb-4">
    {{ page.title }}
</h1>


<div class="schedule-tbl">
  <table>
    <tbody>
      {% for important in site.data.important_dates %}
      <tr>
        <td class="schedule-slot">
            <h5><p class="important-dates">{{ important.name }}:  </p></h5>
        </td>
        <td class="schedule-slot">
            <p class="important-dates undone">{{ important.date }}</p>
        </td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
</div>