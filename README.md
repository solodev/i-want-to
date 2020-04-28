# i-want-to
A well-designed header navigation system is necessary for user experience. With an I Want To menu that provides the links to the most requested pages from your users, you can help your visitors find the content they're looking for easily.

## Tutorial
For detailed instruction's, view Solodev's [How to Create an I Want To Menu Navigation](http://www.solodev.com/blog/web-design/how-to-create-an-i-want-to-menu-navigation.stml)

## Demo
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/9zjtds8u/).

## HTML
The tutorial contains the following basic HTML markup.

```
   <nav id="main-nav" role="navigation">
     <div class="container">
       <div class="row align-items-center">
         <div class="col-xl-3 col-lg-2 col-sm-4 col-5">
           <a href="/">
             <img alt="LunarXP Logo" class="img-fluid py-3" src="https://github.com/solodev/i-want-to/blob/master/images/logo.png?raw=true" aria-role="logo">
           </a>
         </div>
         <div class="col-xl-9 col-lg-10 col-sm-8 col-7">
           <ul class="navbar-nav flex-row justify-content-end flex-wrap align-items-center mr-lg-4 mr-xl-0">
             <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
               <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/about/"><strong>About</strong></a>
               <div class="dropdown position-absolute">
                 <ul class="list-unstyled">
                   <li class="bg-primary">
                     <a class="text-white px-2 d-block w-100" href="/about/team/">Team</a>
                   </li>
                   <li class="bg-primary">
                     <a class="text-white px-2 d-block w-100" href="/about/partners/">Partners</a>
                   </li>
                 </ul>
               </div>
             </li>
             <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
               <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/locations/"><strong>Locations</strong></a>
               <div class="dropdown position-absolute">
                 <ul class="list-unstyled">
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/locations/xp-1.stml">XP-1</a>
                   </li>
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/locations/hab-1.stml">HAB-1</a>
                   </li>
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/locations/orbiter-1.stml">Orbiter-1</a>
                   </li>
                 </ul>
               </div>
             </li>
             <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
               <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/products/"><strong>Products</strong></a>
               <div class="dropdown position-absolute">
                 <ul class="list-unstyled">
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/products/valkyrie1.stml">Valkyrie-1</a>
                   </li>
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/products/talon2.stml">Talon-2</a>
                   </li>
                   <li class="bg-primary nav-item">
                     <a class="text-white px-2 d-block w-100" href="/products/lunar_xplorer.stml">Lunar XPlorer</a>
                   </li>
                 </ul>
               </div>
             </li>
             <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
               <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/shop/"><strong>Shop</strong></a>
             </li>
             <li class="nav-item px-3 text-uppercase mb-0 position-relative d-none d-lg-flex">
               <a class="d-block w-100 h-100 text-black py-4 position-relative top-link" href="/contact/"><strong>Contact</strong></a>
             </li>
             <li class="d-none d-sm-flex nav-item my-3 my-lg-0 mr-5 mr-lg-4 mr-xl-5"><a href="#" class="btn btn-lg btn-primary">I Want To</a>
               <ul class="list-unstyled">
                 <li class="text-uppercase mb-0">
                   <div class="dropdown position-absolute w-md-550p w-xl-600p right-0 p-2 px-md-5 pb-md-5 pt-md-4 site-explorer">
                     <div class="row">
                       <div class="col-md-6">
                         <ul class="pl-0 list-unstyled">
                           <li class="mb-0 text-black">
                             <a class="px-2 px-lg-3 text-white d-block w-100 h-100" href="/events/">Conference</a>
                           </li>
                           <li class="mb-0 text-black"><a class="px-2 px-lg-3 text-white d-block w-100 h-100" href="/careers/">Apply for a Job</a>
                           </li>
                         </ul>
                       </div>
                       <div class="col-md-6">
                         <ul class="pl-0 list-unstyled">
                           <li class="mb-0 text-black">
                             <a class="px-2 px-lg-3 text-white d-block w-100 h-100" href="/events/">Launch Schedule</a>
                           </li>
                           <li class="mb-0 text-black">
                             <a class="px-2 px-lg-3 text-white d-block w-100 h-100" href="/contact/">Training</a>
                           </li>
                         </ul>
                       </div>
                       <div class="col-sm-12 text-center mt-4">
                         <a class="btn btn-white btn-lg d-none d-md-block" href="/search.stml">I want to find something else</a>
                       </div>
                     </div>
                   </div>
                 </li>
               </ul>
             </li>
           </ul>
           <button id="sidenav-open-btn" class="menu-hamburger position-absolute pointer p-0">
             <span class="icon-bar"></span>
             <span class="icon-bar"></span>
             <span class="icon-bar"></span>
           </button>
         </div>
       </div>
     </div>
   </nav>
```

## CSS
All required CSS is contained with style.css

## External Resources
This tutorial includes the following third party resources.

```
<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
```