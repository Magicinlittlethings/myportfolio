<template lang = "html" class="  ">
<div class="relative">
  <transition  @enter = "enter5">
 <div v-if="showMenu" class=" flex justify-center  bg-black opacity-90 z-50 absolute h-screen w-screen pt-4 lg:hidden " style="color:white;`">
      
        <button @click="showMenu = !showMenu" class="absolute right-8"><fa icon="times" class=" text-3xl text-gray-100 hover:text-bora" /></button>
      

        
      <div class="flex-col pt-12">
        <a href="#home" @click="id = 'home'"  :class="` ${ id === 'home' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">HOME</a>
        <a href="#professional" @click="id = 'professional'"  :class="` ${ id === 'professional' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">PROFESSIONAL</a>
         <a href="#portfolio" @click="id = 'portfolio'"  :class="` ${ id === 'portfolio' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">PORTFOLIO</a>
         <a href="#experience" @click="id = 'experience'"  :class="` ${ id === 'experience' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-6 md:mb-8 block text-center`">EXPERIENCE</a>
         <a href="#contact" @click="id = 'contact'"  :class="` ${ id === 'contact' ?  'text-bora' : '' }   hover:text-gray-400 text-lg md:text-xl font-semibold mb-4 block text-center`">CONTACT</a>
      </div>
  </div>
  </transition>
  <div class="hero  bg-black w-screen " id="home">
     <div class=" smallnav flex justify-end  pr-8 py-2 w-screen shadow-sm   lg:hidden">
      
      <button @click="showMenu = true"> <fa  icon="bars" class=" text-2xl text-gray-100 hover:text-bora" /> </button>
       
    </div>
    
    <div class="bignav hidden lg:block ">
     <div class=" flex justify-between    fixed  py-4 px-60  w-screen shadow-md  bg-black  z-50 " style="color:white;">
      
        <a href="#home" @click="id = 'home'"  :class="` ${ id === 'home' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">HOME</a>
        <a href="#professional" @click="id = 'professional'"  :class="` ${ id === 'professional' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">PROFESSIONAL</a>
         <a href="#portfolio" @click="id = 'portfolio'"  :class="` ${ id === 'portfolio' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">PORTFOLIO</a>
         <a href="#experience" @click="id = 'experience'"  :class="` ${ id === 'experience' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">EXPERIENCE</a>
         <a href="#contact" @click="id = 'contact'"  :class="` ${ id === 'contact' ?  'text-bora' : '' }   hover:text-gray-400 text-base font-semibold`">CONTACT</a>
       
     </div>
     
    </div>
    
    
    
   
    <div class="flex justify-center  ">
      
      <div class="intro mt-48 ">
        
      <div class="text-center"><p class="type1  text-gray-100 text-5xl lg:text-8xl font-semibold leading-tight inline-block pr-4">
        I<span class="text-bora"> A</span>M</p> </div>
        
      <div class="text-center"><p class="type2 text-gray-100 text-5xl lg:text-8xl font-semibold leading-tight inline-block">LAWAL </p></div>
        
      <div class="text-center"><p class="type3 text-gray-100 text-5xl lg:text-8xl font-semibold  leading-tight inline-block"> KHADIJAT<span class="text-bora">.</span></p></div>
         
      <div class="text-center"><p class="type4 text-gray-100 text-2xl lg:text-3xl font-normal  leading-tight inline-block mt-12">FRONT END WEB DEVELOPER</p></div>
      <div class=" chevron flex flex-col justify-center mt-4">
         <p class=" chevron1 text-center material-icons font-light text-3xl text-gray-500  text-center">expand_more</p>
         <p class="chevron2 text-center material-icons font-light text-3xl text-gray-500  text-center">expand_more</p>
         <p class="chevron3 text-center material-icons font-light text-3xl text-gray-500  text-center">expand_more</p>
      </div>
     </div>
     
     
    </div>
    
    
   
  </div>
  <div class="second  flex justify-center relative w-screen" :style="{backgroundImage: `url('${bg3}')`} ">
    <div class=" card absolute bg-gray-600 border border-transparent rounded-md p-8 lg:p-16 w-3/5 ">
      <p class="font-bold text-3xl  lg:text-4xl text-center text-gray-100 mb-8">ABOUT <span class=" text-bora">ME</span></p>
      <p class="text-center text-gray-100  lg:px-20 leading-loose">
        Hi, My name is Lawal Khadijat Gbemisoke, Nice to meet you.<br> I'm a Freelance Front-End Web Developer in Lagos, Nigeria. I have  passion for UI effects, animations and creating intuitive, dynamic user experiences.

      </p>
      <p class="mt-28 text-center"><a href="contact" class="text-center text-bora  text-semibold">Let's make something special</a></p>
      
      <div class="bounce flex justify-center">
         <a href="https://drive.google.com/file/d/1EE5Ogv3YM9kwxCxFcQ-pUscBGIgyq9QX/view?usp=sharing" class=" mx-auto border rounded-2xl border-bora hover:bg-bora text-gray-100 mt-8 p-2 font-semibold">DOWNLOAD RESUME</a>
      </div>
     
    </div>
    <div class=" mt-96 " id="professional">
      <p class="professional text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center"><span class="text-gray-400">01</span> PROFESSIONAL</p>
      <p class="text-gray-100 text-xl lg:text-2xl text-center">MY KNOWLEDGE IN SOFTWARE</p>
      <div class="flex-col pb-36 hidden lg:block">
        <div class="flex mt-12  ">
          <p class="text-lg text-gray-100">HTML</p>
          <div class="pcontainer flex justify-between ml-8 ">
           <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress1 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full "></div>
           </transition>
            <div class="percentage text-lg text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">CSS</p>
          <div class="pcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress2 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-lg text-gray-100">80%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">TAILWINDCSS</p>
          <div class="pcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress3 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-lg text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">JAVASCRIPT</p>
          <div class=" pcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress4 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-lg text-gray-100">70%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">GSAP</p>
          <div class="pcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress5 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-lg text-gray-100">75%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-lg text-gray-100">VUE JS</p>
          <div class="pcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="progress6 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-lg text-gray-100">50%</div>
          </div>
          
        </div>
      </div>
      <div class="flex-col pb-36 lg:hidden">
        <div class="flex mt-12  ">
          <p class="text-base text-gray-100">HTML</p>
          <div class="ppcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress1 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">CSS</p>
          <div class="ppcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress2 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">80%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">TAILWINDCSS</p>
          <div class="ppcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress3 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">90%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">JAVASCRIPT</p>
          <div class="ppcontainer flex justify-between ml-8 ">
          <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress4 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">70%</div>
          </div>
          
        </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">GSAP</p>
          <div class="ppcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress5 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">75%</div>
          </div>
          
      </div>
         <div class="flex mt-8 ">
          <p class="text-base text-gray-100">VUE JS</p>
          <div class="ppcontainer flex justify-between ml-8 ">
            <transition appear @before-enter = "beforeEnter" @enter = "enter">
            <div class="pprogress6 bg-bora h-4 mt-1.5 mr-2 border border-transparent rounded-full"></div>
            </transition>
            <div class="percentage text-base text-gray-100">50%</div>
          </div>
          
        </div>
      </div>
    </div>
  </div>
  <div class="third flex-col justify-center pt-32 pb-96 w-screen" id="portfolio" :style="{backgroundImage: `url('${bg2}')`} ">
     <p class="text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center"><span class="text-gray-400">02</span> PORTFOLIO</p>
      <p class="text-gray-100 text-xl lg:text-2xl text-center">MY LATEST WORK.  </p>
      
      <div class="mt-16 mb-36  flex-col  px-8">
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://toynft.netlify.app/" class="text-lg text-center font-semibold">  ToyFaces</a>
         </div>
        </div>
         <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://spotifyyyclone.netlify.app/" class="text-lg text-center font-semibold"> SPOTIFY-CLONE</a>
         </div>
        </div>
        <div class=" flex justify-center mb-4">
          <div class="w-3/5 bg-bora border border-transparent rounded-full py-3 text-gray-100 hover:text-bora  hover:border-bora flex justify-center hover:bg-transparent hover:scale-110 ease-in-out duration-300">
          <a href="https://spotifymusicclonee.netlify.app/" class="text-lg text-center font-semibold"> SPOTIFY MUSIC CLONE</a>
         </div>
        </div>
        
        
      </div>
      <div class="experience flex-col justify-center  px-24 lg:px-40" id="experience">
        <p class="text-gray-100 font-semibold text-4xl lg:text-7xl mb-2 text-center "><span class="text-gray-400">03</span> EXPERIENCE</p>
        <div class="h-full mt-16 flex justify-between">
          <transition appear @enter = "enter2">
          <div class="mt-28">
            <p class="text-bora text-base mb-2"> 2021 - 2022</p>
            <p class="text-gray-100 text-2xl mb-5">CODEBASE TECHNOLOGIES</p>
            <p class="text-gray-400 text-base font-semibold">Intern</p>
            
          </div>
          </transition>
          <div class="w-1 bg-bora border border-bora mx-8 rounded-2xl" ></div>
          <transition appear @enter = "enter3">
          <div >
            <p class="text-bora text-base mb-2"> 2022 - PRESENT</p>
            <p class="text-gray-200 text-2xl mb-5">OURANOS TECHNOLOGIES</p>
            <p class="text-gray-400 text-base font-semibold">Intern</p>
            
          </div>
          </transition>
        </div>
      
      </div>

  </div>
  <div class="fourth relative flex justify-center h-screen w-screen" id="contact" :style="{backgroundImage: `url('${bg1}')`} ">
   <div class=" card2 absolute bg-gray-600 border border-transparent rounded-md p-8 lg:p-16  w-3/5   ">
    <div class="lg:flex lg:justify-between">
     <div class="">
       <p class="text-gray-100 text-2xl mb-5 lg:mb-0 text-center lg:text-left ">CONTACT</p>
       <p class="py-5 text-gray-100 text-base lg:block hidden"></p>
       <p class="text-gray-100 font-semibold lg:block hidden  " >ladeholar@gmail.com</p>
       <p class="text-gray-100 font-semibold lg:block hidden">+2347019849395</p>
     </div>
     <div>
       <form>
         <div class="flex mb-2">
           <input type="text" placeholder=" Name" class="w-full h-12 pl-2 border hover:border-bora mr-1.5 border border-transparent rounded-xl">
           <input type="email" placeholder="Email" class="w-full h-12 pl-2 border hover:border-bora ml-1.5 border border-transparent rounded-xl">
         </div>
         <input type="text" placeholder="Phone" class="w-full h-12 mb-2 pl-2 border hover:border-bora border border-transparent rounded-xl">
         <input type="text" placeholder="Message" class="w-full h-40 mb-2 pl-2 border hover:border-bora py-0 border border-transparent rounded-md ">
         <input type="submit" placeholder="Send" class="w-full h-12 text-center border border-transparent text-gray-100 bg-bora hover:bg-gray-200 hover:text-bora border border-transparent rounded-full">
       </form>
     </div>
    </div>
     
     <div class="flex justify-center  mt-12">
      <a href="https://www.linkedin.com/in/lawalkhadijat/"><fa :icon="['fab', 'linkedin']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.instagram.com/_theblackchild/"><fa :icon="['fab', 'instagram']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.twitter.com/adeholarlawal/"><fa :icon="['fab', 'twitter']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
      <a href="https://www.github.com/magicinlittlethings/"><fa :icon="['fab', 'github']" class="lg:text-2xl text-xl hover:scale-90 pr-3 lg:pr-5 text-white"/></a>
    </div>
    </div>
    
  </div>
  <div class="footer w-full bg-gray-800 py-6 flex justify-center w-screen">
    <transition appear @enter = "enter4"><p class="text-gray-100 text-base"> © 2022 by Lawal Khadijat.</p></transition>
  </div>
