<template>
<NavBar />

<div  class="Title mt-8 mb-8">
    <div class="title">
        <h3 class="mb-4 text-md font-bold tracking-tight leading-none text-gray-900 max-sm:text-3xl max-md:text-4xl md:text-5xl lg:text-6xl dark:text-white">The simplest way to <span class="text-blue-600 dark:text-blue-500">host</span> & <span class="text-blue-600 dark:text-blue-500">share</span> your web project</h3>
    </div>
</div>

<div  class="Drag_Content ">
    <Drag_Drop  class="drag_drop rounded-lg shadow-2xl"/>
</div>

<div class="Ctn ">
    <div class="Content_1">
        <div class="Content_2">
                <h2 class="text-5xl font-extrabold dark:text-white">It's really simple</h2>


                <ul class="mb-8 mt-4 space-y-4 text-left text-gray-500 dark:text-gray-400">
                    <li class="flex items-center space-x-3">
                        <!-- Icon -->
                        <svg class="flex-shrink-0 w-10 h-10 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                        <span class="text-2xl">Drag & drop your individual file or zip file containing your content.</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <!-- Icon -->
                        <svg class="flex-shrink-0 w-10 h-10 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                        <span class="text-2xl">Enter a link-name or just click upload</span>
                    </li>
                    <li class="flex items-center space-x-3">
                        <!-- Icon -->
                        <svg class="flex-shrink-0 w-10 h-10 text-green-500 dark:text-green-400" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
                        <span class="text-2xl">Copy & share your link - that's it!</span>
                    </li>
                </ul>

                <div>
                    <a href="#" class="inline-flex justify-center items-center py-3 px-5 text-base font-medium text-center text-white bg-blue-700 rounded-lg hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 dark:focus:ring-blue-900">
                        Try it out
                        <svg class="ml-2 -mr-1 w-5 h-5" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd"></path></svg>
                    </a>
                </div>
            </div>
    
        <div class="Content_3">
            <img src="../assets/demo.gif" alt="demo">
        </div>
    </div>
</div>

<div   class="Title mb-8">
    <div class="title">
        <h1 class="mb-4 font-extrabold tracking-tight leading-none text-blue-600 max-sm:text-6xl md:text-5xl lg:text-6xl dark:text-white">1,000,000+</h1>
    </div>
    <div>
        <h3 class="text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400">Pageviews across all uploaded content</h3>
    </div>
</div>

<div class="Card_Content">
    <Card class="shadow-xl"/>
    <Card class="shadow-xl"/>
    <Card class="shadow-xl"/>
</div>

<div class="Content_4">
    <div class="Content_5">
        <h2 class="text-4xl font-extrabold dark:text-white">Ready to share your work?</h2>
    </div>

    <div class="Content_6 mt-8">
        <button type="button" class="text-white bg-blue-600 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-md px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">Upload for free</button>
    </div>
</div>

<FooterCompo class="mt-16"/>
</template>

<script setup>
import NavBar from "../components/NavBar.vue"
import Drag_Drop from "../components/Drag_Drop.vue";
import Card from "../components/Card.vue";
import FooterCompo from "../components/FooterCompo.vue";
</script>

<style scoped>
.Drag_Content{
    width: 100%;
    display: flex;
    justify-content:center;
    align-items:center;
    margin-top: 5vw;
}

.drag_drop{
    width: 40vw;
    padding: 1vw;
    background-color:;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    gap: 0.5vw;
}

@media only screen and (max-width: 728px) {
    .drag_drop{
        width: 85vw
    }
}

.title{
    background-color:;
    width: 70vw;
    text-align: center;
}


.Title{
    background-color:;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 1vw;
    margin-top: 5vw;
}

.Card_Content{
    width: 100%;
    display: flex;
    justify-content: center;
    gap: 2vw;
    margin-top: 8vw;
}

.Ctn{
    background-color:;
    width: 100%;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 8vw;
}
.Content_1{
    background-color: ;
    width: 60vw;
    display: grid;
    padding: 0.8vw;
    gap: 25px;
    grid-template-columns: 55% 40%;
    grid-template-rows: 100%;
    grid-template-areas:
    "Content_2 Content_3";
}

.Content_2{
    background-color:;
    grid-area: Content_2;
    display: flex;
    flex-direction: column;
    gap: 1vw;
    padding: 0.5vw;
}

@media only screen and (max-width: 728px) {

    .Content_1{
        width: 85vw;
        display: grid;
        padding: 0.8vw;
        gap: 25px;
        grid-template-columns: 100%;
        grid-template-rows: 100%;
        grid-template-areas:
        "Content_2 Content_3";
        }
    .Content_2{

    }
    
    .Content_3{
        visibility: hidden
    }

    .Card_Content{
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2vw;
    margin-top: 8vw;
}
}
.Content_3{
    background-color:;
    grid-area: Content_3;
    display: flex;
    justify-content: center;
    align-items: center;
}

.Content_4{
    background-color:;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 1vw;
    margin-top: 5vw;
}

.Content_5{
    text-align: center;
}
</style>