<h2 id="projects" style="margin: 2px 0px -15px;">Projects</h2>

<div class="publications">
  <ol class="bibliography">
    {% for link in site.data.projects.main %}
    <li style="margin-bottom: 20px;">
      <div class="row pub-row">
        <div class="col-sm-3 abbr" style="position: relative; padding-right: 15px; padding-left: 15px;">
          {% if link.image %} 
            <img src="{{ link.image }}" class="teaser img-fluid z-depth-1" style="width=100;height=40%">
          {% endif %}
        </div>
        <div class="col-sm-9" style="position: relative; padding-right: 15px; padding-left: 20px;">
          <div class="title" style="color: #3eb7f0;">{{ link.title }}</div>
          <div class="description">{{ link.description }}</div>
          <div class="guide" style="color: #e8e8e8;">
            <span>Guide:</span> <em>{{ link.guide }}</em>
          </div>
        </div>
      </div>
    </li>
    {% endfor %}
  </ol>
</div>
