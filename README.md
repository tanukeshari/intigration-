<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>E-Commerce Project</title>

    <link rel="stylesheet" href="./style.css">

    <!-- <script src="/index.js" defer></script> -->

</head>

<body>

    <header>

        <ul>

            <li><a href="./index.html">HOME</a></li>

            <li><a href="./dynamicstore.html">STORE</a></li>

            <li><a href="#">ABOUT</a></li>

        </ul>

        <h1>The Generics</h1>

    </header>

    <!-- <header>

        <h6><a href="#">STORE</a></h6>

        <h1>The Generics</h1>

    </header> -->

    <section id="about">

        <h2>About</h2>

        <div>

            <img src="./img/Band Members.png" alt="">

            <p>Lorem ipsum carrots enhanced rebates. Excellent sayings of a man of sorrows, hates no prosecutors will unfold in the enduring of which were born in it? Often leads smallest mistake some pain main responsibilities are to stand for the right builder of pleasure, accepted explain up to now. , The things we are accusing of these in the explication of the truth receives from the flattery of her will never be the trouble and they are refused to the pleasures and the pleasures of the pain, explain the treatment of excepturi of the blessed sufferings. I never said will unfold in him receives at another time he may please the one that those works, we are less than they, this refused to the pleasures of deleniti? Those are! Will unfold in times of pleasure, this pain will be a right enjoyed by corrupt, are accusing him of all pleasures, and seek his own, or, to the needs of the agony of the choice. We hate the fellow.<br>



                Lorem ipsum dolor, sit amet consectetur rebates. The distinction, that arise from or to. The greater, therefore, an obstacle to the duties of the debts receives the very great importance to us that these are consequent to that question is answered, which was selected for the fault, it is often one of us, however, have any! Moreover, this is often not at once take the hardships of the life of harsh condemn, we are accusing him? Him whom something large cisterns.</p>

        </div>

    </section>

    <footer>

        <div class="footer-title">

            The Generics

        </div>

        <div class="footer-icons">

            <ul>

                <li><a href="https://www.youtube.com">

                    <img src="./img/6260efc8fc9a9002669d2f4ad9956cc0.jpg" alt="">

                </a></li>

                <li><a href="https://spotify.com">

                    <img src="./img/Spotify Logo.png" alt="">

                </a></li>

                <li><a href="https://facebook.com">

                    <img src="./img/Facebook Logo.png" alt="">

                </a></li>

            </ul>

        </div>

    </footer>

</body>

</html>



//@import url('https://fonts.googleapis.com/css2?family=Metal+Mania&display=swap');



* {

    box-sizing: border-box;

    margin: 0;

    padding: 0;

}

/* body{

    height:100vh;

} */

header {

    text-align: center;

    margin:0;

    padding:0px;

    padding-bottom:30px;

    background:#777;

    color:white;

}



#cart{

    position: fixed;

    height: 95%;

}

header h1{

    padding:40px;

    font-size:100px;

}

header ul{

    display:flex;

    padding:10px;

    font-size:18px;

    font-weight:200;

    justify-content: center;

    list-style-type: none;

    border-bottom:0.1rem solid white;

    position: fixed;

    top: 0%;

    background: black;

    width: 100%;

    z-index: 1;

}

header li{

    margin:0px 40px;

}

header li a{

    text-decoration: none;

    color:white;

}

header h6{

    padding:10px;

    font-size:20px;

    font-weight: normal;;

    border-bottom: 0.1rem solid white;

}

header h6 a {

    text-decoration: none;

    color:white;

}

header .latest-album{

    display:block;

    border:1px solid #56CCF2;

    padding:15px 30px;

    font-size:23px;

    font-weight: 200;

    margin:10px auto;

    background: inherit;

    cursor: pointer;

    color:white;

}

header .play-btn{

    cursor: pointer;

    display:block;

    border:2px solid #56CCF2;

    border-radius:50%;

    padding:20px;

    font-size:30px;

    font-weight: 200;

    margin:20px auto;

    background: inherit;

    color:#56CCF2;

}



#tours .tour-item{

    display:flex;

    border-bottom:1px solid black;

    padding:10px;

}

#tours .tour-item .tour-date{

    width:12%;

}

#tours .tour-item .tour-place{

    width:25%;

    color:#777;

}

#tours .tour-item .tour-spec-place{

    width:53%;

    color:#777;

}

#tours .tour-item .buy-btn{

    width:20%;

    background: #56CCF2;

    color:white;

    border:none;

    padding:7px;

    border-radius:5px;

    font-weight:700;

    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}

section h2{

    font-family:"Metal Mania";

    text-align:center;

    padding:20px;

    font-size:30px;

}

.container{

    max-width:900px;

    margin:0 auto;

    padding:20px 30px;

}

#music-content{

    display:flex;

    flex-wrap: wrap;

    justify-content:space-around;

}

#music-content div{

    margin:30px;

}

