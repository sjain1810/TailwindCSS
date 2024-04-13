<!-- <div class="grid gap-4 m-4 sm:grid-cols-2 grid-cols-2">
  <div class="rounded bg-orange-500 shadow-xl min-h-[100px]">1</div>
  <div class="rounded bg-teal-500 shadow-xl min-h-[100px]">2</div>
</div> -->
<!-- <div class="grid gap-4 m-4 sm:grid-cols-3">
  <div class="rounded bg-orange-500 shadow-xl min-h-[100px]">1</div>
  <div class="rounded bg-teal-500 shadow-xl min-h-[100px]">2</div>
  <div class="rounded bg-red-500 shadow-xl min-h-[100px]">3</div>
</div> -->
<!-- <div class="grid gap-4 m-4 sm:grid-cols-12">
  <div class="min-h-[100px] rounded bg-orange-500 shadow-xl sm:col-span-2"></div>
  <div class="min-h-[100px] rounded bg-teal-500 shadow-xl sm:col-span-10"></div>
</div> -->
<div class="grid gap-4 m-4 sm:grid-cols-12">
  <div class="min-h-[100px] rounded bg-orange-500 shadow-xl sm:col-span-2 sm:block hidden"></div>
  <div class="min-h-[100px] rounded bg-teal-500 shadow-xl sm:col-span-8"></div>
  <div class="min-h-[100px] rounded bg-red-500 shadow-xl sm:col-span-2 sm:block hidden"></div>
</div>

# Details
- In the above code we have learned about grid, equal as well as unequal grid types, the first two depicting equal grid while last two depicting unequal grid. An important point is we keep in mind mobile size(i.e. sm) when we write sm:, this means anything above mobile size and hence the second arg we provide is the alternate behaviour. E.g. : -sm:col-span-2 sm:block hidden, this means anything above mobile size will occupy two parts of the total div and also be visible and anything below will be hidden.