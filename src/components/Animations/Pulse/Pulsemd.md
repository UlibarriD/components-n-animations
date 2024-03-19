```html
<div class="box" id="Pulse"></div>

<style>
  #Pulse {
    border: 0;
    animation: pulse 2s;
    animation-iteration-count: infinite;
    box-shadow: none;
  }

  .box {
    width: 250px;
    height: 250px;
    border-radius: 8px;
    box-shadow: -2px 4px 8px rgba(0, 0, 0, 0.3);
    background-color: #275559;
  }

  @keyframes pulse {
    0% {
      box-shadow: 0 0 0 0px rgba(107, 152, 169, 0.18);
    }
    100% {
      box-shadow: 0 0 0 15px rgba(0, 0, 0, 0);
    }
  }
</style>
```
