<script>
  import Card from './components/Card.svelte';
  import Tooltip from './components/Tooltip.svelte';
</script>

<h1>Cards</h1>

<div>
  <Card
    title="Thomas"
    content="https://storage.googleapis.com/mustsee-earth.appspot.com/places/matterhorn-sam-ferrara-large%402x.jpg"
    color="red"
  />
  
  <Card
    title="Thomfffas"
    content="-sam-ferrara-large%402x.jpg"
    color="green"
  />
  
  <Card
    title="Thomfffas"
    content="-sam-ferrara-large%402x.jpg"
    color="orange"
  />
</div>


<h1>Tooltip</h1>

<div style="text-align: center;">
  <Tooltip
    title="Top"
    texte="Rigth"
    position="Top"
  />
  
  <Tooltip
    title="Rigth"
    texte="Rigth"
    position="Rigth"
  />

  <Tooltip
    title="Bottom"
    texte="Rigth"
    position="Bottom"
  />

  <Tooltip
    title="Left"
    texte="Rigth"
    position="Left"
  />
  
</div>