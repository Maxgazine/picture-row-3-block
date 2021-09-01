# picture-row-3-block
<head>
  <style>
    .content-section{
  margin-top: 3%;
  padding-top: 2%;
  background-color: #242526;
  display: flex;
  position: relative;
  width: 100%; height: auto;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.block-frame{
  width: 80%; height: 50%;
  border: 2px solid white;
  flex-direction: row;
  justify-content: space-around;
  display: flex;
}
.group-picture{
  width: 400px;
  height: 350px;
  border: 3px solid white;
  flex-direction: column;
  margin-top: 20px;
  border-radius: 15px;
}
.picture-frame{
  margin: auto;
  box-sizing: box-border;
  position: relative;
  display: flex;
  cursor: not-allowed;
}
.cropped-picture{
    margin: 0;
    width: 400px; /* width of container */
    height: 300px; /* height of container */
    object-fit: cover;
    object-position: 50% 50%;
    border: 3px solid white;
    margin: auto;
    border-radius: 15px;
    box-shadow: 1px 1px 4px 2px;
}
  </style>
</head>
<body>
  <section class="content-section">
      <div id="first-block-frame" class="block-frame">
        <div class="group-picture"><figure class="picture-frame">
          <img src="https://i.ibb.co/2NJpsJf/89204182-2863432020369406-4825286682066550784-o.jpg" class="cropped-picture" alt="Retouching-picture">
        </figure></div>
        <div class="group-picture"><figure class="picture-frame">
          <img src="https://i.ibb.co/QNy2GGn/90087152-2863431160369492-4608943363981312000-o.jpg" class="cropped-picture" alt="Retouching-picture">
        </figure></div>
        <div class="group-picture"><figure class="picture-frame">
          <img src="https://i.ibb.co/rfRcMjR/113268904-3213007625411842-2886781791141652697-o.jpg" class="cropped-picture" alt="Retouching-picture">
        </figure></div>
      </div>
  </section>
</body>
