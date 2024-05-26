<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- ionic icons -->
    <script type="module" src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.esm.js"></script>
    <script nomodule src="https://unpkg.com/ionicons@5.5.2/dist/ionicons/ionicons.js"></script>
     <!-- AOS css -->
     <link rel="stylesheet" href="./assets/css/aso.css">
     <!-- slick slider paths -->
     <link rel="stylesheet" href="./assets/css/slick.css">
     <link rel="stylesheet" href="./assets/css/slick-theme.css">        
    <!-- title icon -->
    <link rel="shortcut icon" href="./assets/images/titleimg.png" type="image/x-icon">
    <title>PhonePe</title>
    <style>
        html{
           scroll-behavior: smooth;
        }
        ::-webkit-scrollbar {
            width: 10px;
        }
        /* Track */
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        /* Handle */
        ::-webkit-scrollbar-thumb {
            background: #610088;
        }
        /* Handle on hover */
        ::-webkit-scrollbar-thumb:hover {
            background:#420142;
        }

        .box-1 span{
            transition: all .3s linear;
            visibility: hidden;
        }
        .box-1:hover span{
                visibility: visible;
        }
    </style>
     <!-- main tailwind js -->
     <script type="module" crossorigin src="./assets/js/tailwind.js"></script>
     <!-- main tailwind css -->
     <link rel="stylesheet" href="./assets/css/tailwind.css">
