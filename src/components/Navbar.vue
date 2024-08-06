<template>
      <header class="bg-white shadow h-16 flex justify-between items-stretch sticky top-0">
         <router-link :to="{name:'home'}" class="inline-flex items-center h-full px-5">
           Home
         </router-link>

         <div class="flex items-center gap-1">
            <router-link :to="{name:'byName'}"
             class="inline-flex items-center  px-2 h-full hover:bg-purple-100 transition-colors">
               Search Meals
            </router-link>

            <router-link :to="{name:'byLetter'}"
             class="inline-flex items-center  px-2 h-full hover:bg-purple-100 transition-colors">
             Meals By Letter
            </router-link>

            <router-link :to="{name:'byIngredients'}"
             class="inline-flex items-center  px-2 h-full hover:bg-purple-100 transition-colors">
            Meals By Ingredients
            </router-link>
         </div>
      </header>
</template>