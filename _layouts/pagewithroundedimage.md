---
layout: default
---
<div class="column is-three-fifths">
    <main>
        <div class="note-page-section">    
        	<img src="assets/img/{{page.image}}" alt="{{page.image_alt}}" class="is_rounded right">
            <h1>{{page.title}}</h1>
            {%- include Content.html -%} <!-- this is where the obsidian transformation magic happens -->
        </div>
        {%- include Footer.html -%}
    </main>
</div>