</head>
<body class="overflow-x-hidden w-full p-0 m-0 box-border">
    <!-- PhonePe clone with tailwind -->
    <main class="overflow-x-hidden w-full">

        <header class="w-full bg-white border-b-2 border-slate-100 fixed top-0 py-4 px-2 z-50">
            <nav class="flex lg:justify-center items-center justify-between">
                <!-- Logo -->
                <div class="nav-logo lg:w-[20%] w-auto">
                    <img src="./assets/images/logo.f5fe1554.svg" alt="Logo" class="w-36 m-auto lg:pl-0 pl-4">
                </div>
                <div class="nav-menu xl:w-3/5 lg:w-4/5 w-[10%]">
                    <!-- menu toggel btn -->
                    <span class="text-3xl lg:hidden block ">
                        <ion-icon name="menu" onclick="menu(this)"></ion-icon>
                    </span>
                    <!-- menu-list -->
                  <ul class="lg:space-x-0 lg:flex lg:justify-evenly lg:z-auto lg:static lg:opacity-100 lg:w-auto lg:h-auto lg:space-y-0 lg:py-0 lg:bg-transparent
                             py-11 space-y-10 w-full justify-center hidden absolute left-0 top[68px] transition-all ease-in duration-200 bg-purple-100 h-[100vh]">

                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">business acounts</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">Press</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">careers</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">about us</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">blog</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">contact us</a></li>
                        <li class="nav-items uppercase font-medium text-black hover:text-purple-800 lg:pl-0 pl-24"><a href="#!" class="nav-links">trust & safety</a></li>
                    </ul>
                </div>
            </nav>
        </header>

        <!--carousel section -->
        <section class="sec-1 w-full lg:h-3/4 h-auto overflow-hidden mt-10">
            <div class="main-slider">
                <div class="slide">
                    <picture>
                        <source media="(max-width:600px)" srcset="./assets/images/mobile-slider-1.6306f062.png ">
                        <img src="./assets/images/slider-1.c30bf2d2.png" class=" w-full object-cover">
                      </picture>
                </div>
                <div class="slide">
                   <picture>
                    <source media="(max-width:600px)" srcset="./assets/images/mobile-slider-2.308d976c.png ">
                    <img src="./assets/images/slider-2.ecf20c66.png" class=" w-full object-cover">
                   </picture>
                </div>
                <div class="slide">
                    <picture>
                        <source media="(max-width:600px)" srcset="./assets/images/mobile-slider-3.dc3cfa9d.png ">
                        <img src="./assets/images/slider-3.89743d4b.png" class=" w-full object-cover">
                    </picture>
                </div>
            </div>
        </section>

        <!-- phonePe wealth section -->
        <section class="wealth-sec w-full py-4 md:my-40 mt-12">
            <div class="wp-container flex justify-center items-center gap-x-8 md:flex-row lg:mx-0 mx-4 flex-col gap-y-8">

                <div class="wp-box flex flex-col lg:w-[35%] md:w-[45%] w-full md:mb-0 mb-8 border-2 border-solid border-gray-200 rounded-2xl px-8 lg:py-7 py-4 bg-contain bg-no-repeat bg-right	hover:border-0 hover:shadow-xl hover:shadow-stone-300 hover:cursor-pointer"
                    style="background-image:url(./assets/images/wp-img-1.c58f244a.svg);">
                     <h2 class="xl:text-3xl lg:text-2xl text-xl mb-4 font-bold text-purple-900">Insureance made <br>easy</h2>
                     <p class="xl:text-2xl lg:text-xl text-[.75rem] mb-4">Secure your life, health,<br>vehicles & more!</p>
                     <span class="arrow md:text-6xl text-[30px] md:mb-4 mb-0 text-purple-600">→</span>
                </div>

                <div class="wp-box flex flex-col lg:w-[35%] md:w-[45%] md:mb-0 mb-8 w-full border-2 border-solid border-gray-200 rounded-2xl px-8 lg:py-7 py-4 bg-no-repeat bg-contain bg-right	hover:border-0 hover:shadow-xl hover:shadow-stone-300 hover:cursor-pointer"
                     style="background-image:url(./assets/images/wp-img-2.a854650b.svg);">
                    <h2 class="xl:text-3xl lg:text-2xl text-xl mb-4 font-bold text-purple-900">Insureance made <br>easy</h2>
                    <p class="xl:text-2xl lg:text-xl text-[.75rem] mb-4">Secure your life, health,<br>vehicles & more!</p>
                    <span class="arrow md:text-6xl text-[30px] md:mb-4 mb-0 text-purple-600">→</span>
               </div>
            </div>
        </section>

        <!-- phonePe secure section -->
        <section class="secure-sec w-full py-4 md:my-10 mt-10 min-h-[100vh]" data-aos="fade-bottom">
            <h1 class="text-[30px] mb-4 font-bold text-purple-900 lg:hidden block text-center">Simple, Fast & Secure</h1>
            <div class="secure-container flex justify-center items-center mx-auto gap-x-8 lg:flex-row flex-col-reverse">
                <div class="wp-box flex flex-col xl:w-[30%] w-full  px-8 py-7">
                    <h1 class="text-5xl mb-4 font-bold text-purple-900 lg:block hidden">Simple, Fast & Secure</h1>
                    <div class="md:my-6 my-3">
                         <h2 class="text-2xl my-3">One app for all things money.</h2>
                         <p class="text-sm text-gray-400 my-3">Pay bills, recharge, send money, buy gold, invest and shop at your favourite stores.</p>
                         <p class="w-full h-[1px] bg-slate-800"></p>
                    </div>
                    <div class="md:my-6 my-3">
                            <h2 class=" text-2xl my-2">Pay whenever you like, wherever you like.</h2>
                            <p class=" text-sm text-gray-400 my-3">Choose from options like UPI, the PhonePe wallet or your Debit and Credit Card.</p>
                            <p class="w-full h-[1px] bg-slate-800"></p>
                    </div>
                   <div class="md:my-6 my-3">
                        <h2 class=" text-2xl my-2">Find all your favourite apps on PhonePe Switch.</h2>
                        <p class=" text-sm text-gray-400 my-3">Book flights, order food or buy groceries. Use all your favourite apps without downloading them.</p>
                   </div>
                </div>
                <div class="wp-box flex flex-col xl:w-[40%] w-full  px-8 py-7">
                    <video poster="./assets/images/video-poster.d0c96dcd.png" autoplay loop muted>
                       <source src="./assets/images/video.6b6bc150.mp4">
                    </video>
                </div>
            </div>
        </section>

        <!-- phonePe no-tension section -->
        <section class="w-full md:my-10 mt-10 max-h-[100vh]" data-aos="fade-bottom">
            <div class="tension-img mx-auto flex  flex-col justify-center  items-center">
                <picture>
                    <source media="(max-width:750px)" srcset="./assets/images/mobile-no-ten.png">
                    <img src="./assets/images/no-ten.26396505.png" class="w-auto object-cover">
                </picture>
                <div class="md:w-48 w-32"> 
                    <img src="./assets/images/logo.f5fe1554.svg" class="w-auto object-cover">
                </div>
            </div>
            <div class="no-conatiner mx-auto my-6 w-[90%]">  
                <div class="no-slider">
                    <div class="item">
                        <img src="./assets/images/amir-6.f910c6b2.jpg" class="w-auto object-cover">
                    </div>
                    <div class="item">
                        <img src="./assets/images/amir-3.842f2d30.jpg" class="w-auto object-cover">
                    </div>
                    <div class="item">
                        <img src="./assets/images/amir-5.5e809d58.jpg" class="w-auto object-cover">
                    </div>
                    <div class="item">
                        <img src="./assets/images/amir-4.68205e09.jpg" class="w-auto object-cover">
                    </div>
                </div>
            </div>
            <div class="flex flex-col md:w-[50%] w-[90%] mx-auto justify-center items-center">
                <button class="rounded-full border-[2px] border-solid border-purple-900 text-purple-900 py-2  md:w-2/5  w-4/5 hover:bg-purple-900 hover:text-white">Get More Info</button>
                <p class="text-center md:text-xl text-[.85rem] my-5">Live life worry-free! PhonePe fulfills all your insurance needs with a wide variety of insurance choices 
                    that can be bought instantly & easily with no annoying calls and disturbance! 
                    Protect your life, car, two-wheeler and much more in a few simple clicks. 
                    Make a smart choice today and live tension-free tomorrow!</p>
            </div>

        </section>

        <!-- phonePe apps section -->
        <section class="w-full md:my-10 min-h-[100vh]">
            <div class="apps-container bg-[linear-gradient(#ddd8fa,#fff)] mt-[20rem]">
                <div class="ap-bg-box flex md:flex-row flex-col justify-center items-center mx-auto lg:w-[69%] w-[90%] bg-[#967edd] bg-no-repeat md:bg-right bg-center bg-cover translate-y-[-40%] rounded-2xl md:p-16 p-4" style="background-image:url(./assets/images/bg-blur-img.90587a5e.png);">
                      <div class="under-img lg:w-1/5 md:w-2/5 w-32">
                        <img src="./assets/images/secure.0fb45868.png" class="w-auto object-cover">
                      </div>

                      <div class="under-context flex flex-col w-4/5 md:ml-[17%] ml-0">
                        <h1 class="md:text-2xl text-[30px] text-white font-bold my-4 md:text-justify text-center">Your money stays safe.</h1>
                        <p  class="md:text-xl text-[.75rem] text-white my-4 lg:w-3/5 md:w-4/5 md:text-justify text-center">PhonePe protects your money with the best-in-class security systems that help minimize frauds.</p>
                        
                        <div class="un-context-img md:mt-12 mt-3 flex md:w-fit w-full flex-wrap md:justify-start justify-evenly">
                            <img src="./assets/images/u-c-img.png" class="w-[100px] object-cover md:ml-9">
                            <img src="./assets/images/u-c-img-1.c1848538.png" class="w-[100px] object-cover md:ml-9">
                        </div>
                      </div>
                </div>
                <div class="ap-box-2 flex flex-col justify-center items-center w-full md:translate-y-[0%] translate-y-[-11%]">
                    <h1 class=" md:text-5xl text-[30px] font-semibold text-purple-900  text-center my-10">At 30+ Millions <br>  stores, apps, websites & more</h1>
                    <button class="rounded-full py-3  md:w-1/5  w-4/5 text-xl hover:bg-cyan-400 text-white  bg-cyan-500 hover:shadow-md hover:shadow-cyan-400 hover:font-semibold">Partner with us →</button>
                    <div class="md:w-4/5 w-full mt-10 md:my-10 my-4" data-aos="fade-right">
                        <picture>
                            <source media="(max-width:600px)" srcset="./assets/images/mobile-brand-img.5592f513.png">
                            <img src="./assets/images/brands img.096c44d6.png" class="w-auto object-cover">
                        </picture>
                    </div>

                </div>
            </div>
        </section>

        <!-- phonePe business section -->
        <section class="business-sec w-full md:py-4 py-0 md:my-10 min-h-[100vh]">
            <div class="secure-container flex justify-center items-center mx-auto gap-x-8 lg:flex-row flex-col-reverse">
                <div class="wp-box flex flex-col xl:w-[40%] w-full  px-8 py-7" data-aos="fade-right">
                    <img src="./assets/images/Screenshot (434).ccad7fb1.png" class="w-auto object-cover">
                </div>
                <div class="wp-box flex flex-col xl:w-[30%] w-full  px-8 py-7">
                    <h1 class="md:text-5xl text-[30px] mb-4 font-semibold text-purple-900 block">For Business</h1>
                    <p class="text-bases mb-4  text-slate-400 block ">Find the digital payment solution that fits your business needs</p>

                    <div class="my-6 cursor-pointer">
                         <h1 class=" text-xl my-5">I want to:</h1>
                         <h2 class=" text-[20px] font-semibold text-purple-800 mt-2 flex justify-between">One app for all things money. <span>></span></h2>
                         <p class=" text-base text-gray-400 my-5">Pay bills, recharge, send money, buy gold, invest and shop at your favourite stores.</p>
                         <p class="w-full h-[1px] bg-slate-800"></p>
                    </div>

                    <div class="my-2 cursor-pointer">
                        <h2 class=" text-[20px] font-semibold text-purple-800 mt-2 flex justify-between">Pay whenever you like, wherever you like.<span>></span></h2>
                        <p class=" text-base text-gray-400 my-5">Choose from options like UPI, the PhonePe wallet or your Debit and Credit Card.</p>
                        <p class="w-full h-[1px] bg-slate-800"></p>
                   </div>
                   <div class="my-2 cursor-pointer">
                        <h2 class=" text-[20px] font-semibold text-purple-800 mt-2 flex justify-between">Find all your favourite apps on PhonePe Switch.<span>></span></h2>
                        <p class=" text-base text-gray-400 my-5">Book flights, order food or buy groceries. Use all your favourite apps without downloading them.</p>
                        <!-- <p class="w-full h-[1px] bg-slate-800"></p> -->
                   </div>
                </div>
            </div>
        </section>

        <!-- phonePe press section -->
        <section class="press-sec w-full md:mt-20 mt-10  min-h-[100vh] bg-[#f6f2ff] py-10">
               <div class="container flex flex-col justify-center items-center mt-20 mx-auto md:px-0 px-6">
                   <h1 class="md:text-5xl text-[35px] mb-4 font-semibold text-purple-900 text-center">In the Press</h1>
                   <p class="text-base my-3 text-center">Read what the press has to say about us.</p>
                   <div class="flex-container flex  justify-center items-center lg:gap-10 md:gap-5 md:gap-y-0  my-20 flex-wrap" data-aos="fade-bottom">
                        <div class="cursor-pointer box-1 bg-white lg:w-[25%] md:w-[30%] w-full md:mb-0 mb-10 rounded-lg border-2 border-solid border-slate-200 p-4 min-h-[400px] flex flex-col flex-wrap relative after:content-[''] after:md:w-[85%] after:w-[90%] after:md:ml-3.5 after:ml-0 after:h-[4px] after:absolute after:bottom-0 after:bg-cyan-500 hover:border-0 hover:shadow-xl hover:shadow-stone-300">
                            <div class="md:my-6 my-3"><p class="text-slate-600 text-base">04 August</p></div>
                            <div class="md:my-6 my-3"><h2 class="text-2xl font-semibold text-slate-700">PhonePe Launches Smart Speaker For Payment Tracking</h2></div>
                            <div class="md:my-6 my-3"><p class="text-slate-400 text-sm">The Smart Speaker has currently been launched in 8 cities, and over 100k devices are already being used by</p></div>
                            <div class="my-7"><p class="text-slate-800 text-base font-semibold flex justify-between items-center">BW Disrupt <span class="text-5xl font-semibold text-purple-900">→</span></p></div>
                        </div>
                        <div class="cursor-pointer box-1 bg-white lg:w-[25%] md:w-[30%] w-full md:mb-0 mb-10 rounded-lg border-2 border-solid border-slate-200 p-4 min-h-[400px] flex flex-col flex-wrap relative after:content-[''] after:md:w-[85%] after:w-[90%] after:md:ml-3.5 after:ml-0 after:h-[4px] after:absolute after:bottom-0 after:bg-blue-800 hover:border-0 hover:shadow-xl hover:shadow-stone-300">
                            <div class="md:my-6 my-3"><p class="text-slate-600 text-base">04 August</p></div>
                            <div class="md:my-6 my-3"><h2 class="text-2xl font-semibold text-slate-700">PhonePe Launches Smart Speaker For Payment Tracking</h2></div>
                            <div class="md:my-6 my-3"><p class="text-slate-400 text-sm">The Smart Speaker has currently been launched in 8 cities, and over 100k devices are already being used by</p></div>
                            <div class="my-7"><p class="text-slate-800 text-base font-semibold flex justify-between items-center">BW Disrupt <span class="text-5xl font-semibold text-purple-900">→</span></p></div>
                        </div>
                        <div class="cursor-pointer box-1 bg-white lg:w-[25%] md:w-[30%] w-full md:mb-0 mb-8 rounded-lg border-2 border-solid border-slate-200 p-4 min-h-[400px] flex flex-col flex-wrap relative after:content-[''] after:md:w-[85%] after:w-[90%] after:md:ml-3.5 after:ml-0 after:h-[4px] after:absolute after:bottom-0 after:bg-red-600 hover:border-0 hover:shadow-xl hover:shadow-stone-300">
                            <div class="md:my-6 my-3"><p class="text-slate-600 text-base">04 August</p></div>
                            <div class="md:my-6 my-3"><h2 class="text-2xl font-semibold text-slate-700">PhonePe Launches Smart Speaker For Payment Tracking</h2></div>
                            <div class="md:my-6 my-3"><p class="text-slate-400 text-sm">The Smart Speaker has currently been launched in 8 cities, and over 100k devices are already being used by</p></div>
                            <div class="my-7"><p class="text-slate-800 text-base font-semibold flex justify-between items-center">BW Disrupt <span class="text-5xl font-semibold text-purple-900">→</span></p></div>
                        </div>
                   </div>
                   <button class="rounded-full py-3  md:w-1/5  w-4/5 text-xl hover:bg-cyan-400 text-white  bg-cyan-500 hover:shadow-md hover:shadow-cyan-400 hover:font-semibold mb-10">see all news →</button>
               </div>
        </section>

        <!-- phonePe explore section -->
        <section class="w-full md:mb-20 pt-20 max-h-[100vh] bg-[#7962bd]">
            <div class="explore-container md:mt-20 mt-0" data-aos="fade-bottom">
                <div class="bg-repeat-x bg-cover md:bg-[0 100%] bg-[right 73% bottom] max-w-[1268px] md:h-[444px] h-auto mx-auto" style="background-image:url(./assets/images/explore.f01f5a87.png);">
                       <div class="flex justify-evenly md:flex-row flex-col items-baseline gap-8 w-[80%] mx-auto">
                                <div class="explore-box">
                                    <h3 class=" text-base  text-[whitesmoke]">Trusted By</h3>
                                    <h1 class="md:text-4xl text-xl my-3  text-white font-semibold">400 Millions</h1>
                                    <p class="md:text-xl text-sm text-[whitesmoke]">Register Users</p>
                                </div>
                                <div class="explore-box">
                                    <h3 class=" text-base  text-[whitesmoke]">Accepted all over</h3>
                                    <h1 class="md:text-4xl text-xl my-3  text-white font-semibold">India</h1>
                                </div>
                                <div class="explore-box">
                                    <h3 class=" text-base  text-[whitesmoke]">Accepted at</h3>
                                    <h1 class="md:text-4xl text-xl my-3  text-white font-semibold">30+ Million</h1>
                                    <p class="md:text-xl text-sm text-[whitesmoke]">Stores</p>
                                </div>
                       </div>
                       <div class="flex justify-evenly items-baseline md:flex-row flex-col gap-8 w-[80%] mx-auto mt-12 flex-wrap">
                            <p class="md:text-3xl text-xl font-semibold text-gray-300 md:mb-0 mb-8">Get the latest data trends and insights on PhonePe Pulse!</p>
                            <button class="rounded-full border-2  py-3  md:w-1/5  w-4/5 text-xl border-cyan-500  text-white  hover:bg-cyan-500 hover:shadow-md hover:shadow-cyan-400 hover:font-semibold mb-10">Explore Now</button>

                       </div>
                </div>
            </div>
        </section>

        <!-- phonePe footer -->
        <footer class="w-full md:pt-4 pb-4 py-10 h-auto bg-white">
               <div class="footer-container xl:w-[80%] md:min-w-[90%] w-auto md:mx-auto mx-7 flex flex-wrap md:flex-row flex-col justify-center items-start">
                   <div class="footer-img md:w-[15%] w-full my-3">
                    <img src="./assets/images/logo.f5fe1554.svg" class="w-32 object-cover">
                   </div>
                   <div class="footer-list md:w-[15%] w-full px-4">
                    <ul class="list-none"> 
                        <li class="text-xl my-3"><b>General</b></li>
                        <li class="my-2"><a href="#!">About Us</a></li>
                        <li class="my-2"><a href="#!">Business solution</a></li>
                        <li class="my-2"><a href="#!">Report valuenability</a></li>
                        <li class="my-2"><a href="#!">Marchent Partner </a></li>
                    </ul>
                   </div>
                   <div class="footer-list md:w-[15%] w-full px-4">
                    <ul class="list-none"> 
                        <li class="text-xl my-3"><b>Conntect</b></li>
                        <li class="my-2"><a href="#!">Careers</a></li>
                        <li class="my-2"><a href="#!">Contact Us</a></li>
                        <li class="my-2"><a href="#!">Ethics</a></li>
                        <li class="my-2"><a href="#!">Blog</a></li>
                    </ul>
                   </div>
                   <div class="footer-list md:w-[15%] w-full px-4">
                    <ul class="list-none"> 
                        <li class="text-xl my-3"><b>Legal</b></li>
                        <li class="my-2"><a href="#!">Terms and Condition</a></li>
                        <li class="my-2"><a href="#!">Privacy Policy</a></li>
                        <li class="my-2"><a href="#!">Grievence Policy</a></li>
                        <li class="my-2"><a href="#!">How to Play </a></li>
                        <li class="my-2"><a href="#!">E-Waste Policy </a></li>
                    </ul>
                   </div>
                   <div class="footer-list md:w-[15%] w-full px-4">
                    <ul class="list-none">
                        <li class="text-xl mt-3 mb-8"><b>Certificate</b></li>
                        <li class="my-2"><img src="./assets/images/sisa.45dd2126.png" class="w-32 object-cover "></li>
                    </ul>
                   </div>
                   <div class="footer-list md:w-[15%] w-full px-4">
                    <ul class="list-none"> 
                        <li class="text-xl my-3"><b>See All Apps</b></li>
                        <li class="my-2"><button class="rounded-lg border-2 py-2 px-4 text-base border-black  text-black mb-16">Download Now</button></li>
                        <li class="my-2 flex items-center">
                            <a href="https://www.linkedin.com/company/phonepe-internet/" target="_blank"><img src="./assets/images/insta.7189c78e.svg" class="w-8 object-contain mr-4"></a>
                            <a href="https://twitter.com/PhonePe" target="_blank"><img src="./assets/images/twitter.f9f5c003.svg" class="w-8 object-contain mr-4"></a>
                            <a href="https://www.facebook.com/OfficialPhonePe/" target="_blank"><img src="./assets/images/face.30eb27c3.svg" class="w-8 object-contain mr-4"></a>
                       </li>
                    </ul>
                   </div>
               </div>
        </footer>

    </main>

    <script>
        function menu(e){
           let list = document.querySelector("nav ul");
           e.name=== 'menu' ? (e.name="close",list.classList.add('top-[68px]'),list.classList.add('block'),list.classList.remove('hidden'),list.classList.add('z-[1110]')): (e.name="menu",list.classList.remove('top-[68px]'),list.classList.remove('block'),list.classList.add('hidden'),list.classList.remove('z-[1110]'));
        }
    </script>
    <!--  js file -->
    <script  src="./assets/js/jquery-3.6.0.min.js"></script>
    <script  src="./assets/js/aso.js"></script>
    <script  src="./assets/js/slick.min.js"></script>
    <script type="module" src="./assets/js/script.js"></script>
</body>
</html>
