<div class="card-body">

    <{{ include.heading_level | default: 'h2' | strip }} class="card-title h3">About Me</{{ include.heading_level | default: 'h2' | strip }}>
   
    <p></p>
    <p class="card-text">{{ site.about }}</p>
    <p></p>

</div>

<div>

{% include feature/button.html text="Learn More" link="https://emilycomeau.github.io/media-cv/education.html" color="success" centered=true %}  

</div>