<template>
  <div>
    <div class="d-flex justify-content-center vh-100">
      <div class="d-fles align-items-center vw-100">
        <div class="p-3 card w-100">
          <div class="overflow-y" style="height: 70vh;">
            <div class="text-center">
              <h1 class="mb-5">Sandbox Frontend</h1>
            </div>
            <hr>
            <div class="row">

              <!-- Book Input -->
              <partials-book />

              <!-- Reader Input -->
              <partials-reader />

              <!-- Reading History Input -->
              <partials-history />

            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>