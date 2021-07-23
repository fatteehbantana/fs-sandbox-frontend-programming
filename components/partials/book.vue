<template>
    <div class="col-md-4">
      <div class="input-group">
        <input
          type="text"
          placeholder="Book Title"
          class="form-control rounded-pill"
          style="height: 50px"
        />
        <div class="input-group-append">
          <button
            type="button"
            class="btn btn-outline-info rounded-pill ml-3"
            style="width: 50px"
          >
            <i class="fas fa-plus" @click.native="addBook"></i>
          </button>
        </div>
      </div>
      <ul class="list-group list-group-flush mt-3" type="book">
        <li
          class="list-group-item d-flex justify-content-between align-items-center"
          style="padding: 0.75rem 0.25rem"
        >
          Mathematics
          <button class="btn btn-outline-danger rounded-pill">
            <i class="fas fa-minus"></i>
          </button>
        </li>
        <li
          class="list-group-item d-flex justify-content-between align-items-center"
          style="padding: 0.75rem 0.25rem"
        >
          Logic
          <button class="btn btn-outline-danger rounded-pill">
            <i class="fas fa-minus"></i>
          </button>
        </li>
      </ul>
    </div>
</template>

<script>
export default {
    data() {
        return {
            book: "",
        }
    },
    methods: {
      addBook() {
        this.book.push({
          name: "",
        })
      }
    },
}
</script>