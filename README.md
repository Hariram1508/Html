# Html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss/dist/tailwind.min.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
</head>

<body>
    <div class="bg-yellow-400">
        <nav>
            <div class="grid grid-cols-2 text-lg">
                <h1 class="font-bold text-4xl">LOGO</h1>
                <div>
                    <ul class="flex gap-5 font-semibold justify-end uppercase">
                        <li class="text-black hover:text-red-400">home</li>
                        <li class="text-black hover:text-red-400">About</li>
                        <a href="#service"><li class="text-black hover:text-red-400">Services</li></a>
                        <a href="#Portfolio"><li class="text-black hover:text-red-400">Portfolio</li></a>
                        <a href="#Contact"><li class="text-black hover:text-red-400">Contact</li></a>
                    </ul>
                </div>
            </div>
        </nav>
        <main>
            <div class="flex justify-center py-60">
                <div>
                    <img src="messi 10.jpg" class="h-60 w-60 rounded-full" alt="Human">
                </div>
                <div class="py-24 px-20 text-4xl">
                    <h1>Hello, I'm messi</h1>
                    <p>let's connect <span class="text-yellow-400"></span></p>
                    <div>

                    </div>
                </div>
            </div>
        </main>
    </div>
    <div>
        <div class="flex justify-center">
            <h1 class="text-black text-2xl pt-5 font-bold" id="service">My Services</h1>

        </div>
        <div class="grid grid-cols-3 gap-7 px-5  w-full h-72">
            <div class="bg-white border-2 border-purple-400 p-5 hover:bg-purple-400     ">
                <div class="flex justify-center pt-7">
                    <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"
                            id="computer">
                            <g>
                                <path
                                    d="M84 17H16c-3.3 0-6 2.7-6 6v42c0 3.3 2.7 6 6 6h22v4.2c-.1.4-.9 1.5-1.3 2-1.1 1.4-2.2 2.8-1.4 4.4.3.7 1.1 1.4 2.7 1.4h23c1 0 3.3 0 4.1-1.8.8-1.8-.6-3.2-1.8-4.5-.4-.5-1.1-1.2-1.3-1.6V71h22c3.3 0 6-2.7 6-6V23c0-3.3-2.7-6-6-6zM40.3 79c.9-1.1 1.7-2.4 1.7-3.8V71h16v4.2c0 1.4 1 2.7 2 3.8H40.3zM86 65c0 1.1-.9 2-2 2H16c-1.1 0-2-.9-2-2v-6h72v6zm0-10H14V23c0-1.1.9-2 2-2h68c1.1 0 2 .9 2 2v32z">
                                </path>
                            </g>
                            <g>
                                <path fill="#00F" d="M524-370v1684h-1784V-370H524m8-8h-1800v1700H532V-378z"></path>
                            </g>
                        </svg>
                </div>
                <h1 class="font-bold pt-10 ">WEB DEVELOPMENT</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
            <div class="bg-white border-2 border-purple-400 p-5">
                <div class="flex justify-center pt-7 ">
                    <svg xmlns="http://www.w3.org/2000/svg" data-name="Layer 1" viewBox="0 0 53 53" id="file"
                        height="70" width="70">
                        <path
                            d="M8.8,50.5H38.3a1,1,0,0,0,1-1V43.6h4.9a1,1,0,0,0,1-1V10.53a1,1,0,0,0-.37-.78l-8.68-7L36,2.64l-.12-.07a1.1,1.1,0,0,0-.36-.07H14.7a1,1,0,0,0-1,1V9.4H8.8a1,1,0,0,0-1,1V49.5A1,1,0,0,0,8.8,50.5Zm21.82-38,5.45,4.41H30.62Zm5.9-6.9,5,4h-5ZM15.7,4.5H34.52v6.14a1,1,0,0,0,1,1H43.2v30H39.3V17.43a1,1,0,0,0-.37-.78l-8.68-7a.44.44,0,0,0-.15-.08L30,9.47a1.16,1.16,0,0,0-.37-.07H15.7ZM9.8,11.4H28.62v6.51a1,1,0,0,0,1,1H37.3V48.5H9.8Z">
                        </path>
                        <path
                            d="M32.4 22.23H14.7a1 1 0 0 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 27.07H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 31.91H14.7a1 1 0 0 0 0 2H32.4a1 1 0 1 0 0-2zM32.4 36.76H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 41.6H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2z">
                        </path>
                    </svg>
                </div>
                <h1 class="font-bold pt-16">TECHNICAL WRITING</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
            <div class="bg-white border-2 border-purple-400 p-5">
                <div class="flex justify-center pt-7">
                    <svg xmlns="http://www.w3.org/2000/svg" data-name="Layer 1" viewBox="0 0 24 24" id="mobile"
                        width="70" height="70">
                        <path
                            d="M12,1.5a.5.5,0,1,0,.5.5A.5.5,0,0,0,12,1.5ZM17,0H7A2.5,2.5,0,0,0,4.5,2.5v19A2.5,2.5,0,0,0,7,24H17a2.5,2.5,0,0,0,2.5-2.5V2.5A2.5,2.5,0,0,0,17,0Zm1.5,21.5A1.5,1.5,0,0,1,17,23H7a1.5,1.5,0,0,1-1.5-1.5V18h13Zm0-4.5H5.5V4h13Zm0-14H5.5V2.5A1.5,1.5,0,0,1,7,1H17a1.5,1.5,0,0,1,1.5,1.5ZM12,22a1.5,1.5,0,1,0-1.5-1.5A1.5,1.5,0,0,0,12,22Zm0-2a.5.5,0,1,1-.5.5A.5.5,0,0,1,12,20Z">
                        </path>
                    </svg>
                </div>
                <h1 class="font-bold pt-16">MOBILE DEVELOPMENT</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
        </div>
        <div class="grid grid-cols-3 gap-7 px-5  w-full h-72 mt-7 ">
            <div class="bg-white border-2 border-purple-400 p-5">
                <div class="flex justify-center pt-7">
                    <svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"
                            id="computer">
                            <g>
                                <path
                                    d="M84 17H16c-3.3 0-6 2.7-6 6v42c0 3.3 2.7 6 6 6h22v4.2c-.1.4-.9 1.5-1.3 2-1.1 1.4-2.2 2.8-1.4 4.4.3.7 1.1 1.4 2.7 1.4h23c1 0 3.3 0 4.1-1.8.8-1.8-.6-3.2-1.8-4.5-.4-.5-1.1-1.2-1.3-1.6V71h22c3.3 0 6-2.7 6-6V23c0-3.3-2.7-6-6-6zM40.3 79c.9-1.1 1.7-2.4 1.7-3.8V71h16v4.2c0 1.4 1 2.7 2 3.8H40.3zM86 65c0 1.1-.9 2-2 2H16c-1.1 0-2-.9-2-2v-6h72v6zm0-10H14V23c0-1.1.9-2 2-2h68c1.1 0 2 .9 2 2v32z">
                                </path>
                            </g>
                            <g>
                                <path fill="#00F" d="M524-370v1684h-1784V-370H524m8-8h-1800v1700H532V-378z"></path>
                            </g>
                        </svg>
                </div>
                <h1 class="font-bold pt-10">WEB DEVELOPMENT</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
            <div class="bg-white border-2 border-purple-400 p-5">
                <div class="flex justify-center pt-7 ">
                    <svg xmlns="http://www.w3.org/2000/svg" data-name="Layer 1" viewBox="0 0 53 53" id="file"
                        height="70" width="70">
                        <path
                            d="M8.8,50.5H38.3a1,1,0,0,0,1-1V43.6h4.9a1,1,0,0,0,1-1V10.53a1,1,0,0,0-.37-.78l-8.68-7L36,2.64l-.12-.07a1.1,1.1,0,0,0-.36-.07H14.7a1,1,0,0,0-1,1V9.4H8.8a1,1,0,0,0-1,1V49.5A1,1,0,0,0,8.8,50.5Zm21.82-38,5.45,4.41H30.62Zm5.9-6.9,5,4h-5ZM15.7,4.5H34.52v6.14a1,1,0,0,0,1,1H43.2v30H39.3V17.43a1,1,0,0,0-.37-.78l-8.68-7a.44.44,0,0,0-.15-.08L30,9.47a1.16,1.16,0,0,0-.37-.07H15.7ZM9.8,11.4H28.62v6.51a1,1,0,0,0,1,1H37.3V48.5H9.8Z">
                        </path>
                        <path
                            d="M32.4 22.23H14.7a1 1 0 0 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 27.07H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 31.91H14.7a1 1 0 0 0 0 2H32.4a1 1 0 1 0 0-2zM32.4 36.76H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2zM32.4 41.6H14.7a1 1 0 1 0 0 2H32.4a1 1 0 0 0 0-2z">
                        </path>
                    </svg>
                </div>
                <h1 class="font-bold pt-16">TECHNICAL WRITING</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
            <div class="bg-white border-2 border-purple-400 p-5">
                <div class="flex justify-center pt-7">
                    <svg xmlns="http://www.w3.org/2000/svg" data-name="Layer 1" viewBox="0 0 24 24" id="mobile"
                        width="70" height="70">
                        <path
                            d="M12,1.5a.5.5,0,1,0,.5.5A.5.5,0,0,0,12,1.5ZM17,0H7A2.5,2.5,0,0,0,4.5,2.5v19A2.5,2.5,0,0,0,7,24H17a2.5,2.5,0,0,0,2.5-2.5V2.5A2.5,2.5,0,0,0,17,0Zm1.5,21.5A1.5,1.5,0,0,1,17,23H7a1.5,1.5,0,0,1-1.5-1.5V18h13Zm0-4.5H5.5V4h13Zm0-14H5.5V2.5A1.5,1.5,0,0,1,7,1H17a1.5,1.5,0,0,1,1.5,1.5ZM12,22a1.5,1.5,0,1,0-1.5-1.5A1.5,1.5,0,0,0,12,22Zm0-2a.5.5,0,1,1-.5.5A.5.5,0,0,1,12,20Z">
                        </path>
                    </svg>
                </div>
                <h1 class="font-bold pt-16">MOBILE DEVELOPMENT</h1>
                <p class="font-semibold">I can create cool and dynamic website for you</p>
            </div>
        </div>
    </div>
    <div>
        <div class="text-blue-800 text-2xl pt-5 font-bold  flex justify-center"> 
            <h1 class="text-black text-2xl pt-5 font-bold" id="Psortfolio"> Here's what i have done with my past </h1>
        </div>
        <br>
    </div>
    <div class="flex gap-10 pl-16 ">
        <img class="border-4 border-blue-400" src="web design - Copy.jpg" width="700">
            <img class="border-4 border-blue-400" src="web design - Copy.jpg" width="700">
         </div>
         <br>
         <div class="flex gap-10 pl-16 ">
            <img class="border-4 border-blue-400" src="web design - Copy.jpg" width="700">
                <img class="border-4 border-blue-400" src="web design - Copy.jpg" width="700">
             </div>
             <br>
             <div>
                 <div class="text-purple-900 text-2xl pt-5 font-bold  flex justify-center"> 
                    <h1 class="text-black text-2xl pt-5 font-bold" id="Contact"> HERE'S A CONTACT FORM</h1>
                </div>
             </div>
                <div class="text-balck text-2xl flex justify-center">
                    <h2> Have any questions?</h2>
                </div>
                <div>
                    <div class="text-blue-800 text-2xl flex justify-center" >
                    <h3> Lorem ipsum dolor sit amet consectetur adipisicing elit. A, reprehenderit id ut quaerat consequatur quis?</h3>
                </div>
                </div>
                <div>
                    <div class="gap-80 px-64 py-10 " >
                        <input class="border-2 border-purple-400 w-96 block " type="text" placeholder="Name">
                        <br>
                        <input class="border-2 border-purple-400 w-96 block " type="text" placeholder="EMAIL">
                        <br>
                        <input class="border-2 border-purple-400 w-96  h-20" type="text" placeholder="MESSAGE">
                        <br>
                        <button class="border-2 bg-purple-400 w-96 " type="text" > send > </button>
                </div>
</body>

</html>
