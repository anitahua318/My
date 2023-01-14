<template>
    <div>
        <h1 id ="header1">
            Anita Hua
        </h1>
        <p id="intro">
            Hi! I am Anita, a first year at Columbia SEAS IEOR. I succeeded in my first start-up as an educational coach. In 2019, I decided to come to the States. I was luckily accepted into my dream boarding school in Western Mass. To record my journey, I opened a blog account. The 14-year-old Anita wouldn't have known that this simple move gained her popularity amongst study-abroads, and made her a essay tutor, college counselor, and life coach.
        </p>
        <img id="pic1" src="anita1.png" class="center"/>

        <a href="https://mp.weixin.qq.com/s/Jmg4EySpXAYNPNjjOf5fXQ" id="blog">My Writer's Blog</a>

        <h2 class="title">
        <span class="title-word title-word-1">Some </span>
        <span class="title-word title-word-2">Stats </span>
        <span class="title-word title-word-3">About </span>
        <span class="title-word title-word-4">My Startup</span>
        </h2>
        

        <div class="float-parent-element">
            <div class="float-child-element">
                <div class="red">400+ <img id="stud" src="students.png" class="center"/>
                </div>
            </div>
            <div class="float-child-element">
                <div class="yellow">1000+<img id="hour" src="hours.png" class="center"/>

                </div>
            </div>
        </div>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">


    </div>


</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=EB+Garamond&family=Lobster&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lobster&family=Open+Sans:wght@300&display=swap');
#header1{
    font-size: 550px;
    font-family:Lobster;
    text-align: center;
    margin-bottom: 0%;
    margin-top:0%;
}


.float-parent-element { 
    width: 50%; 
} 
.float-child-element { 
    float: left; 
    width: 50%; 
} 
.red { 
    font-size: 700px;
    font-family: EB Garamond;
    text-align:left;
    margin-left: 70%;
    margin-top:0%;
    margin-bottom: -2.5%;
} 
.yellow { 
    font-size: 700px;
    font-family: EB Garamond;
    text-align:right;
    margin-left: 120%;
    margin-top:0%;
    margin-bottom: -2.5%;
}


#stud{
    width:1800px;
    margin-top:-15%;
    margin-left:-30%
}

#hour{
    width:1200px;
    margin-top:-50%;
    margin-right:25%;
}

#intro{
    font-size: 75px;
    font-family:Open Sans;
    margin-left: 15%;
    margin-right:15%;
    margin-top: 0%;
    text-align: center;
    line-height:180%
}

#pic1.center{
    width: 2500px;
    display: block;
    margin-left: auto;
    margin-right: auto;
}

.title{
    font-size: 200px;
    font-family: 'EB Garamond', serif;
    text-align: center;
    margin-top:2.5%;
    margin-bottom: 0%;
}

.title-word{
  animation: color-animation 4s linear infinite;
}

.title-word-1 {
  --color-1: #DF8453;
  --color-2: #3D8DAE;
  --color-3: #E4A9A8;
}

.title-word-2 {
  --color-1: #DBAD4A;
  --color-2: #ACCFCB;
  --color-3: #17494D;
}

.title-word-3 {
  --color-1: #ACCFCB;
  --color-2: #E4A9A8;
  --color-3: #ACCFCB;
}

.title-word-4 {
  --color-1: #3D8DAE;
  --color-2: #DF8453;
  --color-3: #E4A9A8;
}

@keyframes color-animation {
  0%    {color: var(--color-1)}
  32%   {color: var(--color-1)}
  33%   {color: var(--color-2)}
  65%   {color: var(--color-2)}
  66%   {color: var(--color-3)}
  99%   {color: var(--color-3)}
  100%  {color: var(--color-1)}
}
.container {
  display: grid;
  place-items: center;  
  text-align: center;
  height: 200vh;
  font-size:larger
}

#blog{
    font-size: 100px;
    margin-left: 45%;
    font-family:'EB Garamond', serif;
}
</style>