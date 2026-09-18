---
layout: blank
---

<GalleryCarousel :depiction-id="[]" citations height="470px">
  <div class="flex flex-col justify-center items-center w-full h-full bg-black/25 text-white gap-4 px-4 box-border">
    <span class="text-4xl font-medium">{{ app:project_name }}</span>
    <p class="text-lg sm:text-xl text-center container">A comprehensive source of knowledge about the world's Dermaptera</p>
    <div class="mx-auto flex flex-col items-center mt-6 sm:mt-10 w-full">
      <autocomplete-otu class="w-full sm:w-96 text-base-content ml-2 sm:ml-0" placeholder="Search by taxon name" autofocus/>
        <p class="text-sm sm:text-base"><em>Explore! Try searching for species Forficula auricularia, or start your exploration at genus <router-link to="/otus/888460">Forficula</router-link> </p>
    </div>
  </div>
</GalleryCarousel>
        
<div class="container mx-auto my-8 px-4 md:px-0 box-border">


The Dermaptera Species File works to build a comprehensive source for knowledge about the world’s earwigs. Information found here includes valid names, synonyms, bibliographic data, specimen data, images, and distributions for earwigs of the world. Our site seeks to include and serve researchers in taxonomy, systematics, ecology, ethology, conservation, and evolution, as well as educators, policy makers, and citizen scientists. See our [About](about) page for an overview of the project, its data, the development and maintenance team, and details about how you can access the data, contribute, contact us, or get help.
