# Loop-Slider-for-Brands-CSS
My First Repo in GitHub
<a href="https://bonusoutdoors.com/pages/brands-page">
<div class="slider">
  <div class="slider-wrap">
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_43.png?v=1681878037" alt="Triswim">
    </div>
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_44.png?v=1681878160" alt="3-in-one">
    </div>
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_45.png?v=1681878246" alt="KMC">
    </div>
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_3.png?v=1681822905" class="slide-image" alt="wd-40">
    </div>
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_46.png?v=1681878345" alt="ravenmen" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_41.png?v=1681877552" alt="cocalavine">
    </div>
    <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_6.png?v=1681822937" alt="skin slick" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_7.png?v=1681822948" alt="rocknroll" class="slide-image">
    </div>

<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_8.png?v=1681822957" alt="pro club" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_42.png?v=1681877794" alt="Blocksurf" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_47.png?v=1681878481" alt="maxima" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_43.png?v=1681878037" alt="Triswim">
    </div>
 <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_44.png?v=1681878160" alt="3-in-one">
    </div>
  <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_45.png?v=1681878246" alt="KMC">
    </div>
 <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_3.png?v=1681822905" class="slide-image" alt="wd-40">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_46.png?v=1681878345" alt="ravenmen" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_41.png?v=1681877552" alt="cocalavine">
    </div>
 <div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_6.png?v=1681822937" alt="skin slick" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_7.png?v=1681822948" alt="rocknroll" class="slide-image">
    </div>

<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_8.png?v=1681822957" alt="pro club" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_42.png?v=1681877794" alt="Blocksurf" class="slide-image">
    </div>
<div class="slide">
      <img src="https://cdn.shopify.com/s/files/1/0444/6706/0885/files/New_Project_47.png?v=1681878481" alt="maxima" class="slide-image">
    </div>
  </div>
</div>
</a>
<div class="containersa">
<a href="#">
<button class="btnof">
View All Brands
</button>
</a>
</div>
<style>
@keyframes scroll{
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(calc(-250px * 7));
  }
}
.slider {
  width: 100%;
  background: white;
  height: 160px;
  margin: auto;
  overflow: hidden;
  position: relative;
  border: 1px solid #e5e5e5;
}
.slider-wrap {
		animation: scroll 20s linear infinite;
		display: flex;
width: calc(740px * 6);
    height:100%;
	}
.slide-image{
  width:80%;
  height:100%;
  object-fit:cover;
}
.slide{
  width:550px;
  height:100%;
  text-align:center;
}
.containersa{
text-align:center;}
.btnof{

color: #fff;
    background-color: #1e8570;
    border: 1px solid #dddddd;
font-size: var(--font-size-button-medium);
    padding: 0.75rem 1.125rem;
    letter-spacing: 0em;
    align-self: center;
    margin-top: 1.25rem;
    margin-bottom: 0.25rem;
font-family: Cabin,sans-serif;
    font-style: normal;
    font-weight: 600;
    display: inline-block;
    text-decoration: none;
    cursor: pointer;
    border-radius: 3px;
    transition: width 125ms cubic-bezier(.4,0,.2,1),height 125ms cubic-bezier(.4,0,.2,1),border-color 125ms cubic-bezier(.4,0,.2,1),background-color 125ms cubic-bezier(.4,0,.2,1),box-shadow 125ms cubic-bezier(.4,0,.2,1);
}

</style>