</div>
</template>

<script>

import gsap from 'gsap';
import ScrollTriggerPlugin from 'gsap/ScrollTrigger.js';
gsap.registerPlugin(ScrollTriggerPlugin);
export default {
  components: {
    
  },
 
  data(){
    return{
      id:'home',
      showMenu:false,
      bg3:"bg3.jpg",
      bg2:"bg2.jpg",
      bg1:"bg1.jpg",
    links:[
    {title:'HOME', nav:'#home', id:'home'},
    {title:'PROFESSIONAL', nav:'#professional', id:'professional'},
    {title:'PORTFOLIO', nav:'#portfolio', id:'portfolio'},
    {title:'EXPERIENCE', nav:'#experience', id:'experience'},
    {title:'CONTACT', nav:'#contact', id:'contact'},
  ],
  
  }
    
  },
  methods:{
  
    enter(el){
    gsap.from(el,{
      width:0,
      duration:2,
      
      scrollTrigger:{
          trigger:".professional",
          start: "top 50%",
          
          
    }
     })
  },
 
     enter2(el){
    gsap.from(el,{
      x:550,
      duration:2,
      delay:1,
      
      scrollTrigger:{
          trigger:".experience",
          start: "top 70%",
          
          
          
    }
     })
  },
   enter3(el){
    gsap.from(el,{
      x:-550,
      duration:2,
      delay:1,
      
      scrollTrigger:{
          trigger:".experience",
          start: "top 70%",
          
          
    }
     })
  },
    enter4(el){
    gsap.from(el,{
      autoAlpha:0,
      duration:2,
      
      
      scrollTrigger:{
          trigger:".footer",
          start: "top 90%",
          
          
    }
     })
  },
   enter5(el){
    gsap.from(el,{
      autoAlpha:0,
      duration:2,
      
     })
  },
  
  }
 
  
}
</script>

