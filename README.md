# Online-Shoe-Shopping
<!DOCTYPE html>
<html>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: sans-serif;
      line-height: 1.4;
    }

    .clearfix::after {
      content: "";
      display: block;
      clear: both;
    }

    .container {
      /*   background-color: red; */
      display: flex;
      gap: 40px;
    }

    .product-img {
    }

    /* PRODUCT */
    .product {
      border: 4px solid black;
      width: 825px;
      margin: 50px auto;
      position: relative;
    }

    .product-title {
      text-align: center;
      font-size: 22px;
      text-transform: uppercase;
      background-color: #f7f7f7;
      padding: 15px;
    }

    /* PRODUCT INFORMATION */
    .product-info {
      /*  (825 - 8 - 250 - 80) / 2  */
      /*   width: 243px; */
      flex: 1;
      margin-top: 20px;
    }

    .product-price {
      display: flex;
      justify-content: space-between;
      align-items: center;
      margin-bottom: 20px;
    }

    .price {
      font-size: 24px;
    }

    .shipping {
      font-size: 12px;
      text-transform: uppercase;
      font-weight: bold;
      color: #777;
    }

    .sale {
      background-color: #ec2f2f;
      color: #fff;
      font-size: 12px;
      text-transform: uppercase;
      font-weight: bold;
      letter-spacing: 2px;
      padding: 7px 15px;
      display: inline-block;
      position: absolute;
      top: -17px;
      left: -38px;

      /*   width: 40px;
  text-align: center; */
    }

    .product-description {
      margin-bottom: 10px;
    }

    .more-info:link,
    .more-info:visited {
      color: black;
      margin-bottom: 30px;
      display: inline-block;
    }

    .more-info:hover,
    .more-info:active {
      text-decoration: none;
    }

    .product-colors {
      display: flex;
      gap: 10px;
    }

    .color {
      background-color: #000;
      height: 22px;
      width: 22px;
    }

    .color-blue {
      background-color: #2f6ee2;
    }
    .color-red {
      background-color: #ec2f2f;
    }
    .color-yellow {
      background-color: #f0bf1e;
    }
    .color-green {
      background-color: #90cc20;
    }
    .color-brown {
      background-color: #885214;
    }

    /* PRODUCT DETAILS */
    .product-details {
      /*   width: 243px; */
      margin-top: 20px;
      flex: 1;
    }

    .details-title {
      text-transform: uppercase;
      font-size: 16px;
      margin-bottom: 15px;
    }

    .details-list {
      list-style: square;
      margin-left: 20px;
    }

    .details-list li {
      margin-bottom: 10px;
    }

    /* BUTTON */
    .add-cart {
      background-color: #000;
      border: none;
      color: #fff;
      font-size: 20px;
      text-transform: uppercase;
      cursor: pointer;
      padding: 15px;
      width: 100%;
      border-top: 4px solid black;
    }

    .add-cart:hover {
      color: #000;
      background-color: #fff;
    }
  </style>
  <body>
    <article class="product">
      <h2 class="product-title">Converse Chuck Taylor All Star Low Top</h2>
      <div class="container">
        <img
          src="https://i.imgur.com/ZrTU3VK.jpeg"
          alt="Chuck Taylor All Star Shoe"
          height="250"
          width="250"
          class="product-img"
        />
        <div class="product-info">
          <div class="product-price">
            <p class="price"><strong>$65.00</strong></p>
            <p class="shipping">Free shipping</p>
          </div>
          <p class="sale">Sale</p>

          <p class="product-description">
            Ready to dress up or down, these classic canvas Chucks are an
            everyday wardrobe staple.
          </p>
          <a href="https://converse.com" target="_blank" class="more-info"
            >More information &rarr;</a
          >
          <div class="product-colors">
            <div class="color"></div>
            <div class="color color-blue"></div>
            <div class="color color-red"></div>
            <div class="color color-yellow"></div>
            <div class="color color-green"></div>
            <div class="color color-brown"></div>
          </div>
        </div>

        <div class="product-details">
          <h3 class="details-title">Product details</h3>
          <ul class="details-list">
            <li>Lightweight, durable canvas sneaker</li>
            <li>Lightly padded footbed for added comfort</li>
            <li>Iconic Chuck Taylor ankle patch.</li>
          </ul>
        </div>
      </div>
      <button class="add-cart">Add to cart</button>
    </article>
  </body>
</html>