#music-content div h3{

    display: block;

    width: 100%;

    text-align: center;

    font-size: 24px;

    color: #333;

    margin-bottom: 15px;

}

#music-content .prod-details{

    display: flex;

    margin: 8px;

    align-items: center;

    justify-content: space-between;

}

#music-content .shop-item-button{

    cursor:pointer;

    padding:8px;

    color:white;

    border:none;

    font-size:15px;

    font-weight: bold;

    border-radius: 4%;

    background: #56CCF2;

}

#music-content .shop-item-button:hover, #merch-content .shop-item-button:hover{

    background: #0eabdf;

}

#merch-content{

    display:flex;

    flex-wrap: wrap;

    justify-content:space-around;

}

#merch-content div{

    margin:30px;

}

#merch-content div h3{

    display: block;

    width: 100%;

    text-align: center;

    font-size: 24px;

    color: #333;

    margin-bottom: 15px;

}

#merch-content .prod-details{

    display:flex;

    margin:8px;

    align-items:center;

    justify-content: space-between;

}

#merch-content .shop-item-button{

    cursor:pointer;

    padding:8px;

    color:white;

    border:none;

    font-size:15px;

    font-weight: bold;

    border-radius: 4%;

    background: #56CCF2;

}

.cart-row{

    font-size:18px;

    display:flex;

}

.cart-header{

    font-size:1.2rem;

    font-weight: bold;

}

.cart-item{

    width:45%;

}

.cart-img{

    width:80px;

    border-radius:8%;

    margin-right:20px;

}

.cart-price{

    width:20%;

}

.cart-quantity{

    width:35%;

}

.cart-column{

    display: flex;

    align-items: center;

    border-bottom: 1px solid black;

    margin-right: 1.5em;

    padding-bottom: 10px;

    margin-top: 10px;

}

.cart-quantity input{

    width:40px;

    height:30px;

    border:1px solid rgb(0, 204, 255) ;

    border-radius:8%;

    outline:none;

    text-align:center;

    margin-right:20px;

}

.cart-quantity button{

    color:white;

    font-weight: bold;

    background: rgb(231, 76, 76);

    cursor: pointer;

    border:none;

    border-radius:8%;

    height:30px;

    outline:none;

    padding: 0px 7px;

}

.cart-quantity button:hover{

    background: rgb(218, 37, 37);;

}

.cart-total{

    display:flex;

    flex-direction: row-reverse;

    font-size:1.2rem;

    margin:20px;

}

.cart-total .total-title{

    margin-right:10px;

    font-size:1.5rem;

}



.purchase-btn{

    display: flex;

    align-items: center;

    justify-content: center;

    margin:auto;

    margin-top: 50px;

    background: #56CCF2;

    color:white;

    font-size:1.2rem;

    font-weight: bold;

    border:none;

    border-radius:8%;

    padding:12px;

    cursor: pointer;

}

.purchase-btn:hover{

    background-color:#18acdd;

}

footer{

    display:flex;

    margin-top:40px;

    padding:20px;

    background: #56CCF2;

}

footer .footer-title{

    text-align: center;

    color:white;

    width:50%;

    font-size:50px;

    font-weight:bold;

    margin:0 auto;

}

footer .footer-icons{

    width:50%;

    display:flex;

    align-items:center;

    justify-content: space-around;

}

.footer-icons ul{

    list-style-type: none;

    display:flex;

}

.footer-icons li{

    padding:10px;

    margin:0px 20px;

}

.footer-icons li:hover{

    background:rgb(17, 206, 206);

}

.footer-icons img{

    width:30px;

}



/* About */

#about{

    max-width:900px;

    margin:0 auto;

    font-size: 22px;

}

#about h3{

    text-align: center;

    font-size:25px;

    margin:20px;

}

/* #about div{

    /* display:flex; */

 */



#about img{

    float:left;

    margin:20px 50px;

    border-radius: 50%;

    width:200px;

    height:200px;

}



#about p{

    font-size:17px;

    margin:20px;

    color:#777;

}



#container{

    position:fixed;

    bottom:10px;

    right:10px;

}

.notification {

    background-color: #56CCF2;

    border-radius: 5px;

    color: black;

    padding: 2rem;

    margin: 1rem;

}



.notification h4 span{

    color:rgb(235, 33, 33);

}



.image-container{

    height: 250px;

    width: 250px;

    overflow: hidden;

}

.prod-images{

    transform-origin: center center;

    object-fit: cover;

    height: 100%;

    width: 100%;

    padding:0px;

    margin:0px;

    transition: ease-in 0.5s;

    filter: brightness(100%);

}

.prod-images:hover{

    transform: scale(1.5);

    filter: brightness(130%);

}

header ul a{

    color:white;

    text-decoration:none;

    cursor: pointer;

}

.fa-shopping-cart{

    color:white;

}

