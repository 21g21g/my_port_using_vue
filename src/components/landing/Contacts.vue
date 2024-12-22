<script setup>
import { ref } from "vue";
import Textarea from 'primevue/textarea';
import InputText from 'primevue/inputtext';

const firstName=ref("")
const lastName=ref("")
const phone=ref("")
const email=ref("")
const content=ref("")

</script>
<template>
  <div class=" min-h-screen  bg-black w-full pt-24 pb-40">
    <div class="flex flex-col px-16 md:px-64">
      <h1 class="text-5xl text-white font-bold  md:self-center">Contact <span class="text-5xl text-teal-500">Me</span></h1>
      <form class="mt-20 md:ml-24"  action="https://formsubmit.co/assegagebeyehu21@gmail.com"
       method="POST">
        <div class="flex flex-col gap-4">
        <div class="flex flex-col md:flex-row w-[50rem] gap-4">
       <InputText type="text" v-model="firstName" class="!bg-slate-600 !rounded-lg !py-3 !pl-2 !w-1/2 " placeholder="First Name" name="firstName"/>
        <InputText type="text" v-model="lastName" class="!bg-slate-600 !rounded-lg !py-3 !pl-2 !w-1/2" placeholder="Last Name" name="lastName"/>

      </div>
       <div class="flex flex-col md:flex-row w-[50rem] gap-4">
        <InputText type="number" v-model="phone" class="!bg-slate-600 !rounded-lg !pl-2 !py-3 !w-1/2" placeholder="Phone Number" name="phone"/>
        <InputText type="email" v-model="email" class="!bg-slate-600 !rounded-lg !pl-2 !py-3 !w-1/2" placeholder="Email" name="email"/>

      </div>
      <Textarea v-model="content" rows="10"  class="!bg-slate-600 w-[25rem] md:!w-[50rem] !px-7 !pt-4 !rounded-lg" name="content"/>

     </div>
          <input type="hidden" name="_next" value="https://www.google.com/search?q=english+to+amharic+translation&oq=&gs_lcrp=EgZjaHJvbWUqBggBEEUYOzIGCAAQRRg5MgYIARBFGDsyDQgCEAAYgwEYsQMYgAQyDQgDEC4YgwEYsQMYgAQyDQgEEC4YxwEY0QMYgAQyBggFEEUYPDIGCAYQRRg8MgYIBxBFGDzSAQgyNjY5ajBqNKgCALACAQ&sourceid=chrome&ie=UTF-8" />
     
    <button class="self-center bg-teal-500 hover:bg-blue-600 transition-all duration-700 rounded-xl mt-5 ml-10 md:ml-80 text-xl w-28 text-white px-4 py-1 font-bold" type="submit">Submit</button>

      </form>
    

    </div>
    
    
  </div>
</template>