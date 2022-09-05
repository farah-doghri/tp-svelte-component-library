<script>

export let title = ''; 
export let texte = ''; 
export let position = 'Top'; 

</script>

<div class="tooltip { position }"> { title }
    <span class="tooltiptext">{ texte }</span>
</div>

<style>
.tooltip {
    position: relative;
    display: inline-block;
    text-align: center;
    flex: 100%;
    margin: 10px 0;
}

.tooltip .tooltiptext {
    visibility: hidden;
    width: 120px;
    background-color: black;
    color: #fff;
    text-align: center;
    border-radius: 6px;
    padding: 5px 0;

}
.Top .tooltiptext {
    /* Position the tooltip */
    position: absolute;
    z-index: 1;
    bottom: 100%;
    left: 50%;
    margin-left: -60px;
}
.Rigth .tooltiptext {
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: -5px;
  left: 105%;
}
.Left .tooltiptext {
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: -5px;
  right: 105%;
}
.Bottom .tooltiptext {
  /* Position the tooltip */
  position: absolute;
  z-index: 1;
  top: 100%;
  left: 50%;
  margin-left: -60px;
}

.tooltip:hover .tooltiptext {
    visibility: visible;
}
</style>