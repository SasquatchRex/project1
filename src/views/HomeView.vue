<template>
  <div class="min-h-screen min-w-[100vw] bg-neutral-800 px-[8vw]">
    <div class="absolute left-42 py-10">
      <a class="cursor-pointer font-bold text-2xl font-mono  border-black px-3 py-2 bg-neutral-500 rounded-xl">Company Logo</a>
    </div>
    <div class="pt-9"> 
      <form>
        
        <input type="text" placeholder="Search.." class="border-0 w-[55vw] border-black px-3 py-2 rounded-xl rounded-r-none bg-neutral-600">
        <button class="border-0 py-2 px-4 rounded-xl rounded-l-none bg-green-300 border-black hover:bg-green-400">Search</button>
      </form>
      <div>
        <div class="mt-7 text-left text-slate-400">Possible Results : </div>
      </div>
    </div>
    <div class="text-left space-y-3 pt-2">
      <div class="space-y-2 px-4 py-2 border-black bg-neutral-700 rounded-xl " v-for="i in 3" :key="i">
        <div class="font-bold text-xl text-blue-400">This is the heading of the possible Results {{ i }}</div>
        <div class="text-slate-300">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ratione necessitatibus vitae, dolorum nostrum voluptate dicta? Laborum inventore quam sapiente ratione recusandae, laboriosam harum. Quaerat accusantium autem excepturi dolor eum consequuntur! Reiciendis similique, eveniet soluta numquam repudiandae officiis explicabo hic porro! Nemo iusto saepe doloremque vel explicabo qui dolor dolorum aliquid eligendi. Totam perspiciatis ipsa quos, assumenda dicta recusandae odio consequuntur harum quae. Obcaecati eum vero numquam, minus quos quia adipisci, eaque dolorem consequuntur qui quisquam commodi, eveniet earum. Ipsam, maxime, laboriosam suscipit dolorem earum velit qui quo perspiciatis deleniti dolorum nam recusandae porro cum nostrum officiis nulla reiciendis adipisci, totam esse praesentium libero ea unde. Consequuntur et vel magnam dolor sit fugiat voluptas voluptatum sequi quasi dolores. Et, ullam repellendus? Ex alias distinctio velit neque. Deserunt cumque eveniet vitae tempora quasi maxime corporis accusantium, culpa exercitationem voluptates quidem nostrum, officia obcaecati odit placeat voluptate ipsum ratione eum reiciendis. Autem obcaecati, enim doloribus inventore laboriosam incidunt porro assumenda eos soluta facilis architecto perspiciatis! Aperiam, quia voluptate possimus est tempore, sint asperiores enim culpa illum expedita, a error veniam perferendis quae laborum repudiandae non ratione doloribus sunt minus. Quod voluptatum tempore ipsam praesentium, adipisci maxime quae. Veritatis tempora quod cum dolores ipsum?</div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src


export default {
  name: 'HomeView',

}
</script>
