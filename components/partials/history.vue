<template>
    <div class="col-md-4">
      <div class="input-group">
        <div class="w-75">
          <select class="form-control mb-3 rounded-pill">
            <option value selected="selected">Choose Reader</option>
            <option value="Fatteeh">Fatteeh</option>
            <option value="Bantana">Bantana</option>
          </select>
          <select class="form-control mb-3 rounded-pill">
            <option value selected="selected">Choose Book</option>
            <option value="Fatteeh">Mathematics</option>
            <option value="Bantana">Logic</option>
          </select>
        </div>
        <div class="input-group-append">
          <button
            type="button"
            class="btn btn-outline-info rounded-pill ml-3"
            style="width: 50px"
          >
            <i class="fas fa-plus"></i>
          </button>
        </div>
        <ul class="list-group list-group-flush mt-3" type="history">
          <li
            class="list-group-item d-flex justify-content-between align-items-center"
            style="padding: 0.75rem 0.25rem"
          >Fatteeh - Mathematics
            <button class="btn btn-outline-danger rounded-pill ml-3">
              <i class="fas fa-minus"></i>
            </button>
          </li>
        </ul>
      </div>
    </div>
</template>