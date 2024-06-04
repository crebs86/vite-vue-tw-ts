<template>
  <div class="container my-2">

    <div>
      <span class="badge text-bg-primary mx-1">Primary</span>
      <span class="badge text-bg-secondary mx-1">Secondary</span>
      <span class="badge text-bg-success mx-1">Success</span>
      <span class="badge text-bg-danger mx-1">Danger</span>
      <span class="badge text-bg-warning mx-1">Warning</span>
      <span class="badge text-bg-info mx-1">Info</span>
      <span class="badge text-bg-light mx-1">Light</span>
      <span class="badge text-bg-dark mx-1">Dark</span>
    </div>

    <h1>Example heading <span class="badge text-bg-secondary">New</span></h1>
    <h2>Example heading <span class="badge text-bg-secondary">New</span></h2>
    <h3>Example heading <span class="badge text-bg-secondary">New</span></h3>
    <h4>Example heading <span class="badge text-bg-secondary">New</span></h4>
    <h5>Example heading <span class="badge text-bg-secondary">New</span></h5>
    <h6>Example heading <span class="badge text-bg-secondary">New</span></h6>


    <div class="d-flex gap-5">

      <button type="button" class="btn btn-primary">
        Notifications <span class="badge text-bg-secondary">4</span>
      </button>

      <button type="button" class="btn btn-primary position-relative">
        Inbox
        <span class="position-absolute top-0 start-100 translate-middle badge rounded-pill bg-danger">
          99+
          <span class="visually-hidden">unread messages</span>
        </span>
      </button>

      <button type="button" class="btn btn-primary position-relative">
        Profile
        <span
          class="position-absolute top-0 start-100 translate-middle p-2 bg-danger border border-light rounded-circle">
          <span class="visually-hidden">New alerts</span>
        </span>
      </button>

    </div>

  </div>
</template>