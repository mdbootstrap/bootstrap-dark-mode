
Responsive Dark Mode theme built with Bootstrap 5 with Dark Mode toggle button that switches between dark and light themes.

Check out [Bootstrap Dark Mode Documentation](https://mdbootstrap.com/docs/standard/extended/dark-mode/) for detailed instructions & even more examples.

![Bootstrap Dark Mode](https://mdbootstrap.com/img/Marketing/github/dark-mode/basic.jpeg)


## Dark Mode toggle/switch button

To create a dark mode toggle button add dark mode styles to your main scss file. Use the `@include` rule for any customized class. After that create a toggle button for switching those classes within the entire body.

Learn more how to create your own theming systems and advanced configurations in our [theming docs](https://mdbootstrap.com/docs/standard/content-styles/theme/).

```html
<button class="btn btn-primary" id="skinToggler">Toggle skin</button>
```

```scss
@import '~mdb-ui-kit/src/scss/mdb.pro.scss';

// DARK SKIN
$my-theme-primary: #1266f1;
$my-theme-secondary: #b23cfd;
$my-dark-theme: mdb-dark-theme($my-theme-primary, $my-theme-secondary);

.dark {
@include mdb-theme($my-dark-theme);
}
```

```JavaScript 
const skinToggler = document.getElementById('skinToggler');

const toggleSkin = () => {
document.body.classList.toggle('dark');
}

skinToggler.addEventListener('click', toggleSkin);
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)



___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/padding/">Bootstrap Padding</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/modal-size/">Bootstrap Modal Size</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/modal-methods/">Bootstrap Modal Methods</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/modal-backdrop/">Bootstrap Modal Backdrop</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/card-deck/">Bootstrap Card Deck</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/table-filter/">Bootstrap Table Filter</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/slider/">Bootstrap Slider</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/logo/">Bootstrap Logo</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/popup/">Bootstrap Popup</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/max-width/">Bootstrap Max Width</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/hero/">Bootstrap Hero</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/select-dropdown/">Bootstrap Select Dropdown</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/labels/">Bootstrap Labels</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/dialog/">Bootstrap Dialog</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/screen-sizes/">Bootstrap Screen Sizes</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-button/">Bootstrap Dropdown Button</a></li>  
  <li><a href="https://mdbootstrap.com/docs/standard/extended/widgets/">Bootstrap Widgets</a></li>  
</ul>

