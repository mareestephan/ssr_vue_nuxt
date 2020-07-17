
<template>
    <div>
        <template> </template>

        <header class="pt-2 pb-0 pb-sm-2" id="header" style="background-color:#494949 !important">
            <a href="javascript:" id="scroll-to-top" aria-label="scroll to the top">
                <i class="icon-return"></i>
            </a>
            <div class="container">
                <div class="header-grid">
                    <div class="header-logo mt-4 mb-5 my-sm-0">
                        <a style="width:100%; height: auto" href="https://www.allsale.co.za/">
                            <img class="pr-sm-4 mb-sm-2 goHome" src="../../assets/new-logo.svg" alt="" style="cursor: pointer;" aria-label="website logo">
                        </a>
                    </div>
                    <div class="header-mobile-menu-toggle d-flex d-sm-none">
                        <a class="" href="fad.html#nav" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="nav">
                            <img src="../../assets/bars.svg" alt="" aria-label="menu image">
                        </a>
                    </div>
                    <div class="header-local-tag mr-0 mr-sm-2">
                    </div>
                    <div class="header-contact mr-0 mr-sm-2">
                    </div>
                    <div class="header-about mr-0 mr-sm-2">
                    </div>
                    <div class="header-join mr-0 mr-sm-2">
                        <a class="ml-5 joinClubLink" href="https://www.allsale.co.za/signup">JOIN THE CLUB</a>
                    </div>
                    <div class="header-profile loggedInHeader" style="display: none;">
                        <a class="mr-2 dropdown-toggle" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" href="fad.html#">
                            <span id="userName" style="margin-right: 5px; color:white !important"></span>
                        </a>
                        <div class="dropdown-menu profile-dropdown">
                            <a class="dropdown-item mt-0" href="https://www.allsale.co.za/account/lists?id=WishList">View Wishlists</a>
                            <a class="dropdown-item" href="https://www.allsale.co.za/account/details">Update Personal Details</a>
                            <a class="dropdown-item" href="https://www.allsale.co.za/account/orders">Order History</a>
                            <a class="dropdown-item" href="https://www.allsale.co.za/return">Log a Free Return</a>
                            <a class="dropdown-item" href="https://www.allsale.co.za/account/addresses">Change Address</a>
                            <a class="dropdown-item" href="https://www.allsale.co.za/login">Logout</a>
                        </div>
                        <div class="mx-auto text-light-gray">
                            |
                        </div>
                    </div>
                    <div class="header-wishlist loggedInHeader" style="display: none;">
                        <a class="mr-2" href="https://www.allsale.co.za/account/lists?id=Wishlist">
                            <img src="../../assets/_icons/heart.svg" aria-label="heart icon for wishlist">
                        </a>
                        <span id="favouriteListTotalLoggedIn" style="color:white !important"></span>
                    </div>
                    <div class="header-profile joinClubLink" style="display: none !important;">
                        <a class="mr-2" style="color:white !important" href="https://www.allsale.co.za/login">SIGN IN</a>
                    </div>
                    <div class="header-wishlist joinClubLink">
                        <a class="mr-2" href="https://www.allsale.co.za/account/lists?id=Wishlist">
                            <img src="../../assets/_icons/heart.svg" aria-label="heart icon for wishlist">
                        </a>
                        <span id="favouriteListTotalNotLoggedIn" style="color:white !important"></span>
                    </div>
                    <div class="header-search-bar px-0 mb-4 mb-sm-0">
                        <div class="input-group guide search-select search-bar search-input">
                            <div class="input-group-prepend">
                                <button class="btn btn-grey dropdown-toggle pr-5 pl-4 d-flex align-items-center" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false" style="text-align: center; min-width: 181px;" aria-label="All Departments">
                                    <span class="d-none d-sm-inline searchSpan" style="color: black !important; margin: 0 auto;" data-categorycode="all">All Departments</span>
                                </button>
                                <div class="dropdown-menu">
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="all">All Departments</a>
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="A">Baby &amp; Kids</a>
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="F">Fashion</a>
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="H">Health &amp; Beauty</a>
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="L">Homeware</a>
                                    <a class="dropdown-item catSpan" href="fad.html#" data-categorycode="M">Household</a>
                                </div>
                            </div>
                            <input type="search" class="form-control mr-0 mr-sm-3" aria-label="Text input with dropdown button" id="Search" placeholder="">
                            <a href="fad.html#" class="search-btn-icon" id="SearchButton">
                                <img src="../../assets/_icons/magnify-glass.svg" aria-label="search icon for search">
                            </a>
                        </div>
                    </div>
                    <div class="header-checkout">
                        <a class="btn btn-success btn-block checkout-btn text-white" href="https://www.allsale.co.za/cart">
                            <img class="mr-2 d-none d-sm-inline-block" src="../../assets/_icons/cart.svg" alt="">
                            <img class="mr-2 d-flex d-sm-none" src="../../assets/_icons/cart-orange.svg" aria-label="image for cart">
                            <span id="CartTotal" style="color:white !important"></span>
                            <span class="d-none d-sm-inline-block ml-2">CART</span>
                        </a>
                    </div>
                </div>
            </div>
        </header>
        <div style="background-color:white;">
            <div class="container">
                <nav class="nav nav-pills nav-fill custom-nav collapse" id="nav">
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/a/baby&#32;&amp;&#32;kids" role="button" aria-expanded="false" aria-controls="fashionSubMenu" aria-label="Category Name">BABY &amp; KIDS</a>
                        <div class="drop-content p-5 text-left collapse" style="background-color: #626262;">
                            <div style="display: grid; grid-auto-flow:column; justify-content:center; font-size:1.1rem">
                                <div>
                                    <a href="https://www.allsale.co.za/c/changing-bathing/aa" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">CHANGING &amp; BATHING</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bath-skincare/aaa">Bath &amp; Skincare</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/shampoo-conditioner/aab">Shampoo &amp; Conditioner</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/wipes/aac">Wipes</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/nappies/aad">Nappies</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/baby-gear/ab" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">BABY GEAR</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/essentials/aba">Essentials</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/feeding/ac" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">FEEDING</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/feeding-gear/aca">Feeding Gear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/dummies/acd">Dummies</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/toys/af" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">TOYS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/baby-toddler-toys/afa">Baby &amp; Toddler Toys</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/games/afc">Games</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/dolls-action-figures/aff">Dolls &amp; Action Figures</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/building-blocks/afe">Building Blocks</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/costumes/afh">Costumes</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/educational-toys/afk">Educational Toys</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/plush-toys/afl">Plush Toys</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/pretend-play/afm">Pretend Play</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/f/fashion" role="button" aria-expanded="false" aria-controls="fashionSubMenu" aria-label="Category Name">FASHION</a>
                        <div class="drop-content p-5 text-left collapse" style="background-color: #626262;">
                            <div style="display: grid; grid-auto-flow:column; justify-content:center; font-size:1.1rem">
                                <div>
                                    <a href="https://www.allsale.co.za/c/accessories/fa" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">ACCESSORIES</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/cold-weather/fag">Cold Weather</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/handbags-leather-smalls/faa">Handbags &amp; Leather Smalls</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/tech/fah">Tech</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/fashion-accessories/fab">Fashion Accessories</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/sunglasses-eyewear/fac">Sunglasses &amp; Eyewear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/mens-jewellery/faf">Men&#x27;s Jewellery</a>
                                        </li>
                                        <li>
                                            <a href="fad.html">Watches</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/mens/fc" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">MENS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/accessories/fck">Accessories</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/shirts/fcg">Shirts</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/womens/fb" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">WOMENS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/activewear/fbb">Activewear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/dresses-skirts/fbd">Dresses &amp; Skirts</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/footwear/fba">Footwear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/intimate-loungewear/fbg">Intimate &amp; Loungewear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/jackets-outerwear/fbh">Jackets &amp; Outerwear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/maternity/fbl">Maternity</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/pants-shorts/fbf">Pants &amp; Shorts</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/swimwear/fbi">Swimwear</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/tops-knitwear/fbe">Tops &amp; Knitwear</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/boys/fe" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">BOYS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/accessories/fea">Accessories</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/girls/fd" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">GIRLS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/accessories/fda">Accessories</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/underwear-sleepwear/fdj">Underwear &amp; Sleepwear</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/h/health&#32;&amp;&#32;beauty" role="button" aria-expanded="false" aria-controls="fashionSubMenu" aria-label="Category Name">HEALTH &amp; BEAUTY</a>
                        <div class="drop-content p-5 text-left collapse" style="background-color: #626262;">
                            <div style="display: grid; grid-auto-flow:column; justify-content:center; font-size:1.1rem">
                                <div>
                                    <a href="https://www.allsale.co.za/c/fragrances/ha" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">FRAGRANCES</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/men/haa">Men</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/women/hab">Women</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/unisex/hac">Unisex</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/aromatherapy/had">Aromatherapy</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/makeup/hb" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">MAKEUP</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/body/hba">Body</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/eyes/hbb">Eyes</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/face/hbc">Face</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/lips/hbd">Lips</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/tools/hbe">Tools</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/toiletries/hc" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">TOILETRIES</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bath-body/hca">Bath &amp; Body</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/mens/hcb">Mens</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/foot-care/hcl">Foot Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/hand-nail-care/hcd">Hand &amp; Nail Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/intimate-care/hce">Intimate Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/oral-care/hcf">Oral Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/shaving-grooming/hcg">Shaving &amp; Grooming</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/skin-care/hcj">Skin Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/suncare/hck">Suncare</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/mens-skincare/hch">Men&#x27;s Skincare</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/hair-care/hd" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">HAIR CARE</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/treatments/hdi">Treatments</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/hair-colouring/hdc">Hair Colouring</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/accessories-tools/hdd">Accessories &amp; Tools</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/mens/hde">Mens</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/kids/hdf">Kids</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/styling-products/hda">Styling Products</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/shampoo-conditioners/hdh">Shampoo &amp; Conditioners</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/extensions-wigs/hdj">Extensions &amp; Wigs</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/health-personal-care/he" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">HEALTH &amp; PERSONAL CARE</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/health-care/hea">Health Care</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/vision-care/hec">Vision Care</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/l/homeware" role="button" aria-expanded="false" aria-controls="fashionSubMenu" aria-label="Category Name">HOMEWARE</a>
                        <div class="drop-content p-5 text-left collapse" style="background-color: #626262;">
                            <div style="display: grid; grid-auto-flow:column; justify-content:center; font-size:1.1rem">
                                <div>
                                    <a href="https://www.allsale.co.za/c/bed-bath/la" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">BED &amp; BATH</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bathroom-accessories/laa">Bathroom Accessories</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/home-decor/lb" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">HOME DECOR</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/candles-home-fragrances/lbb">Candles &amp; Home Fragrances</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/home-decor-items/lbd">Home Decor Items</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/picture-frames/lbe">Picture Frames</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/kids-decor-bedding/lbg">Kids Decor &amp; Bedding</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/kitchen/ld" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">KITCHEN</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bakeware/lda">Bakeware</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/coffee-tea/ldb">Coffee &amp; Tea</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/cookware/ldc">Cookware</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/small-appliances-accessories/ldd">Small Appliances &amp; Accessories</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/organisation-storage/lde">Organisation &amp; Storage</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/utensils-tools/ldf">Utensils &amp; Tools</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/food-preparation/ldh">Food Preparation</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/dining-entertaining/le" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">DINING &amp; ENTERTAINING</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/barware/lea">Barware</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/cutlery/leb">Cutlery</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/drinkware/lee">Drinkware</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/serveware/lef">Serveware</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/tabletop-accessories/lei">Tabletop Accessories</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/luggage-travel/lf" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">LUGGAGE &amp; TRAVEL</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bags/lfa">Bags</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/travel-accessories/lfb">Travel Accessories</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/suitcases-sets/lfc">Suitcases &amp; Sets</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/m/household" role="button" aria-expanded="false" aria-controls="fashionSubMenu" aria-label="Category Name">HOUSEHOLD</a>
                        <div class="drop-content p-5 text-left collapse" style="background-color: #626262;">
                            <div style="display: grid; grid-auto-flow:column; justify-content:center; font-size:1.1rem">
                                <div>
                                    <a href="https://www.allsale.co.za/c/household-cleaning/ma" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">HOUSEHOLD CLEANING</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/cleaning-products/maa">Cleaning Products</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/bathroom/mac">Bathroom</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/floors-carpet/mad">Floors &amp; Carpet</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/furniture-upholstery/mae">Furniture &amp; Upholstery</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/insect-repellant/maf">Insect Repellant</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/kitchen/mag">Kitchen</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/laundry/mah">Laundry</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/shoe-care/mai">Shoe Care</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/general-goods/mb" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">GENERAL GOODS</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/general-goods/mba">General Goods</a>
                                        </li>
                                    </ul>
                                </div>
                                <div>
                                    <a href="https://www.allsale.co.za/c/pantry/md" style="font-weight:800; font-size: 1.3rem; color: rgb(42, 183, 164);">PANTRY</a>
                                    <ul style="list-style-type: none; padding: 0; margin-top: 10px; color: white;">
                                        <li>
                                            <a href="https://www.allsale.co.za/c/canned-food/mda">Canned Food</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/condiments-sauces/mdb">Condiments &amp; Sauces</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/drinks/mdc">Drinks</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/snacks-cereals/mde">Snacks &amp; Cereals</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/international-cooking/mdg">International Cooking</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/snacks-cereals/mdf">Snacks &amp; Cereals</a>
                                        </li>
                                        <li>
                                            <a href="https://www.allsale.co.za/c/dips-spreads/mdh">Dips &amp; Spreads</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="nav-item nav-link">
                        <a href="https://www.allsale.co.za/brands">BRANDS</a>
                    </div>
                    <div class="nav-item nav-link promo">
                        <a data-toggle="collapse" href="fad.html#promoSubMenu" role="button" aria-expanded="false" aria-controls="promoSubMenu" aria-label="Offers">OFFERS</a>
                        <div class="promo-drop-content p-5 text-left collapse" id="promoSubMenu" style="cursor: default;">
                            <div class="row mt-4 mb-2">
                                <div class="col-12 col-sm-3 ml-0 ml-sm-5">
                                    <a href="javascript:;" class="font-weight-bold text-white" role="button" aria-expanded="false" style="cursor: default;" aria-controls="p1" aria-label="Quick Links">QUICK LINKS</a>
                                    <ul class="list-unstyled mt-4 collapse" id="p1">
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/brands">Shop by Brand</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/search?promo=1">Featured</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/search?promo=2">Everyday Essentials</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/search?promo=3">Member Exclusive</a>
                                        </li>
                                    </ul>
                                </div>
                                <div class="col-12 col-sm-3">
                                    <a href="javascript:;" class="font-weight-bold text-white" role="button" aria-expanded="false" style="cursor: default;" aria-controls="p3" aria-label="New In">NEW IN</a>
                                    <ul class="list-unstyled mt-4 collapse" id="p3">
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/womens/fb?sort=Newest">New In Women's Fashion</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/mens/fc?sort=Newest">New In Men's Fashion</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/homeware/l?sort=Newest">New In Home</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/watches/fad?sort=Newest">New In Watches</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/fragrances/ha?sort=Newest">New In Fragrances</a>
                                        </li>
                                        <li>
                                            <a class="text-white" href="https://www.allsale.co.za/c/toys/af?sort=Newest">New In Toys</a>
                                        </li>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </nav>
            </div>
        </div>
        <div id="cta">
            <div class="notice text-center p-2 mt-3 mb-2 mb-sm-4" style="background-color:#ed778d !important ; margin-top: 0rem !important">
                <h5 class="mb-0 py-2 py-sm-0" style="text-transform: uppercase">Essential items will still be delivered during the lockdown period. However, all other orders may be delayed.</h5>
            </div>
        </div>
        <div class="container guide">
            <div class="text-center text-dark mt-3 mb-3 font-weight-bold" style="float:left; width:100%">
                <span class="display-4" style="font-size:1.4rem ; float:left">
                    <small class="font-weight-bold">
                        <a href="https://www.allsale.co.za/c/accessories/fa">ACCESSORIES</a>
                    </small>
                    <small class="font-weight-bold"> &gt;
                        <span class="">WATCHES</span>
                    </small>
                </span>
            </div>
            <div style="clear:both"></div>
            <div id="rowGrid" class="row">
                <div class="col-10 d-block offset-1 col-sm-3 offset-sm-0 px-0 mb-2 filterby-mobile">
                    <a class="bg-teal text-white btn py-2 px-4 col-10 text-left d-sm-none" href="fad.html#filterBy" data-toggle="collapse" role="button" aria-expanded="false" aria-controls="filterBy">FILTER BY</a>
                    <div class="col-12 side-collapse guide px-0 px-sm-3 mx-auto row collapse multi-collapse d-sm-block" id="filterBy">
                        <div id="selectedFilters" class="mb-0 mb-sm-4  bg-light-teal pt-3 pr-3 pb-1 pl-3 guide wide-spacing" style="display:none">
                            <span class="font-weight-bold">REFINE BY</span>
                            <div class="text-orange">
                                <ul class="list-unstyled mt-3 subCategoryFilter">
                                    <li class="removeFilterTemplate">
                                        <span class="close-icon">
                                            <img class="icon m-auto" src="../../assets/_icons/times.svg" alt="">
                                        </span>
                                        <h6 class="bold d-inline-block">
                                            <small></small>
                                        </h6>
                                    </li>
                                </ul>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4 bg-light-teal p-3 guide wide-spacing" style="">
                            <a id="genderFilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#gender" role="button" aria-expanded="false" aria-controls="gender">
                                <div class="font-weight-bold bg-light-teal">GENDER</div>
                            </a>
                            <div class="collapse mt-3 checkboxes filterList" id="gender">
                                <label class="container">
                                    <input type="checkbox" class="genderFilter" data-type="Gender" data-value="Mens" data-text="Mens">
                                    <span class="checkmark"></span>
                                    Mens (1287)
                                </label>
                                <label class="container">
                                    <input type="checkbox" class="genderFilter" data-type="Gender" data-value="Unisex" data-text="Unisex">
                                    <span class="checkmark"></span>
                                    Unisex (1)
                                </label>
                                <label class="container">
                                    <input type="checkbox" class="genderFilter" data-type="Gender" data-value="Womens" data-text="Womens">
                                    <span class="checkmark"></span>
                                    Womens (1602)
                                </label>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4 bg-light-teal p-3 guide wide-spacing" style="">
                            <a id="categoryFilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#category" role="button" aria-expanded="false" aria-controls="category">
                                <div class="font-weight-bold bg-light-teal">CATEGORY</div>
                            </a>
                            <div class="collapse mt-3 checkboxes filterList" id="category">
                                <label class="container">
                                    <input type="checkbox" class="categoryFilter" data-type="Category" data-value="FAD02" data-text="Men&#x27;s Watches">
                                    <span class="checkmark"></span>
                                    Men&#x27;s Watches (1278)
                                </label>
                                <label class="container">
                                    <input type="checkbox" class="categoryFilter" data-type="Category" data-value="FAD03" data-text="Unisex Watches">
                                    <span class="checkmark"></span>
                                    Unisex Watches (10)
                                </label>
                                <label class="container">
                                    <input type="checkbox" class="categoryFilter" data-type="Category" data-value="FAD01" data-text="Women&#x27;s Watches">
                                    <span class="checkmark"></span>
                                    Women&#x27;s Watches (1602)
                                </label>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4  bg-light-teal p-3 guide wide-spacing" style="">
                            <a id="brandFilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#brand" role="button" aria-expanded="false" aria-controls="brand">
                                <div class="font-weight-bold bg-light-teal">BRAND</div>
                            </a>
                            <div class="collapse checkboxes filterList" id="brand">
                                <div id="showMoreDiv0" class="" data-page="0" style="">
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Alex And Ani" data-text="Alex And Ani">
                                        <span class="checkmark"></span>
                                        Alex And Ani (46)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Anne Klein" data-text="Anne Klein">
                                        <span class="checkmark"></span>
                                        Anne Klein (22)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="AquaSwiss" data-text="AquaSwiss">
                                        <span class="checkmark"></span>
                                        AquaSwiss (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Armani" data-text="Armani">
                                        <span class="checkmark"></span>
                                        Armani (25)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Armani Exchange" data-text="Armani Exchange">
                                        <span class="checkmark"></span>
                                        Armani Exchange (19)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Breitling" data-text="Breitling">
                                        <span class="checkmark"></span>
                                        Breitling (2)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Bulova" data-text="Bulova">
                                        <span class="checkmark"></span>
                                        Bulova (29)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Cartier" data-text="Cartier">
                                        <span class="checkmark"></span>
                                        Cartier (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Casio" data-text="Casio">
                                        <span class="checkmark"></span>
                                        Casio (21)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Christian Van Sant" data-text="Christian Van Sant">
                                        <span class="checkmark"></span>
                                        Christian Van Sant (270)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Citizen" data-text="Citizen">
                                        <span class="checkmark"></span>
                                        Citizen (2)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Coach" data-text="Coach">
                                        <span class="checkmark"></span>
                                        Coach (87)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Diesel" data-text="Diesel">
                                        <span class="checkmark"></span>
                                        Diesel (42)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="DKNY" data-text="DKNY">
                                        <span class="checkmark"></span>
                                        DKNY (25)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Dogeared" data-text="Dogeared">
                                        <span class="checkmark"></span>
                                        Dogeared (3)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Ferrari" data-text="Ferrari">
                                        <span class="checkmark"></span>
                                        Ferrari (32)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Fossil" data-text="Fossil">
                                        <span class="checkmark"></span>
                                        Fossil (125)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Gucci" data-text="Gucci">
                                        <span class="checkmark"></span>
                                        Gucci (5)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Guess" data-text="Guess">
                                        <span class="checkmark"></span>
                                        Guess (80)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Hugo Boss" data-text="Hugo Boss">
                                        <span class="checkmark"></span>
                                        Hugo Boss (58)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Jean Paul Gaultier" data-text="Jean Paul Gaultier">
                                        <span class="checkmark"></span>
                                        Jean Paul Gaultier (42)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Jivago" data-text="Jivago">
                                        <span class="checkmark"></span>
                                        Jivago (150)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Jovial" data-text="Jovial">
                                        <span class="checkmark"></span>
                                        Jovial (31)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Juicy Couture" data-text="Juicy Couture">
                                        <span class="checkmark"></span>
                                        Juicy Couture (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Just Cavalli" data-text="Just Cavalli">
                                        <span class="checkmark"></span>
                                        Just Cavalli (57)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Kate Spade" data-text="Kate Spade">
                                        <span class="checkmark"></span>
                                        Kate Spade (18)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Kenneth Cole" data-text="Kenneth Cole">
                                        <span class="checkmark"></span>
                                        Kenneth Cole (36)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Lacoste" data-text="Lacoste">
                                        <span class="checkmark"></span>
                                        Lacoste (28)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Locman" data-text="Locman">
                                        <span class="checkmark"></span>
                                        Locman (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Longines" data-text="Longines">
                                        <span class="checkmark"></span>
                                        Longines (1)
                                    </label>
                                    <span class="showMore" data-target="1" style="color:cornflowerblue;cursor:pointer">Show more</span>
                                </div>
                                <div id="showMoreDiv1" class="showMoreDiv" data-page="1" style="display:none">
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Marc Jacobs" data-text="Marc Jacobs">
                                        <span class="checkmark"></span>
                                        Marc Jacobs (42)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Mathey Tissot" data-text="Mathey Tissot">
                                        <span class="checkmark"></span>
                                        Mathey Tissot (52)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Michael Kors" data-text="Michael Kors">
                                        <span class="checkmark"></span>
                                        Michael Kors (74)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Mont Blanc" data-text="Mont Blanc">
                                        <span class="checkmark"></span>
                                        Mont Blanc (2)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Movado" data-text="Movado">
                                        <span class="checkmark"></span>
                                        Movado (284)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Mulco" data-text="Mulco">
                                        <span class="checkmark"></span>
                                        Mulco (13)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Nina Ricci" data-text="Nina Ricci">
                                        <span class="checkmark"></span>
                                        Nina Ricci (15)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Nixon" data-text="Nixon">
                                        <span class="checkmark"></span>
                                        Nixon (3)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Obaku" data-text="Obaku">
                                        <span class="checkmark"></span>
                                        Obaku (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Oceanaut" data-text="Oceanaut">
                                        <span class="checkmark"></span>
                                        Oceanaut (224)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Olivia Burton" data-text="Olivia Burton">
                                        <span class="checkmark"></span>
                                        Olivia Burton (15)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Omega" data-text="Omega">
                                        <span class="checkmark"></span>
                                        Omega (10)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Pandora" data-text="Pandora">
                                        <span class="checkmark"></span>
                                        Pandora (148)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Rado" data-text="Rado">
                                        <span class="checkmark"></span>
                                        Rado (6)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Ray-Ban" data-text="Ray-Ban">
                                        <span class="checkmark"></span>
                                        Ray-Ban (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Raymond Weil" data-text="Raymond Weil">
                                        <span class="checkmark"></span>
                                        Raymond Weil (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Roberto Bianci" data-text="Roberto Bianci">
                                        <span class="checkmark"></span>
                                        Roberto Bianci (167)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Saint Laurent" data-text="Saint Laurent">
                                        <span class="checkmark"></span>
                                        Saint Laurent (3)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Seapro" data-text="Seapro">
                                        <span class="checkmark"></span>
                                        Seapro (125)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Sector" data-text="Sector">
                                        <span class="checkmark"></span>
                                        Sector (8)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Seiko" data-text="Seiko">
                                        <span class="checkmark"></span>
                                        Seiko (3)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Skagen" data-text="Skagen">
                                        <span class="checkmark"></span>
                                        Skagen (72)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Swarovski" data-text="Swarovski">
                                        <span class="checkmark"></span>
                                        Swarovski (65)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Swatch" data-text="Swatch">
                                        <span class="checkmark"></span>
                                        Swatch (31)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Swiss Army" data-text="Swiss Army">
                                        <span class="checkmark"></span>
                                        Swiss Army (5)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Tag Heuer" data-text="Tag Heuer">
                                        <span class="checkmark"></span>
                                        Tag Heuer (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Ted Baker" data-text="Ted Baker">
                                        <span class="checkmark"></span>
                                        Ted Baker (11)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Ted Lapidus" data-text="Ted Lapidus">
                                        <span class="checkmark"></span>
                                        Ted Lapidus (59)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Timex" data-text="Timex">
                                        <span class="checkmark"></span>
                                        Timex (5)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Tissot" data-text="Tissot">
                                        <span class="checkmark"></span>
                                        Tissot (96)
                                    </label>
                                    <span class="hideMore" data-target="2" style="color:cornflowerblue;cursor:pointer;padding-right: 114px;">Hide</span>
                                    <span class="showMore" data-target="2" style="color:cornflowerblue;cursor:pointer">Show more</span>
                                </div>
                                <div id="showMoreDiv2" class="showMoreDiv" data-page="2" style="display:none">
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Tommy Hilfiger" data-text="Tommy Hilfiger">
                                        <span class="checkmark"></span>
                                        Tommy Hilfiger (74)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Tory Burch" data-text="Tory Burch">
                                        <span class="checkmark"></span>
                                        Tory Burch (2)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Toywatch" data-text="Toywatch">
                                        <span class="checkmark"></span>
                                        Toywatch (1)
                                    </label>
                                    <label class="container">
                                        <input type="checkbox" class="brandFilter" data-type="Brand" data-value="Wenger" data-text="Wenger">
                                        <span class="checkmark"></span>
                                        Wenger (11)
                                    </label>
                                    <span class="hideMore" data-target="3" style="color:cornflowerblue;cursor:pointer;padding-right: 114px;">Hide</span>
                                </div>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4  bg-light-teal p-3 guide wide-spacing" style="display:none">
                            <a id="colorFilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#color" role="button" aria-expanded="false" aria-controls="color">
                                <div class="font-weight-bold bg-light-teal">COLOUR</div>
                            </a>
                            <div class="collapse checkboxes filterList" id="color">
                                <label class="container">
                                    <input type="checkbox" class="colourFilter" data-type="Colour" data-value="Black" data-text="Black">
                                    <span class="checkmark"></span>
                                    Black (1)
                                </label>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4  bg-light-teal p-3 guide wide-spacing" style="display:none">
                            <a id="sizeFilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#size" role="button" aria-expanded="false" aria-controls="size">
                                <div class="font-weight-bold bg-light-teal">SIZE</div>
                            </a>
                            <div class="collapse checkboxes filterList" id="size">
                                <label class="container">
                                    <input type="checkbox" class="sizeFilter" data-type="Size" data-value="One Size" data-text="One Size">
                                    <span class="checkmark"></span>
                                    One Size (1)
                                </label>
                            </div>
                        </div>
                        <div class="mb-0 mb-sm-4  bg-light-teal p-3 guide wide-spacing" style="">
                            <a id="pricefilter" class="filterToggle collapsed" data-toggle="collapse" href="fad.html#price" role="button" aria-expanded="false" aria-controls="price">
                                <div class="font-weight-bold bg-light-teal">PRICE</div>
                            </a>
                            <div class="collapse mt-3 filterList" id="price">
                                <div class="form-group">
                                    <label for="formControlRange">R0</label>
                                    <label class="float-right" for="formControlRange">R176 400</label>
                                    <input type="range" class="priceFilter form-control-range" id="formControlRange" min="0" max="176400" step="100" value="0">
                                </div>
                                <div id="displayPrice">
                                    R0
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-sm-9 guide px-0 overflow-hidden">
                    <div class="row products mobile-products search-page">
                        <div class="col-12 col-sm-5 guide mx-auto mx-sm-0 text-center text-sm-left mb-3 mb-sm-2 align-self-center">
                            <b class="resultCount text-muted wide-spacing d-none d-sm-block ml-2">
                                2890 PRODUCTS FOUND
                            </b>
                        </div>
                        <div class="col-12 col-sm-5 guide mx-auto mx-sm-0 text-center text-sm-left mb-3 mb-sm-2 d-block d-sm-none">
                            <b class="resultCount text-muted wide-spacing">
                                2890 PRODUCTS FOUND
                            </b>
                        </div>
                        <div class="col-10 offset-1 offset-sm-0 col-sm-7 guide search-products text-right d-flex flex-column flex-sm-row align-items-start justify-content-end mb-1">
                            <div class="dropdown mt-0 mb-2 mr-sm-2 mx-auto ml-sm-0" id="sortOrder">
                                <button class="btn btn-secondary dropdown-toggle dropdown-button mx-auto" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    NEW IN
                                </button>
                                <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                    <a class="dropdown-item" href="fad.html#" data-sort="Savings">SAVINGS</a>
                                    <a class="dropdown-item" href="fad.html#" data-sort="PriceLow">PRICE LOW TO HIGH</a>
                                    <a class="dropdown-item" href="fad.html#" data-sort="PriceHigh">PRICE HIGH TO LOW</a>
                                    <a class="dropdown-item" href="fad.html#" data-sort="Newest">NEW IN</a>
                                </div>
                            </div>
                            <div class="dropdown mt-0 mb-2 d-none d-sm-flex" id="searchSize">
                                <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                    VIEW 40
                                </button>
                                <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
                                    <a class="dropdown-item" href="fad.html#" data-size="20">VIEW 20</a>
                                    <a class="dropdown-item" href="fad.html#" data-size="40">VIEW 40</a>
                                    <a class="dropdown-item" href="fad.html#" data-size="80">VIEW 80</a>
                                </div>
                            </div>
                        </div>
                        <div id="products4" class="col-12">
                            <div class="row products mb-4 mt-4 mt-sm-0 mx-sm-0 px-3 px-sm-0">
                                <!-- +++++++++++++++++++++++++ Start of Categories being displayed +++++++++++++++++++++++++  -->
                                <!-- <div v-for="(post, ) of posts" :key="post.id" class="col-6 col-md one-quarter guide mt-0 pl-0 pl-sm-2 pr-1 pr-sm-2">
                                    <div class="col-6 col-md one-quarter guide mt-0 pl-0 pl-sm-2 pr-1 pr-sm-2">

                                        <nuxt-link :to="`/posts/${post.slug}`">

                                            <a aria-label="product link">

                                                <div className="card product mb-0 mb-sm-2 ">

                                                    <div className="col-12 text-center text-sm-left product-text">

                                                        <p className="mb-0">{{post.brand}}</p>

                                                        <h6 className="mb-0">{{post.meta_title}}</h6>

                                                    </div>
                                                </div>
                                            </a>

                                        </nuxt-link>
                                    </div>

                                </div> -->
                                <template v-for="(post, index) in posts">
                                    <div class="w-100 my-1 d-sm-block d-none" v-if="(index % 4 == 0) && index != 0" :key="post.id">

                                        <div class="w-100 my-1 d-sm-block d-none"></div>
                                    </div>
                                    <div class="col-6 col-md one-quarter guide mt-0 pl-0 pl-sm-2 pr-1 pr-sm-2" :key="index">

                                        <nuxt-link :to="`/posts/${post.slug}`">

                                            <a aria-label="product link">

                                                <div class="card product mb-0 mb-sm-2 ">

                                                    <div class="col-12 text-center text-sm-left product-text">

                                                        <p class="mb-0">{{post.brand}}</p>

                                                        <h6 class="mb-0">{{post.meta_title}}</h6>

                                                    </div>
                                                </div>
                                            </a>

                                        </nuxt-link>
                                    </div>
                                </template>

                                <!-- +++++++++++++++++++++++++ End of Categories being displayed +++++++++++++++++++++++++  -->

                            </div>
                            <div id="gtmData" style="display:none">
                                <div class="gtmDataItem" data-sku="AKU-SFK399G-ST" data-name="Swatch SFK399G Female Gold Stainless Steel 34MM Quartz Analog Watch" data-price="2379.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="1"></div>
                                <div class="gtmDataItem" data-sku="AKU-YWS439G-ST" data-name="Swatch YWS439G Male Watch" data-price="2509.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="2"></div>
                                <div class="gtmDataItem" data-sku="AKU-LW161-ST" data-name="Swatch LW161 Female Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="3"></div>
                                <div class="gtmDataItem" data-sku="AKU-LW164-ST" data-name="Swatch LW164 Female Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="4"></div>
                                <div class="gtmDataItem" data-sku="AKU-5484070-ST" data-name="Swarovski 5484070 Watches Female Watch" data-price="5559.00" data-brand="Swarovski" data-category="Watches" data-variant="" data-count="5"></div>
                                <div class="gtmDataItem" data-sku="AKU-SUOB722-ST" data-name="Swatch SUOB722 Male Watch" data-price="1529.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="6"></div>
                                <div class="gtmDataItem" data-sku="AKU-GW170-ST" data-name="Swatch GW170 Unisex White Rubber 34MM Quartz Analog Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="7"></div>
                                <div class="gtmDataItem" data-sku="AKU-5205993-ST" data-name="Swarovski 5205993 Watches Female Watch" data-price="7129.00" data-brand="Swarovski" data-category="Watches" data-variant="" data-count="8"></div>
                                <div class="gtmDataItem" data-sku="AKU-SUOK713-ST" data-name="Swatch SUOK713 Female Watch" data-price="1479.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="9"></div>
                                <div class="gtmDataItem" data-sku="AKU-SVCK4081AG-ST" data-name="Swatch SVCK4081AG Male White Aluminum 43MM Quartz Analog Chronograph Watch" data-price="3309.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="10"></div>
                                <div class="gtmDataItem" data-sku="AKU-LL117-ST" data-name="Swatch LL117 Female Two Tone Rubber 25MM Quartz Analog Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="11"></div>
                                <div class="gtmDataItem" data-sku="AKU-YES4012AG-ST" data-name="Swatch YES4012AG Male Watch" data-price="2549.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="12"></div>
                                <div class="gtmDataItem" data-sku="AKU-YCS589G-ST" data-name="Swatch YCS589G Unisex Watch" data-price="3309.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="13"></div>
                                <div class="gtmDataItem" data-sku="AKU-YVZ400-ST" data-name="Swatch YVZ400 Male Watch" data-price="3419.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="14"></div>
                                <div class="gtmDataItem" data-sku="AKU-LW165-ST" data-name="Swatch LW165 Female Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="15"></div>
                                <div class="gtmDataItem" data-sku="AKU-YWM400G-ST" data-name="Swatch YWM400G Male Watch" data-price="3229.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="16"></div>
                                <div class="gtmDataItem" data-sku="AKU-LK382-ST" data-name="Swatch LK382 Female Watch" data-price="1329.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="17"></div>
                                <div class="gtmDataItem" data-sku="AKU-SVON102-ST" data-name="Swatch SVON102 Female Watch" data-price="1969.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="18"></div>
                                <div class="gtmDataItem" data-sku="AKU-LB170E-ST" data-name="Swatch LB170E Female Watch" data-price="1129.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="19"></div>
                                <div class="gtmDataItem" data-sku="AKU-YWB404G-ST" data-name="Swatch YWB404G Male Watch" data-price="3219.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="20"></div>
                                <div class="gtmDataItem" data-sku="AKU-YYS4019AG-ST" data-name="Swatch YYS4019AG Male Watch" data-price="3309.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="21"></div>
                                <div class="gtmDataItem" data-sku="AKU-5484058-ST" data-name="Swarovski 5484058 Watches Female Watch" data-price="5939.00" data-brand="Swarovski" data-category="Watches" data-variant="" data-count="22"></div>
                                <div class="gtmDataItem" data-sku="AKU-SUOB402-ST" data-name="Swatch SUOB402 Unisex Watch" data-price="1479.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="23"></div>
                                <div class="gtmDataItem" data-sku="AKU-LK360G-ST" data-name="Swatch LK360G Female Watch" data-price="1699.00" data-brand="Swatch" data-category="Watches" data-variant="" data-count="24"></div>
                                <div class="gtmDataItem" data-sku="AKU-5215038-ST" data-name="Swarovski 5215038 Necklaces Female Jewelry" data-price="1739.00" data-brand="Swarovski" data-category="Watches" data-variant="" data-count="25"></div>
                                <div class="gtmDataItem" data-sku="AKU-W4BB0015" data-name="Cartier Women&#x27;s White Dial Watch - W4BB0015" data-price="176339.00" data-brand="Cartier" data-category="Watches" data-variant="" data-count="26"></div>
                                <div class="gtmDataItem" data-sku="AKU-O21533402003001" data-name="Omega Men&#x27;s Seamaster Planet Ocean Blue Dial Watch - O21533402003001" data-price="126199.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="27"></div>
                                <div class="gtmDataItem" data-sku="AKU-O22010286051001" data-name="Omega Women&#x27;s Aqua Terra Black Dial Watch - O22010286051001" data-price="54109.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="28"></div>
                                <div class="gtmDataItem" data-sku="AKU-O22010402001001" data-name="Omega Men&#x27;s Rail Master Black Dial Watch - O22010402001001" data-price="92729.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="29"></div>
                                <div class="gtmDataItem" data-sku="AKU-O22010402006001" data-name="Omega Men&#x27;s Rail Master Grey Dial Watch - O22010402006001" data-price="92729.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="30"></div>
                                <div class="gtmDataItem" data-sku="AKU-O32632405001002" data-name="Omega Men&#x27;s Speedmaster Black Dial Watch - O32632405001002" data-price="81529.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="31"></div>
                                <div class="gtmDataItem" data-sku="AKU-O22010402003001" data-name="Omega Men&#x27;s Rail Master Blue Dial Watch - O22010402003001" data-price="92729.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="32"></div>
                                <div class="gtmDataItem" data-sku="AKU-O32630405001002" data-name="Omega Men&#x27;s Speedmaster Black Dial Watch - O32630405001002" data-price="82519.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="33"></div>
                                <div class="gtmDataItem" data-sku="AKU-O32632405002001" data-name="Omega Men&#x27;s Speedmaster Silver Dial Watch - O32632405002001" data-price="79659.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="34"></div>
                                <div class="gtmDataItem" data-sku="AKU-O42410276001001" data-name="Omega Women&#x27;s De Ville Black Dial Watch - O42410276001001" data-price="42739.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="35"></div>
                                <div class="gtmDataItem" data-sku="AKU-O33110425101001" data-name="Omega Men&#x27;s Speedmaster Black Dial Watch - O33110425101001" data-price="146569.00" data-brand="Omega" data-category="Watches" data-variant="" data-count="36"></div>
                                <div class="gtmDataItem" data-sku="AKU-BA110PP-7ACR-ST" data-name="Casio BA110PP-7ACR Female Watch" data-price="2599.00" data-brand="Casio" data-category="Watches" data-variant="" data-count="37"></div>
                                <div class="gtmDataItem" data-sku="AKU-ES4317-ST" data-name="Fossil ES4317 Ladies Female Watch" data-price="2199.00" data-brand="Fossil" data-category="Watches" data-variant="" data-count="38"></div>
                                <div class="gtmDataItem" data-sku="AKU-FS4813IE-ST" data-name="Fossil FS4813IE Outlet Male Watch" data-price="2549.00" data-brand="Fossil" data-category="Watches" data-variant="" data-count="39"></div>
                                <div class="gtmDataItem" data-sku="AKU-FS5151-ST" data-name="Fossil FS5151 Mens Male Watch" data-price="2889.00" data-brand="Fossil" data-category="Watches" data-variant="" data-count="40"></div>
                            </div>
                            <input data-val="true" data-val-required="The TotalPages field is required." id="TotalPages" name="TotalPages" type="hidden" value="73" />
                            <input data-val="true" data-val-required="The TotalProducts field is required." id="TotalProducts" name="TotalProducts" type="hidden" value="2890" />
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div id="rowPaging" class="row">
            <div class="col-10 col-sm-12 pr-0 text-right">
                <nav id="catPaging" aria-label="...">
                    <ul class="pagination justify-content-center justify-content-sm-end">
                        <li class="page-item disabled">
                            <a class="page-link py-1" href="fad.html#" tabindex="-1" aria-disabled="true">Page</a>
                        </li>
                        <li class="page-item active" aria-current="page">
                            <a class="linkPage page-link py-1" href="fad.html#" data-page="1">1
                                <span class="sr-only">(current)</span>
                            </a>
                        </li>
                        <li class="page-item">
                            <a class="linkPage page-link py-1" href="fad.html#" data-page="2">2</a>
                        </li>
                        <li class="page-item">
                            <a class="linkPage page-link py-1" href="fad.html#" data-page="3">3</a>
                        </li>
                        <li class="page-item">
                            <a class="linkPage page-link py-1" href="fad.html#" data-page="2">Next
                                <span class="pt-1 pr-2 pb-1 pl-2">
                                    <svg class="svg-inline--fa fa-angle-right fa-w-8" aria-hidden="true" focusable="false" data-prefix="fas" data-icon="angle-right" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 256 512" data-fa-i2svg="">
                                        <path fill="currentColor" d="M224.3 273l-136 136c-9.4 9.4-24.6 9.4-33.9 0l-22.6-22.6c-9.4-9.4-9.4-24.6 0-33.9l96.4-96.4-96.4-96.4c-9.4-9.4-9.4-24.6 0-33.9L54.3 103c9.4-9.4 24.6-9.4 33.9 0l136 136c9.5 9.4 9.5 24.6.1 34z"></path>
                                    </svg>
                                </span>
                            </a>
                        </li>
                    </ul>
                </nav>
            </div>
        </div>
        <!-- <div>
            {{counter}}
            <br>
            <button @click="counter++"> Press me</button>
        </div> -->

        <!-- <div v-for="(post, index) of posts" :key="post.id">
            {{ doMath(index) }}
            <span>{{index}}</span>

        </div> -->

    </div>

</template>

<script>
import axios from "axios";
export default {
  //   asyncData({ $axios }) {
  //     return (
  //       $axios
  //         // .get("http://35.190.35.153/system-api/pages-to-create/all-sale")
  //         .get("http://35.190.35.153/system-api/pages-to-create/all-sale")
  //         // .get(
  //         //   "https://my-json-server.typicode.com/mareestephan/jsonProducts/pages_to_create"
  //         // )
  //         .then(response => {
  //           // console.log(response.data);
  //           return { posts: response.data.pages_to_create };
  //         })
  //     );
  //   },

  async fetch() {
    // const config = {
    //   header: {
    //     Accept: "application.json"
    //   }
    // };

    const res = await axios.get(
      "http://35.190.35.153/system-api/pages-to-create/all-sale"
    );
    this.posts = res.data.pages_to_create;
  },
  data() {
    return {
      posts: []
    };
  },
  head() {
    return {
      title: "All Sale"
    };
  }
};
</script>

<style>
</style>