<style>
html{
scroll-behavior: smooth;
 
}
::-webkit-scrollbar{
width:12px;
background:black;
 
}
::-webkit-scrollbar-thumb{
background:linear-gradient(transparent, rgb(104, 95, 95));
border-radius: 4px;
 
}
::-webkit-scrollbar-thumb:hover{
background:linear-gradient(transparent, #b5838d);
border-radius: 6px;
 
}
body{
overflow-x: hidden;
 
}
.hero{
height:170vh;
 
}


.second{
background-size: cover;
background-attachment: fixed;
background-repeat: no-repeat;
 
}
.card{
top:-280px;
 
}
.card2{
top:-250px;
 
}
.pcontainer{
width:46rem;
 
}
.progress1{
width:45rem;
 
}
.progress2{
width:40rem;
 
}
.progress3{
width:45rem;
 
}
.progress4{
width:35rem;
 
}
.progress5{
width:37.5rem;
 
}
.progress6{
width:25rem;
 
}
.ppcontainer{
width:26rem;
 
}
.pprogress1{
width:25rem;
 
}
.pprogress2{
width:22rem;
 
}
.pprogress3{
width:25rem;
 
}
.pprogress4{
width:18rem;
 
}
.pprogress5{
width:20rem;
 
}
.pprogress6{
width:10rem;
 
}
.third{
background-size: cover;

background-repeat: no-repeat;
 
}
.fourth{
background-size: cover;
background-attachment: fixed;
background-repeat: no-repeat;
 
}
.work::before{
    
    content:'';
    position: absolute;
   width:100%;
   height:100%;
    background: linear-gradient(to right, #42275a, #734b6d); 
    opacity: 0.5;
    border-radius: 0.375rem;
   
}

.type1{
position:relative;
width:max-content;
 
}
.type2{
position:relative;
width:max-content;
 
}
.type3{
position:relative;
width:max-content;
 
}
.type1::before, .type1::after{
content:'';
position:absolute;
top:0;
left:0;
right:0;
bottom:0;
 
}
.type2::before, .type2::after{
content:'';
position:absolute;
top:0;
left:0;
right:0;
bottom:0;
 
}
.type3::before, .type3::after{
content:'';
position:absolute;
top:0;
left:0;
right:0;
bottom:0;
 
}
.type1::before{
background:black;
animation:typewriter 0.5s steps(4) 0.5s forwards;
 
}
.type2::before{
background:black;
animation:typewriter 1s steps(5) 1.5s forwards;
 
}

.type3::before{
background:black;
animation:typewriter 1.5s steps(8) 3.8s forwards;
 
}
.type1::after{
  width:0.125em;
background: transparent;
animation: typewriter 0.5s steps(4) 0.5s forwards,
blink 500ms steps(4) 3 backwards;
 
}
.type2::after{
  width:0.125em;
background: transparent;
animation: typewriter 1s steps(5) 1.5s forwards,
blink 500ms steps(5) 4 1.5s backwards;
 
}
.type3::after{
  width:0.125em;
background: transparent;
animation: typewriter 1.5s steps(8) 3.8s forwards,
blink 500ms steps(8)  infinite 3.8s ;
 
}
.type4{
  opacity:0;
  transform:translateY(4rem);
  animation: fadeInUp 1.5s 5.8s forwards;
 
}
.bignav{
  opacity:0;
  transform:translateY(-4rem);
  animation: fadeInDown 1.5s  forwards;
 
}
.smallnav{
  opacity:0;
  transform:translateY(-4rem);
  animation: fadeInDown 1.5s  forwards;
 
}
.chevron{
  
  opacity:0;
  animation:fadeIn 1s 7.5s  forwards;
  
 
}
.chevron1{
  
  
  animation:blinkIn 1s   infinite;
  
 
}
.chevron2{
  
  transform:translateY(-1.8rem);
  animation:blinkIn 1s 1.2s infinite;
  
 
}
.chevron3{
  
  transform:translateY(-3.6rem);
  animation:blinkIn 1s 2.4s infinite;
 
}
.bounce{
  
  animation:bounce 10s infinite forwards;
 
}
@keyframes typewriter{

to {
 left:100%;
}
 
}
@keyframes blink {
 
to{
 background: #b5838d;
}
}
@keyframes fadeInUp {
 
to{
 opacity:1;
 transform:translateY(0);
}
}
@keyframes fadeInDown {
 
to{
 opacity:1;
 transform:translateY(0)
}
}
@keyframes fadeIn {
 
to{
 opacity:1;

}
}
@keyframes blinkIn {
 
to{
 color:white;
}
}
@keyframes bounce {
 
0%{
 transform:translateY(0);
}
90%{
 transform:translateY(0);
}
92%{
 transform:translateY(-1.5rem);
}
94%{
 transform:translateY(0);
}
96%{
 transform:translateY(-1rem);
}
98%{
 transform:translateY(0);
}
100%{
 transform:translateY(-0.5rem);
}
}
</style>
