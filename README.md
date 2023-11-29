<div class="root">
  <div class="logo"></div>
</div>
<style>
  @keyframes get {
    0% {
      margin-top: -32px;
      box-shadow: 0 0px 32px rgba(255, 255, 255, 0.25);
    }
    50% {
      margin-top: 0px;
      box-shadow: 0 0px 24px rgba(255, 255, 255, 0);
    }
    100% {
      margin-top: -32px;
      box-shadow: 0 0px 32px rgba(255, 255, 255, 0.25);
    }
  }
  .root {
    width: 100%;
    height: 256px;
    background-color: black;
    border-radius: 16px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-image: url(modlin_inc.png);
    background-repeat: no-repeat;
    background-position: 50% 50%;
  }
  .logo {
    width: 128px;
    height: 128px;
    background-color: white;
    border-radius: 16px;
    animation-duration: 2s;
    animation-name: get;
    animation-iteration-count: infinite;
  }
</style>