.cart-holder{

    border:2px solid #56CCF2;

    border-radius: 7px;;

    padding:2px 10px;

    position: absolute;

    right: 2%;

}

.cart-number{

    position:absolute;

    color:#56CCF2;

    font-size: 20px;

    top:-10px;

    right:-15px;

}



@media(max-width:600px){

    header li{

        margin:0px 20px;

    }

}

#cart{

    margin:0px;

    display: none;

    position:fixed;

    top:50px;

    height: 95%;

    right:0;

    background-color:rgb(255, 255, 255);

    border:1px solid rgb(177, 103, 103);

    min-height:50vh;

}

#cart h2{

    margin:20px 0px;

    padding:0;

}



.cart-btn-bottom{

    display:flex;

    padding:15px;

    background-color: #777;

    border:none;

    border-radius:7px;

    margin:auto;

    cursor:pointer;

}

.cart-bottom{

    text-decoration: none;

    color:#56CCF2;

    font-size: 16px;

    font-weight:700;

}

.cancel{

    position:absolute;

    cursor:pointer;

    color:rgb(121, 117, 117);

    top:0;

    right:0;

    margin:20px;

    background:none;

    font-size:16px;

    font-weight: 700;

    border:1px solid rgb(121, 117, 117);

    border-radius:7px;

    padding:5px;

}





const cart_items = document.querySelector('#cart .cart-items');





const parentNode = document.getElementById('music-content');





window.addEventListener('load', () => {

    console.log('loaded');



    axios.get('http://localhost:3000/products').then((products) => {

        console.log(products)

        products.data.forEach(product => {

            const productHtml = `

                <div id="album-${product.id}">

                    <h3>${product.title}</h3>

                    <div class="image-container">

                        <img class="prod-images" src=${product.imageUrl} alt="">

                    </div>

                                    <div class="prod-details">

                        <span>$<span>${product.price}</span></span>

                        <button class="shop-item-button" type='button'>ADD TO CART</button>

                    </div>

                </div>`

            parentNode.innerHTML += productHtml



        })

    })



})



document.addEventListener('click',(e)=>{



    if (e.target.className=='shop-item-button'){

        const prodId = Number(e.target.parentNode.parentNode.id.split('-')[1]);

        axios.post('http://localhost:3000/cart', { productId: prodId}).then(data => {

            if(data.data.error){

                throw new Error('Unable to add product');

            }

            showNotification(data.data.message, false);

        })

        .catch(err => {

            console.log(err);

            showNotification(err, true);

        });



    }

    if (e.target.className=='cart-btn-bottom' || e.target.className=='cart-bottom' || e.target.className=='cart-holder'){

        axios.get('http://localhost:3000/cart').then(carProducts => {

            showProductsInCart(carProducts.data);

            document.querySelector('#cart').style = "display:block;"



        })

    }

    if (e.target.className=='cancel'){

        document.querySelector('#cart').style = "display:none;"

    }

    if (e.target.className=='purchase-btn'){

        if (parseInt(document.querySelector('.cart-number').innerText) === 0){

            alert('You have Nothing in Cart , Add some products to purchase !');

            return

        }

        alert('This Feature is yet to be completed ')

    }

})



function showProductsInCart(listofproducts){

    cart_items.innerHTML = "";

    listofproducts.forEach(product => {

        const id = `album-${product.id}`;

        const name = document.querySelector(`#${id} h3`).innerText;

        const img_src = document.querySelector(`#${id} img`).src;

        const price = product.price;

        document.querySelector('.cart-number').innerText = parseInt(document.querySelector('.cart-number').innerText)+1

        const cart_item = document.createElement('div');

        cart_item.classList.add('cart-row');

        cart_item.setAttribute('id',`in-cart-${id}`);

        cart_item.innerHTML = `

        <span class='cart-item cart-column'>

        <img class='cart-img' src="${img_src}" alt="">

            <span>${name}</span>

        </span>

        <span class='cart-price cart-column'>${price}</span>

        <form onsubmit='deleteCartItem(event, ${product.id})' class='cart-quantity cart-column'>

            <input type="text" value="1">

            <button>REMOVE</button>

        </form>`

        cart_items.appendChild(cart_item)

    })

}

function deleteCartItem(e, prodId){

    e.preventDefault();

    axios.post('http://localhost:3000/cart-delete-item', {productId: prodId})

        .then(() => removeElementFromCartDom(prodId))

}



function showNotification(message, iserror){

    const container = document.getElementById('container');

    const notification = document.createElement('div');

    notification.style.backgroundColor = iserror ? 'red' : 'green';

    notification.classList.add('notification');

    notification.innerHTML = `<h4>${message}<h4>`;

    container.appendChild(notification);

    setTimeout(()=>{

        notification.remove();

    },2500)

}



function removeElementFromCartDom(prodId){

        document.getElementById(`in-cart-album-${prodId}`).remove();

        showNotification('Succesfuly removed product')

}
