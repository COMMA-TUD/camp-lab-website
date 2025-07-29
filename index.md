---
---
# The Composites and Advanced Materials Processing Lab

CAMP Lab is a research group at [TU Delft (NL)](https://www.tudelft.nl/en/) focusing on advanced materials processing and composite structures. The group is led by [Prof. Baris Caglar](members/baris-caglar), and is part of the [Aerospace Structures and Materials department from the Faculty of Aerospace Engineering](https://www.tudelft.nl/en/ae/organisation/departments/aerospace-structures-and-materials).

At CAMP Lab, our research focuses on sustainable composites and their manufacturing through resource and energy efficient processing enabled by data-driven approaches. The three main pillars of our research are:
- **Resource-efficient** advanced composites based on unidirectional thermoplastic tapes 
- **Energy-efficient** processing of thermoset-based advanced composites through frontal polymerization
- **Data-driven** approaches for improved process design and control through the use state-of-the-art AI models


{% include section.html %}

## Highlights

<div class="glider-container">
  <div class="glide">
    <div class="glide__track" data-glide-el="track">
      <div class="glide__slides">
        {% include project-list.html data="projects" component="project-excerpt" glider=true filter="!end_date"%}
      </div>
    </div>
    <div class="glide__arrows" data-glide-el="controls">
      <button class="glide__arrow glide__arrow--left" data-glide-dir="<">{% include icon.html icon="fa-solid fa-arrow-left" %}</button>
      <button class="glide__arrow glide__arrow--right" data-glide-dir=">">{% include icon.html icon="fa-solid fa-arrow-right" %}</button>
    </div>
  </div>
</div>
<script src="https://cdn.jsdelivr.net/npm/@glidejs/glide"></script>
<script>
  const config = {
    type: "carousel",
    perView: 2,
    breakpoints: {
      600: {
        perView: 1
      },
      1200: {
        perView: 2
      }
    },
    autoplay: 3000,
    hoverpause: true
  }
  new Glide('.glide', config).mount()
</script>
